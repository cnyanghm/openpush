# openpush
open push messaging framework for android phone in china


	OpenPush Messaging Framework for Android mobile in China

	Author : yanghm.cn@139.com




This file is in English and Chinese ( below )

------------------------------------------------------------------------------

Why is there this project?


	As all know, we can't use the google services in china. the the Google
	service maybe even not installed in the android mobile sold in china.
	For me, one important thing is the gcm, google messaging, can't be used
	here.

	If you want your app used in china properly, you must have yourself
	messaging built-in your app. It seems no problem for android allows any
	app runing service in background.

	Imaging the case, in a mobile phone , a lot of app run their services
	in the background, the bettery usage time will decreased significantly !
	so, our vendor have get a smart solution making their android system to
	kill the app's background services. Obviously, your app is not immune.

	But we need a reliable messaging service, not killed by the system.

	This service should be supplied by the mobile phone vendor,  but many of
	them just ignore this matter. Some vendors such as xiaomi, huawei have
	done it and public their API for all app.

	OK ? but they are not the same. We must write different code for
	different vendor. Our app need an unified API to get the service, like
	we do the same thing for gcm.

	How to ?

	Here, we proposed a simple messaging service framework. Each mobile
	phone vendor provides this service in its mobile.

	In this framework, our app doesn't need to use any additional library.


Code

	OpenPush is the ref source code for the service. You can rewrite it,
	especially the networking part.

	Pushapp is a demo app using this service. It is simple and clear, you
	can understand how it uses the service.
	Through this demo code, you will get how to write your service code.


promotion

	I call this framework as "unified messaging", hope each mobile phone
	vendor provides this service in their mobile.

	All app can simply adapt it to avoid the mess situation now.

	If you are interested in this promotion, contact me.

------------------------------------------------------------------------------
Chinese here

为什么有这个项目 ?


	我们知道, 在中国不能使用 google 的服务. 在中国销售的手机甚至没有安装 google 的服务.
	所以, 象推送消息这样由 google gcm 提供的服务, 在中国是不可以使用的.

	这是一个问题. 你的 app 要在中国市场的 android 手机上可用, 需要自带消息推送. 这是可以做到的,
	因为 android 允许 app 使用后台服务.

	重要的问题来了, 一大堆 app 在后台运行, 会减少手机电池的续航时间. 所以, 在中国销售的手机
	系统有一个特殊任务, 就是杀死这些后台服务. 这样的话, 你的 app 就收不到推送消息了.

	我们 app 需要一个可靠的,不被杀死的推送消息系统.

	这件事应该由手机厂商来做. 例如小米, 华为已经在做这件事. 但它们使用不同的 API, app 厂商需要
	专门为不同品牌的手机编写不同的适应程序. 还有更多的厂商根本不关心这件事.

	在中国市场销售的手机厂商众多, 需要共同制定 API 来代替 google gcm, 让各 app 来使用.

	我们这里提出了一个简单的推送服务框架. 每个手机厂商为它自己生产的手机提供推送服务. 基于一致
	的接口, app 可以简单地, 一致地, 适应它们.

	 app 不需要使用任何附加的库文件, 就可以使用这个服务.


代码


	OpenPush 是推送服务的参考源代码. 你可以改写它, 特别其中的网络通讯部分.

	pushapp  是使用这个推送服务的 app, 它非常简单, 你通过它可以了解 OpenPush 应该怎么编写.



推动这件事


	我把这个推送机制叫"统一推送", 希望最终各手机厂商能在出厂的手机上提供这个服务. 这样的话,
	app 厂商就可以很简单地适应这些手机, 而不是现在这个混乱的局面.

	如果你有兴趣来共同推动这件事, 联系我.



------------------------------------------------------------------------------



