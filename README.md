# Activity-Life-Cycle

As an activity transitions from state to state, it is notified of the change by calls to the following protected methods:

 void onCreate(Bundle savedInstanceState)
 void onStart()
 void onRestart()
 void onResume()
 void onPause()
 void onStop()
 void onDestroy()
These seven methods define the entire lifecycle of an activity.





2018-11-09 14:18:05.433 3748-3748/com.blogspot.androiddeveloperskills.androidactivity I/com.blogspot.androiddeveloperskills.androidactivity.BaseActivity: onCreate
2018-11-09 14:18:05.519 3748-3748/com.blogspot.androiddeveloperskills.androidactivity I/com.blogspot.androiddeveloperskills.androidactivity.BaseActivity: onStart
2018-11-09 14:18:05.520 3748-3748/com.blogspot.androiddeveloperskills.androidactivity I/com.blogspot.androiddeveloperskills.androidactivity.BaseActivity: onResume
2018-11-09 14:18:25.623 3748-3748/com.blogspot.androiddeveloperskills.androidactivity I/com.blogspot.androiddeveloperskills.androidactivity.BaseActivity: onPause
2018-11-09 14:18:25.776 3748-3748/com.blogspot.androiddeveloperskills.androidactivity I/com.blogspot.androiddeveloperskills.androidactivity.BaseActivity: onStop
