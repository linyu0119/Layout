线性布局： 
  drawable.xml
  
  <solid android:color="@android:color/black" />
  <stroke android:width="1dp" android:color="@android:color/darker_gray"/>
  
  activity_main.xml
  
  <LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:background="@android:color/background_dark"
    android:orientation="vertical">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">
        <Button
            android:id="@+id/btn_one_one"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:layout_marginLeft="1dp"
            android:layout_marginTop="1dp"
            android:layout_marginRight="1dp"
            android:layout_marginBottom="1dp"
            android:text="One，One"
            android:background="@drawable/drawable1"
            android:textSize="10sp"
            android:textColor="@android:color/darker_gray" />

        <Button
            android:id="@+id/btn_one_two"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="2"
            android:layout_marginLeft="1dp"
            android:layout_marginTop="1dp"
            android:layout_marginRight="1dp"
            android:layout_marginBottom="1dp"
            android:text="One，Two"
            android:background="@drawable/drawable1"
            android:textSize="10sp"
            android:textColor="@android:color/darker_gray"/>
        <Button
            android:id="@+id/btn_one_three"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:layout_marginLeft="1dp"
            android:layout_marginTop="1dp"
            android:layout_marginRight="1dp"
            android:layout_marginBottom="1dp"
            android:text="One，Three"
            android:background="@drawable/drawable1"
            android:textSize="10sp"
            android:textColor="@android:color/darker_gray"/>
        <Button
            android:id="@+id/btn_one_four"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:layout_marginLeft="1dp"
            android:layout_marginTop="1dp"
            android:layout_marginRight="1dp"
            android:layout_marginBottom="1dp"
            android:text="One，Four"
            android:background="@drawable/drawable1"
            android:textSize="10sp"
            android:textColor="@android:color/darker_gray"/>
    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">
        <Button
            android:id="@+id/btn_two_one"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:layout_marginLeft="1dp"
            android:layout_marginTop="1dp"
            android:layout_marginRight="1dp"
            android:layout_marginBottom="1dp"
            android:text="Two，One"
            android:background="@drawable/drawable1"
            android:textSize="10sp"
            android:textColor="@android:color/darker_gray" />

        <Button
            android:id="@+id/btn_two_two"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="2"
            android:layout_marginLeft="1dp"
            android:layout_marginTop="1dp"
            android:layout_marginRight="1dp"
            android:layout_marginBottom="1dp"
            android:text="Two，Two"
            android:background="@drawable/drawable1"
            android:textSize="10sp"
            android:textColor="@android:color/darker_gray"/>
        <Button
            android:id="@+id/btn_two_three"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:layout_marginLeft="1dp"
            android:layout_marginTop="1dp"
            android:layout_marginRight="1dp"
            android:layout_marginBottom="1dp"
            android:text="Two，Three"
            android:background="@drawable/drawable1"
            android:textSize="10sp"
            android:textColor="@android:color/darker_gray"/>
        <Button
            android:id="@+id/btn_two_four"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:layout_marginLeft="1dp"
            android:layout_marginTop="1dp"
            android:layout_marginRight="1dp"
            android:layout_marginBottom="1dp"
            android:text="Two，Four"
            android:background="@drawable/drawable1"
            android:textSize="10sp"
            android:textColor="@android:color/darker_gray"/>
    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">
        <Button
            android:id="@+id/btn_three_one"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:layout_marginLeft="1dp"
            android:layout_marginTop="1dp"
            android:layout_marginRight="1dp"
            android:layout_marginBottom="1dp"
            android:text="Three，One"
            android:background="@drawable/drawable1"
            android:textSize="10sp"
            android:textColor="@android:color/darker_gray" />

        <Button
            android:id="@+id/btn_three_two"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:layout_marginLeft="1dp"
            android:layout_marginTop="1dp"
            android:layout_marginRight="1dp"
            android:layout_marginBottom="1dp"
            android:text="Three，Two"
            android:background="@drawable/drawable1"
            android:textSize="10sp"
            android:textColor="@android:color/darker_gray"/>
        <Button
            android:id="@+id/btn_three_three"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:layout_marginLeft="1dp"
            android:layout_marginTop="1dp"
            android:layout_marginRight="1dp"
            android:layout_marginBottom="1dp"
            android:text="Three，Three"
            android:background="@drawable/drawable1"
            android:textSize="10sp"
            android:textColor="@android:color/darker_gray"/>
        <Button
            android:id="@+id/btn_three_four"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:layout_marginLeft="1dp"
            android:layout_marginTop="1dp"
            android:layout_marginRight="1dp"
            android:layout_marginBottom="1dp"
            android:text="Three，Four"
            android:background="@drawable/drawable1"
            android:textSize="10sp"
            android:textColor="@android:color/darker_gray"/>
    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">
        <Button
            android:id="@+id/btn_four_one"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:layout_marginLeft="1dp"
            android:layout_marginTop="1dp"
            android:layout_marginRight="1dp"
            android:layout_marginBottom="1dp"
            android:text="Four，One"
            android:background="@drawable/drawable1"
            android:textSize="10sp"
            android:textColor="@android:color/darker_gray" />

        <Button
            android:id="@+id/btn_four_two"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="2"
            android:layout_marginLeft="1dp"
            android:layout_marginTop="1dp"
            android:layout_marginRight="1dp"
            android:layout_marginBottom="1dp"
            android:text="Four，Two"
            android:background="@drawable/drawable1"
            android:textSize="10sp"
            android:textColor="@android:color/darker_gray"/>
        <Button
            android:id="@+id/btn_four_three"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:layout_marginLeft="1dp"
            android:layout_marginTop="1dp"
            android:layout_marginRight="1dp"
            android:layout_marginBottom="1dp"
            android:text="Four，Three"
            android:background="@drawable/drawable1"
            android:textSize="10sp"
            android:textColor="@android:color/darker_gray"/>
        <Button
            android:id="@+id/btn_four_four"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:layout_marginLeft="1dp"
            android:layout_marginTop="1dp"
            android:layout_marginRight="1dp"
            android:layout_marginBottom="1dp"
            android:text="Four，Four"
            android:background="@drawable/drawable1"
            android:textSize="10sp"
            android:textColor="@android:color/darker_gray"/>
    </LinearLayout>
  </LinearLayout>
  
约束布局主要代码：
<?xml version="1.0" encoding="utf-8"?>

<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"

    xmlns:app="http://schemas.android.com/apk/res-auto"

    android:layout_width="match_parent"

    android:layout_height="match_parent"

    android:background="#000000">



    <Button

        android:id="@+id/yellow"

        android:layout_width="67dp"

        android:layout_height="44dp"

        android:background="#FFFF00"

        android:text="YELLOW"

        app:layout_constraintBottom_toBottomOf="parent"

        app:layout_constraintEnd_toEndOf="parent"

        app:layout_constraintHorizontal_bias="1.0"

        app:layout_constraintStart_toEndOf="@+id/red"

        app:layout_constraintTop_toTopOf="parent"

        app:layout_constraintVertical_bias="0.0" />



    <Button

        android:id="@+id/red"

        android:layout_width="73dp"

        android:layout_height="44dp"

        android:background="@android:color/holo_red_light"

        android:text="RED"

        app:layout_constraintBottom_toBottomOf="parent"

        app:layout_constraintStart_toStartOf="parent"

        app:layout_constraintTop_toTopOf="parent"

        app:layout_constraintVertical_bias="0.0" />



    <Button

        android:id="@+id/button4"

        android:layout_width="wrap_content"

        android:layout_height="46dp"

        android:background="@android:color/holo_orange_light"

        android:text="ORANGE"

        app:layout_constraintEnd_toStartOf="@+id/yellow"

        app:layout_constraintStart_toEndOf="@+id/red"

        app:layout_constraintTop_toTopOf="parent" />



    <Button

        android:id="@+id/green"

        android:layout_width="71dp"

        android:layout_height="wrap_content"

        android:background="#90EE90"

        android:text="GREEN"

        app:layout_constraintBottom_toBottomOf="parent"

        app:layout_constraintEnd_toStartOf="@+id/blue"

        app:layout_constraintHorizontal_bias="0.858"

        app:layout_constraintStart_toStartOf="parent"

        app:layout_constraintTop_toTopOf="parent"

        app:layout_constraintVertical_bias="0.237" />



    <Button

        android:id="@+id/blue"

        android:layout_width="71dp"

        android:layout_height="48dp"

        android:layout_marginStart="8dp"

        android:layout_marginLeft="8dp"

        android:layout_marginTop="132dp"

        android:layout_marginEnd="8dp"

        android:layout_marginRight="8dp"

        android:background="#0000FF"

        android:text="BLUE"

        app:layout_constraintEnd_toEndOf="parent"

        app:layout_constraintStart_toStartOf="parent"

        app:layout_constraintTop_toTopOf="parent" />



    <Button

        android:id="@+id/indigo"

        android:layout_width="71dp"

        android:layout_height="48dp"

        android:layout_marginStart="12dp"

        android:layout_marginLeft="12dp"

        android:layout_marginTop="8dp"

        android:layout_marginEnd="8dp"

        android:layout_marginRight="8dp"

        android:layout_marginBottom="8dp"

        android:background="#4B0082"

        android:text="INDIGO"

        app:layout_constraintBottom_toBottomOf="parent"

        app:layout_constraintEnd_toEndOf="parent"

        app:layout_constraintHorizontal_bias="0.0"

        app:layout_constraintStart_toEndOf="@+id/blue"

        app:layout_constraintTop_toTopOf="parent"

        app:layout_constraintVertical_bias="0.23" />



    <Button

        android:id="@+id/violet"

        android:layout_width="411dp"

        android:layout_height="64dp"

        android:layout_marginTop="8dp"

        android:layout_marginBottom="8dp"

        android:background="#EE82EE"

        android:text="VIOLET"

        app:layout_constraintBottom_toBottomOf="parent"

        app:layout_constraintEnd_toEndOf="parent"

        app:layout_constraintHorizontal_bias="0.0"

        app:layout_constraintStart_toStartOf="parent"

        app:layout_constraintTop_toBottomOf="@+id/blue"

        app:layout_constraintVertical_bias="0.196" />

</android.support.constraint.ConstraintLayout>
表格布局主要代码：
<?xml version="1.0" encoding="utf-8"?>

<TableLayout xmlns:android="http://schemas.android.com/apk/res/android"

    android:layout_width="match_parent"

    android:layout_height="match_parent"

    android:background="@android:color/black"

    android:stretchColumns="0">

    <TableRow>

        <TextView

            android:text="    Open..."

            android:textColor="#FFFFFF"/>

        <TextView

            android:gravity="right"

            android:text="Ctrl-O"

            android:textColor="#FFFFFF"/>

    </TableRow>

    <TableRow>

        <TextView

            android:text="    Save..."

            android:textColor="#FFFFFF"/>

        <TextView

            android:gravity="right"

            android:text="Ctrl-S"

            android:textColor="#FFFFFF"/>

    </TableRow>

    <TableRow>

        <TextView

            android:text="    Save As..."

            android:textColor="#FFFFFF"/>

        <TextView

            android:gravity="right"

            android:text="Ctrl-Shift-S"

            android:textColor="#FFFFFF"/>

    </TableRow>

    <View

        android:layout_alignParentBottom="true"

        android:background="#FFFFFF"

        android:layout_width="fill_parent"

        android:layout_height="2dip"/>

    <TableRow>

        <TextView

            android:text="X Import..."

            android:textColor="#FFFFFF"

            />

    </TableRow>

    <TableRow>

        <TextView

            android:text="X Export..."

            android:textColor="#FFFFFF"/>

        <TextView

            android:gravity="right"



            android:text="Ctrl-E"

            android:textColor="#FFFFFF"/>

    </TableRow>

    <View

        android:layout_alignParentBottom="true"

        android:background="#FFFFFF"

        android:layout_width="fill_parent"

        android:layout_height="2dip"/>

    <TableRow>

        <TextView

            android:text="    Quit"

            android:textColor="#FFFFFF"/>

    </TableRow>

</TableLayout>
结果截图
线性布局：
  https://github.com/linyu0119/Layout/blob/master/app/images/4.png
约束布局：
  https://github.com/linyu0119/Layout/blob/master/app/images/5.png
表格布局：
  https://github.com/linyu0119/Layout/blob/master/app/images/6.png
