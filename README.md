

    1.在什么条件下，代码示例可能会导致应用程序崩溃？你将如何修改代码以避免这个潜在的问题？解释你的答案。
    Intent sendIntent = new Intent();
    sendIntent.setAction(Intent.ACTION_SEND);
    sendIntent.putExtra(Intent.EXTRA_TEXT, textMessage);
    sendIntent.setType(HTTP.PLAIN_TEXT_TYPE); // "text/plain" MIME type
    startActivity(sendIntent);

    2.活动生命周期中的最后一个回调是onDestroy()。系统在您的活动上调用此方法，作为您的活动实例从系统内存中完全删除的最终信号。
   通常情况下，系统会调用onPause()和onStop()之前调用onDestroy()。描述一个场景，
   但是，在这里onPause()和onStop()将不会被调用。

    3.Serializable和Parcelable有什么区别？在Android中哪个是最好的方法？

    4.可以将所有数据库表更新保存在activity的onStop()吗？如果不行，解释为什么，并解释应该在哪里进行保存
         A.可以，   B.不可以保存在onSaveInstanceState   C.不，因为onStop不会被调用 
  
    5.请列出Android所有Context的类型。并简单说明他们的使用场景以及区别

    6.ArrayList和Vector之间有什么区别

    7.java中什么是检查异常，什么是未检查异常

    8.请给出几种屏幕适配的思路，尽可能详细。

    9. 请描述下Activity的生命周期。如何安全退出已调用多个Activity的Application？

    10. 简要解释一下Activity、Intent 、Intent filter、Service、Broadcase、BroadcaseReceiver。

    11. 请解释下在单线程模型中Message,Handler,Message Queue,Looper之间的关系。

    12. 列举Android的文件存储方式。

    13. AsyncTask使用在哪些场景？它的缺陷是什么？如何解决？

14. 什么情况会导致Crash ?如何避免?如何捕获导致其的异常?

15. Activity的几种LaunchMode及使用场景。

16. 内存溢出和内存泄漏有什么区别？何时会产生内存泄漏？内存优化有哪些方法？

17. ANR定位和修正。

18. 简要描述hybrid的通讯方式。

19. 简要描述Android中的几种动画。

20. 简要描述View的绘制流程。

21. 简要描述对MVC、MVP、MVVM的理解。

22. RecyclerView的常用方法。

23. 请列举使用过的热门开源项目，若有进行过源码分析和一定程度的改造可以整理一下思绪，面试的时候进行口述。
