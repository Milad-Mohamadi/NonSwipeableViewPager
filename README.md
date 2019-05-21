# NonSwipeableViewPager
somtime we need to viewpager that can't swipe left or right because we use this view that extend viewpager android

1-crate LNonSwipeableViewPager class

2-use custom view in XML file:

    <com.example.lococoder.nonswipeableviewpager.LNonSwipeableViewPager
    android:id="@+id/viewPager"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    app:tabMode="fixed" />
