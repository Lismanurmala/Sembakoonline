About
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".About">

    <EditText
        android:id="@+id/editTextTextPersonName5"
        android:layout_width="275dp"
        android:layout_height="57dp"
        android:ems="10"
        android:inputType="textPersonName"
        android:text="Call Center : 52341"
        tools:ignore="MissingConstraints"
        tools:layout_editor_absoluteX="68dp"
        tools:layout_editor_absoluteY="385dp" />

    <ImageView
        android:id="@+id/imageView"
        android:layout_width="245dp"
        android:layout_height="180dp"
        app:srcCompat="@drawable/logo"
        tools:ignore="MissingConstraints"
        tools:layout_editor_absoluteX="83dp"
        tools:layout_editor_absoluteY="116dp" />

    <EditText
        android:id="@+id/editTextTextPersonName3"
        android:layout_width="279dp"
        android:layout_height="55dp"
        android:ems="10"
        android:inputType="textPersonName"
        android:text="WhatsApp : 085678643254"
        tools:ignore="MissingConstraints"
        tools:layout_editor_absoluteX="66dp"
        tools:layout_editor_absoluteY="536dp" />

    <EditText
        android:id="@+id/editTextTextPersonName4"
        android:layout_width="279dp"
        android:layout_height="54dp"
        android:ems="10"
        android:inputType="textPersonName"
        android:text="Email :Smbk.Online@gmail.com"
        tools:ignore="MissingConstraints"
        tools:layout_editor_absoluteX="66dp"
        tools:layout_editor_absoluteY="461dp" />

    <EditText
        android:id="@+id/editTextTextPersonName2"
        android:layout_width="279dp"
        android:layout_height="55dp"
        android:ems="10"
        android:inputType="textPersonName"
        android:text="FAQ"
        tools:ignore="MissingConstraints"
        tools:layout_editor_absoluteX="64dp"
        tools:layout_editor_absoluteY="616dp" />

</androidx.constraintlayout.widget.ConstraintLayout>

SplashScreen
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".SplashScreen"
    android:id="@+id/splash_screen">

    <ImageView
        android:layout_width="250dp"
        android:layout_height="250dp"
        android:layout_centerHorizontal="true"
        android:layout_centerVertical="true"
        android:backgroundTint="#FFFFFF"
        android:scaleType="centerCrop"
        android:src="@drawable/logo"/>

</RelativeLayout>

Main
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    tools:context=".MainActivity">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_margin="16dp"
        android:orientation="vertical">

        <LinearLayout
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:orientation="horizontal">

            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Warung Online"
                android:textColor="#595959"
                android:textSize="20dp"/>

            <View
                android:layout_gravity="center"
                android:layout_width="40dp"
                android:layout_height="6dp"
                android:layout_marginLeft="5dp"
                android:background="@color/colorPrimary"/>
        </LinearLayout>

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Selamat Datang di Warung Online"/>

    </LinearLayout>

    <androidx.cardview.widget.CardView

        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_margin="16dp"
        android:clickable="true"
        app:cardElevation="13dp"
        app:cardCornerRadius="6dp"
        android:focusable="true"
        app:cardBackgroundColor="@color/colorPrimary">


        <LinearLayout
            android:padding="10dp"
            android:gravity="center"
            android:layout_width="match_parent"
            android:layout_height="100dp"
            android:orientation="horizontal">

            <LinearLayout
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:orientation="vertical">

                <TextView
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text=""
                    android:textColor="#fff"
                    android:textSize="20dp"/>

                <TextView
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text="Warung Online"
                    android:textColor="#fff"
                    android:textSize="35dp" />

            </LinearLayout>

            <RelativeLayout
                android:layout_width="match_parent"
                android:layout_height="match_parent">

                <ImageView
                    android:layout_width="78dp"
                    android:layout_height="80dp"
                    android:layout_alignParentRight="true"
                    android:layout_centerVertical="true"
                    android:src="@drawable/logo" />

            </RelativeLayout>

        </LinearLayout>

    </androidx.cardview.widget.CardView>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_margin="16dp"
        android:weightSum="2"
        android:orientation="horizontal">

        <androidx.cardview.widget.CardView
        android:layout_weight="1"
        android:layout_width="match_parent"
        android:layout_height="120dp"
        android:layout_margin="5dp"
        android:clickable="true"
        android:foreground="?android:attr/selectableItemBackground"
        app:cardCornerRadius="3dp"
        app:cardElevation="3dp">

        <RelativeLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:padding="3dp">

            <RelativeLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:padding="3dp">

                <TextView
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text="Produk"
                    android:textSize="18dp"
                    android:textColor="#5e5e5e"
                    android:textStyle="bold"/>
                <ImageView
                    android:layout_width="120dp"
                    android:layout_height="90dp"
                    android:src="@drawable/product"
                    android:layout_alignParentRight="true"
                    android:layout_alignParentBottom="true"/>

            </RelativeLayout>

        </RelativeLayout>


    </androidx.cardview.widget.CardView>

        <androidx.cardview.widget.CardView
            android:layout_width="match_parent"
            android:layout_height="120dp"
            android:layout_margin="5dp"
            android:clickable="true"
            android:foreground="?android:attr/selectableItemBackground"
            app:cardCornerRadius="3dp"
            app:cardElevation="3dp">

            <RelativeLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:padding="3dp">

                <RelativeLayout
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:padding="3dp">

                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:text="Pesanan"
                        android:textSize="18dp"
                        android:textColor="#5e5e5e"
                        android:textStyle="bold"/>

                    <ImageView
                        android:layout_width="120dp"
                        android:layout_height="90dp"
                        android:layout_alignParentRight="true"
                        android:layout_alignParentBottom="true"
                        android:layout_marginRight="168dp"
                        android:layout_marginBottom="4dp"
                        android:src="@drawable/pesanan" />

                </RelativeLayout>

            </RelativeLayout>



        </androidx.cardview.widget.CardView>



    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_margin="16dp"
        android:weightSum="2"
        android:orientation="horizontal">

        <androidx.cardview.widget.CardView
            android:layout_weight="1"
            android:layout_width="match_parent"
            android:layout_height="120dp"
            android:layout_margin="5dp"
            android:clickable="true"
            android:foreground="?android:attr/selectableItemBackground"
            app:cardCornerRadius="3dp"
            app:cardElevation="3dp">

            <RelativeLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:padding="3dp">

                <RelativeLayout
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:padding="3dp">

                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:text="Lacak"
                        android:textSize="18dp"
                        android:textColor="#5e5e5e"
                        android:textStyle="bold"/>
                    <ImageView
                        android:layout_width="120dp"
                        android:layout_height="90dp"
                        android:src="@drawable/lacak"
                        android:layout_alignParentRight="true"
                        android:layout_alignParentBottom="true"/>

                </RelativeLayout>

            </RelativeLayout>


        </androidx.cardview.widget.CardView>

        <androidx.cardview.widget.CardView
            android:layout_width="match_parent"
            android:layout_height="120dp"
            android:layout_margin="5dp"
            android:clickable="true"
            android:foreground="?android:attr/selectableItemBackground"
            app:cardCornerRadius="3dp"
            app:cardElevation="3dp">

            <RelativeLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:padding="3dp">

                <RelativeLayout
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:padding="3dp">

                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:text="About"
                        android:textSize="18dp"
                        android:textColor="#5e5e5e"
                        android:textStyle="bold"/>

                    <ImageView
                        android:layout_width="120dp"
                        android:layout_height="90dp"
                        android:layout_alignParentRight="true"
                        android:layout_alignParentBottom="true"
                        android:layout_marginRight="168dp"
                        android:layout_marginBottom="4dp"
                        android:src="@drawable/icon" />

                </RelativeLayout>

            </RelativeLayout>

        </androidx.cardview.widget.CardView>

    </LinearLayout>

    <TextView
        android:layout_width="match_parent"
        android:textAlignment="center"
        android:layout_height="wrap_content"
        android:layout_margin="16dp"
        android:text="Apk v.0.0.1"/>

</LinearLayout>

Produk
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    tools:context=".MainActivity">

    <SearchView
        android:id="@+id/searchView"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        app:layout_constraintBottom_toBottomOf="@id/searchView" />

    <ListView
        android:id="@+id/listView"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:padding="2dp"
        app:layout_constraintTop_toBottomOf="@id/searchView" />
</LinearLayout>


