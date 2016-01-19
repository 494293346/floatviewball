# floatviewball
控件在该布局内可自由拖动，当控件拖动至中间释放时，自动向四周吸附,用法很简单（将需要的控件放入布局中即可:
 ```xml
 <cn.asheng.floatviewball.widget.FloatViewBall
        android:id="@+idiwFloatBall"
        android:layout_width="match_parent"
        android:layout_height="match_parent">
        <ImageView
            android:scaleType="fitXY"
            android:layout_marginTop="300dp"
            android:id="@+id/ivBall"
            android:layout_width="70dp"
            android:layout_height="70dp"
            android:layout_alignParentRight="true"
            android:src="@drawable/ic_launcher"
            android:visibility="gone" />   
 </cn.asheng.floatviewball.widget.FloatViewBall>
```

