# NonSwipeableViewPager
somtime we need viewpager that doesn't swipe left or right so we use this view that is extended from android viewpager 

1-crate LNonSwipeableViewPager class

2-use custom view in XML file:

    <com.example.lococoder.nonswipeableviewpager.LNonSwipeableViewPager
    android:id="@+id/viewPager"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    app:tabMode="fixed" />
