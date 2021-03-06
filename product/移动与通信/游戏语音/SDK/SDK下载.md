

## v1.1.22
[Unity](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.22/gcloud_voice_1_1_22_184516_20181101_Unity3D.zip)
[Unity(bitcode)](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.22/gcloud_voice_1_1_22_184516_20181106_Unity3D_bitcode.zip)
[Cocos](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.22/gcloud_voice_1_1_22_184516_20181101_Cocos.zip)
[Cocos(bitcode)](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.22/gcloud_voice_1_1_22_184516_20181106_Cocos_bitcode.zip)
[Win64](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.22/gcloud_voice_winx64_1_1_22_184516_20181101.zip)
[Win32](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.22/gcloud_voice_win_1_1_22_184516_20181101.zip)
[iOS](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.22/gcloud_voice_1_1_22_184516_20181101_iOS.zip)
[iOS(bitcode)](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.22/gcloud_voice_1_1_22_184516_20181106_iOS_bitcode.zip)
[iOS(cpplib)](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.22/gcloud_voice_1_1_22_184516_20181101_iOS_cpplib.zip)
[Android](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.22/gcloud_voice_1_1_22_184516_20181101_Android.zip)
[UE4](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.22/gcloud_voice_1_1_22_184516_20181101_UE4.zip)

### 更新说明
- 增加对 IPV6 的支持（暂不包括离线语音和语音转文字功能）；
- 增加开麦被占用的回调；
- 增加部分动态开关的配置功能。



## v1.1.21
[Unity](http://lexizhang-1251557890.file.myqcloud.com/gvioce1.1.21/gcloud_voice_1_1_21_183471_20181016_Unity3D.zip)
[Unity(bitcode)](http://lexizhang-1251557890.file.myqcloud.com/gvioce1.1.21/gcloud_voice_1_1_21_183471_20181016_Unity3D_bitcode.zip)
[Cocos](http://lexizhang-1251557890.file.myqcloud.com/gvioce1.1.21/gcloud_voice_1_1_21_183471_20181016_Cocos.zip)
[Cocos(bitcode)](http://lexizhang-1251557890.file.myqcloud.com/gvioce1.1.21/gcloud_voice_1_1_21_183471_20181016_Cocos_bitcode.zip)
[Win64](http://lexizhang-1251557890.file.myqcloud.com/gvioce1.1.21/gcloud_voice_winx64_1_1_21_183471_20181016.zip)
[Win32](http://lexizhang-1251557890.file.myqcloud.com/gvioce1.1.21/gcloud_voice_win_1_1_21_183471_20181016.zip)
[iOS](http://lexizhang-1251557890.file.myqcloud.com/gvioce1.1.21/gcloud_voice_1_1_21_183471_20181016_iOS.zip)
[iOS(bitcode)](http://lexizhang-1251557890.file.myqcloud.com/gvioce1.1.21/gcloud_voice_1_1_21_183471_20181016_iOS_bitcode.zip)
[Android](http://lexizhang-1251557890.file.myqcloud.com/gvioce1.1.21/gcloud_voice_1_1_21_183471_20181016_Android.zip)
[UE4](http://lexizhang-1251557890.file.myqcloud.com/gvioce1.1.21/gcloud_voice_1_1_21_183471_20181016_UE4.zip)
### 更新说明
#### 一，性能优化
- 开启 pitch vad，预计流量可以降低 30%。
- 杂音优化；
- 增加静音键是否开启回调，详见接口变更；
- 混音算法优化；
- 瞬态降噪优化，无人声情况下消除屏幕敲击声；
- 去除对 libstdc++.6.0.9 依赖，支持 xcode 9.4。

#### 二，接口新增
增加接口判断 iOS 是否开启了静音键，通过回调通知游戏，建议项目组给玩家一个文本提示。
- 新加接口：GCloudVoiceErrno CheckDeviceMuteState()
- 新加回调：void OnMuteSwitchResult(int nState)

#### 三，其它说明
新加配置文件：mute_detect.aiff（请更新GCloudVoice.bundle）





## v1.1.19
[Unity](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.19/gcloud_voice_1_1_19_179869_20180808_Unity3D.zip)
[Unity(bitcode)](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.19/gcloud_voice_1_1_19_179869_20180808_Unity3D_bitcode.zip)[]()
[Cocos](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.19/gcloud_voice_1_1_19_179869_20180808_Cocos.zip)
[Cocos(bitcode)](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.19/gcloud_voice_1_1_19_179869_20180808_Cocos_bitcode.zip)
[Win64](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.19/gcloud_voice_winx64_1_1_19_179869_20180808.zip)
[Win32](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.19/gcloud_voice_win_1_1_19_179869_20180808.zip)
[iOS](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.19/gcloud_voice_1_1_19_179869_20180808_iOS.zip)
[iOS(bitcode)](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.19/gcloud_voice_1_1_19_179869_20180808_iOS_bitcode.zip)
[Android](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.19/gcloud_voice_1_1_19_179869_20180808_Android.zip)
[UE4](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.19/gcloud_voice_1_1_19_179869_20180808_UE4.zip)
[symbol](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.19/gcloud_voice_1_1_19_179869_20180808_symbol.zip)

### 更新说明
#### 1、新增功能
- 音质优化，流畅性优化;
- 蓝牙耳机兼容性优化；
- 第三方 app 中断响应（QQ，微信，系统闹钟，电话等）优化;
- 服务器动态调整算法参数支持。

#### 2、新增接口
增加开关麦成功或失败回调（见 OnEvent 回调接口，枚举值详见 GCloudVoiceErrno.h）



## v1.1.17
[C++\Cocos2D SDK 1.1.17 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.17.0719/0719/gcloud_voice_1_1_17_173027_20180428_Cocos.zip)

[Unity3D SDK 1.1.17 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.17.0719/0719/gcloud_voice_1_1_17_173027_20180428_Unity3D.zip)

[Android SDK 1.1.17 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.17.0719/0719/gcloud_voice_1_1_17_173027_20180428_Android.zip)

[iOS SDK 1.1.17 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.17.0719/0719/gcloud_voice_1_1_17_173027_20180428_iOS.zip)

[iOS(bitcode) SDK 1.1.17 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.17.0719/0719/gcloud_voice_1_1_17_168537_20180211_iOS_bitcode.zip)

[Win64 1.1.17 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.17.0719/0719/gcloud_voice_winx64_1_1_17_173027_20180428.zip)

[Win32 1.1.17 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.17.0719/0719/gcloud_voice_win_1_1_17_173027_20180428.zip)

[UE4 1.1.17 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.17.0719/0719/gcloud_voice_1_1_17_168537_20180211_UE4.zip)

#### 1、新增功能
- OC 接口修复设置音效功能。
- 修复部分数据上报异常（openID+url）为空。
- OC 增加 setvoiceeffict 接口。

## v1.1.17.beta
[C++\Cocos2D SDK 1.1.17.beta 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.17.beta/gcloud_voice_1_1_17_168230_20180206_Cocos.zip)

[Unity3D SDK 1.1.17.beta 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.17.beta/gcloud_voice_1_1_17_168230_20180206_Unity3D.zip)

[Android SDK 1.1.17.beta 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.17.beta/gcloud_voice_1_1_17_168230_20180206_Android.zip)

[iOS SDK 1.1.17.beta 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.17.beta/gcloud_voice_1_1_17_168230_20180206_iOS.zip)

[iOS(bitcode) SDK 1.1.17.beta 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.17.beta/gcloud_voice_1_1_17_168230_20180206_iOS_bitcode.zip)

[Win64 1.1.17.beta 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.17.beta/gcloud_voice_winx64_1_1_17_168230_20180207.zip)

[Win32 1.1.17.beta 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.17.beta/gcloud_voice_win_1_1_17_168230_20180207.zip)

[UE4 1.1.17.beta 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.17.beta/gcloud_voice_1_1_17_168230_20180206_UE4.zip)


#### 1、新增功能
- 增强抗丢包和网络抖动能力，提升上下行语音数据的可靠性。
- 此版本为公测版本，请根据需求选择接入。

## v1.1.16
[C++\Cocos2D SDK 1.1.16 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.16/gcloud_voice_1_1_16_166568_20180111_Cocos.zip) 

[Unity3D SDK 1.1.16 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.16/gcloud_voice_1_1_16_166568_20180111_Unity3D.zip) 

[Android SDK 1.1.16 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.16/gcloud_voice_1_1_16_166568_20180111_Android.zip) 

[iOS SDK 1.1.16 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.16/gcloud_voice_1_1_16_166568_20180111_iOS.zip) 

[iOS(bitcode) SDK 1.1.16 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.16/gcloud_voice_1_1_16_166568_20180111_iOS_bitcode.zip) 

[Win64 1.1.16 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.16/gcloud_voice_winx64_1_1_16_166568_20180112.zip) 

[Win32 1.1.16 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.16/gcloud_voice_win_1_1_16_166568_20180112.zip) 

[UE4 1.1.16 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.16/gcloud_voice_1_1_16_166568_20180111_UE4.zip)

#### 1、新增功能
- 修复部分 BUG。
- 在使用变声功能的时候，提高语音识别的翻译准确率。

## v1.1.15
[C++\Cocos2D SDK 1.1.15 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.15/gcloud_voice_1_1_15_164628_20171214_Cocos.zip)

[Unity3D SDK 1.1.15 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.15/gcloud_voice_1_1_15_164628_20171214_Unity3D.zip)

[Android SDK 1.1.15 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.15/gcloud_voice_1_1_15_164628_20171214_Android.zip)

[iOS SDK 1.1.15 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.15/gcloud_voice_1_1_15_164628_20171214_iOS.zip)

[iOS(bitcode) SDK 1.1.15 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.15/gcloud_voice_1_1_15_164628_20171214_iOS_bitcode.zip)

[Win64 1.1.15 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.15/gcloud_voice_winx64_1_1_15_164628_20171214.zip)

[Win32 1.1.15 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.15/gcloud_voice_win_1_1_15_164628_20171214.zip)

[UE4 1.1.15 版本](http://lexizhang-1251557890.file.myqcloud.com/gvoice1.1.15/gcloud_voice_1_1_15_164628_20171214_UE4.zip)

#### 1、新增功能
1. 提供全局范围语音功能，基于游戏中玩家坐标范围来决定语音通话参与者数量（可参考 PUBG 中的全局语音功能）。
2. 支持加入多语音房间，现在一个玩家最多可以参与 2 个小队语音，或参与 1 个小队语音和 1 个范围语音。

## v1.1.14（不发布）

1. 代码合入

## v1.1.13 
[C++\Cocos2D SDK 1.1.13 版本](http://lexizhang-1251557890.cossh.myqcloud.com/gcloud_voice_1_1_13_160197_20171026_Cocos.zip)

[Unity3D SDK 1.1.13 版本](http://lexizhang-1251557890.cossh.myqcloud.com/gcloud_voice_1_1_13_160197_20171026_Unity3D.zip)

[Android SDK 1.1.13 版本](http://lexizhang-1251557890.cossh.myqcloud.com/gcloud_voice_1_1_13_160197_20171026_Android.zip)

[iOS SDK 1.1.13 版本](http://lexizhang-1251557890.cossh.myqcloud.com/gcloud_voice_1_1_13_160197_20171026_iOS.zip)

[iOS(bitcode) SDK 1.1.13 版本](http://lexizhang-1251557890.cossh.myqcloud.com/gcloud_voice_1_1_13_160197_20171026_iOS_bitcode.zip)

[Win64 1.1.13 版本](http://lexizhang-1251557890.cossh.myqcloud.com/gcloud_voice_winx64_1_1_12_159258_20171016.zip)

[Win32 1.1.13 版本](http://lexizhang-1251557890.cossh.myqcloud.com/gcloud_voice_win_1_1_12_159258_20171016.zip)

#### 1、新增功能
- 噪音优化  
- 回声优化  


## v1.1.12 （2017-10-18）   
[C++\Cocos2D SDK 1.1.12 版本](http://lexizhang-1251557890.cossh.myqcloud.com/gcloud_voice_1_1_12_159258_20171014_Cocos.zip)

[Unity3D SDK 1.1.12 版本](http://lexizhang-1251557890.cossh.myqcloud.com/gcloud_voice_1_1_12_159258_20171014_Unity3D.zip)

[Android SDK 1.1.12 版本](http://lexizhang-1251557890.cossh.myqcloud.com/gcloud_voice_1_1_12_159258_20171014_Android.zip)

[iOS SDK 1.1.12 版本](http://lexizhang-1251557890.cossh.myqcloud.com/gcloud_voice_1_1_12_159258_20171014_iOS.zip)

[iOS(bitcode) SDK 1.1.12 版本](http://lexizhang-1251557890.cossh.myqcloud.com/gcloud_voice_1_1_12_159258_20171014_iOS_bitcode.zip)

[Win64 1.1.12 版本](http://lexizhang-1251557890.cossh.myqcloud.com/gcloud_voice_winx64_1_1_12_159258_20171016.zip)

[Win32 1.1.12 版本](http://lexizhang-1251557890.cossh.myqcloud.com/gcloud_voice_win_1_1_12_159258_20171016.zip)
      
#### 1、新增功能
- 语音增强扛丢包和网络抖动的能力  
- 语音消息最长时间从 3 分钟提升至 5 分钟  
- 支持每个用户（按 OpenID 区别）保存一条永久语音消息  


## v1.1.11（2017-9-13）
#### 1、新增功能
- 支持识别男、女声音  
- 支持变声  
- 解决部分小运营商域名劫持的问题  
- 解决高质量语音模式下，小队语音出现声音卡顿的问题  
- 修复接入蓝牙耳机，耳机低电量时，声音从扬声器出来的缺陷  
- 修复接入蓝牙耳机，录制语音消息时，结束录音后声音从扬声器出来的缺陷  
- 修复接入蓝牙耳机，实时语音中，拨打电话后，声音从扬声器出来的缺陷  


## v1.1.8（2017-06-23）   

[C++\Cocos2D SDK 1.1.8 版本](https://mc.qcloudimg.com/static/archive/ad7e3bd1bdc742c0a2272cd85bdee3a9/gcloud_voice_1_1_8_151417_20170704_Cocos.zip)

[Unity3D SDK 1.1.8 版本](https://mc.qcloudimg.com/static/archive/29f013461515642b4b99e46b327a865a/gcloud_voice_1_1_8_151417_20170704_Unity3D.zip)

[Android SDK 1.1.8 版本](https://mc.qcloudimg.com/static/archive/ae191d585529ba38d16f921f37cf8917/gcloud_voice_1_1_8_151417_20170704_Android.zip)

[iOS SDK 1.1.8 版本](https://mc.qcloudimg.com/static/archive/5e719fa75cc4ae9150e31a5990f29c0b/gcloud_voice_1_1_8_151417_20170704_iOS.zip)

[Win64 1.1.8 版本](https://mc.qcloudimg.com/static/archive/01ea9bec7ba32948b16c00caeae14e5b/gcloud_voice_winx64_1_1_8_150892_20170622.zip)

[Win32 1.1.8 版本](https://mc.qcloudimg.com/static/archive/ad0e05ca7d710811621c1bfc3f6dbee6/gcloud_voice_win_1_1_8_150892_20170622.zip)

#### 1、新增功能
- GVoice 海外服务地区新增日本、马来西亚两个国家  
- 新增高质量语音模式，语音更清晰，同时会增加流量消耗，专门应用于狼人杀等以语音为核心玩法的游戏。  
- 在调用 SetMode() 的时候，传入 HIGHQUALITY 枚举值即可使用高质量语音模式  
- iOS 平台的 SDK，由 C++ 变为 Objective-C  
- 由于关闭了 iOS bitcode 选项，SDK 包变小是正常现象 
