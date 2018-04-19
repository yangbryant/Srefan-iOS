# Srefan-iOS
![Language](https://img.shields.io/badge/language-ObjC-green.svg)![License](https://img.shields.io/github/license/yangbryant/Srefan-iOS.svg)

[Swift 版本请点击这里](https://github.com/yangbryant/Srefan-iOS/blob/master/README-Swift.md)



###  目录

* [库和框架](#libraries-and-frameworks)
* [数据存储](#data-saved)
	- [缓存](#cache)
	- [序列化](#serialization)
	- [Core Data](#core-data)
* [图表](#charts)
* [数据库](#database)
* [硬件](#hardware)
	- [动作](#motion)
	- [蓝牙](#bluetooth)
	- [位置](#location)
	- [iBeacon](#ibeacon)
* [事件总线（ EventBus ）](#eventbus)
* [文件](#files)
* [格式解析](#format)
	- [JSON](#json)
	- [CSV](#csv)
	- [XML&HTML](#xml&html)
* [日志](#logging)
* [地图](#maps)
* [浏览器](#browser)
* [多媒体](#media)
	- [图片](#image)
	- [音频](#audio)
	- [视频](#video)
	- [流媒体](#stream)
	- [PDF](#pdf)
	- [GIF](#GIF)
	- [VR](#VR)
	- [AR](#AR)
	- [二维码](#qrcode)
* [消息](#messaging)
* [网络](#networking)
* [Socket](#socket)
* [IM](#IM)
* [网络测试](#networking-test)
* [推送通知](#push-notifications)
* [Passbook](#passbook)
* [权限](#permissions)
* [URL Scheme](#url-scheme)
* [文本](#text)
* [UI](#ui)
	- [布局](#layout)
	- [Tabbar相关](#tabbar)
	- [Table相关](#tableview)
	- [HUD与Toast](#hud-and-toast)
	- [PopView](#pop)
	- [键盘与输入法](#keyboard)
	- [动画](#animation)
	- [定制化控件](#customized_widget)
* [分析](#analytics)
* [支付](#payments)
* [产品化工具](#products)
* [其他](#other)
* [实用工具](#utility)
* [安全](#security)
* [区块链](#blockchain)
* [逆向](#reverse)
* [数据结构/算法](#algorithm)
* [机器学习](#machine-learning)
* [App更新提示](#app-update-tips)
* [测试调试](#test-and-debug)


---

# <a name="libraries-and-frameworks"></a>库和框架

# <a name="data-saved"></a>数据存储

### <a name="cache"></a>缓存

* [YYCache](https://github.com/ibireme/YYCache): 高性能iOS缓存框架.

### <a name="serialization"></a>序列化

### <a name="core-data"></a>Core Data

# <a name="charts"></a>图表

* [AAChartKit](https://github.com/AAChartModel/AAChartKit): 流行的开源前端图表库Highcharts的基础上,封装的面向对象的,一组简单易用,极其精美的图表绘制控件.

# <a name="database"></a>数据库

* [FMDB](https://github.com/ccgus/fmdb): 基于SQLite封装的Cocoa/ObjC数据库的第三方框架.
* [OHMySQL](https://github.com/oleghnidets/OHMySQL): 一款App直连后台MySQL数据库的库.
* [](https://github.com/realm/realm-cocoa): 一款移动数据库,可替换Core Data和SQLite.

# <a name="hardware"></a>硬件

* [GBDeviceInfo](https://github.com/lmirosevic/GBDeviceInfo): 在运行时检测当前iOS或macOS设备硬件软件信息的第三个框架.

### <a name="motion"></a>动作

### <a name="bluetooth"></a>蓝牙

### <a name="location"></a>位置

### <a name="ibeacon"></a>iBeacon

# <a name="eventbus"></a>事件总线（EventBus）

# <a name="files"></a>文件

* [ZipArchive](https://github.com/ZipArchive/ZipArchive): 一款针对iOS,macOS和tvOS的简单实用的压缩解压缩的第三方框架.

# <a name="format"></a>格式解析

### <a name="json"></a>JSON

* [JSONModel](https://github.com/jsonmodel/jsonmodel): 一个快速巧妙的创建JSON数据模型的库.

### <a name="csv"></a>CSV

### <a name="xml&html"></a>XML&HTML

* [hpple](https://github.com/topfunky/hpple): 一款使用XPathQuery库解析HTML的ObjC封装的第三方框架.

# <a name="logging"></a>日志

* [CocoaLumberjack](https://github.com/CocoaLumberjack/CocoaLumberjack): 一个快速简单好用的日志框架.

# <a name="maps"></a>地图

# <a name="browser"></a>浏览器

* [KINWebBrowser](https://github.com/dfmuir/KINWebBrowser): 一款应用内的Web浏览器模块.
* [WebViewJavascriptBridge](https://github.com/marcuswestin/WebViewJavascriptBridge): 用于在WKWebViews/UIWebViews/WebViews中的ObjC和JavaScript之间发送消息的iOS/OSX桥接器.

# <a name="media"></a>多媒体

### <a name="image"></a>图片

* [LKImageKit](https://github.com/Tencent/LKImageKit): 腾讯开源的一个高性能的图片框架.包括了图片控件,图片下载,内存缓存,磁盘缓存,图片解码,图片处理等一系列能力.
* [SDWebImage](https://github.com/rs/SDWebImage): 一款知名高效的图片加载框架,其使用内存缓存,磁盘缓存和下载的方式加快了图片处理的效率.
* [RSKImageCropper](https://github.com/ruslanskorb/RSKImageCropper): 一个iOS的图片切片器,适用于头像的场景.

### <a name="audio"></a>音频

### <a name="video"></a>视频

* [ZFPlayer](https://github.com/renzifeng/ZFPlayer): 一款基于AVPlayer,支持竖屏,横屏(横屏可锁定屏幕方向),上下滑动调节音量、屏幕亮度，左右滑动调节播放进度的播放器.
* [JPVideoPlayer](https://github.com/newyjp/JPVideoPlayer): 在UITableViewCell内自动播放在线视频和缓存视频.

### <a name="stream"></a>流媒体

* [LFLiveKit](https://github.com/LaiFengiOS/LFLiveKit): 一款开源的RTMP流SDK,支持H264和AAC硬解码,支持GPUImage Beauty,rtmp传输,弱网络丢帧,动态切换速率.

### <a name="pdf"></a>PDF

### <a name="GIF"></a>GIF

### <a name="VR"></a>VR

### <a name="AR"></a>AR

### <a name="qrcode"></a>二维码

# <a name="messaging"></a>消息

# <a name="networking"></a>网络

* [AFNetworking](https://github.com/AFNetworking/AFNetworking): 一个轻量级的iOS网络通信类库.
* [YTKNetwork](https://github.com/yuantiku/YTKNetwork): 基于AFNetworking封装的iOS网络库,其实现了一套High Level的API,提供了更高层次的网络访问抽象.
    
# <a name="socket"></a>Socket

* [CocoaAsyncSocket](https://github.com/robbiehanson/CocoaAsyncSocket): 基于BSD-Socket的IM框架,强大的异步套接字库,向上封装出简单易用ObjC接口.

# <a name="IM"></a>IM

# <a name="networking-test"></a>网络测试

# <a name="push-notifications"></a>推送通知

# <a name="passbook"></a>Passbook

# <a name="permissions"></a>权限

# <a name="url-scheme"></a>URL Scheme

# <a name="text"></a>文本

* [TTTAttributedLabel](https://github.com/TTTAttributedLabel/TTTAttributedLabel): 一个富文本的UILabel替代方案,支持链接,数据检测,属性等.
* [RegexKitLite](https://github.com/wezm/RegexKitLite): 一个正则表达式的ObjC框架.
* [MitRegx](https://github.com/mcmengchen/MitRegx):用来校验手机号格式,密码格式,验证码格式和Email格式的ObjC框架.

# <a name="ui"></a>UI

* [YYKit](https://github.com/ibireme/YYKit): YYKit是一组功能丰富的iOS组件,包含 [YYModel](https://github.com/ibireme/YYModel) [YYCache](https://github.com/ibireme/YYCache) [YYImage](https://github.com/ibireme/YYImage) [YYWebImage](https://github.com/ibireme/YYWebImage) [YYText](https://github.com/ibireme/YYText) [YYKeyboardManager](https://github.com/ibireme/YYKeyboardManager) [YYDispatchQueuePool](https://github.com/ibireme/YYDispatchQueuePool) [YYAsyncLayer](https://github.com/ibireme/YYAsyncLayer) [YYCategories](https://github.com/ibireme/YYCategories) 独立组件.
* [QMUI](https://github.com/QMUI/QMUI_iOS): QMUI iOS是一个致力于提高项目UI开发效率的解决方案.

### <a name="layout"></a>布局

* [Masonry](https://github.com/SnapKit/Masonry): 应用最广的简单方便的自动布局框架.

### <a name="tabbar"></a>Tabbar相关

* [CYLTabBarController](https://github.com/ChenYilong/CYLTabBarController): 一个自定义的TabBarController框架,支持高度自定义,功能强大,使用起来非常方便.

### <a name="tableview"></a>Table相关

* [IGListKit](https://github.com/Instagram/IGListKit): 一款Instagram工程师开发的快速构建且滑动流畅的CollectView框架.
* [STDTableView](https://github.com/XuQibin/STDTableView): 基于UITableView的封装,实现了一套High Level的API.
* [MJRefresh](https://github.com/CoderMJLee/MJRefresh): 一款简单好用的下拉刷新的第三方框架.
* [ODRefreshControl](https://github.com/Sephiroth87/ODRefreshControl): 一款对UIScrollView下拉刷新的控件.
* [DZNEmptyDataSet](https://github.com/dzenbot/DZNEmptyDataSet): UITableView/UICollectionView空数据提示内容显示的控件.
* [CYLTableViewPlaceHolder](https://github.com/ChenYilong/CYLTableViewPlaceHolder): 一行代码完成'空TableView占位视图'管理的控件.

### <a name="hud-and-toast"></a>HUD与Toast

* [YBHud](https://github.com/YahyaBagia/YBHud): 一个简单的点动画,轻量级的指示器HUD.
* [SVProgressHUD](https://github.com/SVProgressHUD/SVProgressHUD): 一个进度加载的第三方控件.
* [MBProgressHUD](https://github.com/jdg/MBProgressHUD): 另外一个非常流行的进度加载的第三方控件.
* [RKDropdownAlert](https://github.com/cwRichardKim/RKDropdownAlert): 一个非常简单的向下弹出Alert视图的控件,灵感来自于SVProgressHUD.
* [JDStatusBarNotification](https://github.com/calimarkus/JDStatusBarNotification): 一个简单,可定制的状态栏显示通知控件.
* [CWStatusBarNotification](https://github.com/cezarywojcik/CWStatusBarNotification): 另外一个基于文本的状态栏通知控件.

### <a name="pop"></a>PopView

* [PSTAlertController](https://github.com/steipete/PSTAlertController): 向下兼容iOS7使用UIAlertController的第三方框架.
* [MMPopupView](https://github.com/adad184/MMPopupView): 一款简单的创建PopUpView的Pop-Up控件.

### <a name="keyboard"></a>键盘与输入法

* [IQKeyboardManager](https://github.com/hackiftekhar/IQKeyboardManager): 解决弹起键盘遮盖输入框的问题的便捷方案.
* [TPKeyboardAvoiding](https://github.com/michaeltyson/TPKeyboardAvoiding): 另外一个解决弹起键盘躲避文本框遮挡的通用方案.

### <a name="animation"></a>动画

* [lottie-ios](https://github.com/airbnb/lottie-ios): Airbnb开源的将AE动画效果转化为iOS原生动画的库.
* [JazzHands](https://github.com/IFTTT/JazzHands):一款简单的基于关键帧动画的框架,动画可以通过手势,scrollview,KVO和ReactiveCocoa控制.
* [FXBlurView](https://github.com/nicklockwood/FXBlurView): 实现毛玻璃效果的View视图,目前该项目不再更新.

### <a name="customized_widget"></a>定制化控件

* [STPickerView](https://github.com/STShenZhaoliang/STPickerView): 一个多功能的选择器,有城市选择,日期选择和单数组源自定的功能,方便大家的使用,低耦合,易扩展.
* [JKCountDownButton](https://github.com/shaojiankui/JKCountDownButton):iOS倒计时按钮,UIButton子类实现,常常用于注册等发送验证码的时候进行倒计时操作.
* [DGActivityIndicatorView](https://github.com/gontovnik/DGActivityIndicatorView): 一个比UIActivityIndicatorView更好看的显示加载进度的控件.

# <a name="analytics"></a>分析

# <a name="payments"></a>支付

# <a name="products"></a>产品化工具

# <a name="other"></a>其他

* [DateTools](https://github.com/MatthewYork/DateTools): 一款ObjC中简化日期和时间处理的工具.

# <a name="utility"></a>实用工具

* [BlocksKit](https://github.com/BlocksKit/BlocksKit): Block实用工具,可以把用delegate实现的方法整合成了block的形式.
* [ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa): 具有函数式编程和响应式编程特性的iOS和OS X开发的新框架.
* [SAMCategories](https://github.com/soffes/SAMCategories): 一个对Foundation和UIKit类别的有用的扩展集合.

# <a name="security"></a>安全

# <a name="blockchain"></a>区块链

# <a name="reverse"></a>逆向

# <a name="algorithm"></a>数据结构/算法

# <a name="machine-learning"></a>机器学习

# <a name="app-update-tips"></a>App更新提示

# <a name="test-and-debug"></a>测试调试
