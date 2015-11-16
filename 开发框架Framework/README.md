# AndroidLibs == 开发框架 Framework

包含：各种快速开发框架、测试框架、系统框架、设计模式框架……

[<==返回首页==](https://github.com/XXApple/AndroidLibs)

---

**PalDB**:[https://github.com/linkedin/PalDB](https://github.com/linkedin/PalDB)

PalDB is an embeddable write-once key-value store written in Java.

<img src="https://camo.githubusercontent.com/ecc61cd7891461f7f839c47a58f47ac15b114cc7/687474703a2f2f6c696e6b6564696e2e6769746875622e696f2f50616c44422f646f632f7468726f7567687075742e706e67" width="320" />
<img src="https://camo.githubusercontent.com/5b16b19cd524b0fc3307ae37d96bf939295f0d4f/687474703a2f2f6c696e6b6564696e2e6769746875622e636f6d2f50616c44422f646f632f6d656d6f72792e706e67" width="320" />

---

**Lynx**：[https://github.com/pedrovgs/Lynx](https://github.com/pedrovgs/Lynx)

Lynx is an Android library created to show a custom view with all the information logcat is printing

---

**MultipleTheme**：[https://github.com/dersoncheng/MultipleTheme](https://github.com/dersoncheng/MultipleTheme)

Android换肤／夜间模式的Android框架，配合theme和换肤控件框架可以做到无缝切换换肤（无需重启应用和当前页面）。 This framework of Android app support multiple theme(such as day/night mode) and needn’t finish current application or current activity when you switch theme-mode.

---

**AndroidFontsManager**: [https://github.com/GcsSloop/AndroidFontsManager](https://github.com/GcsSloop/AndroidFontsManager)

字体管理器，方便快速的为应用内所有组件更换字体。

<img src="https://github.com/GcsSloop/AndroidFontsManager/blob/master/Pic/fontsmanagerdemo.gif" width="320" />

---

**xUtils**: [https://github.com/wyouflf/xUtils](https://github.com/wyouflf/xUtils)

android orm, bitmap, http, view inject...

---

**afinal**: [https://github.com/yangfuhai/afinal](https://github.com/yangfuhai/afinal)

Afinal是一个android的ioc，orm框架，内置了四大模块功能：FinalAcitivity,FinalBitmap,FinalDb,FinalHttp。通过finalActivity，我们可以通过注解的方式进行绑定ui和事件。通过finalBitmap，我们可以方便的加载bitmap图片，而无需考虑oom等问题。通过finalDB模块，我们一行代码就可以对android的sqlite数据库进行增删改查。通过FinalHttp模块，我们可以以ajax形式请求http数据。

---

**KJFrameForAndroid**: [https://github.com/kymjs/KJFrameForAndroid](https://github.com/kymjs/KJFrameForAndroid)

An Android library and includes ActivityFrame, KJHttp, KJBitmap, KJDataBase. KJFrameForAndroid is designed to wrap complexity of the Android native SDK and keep things simple.[http://www.kymjs.com/works](http://www.kymjs.com/works)

---

**ThinkAndroid**: [https://github.com/white-cat/ThinkAndroid](https://github.com/white-cat/ThinkAndroid)

ThinkAndroid是一个免费的开源的、简易的、遵循Apache2开源协议发布的Android开发框架，其开发宗旨是简单、快速的进行 Android应用程序的开发，包含Android mvc、简易sqlite orm、ioc模块、封装Android httpclitent的http模块, 具有快速构建文件缓存功能，无需考虑缓存文件的格式，都可以非常轻松的实现缓存，它还基于文件缓存模块实现了图片缓存功能， 在android中加载的图片的时候，对oom的问题，和对加载图片错位的问题都轻易解决。他还包括了一个手机开发中经常应用的实用工具类， 如日志管理，配置文件管理，android下载器模块，网络切换检测等等工具。[http://www.thinkandroid.cn](http://www.thinkandroid.cn)

---

**AndroidFine**: [https://github.com/tianshaojie/AndroidFine](https://github.com/tianshaojie/AndroidFine)

* 沉浸式状态栏，界面更漂亮
* 左滑返回，非常流畅
* 简单、可复用、易扩展的底部导航
* PagerSlidingTabStrip，导航标签文字颜色和选中时文字颜色，都可以通过xml设置
* 轮播图，自动+无限轮播
* 启动导航图SplashActivity，或许不用改就可以用
* 查看大图，集成了PhotoView的可用Activity，你不用再写了
* QuickAdapter快速的Adapter开发，不用在重复写ViewHolder类
* 如果发现ListView不流畅请告诉我
* PullToRefresh、PullToZoomView，这些常用的看demo吧
* HttpClient集成了OkHttpClient，基本的get，post，方便扩展和整合
* Picasso.with(context).load("url).into(imageView)，舒服且强大的图片加载
* 各种utils，拿来就可以用
* [Android编码规范](http://tianshaojie.github.io/android-code-style)，简单才能规范


精致Demo

<img src="http://images0.cnblogs.com/blog2015/275810/201508/232033560975081.jpg" width="320" />

---

**FastAndroid**: [https://github.com/huntermr/FastAndroid](https://github.com/huntermr/FastAndroid)

这是一个封装了多方面开源库后基于MVP模式的一个Android快速开发框架。融入了MVP模式,将Activity或Fragment做为View层、抽象出Presenter用于处理业务逻辑、Model处理网络访问，数据封装等，降低模块之间耦合，提高可维护性及扩展。QQ交流群：310262562

主要功能有：网络访问、上传下载、数据库操作、图片加载、View注解等等

项目说明：<br />
1.在项目中自定义了Header视图,可自定义左右按钮,点击事件以及标题<br />
2.项目中有演示MVP的源码,请自行翻阅<br />
3.封装了BaseAdapter,提供了更加完善的方法,具体请查看CustomBaseAdapter源码<br />
4.以单例模式封装了网络访问层,整个项目的访问接口共用一个,并且初始化时设置了一些访问配置,方便开发者自行修改。请查看NetCenter源码<br />
5.抽象出公共请求参数及响应参数,所有的请求实体类都继承自BaseRequest,方便设置公共请求参数<br />
6.所有响应实体类都可通过Response解析获得,Response继承自BaseResponse,请自行查阅源码<br />
7.请求时可直接传入请求实体类,框架会自动封装成相应的请求参数及公共请求参数.<br />
8.该框架自定义了Activity的回退栈,方便用户在任何地方获取当前的Context.可自行查阅AppManager源码<br />
9.框架中新增了一个BaseCameraActivity,该Activity主要用于调用系统摄像头及相册,并自带剪切功能<br />
10.IBaseView中封装了常用的View操作,如Toast,进度条等等,并通过BaseActivity实现了,所以建议所有Activity都继承自BaseActivity以便更好的使用本框架<br />
11.TransactionListener该监听是Presenter用于监听Model的处理状态,可接受泛型后在onSuccess(T t)中接受处理结果<br />

---
