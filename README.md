# 重要提醒
anyRTC 对该版本已经不再维护。[前往新版本](https://github.com/anyRTC/AriOSSDK).

**新版本功能如下：**
- 频道管理
- 音频管理
- 视频管理
- 音频文件播放及混音
- 音效文件播放管理
- CDN推流
- 本地推流CDN组件
- 本地播放器组件
- 跨频道流媒体转发
- 直播导入在线媒体流
- 视频双流模式
- 音频自采集自渲染
- 视频自采集自渲染
- 耳返功能
- 。。。

更多示列请前往**公司网址： [www.anyrtc.io](https://www.anyrtc.io)**

# anyRTC-RTCP-iOS

## 简介
anyRTC-RTCP-iOS实时直播，基于RTCPEngine SDK，实现快速实时直播，相比RTMPC更加快捷。</br>

## 安装
### 1、编译环境
Xcode 8以上</br>

### 2、运行环境
真机运行、iOS 8.0以上（建议最新）


## 导入SDK

### Cocoapods导入
```
pod 'RTCPEngine', '~> 3.0.2'
```
### 手动导入

1. 下载Demo，或者前往[anyRTC官网](https://www.anyrtc.io)下载SDK</br>
![list_directory](/image/list_directory.png)

2. 在Xcode中选择“Add files to 'Your project name'...”，将RTCPEngine.framework添加到你的工程目录中</br>

3.  打开General->Embedded Binaries中添加RTCPEngine.framework</br>


## 如何使用？

### 注册账号
登陆[AnyRTC官网](https://www.anyrtc.io/)

### 填写信息
创建应用，在管理中心获取开发者ID，AppID，AppKey，AppToken，替换AppDelegate.h中的相关信息

### 操作步骤：
1、一部手机开启直播，点击右上角复制按钮，将复制的内容发送给另一部手机；</br>

2、另一部手机复制，点击观看直播，粘贴复制的内容到输入框，开始观看直播。</br>

### 资源中心
 [更多详细方法使用，请查看API文档](https://docs.anyrtc.io/v1/RTCP/)

## 扫描二维码下载demo
![RTCP](/image/kRHw.png)


## 支持的系统平台
**iOS** 8.0及以上

## 支持的CPU架构
**iOS** armv7 、arm64。  支持bitcode

## ipv6
苹果2016年6月新政策规定新上架app必须支持ipv6-only。该库已经适配

## Android版anyRTC-RTCP
[anyRTC-Meeting-Android](https://github.com/AnyRTC/anyRTC-RTCP-Android)

## 网页版anyRTC-RTCP
[anyRTC-RTCP-Web](https://www.anyrtc.io/demo/rtcp)

## 更新日志

* 2020年02月27日：</br>

添加发布、取消发布监听</br>

* 2019年05月24日：</br>

修复观看端不操作锁屏问题</br>

* 2019年05月15日：</br>

SDK更新3.0.0版本</br>

* 2018年11月09日：</br>

修复观看实时直播几率崩溃问题

* 2018年11月08日：</br>

添加本地和远程的第一帧回调</br>

```
//本地视频第一帧
-(void)onRTCFirstLocalVideoFrame:(UIView*)videoView videoSize:(CGSize)size;

//远程视频第一帧
-(void)onRTCFirstRemoteVideoFrame:(UIView*)videoView videoSize:(CGSize)size;

//视频大小变化回调
- (void)onRTCVideoViewChanged:(UIView*)videoView didChangeVideoSize:(CGSize)size;
```

## 技术支持
* anyRTC官方网址：https://www.anyrtc.io </br>
* QQ技术交流群：554714720 </br>
* 联系电话:021-65650071-816 </br>
* Email:hi@dync.cc </br>

## 关于直播
本公司有一整套直播解决方案，特别针对移动端。本公司开发者平台[www.anyrtc.io](http://www.anyrtc.io)。除了基于RTMP协议的直播系统外，我公司还有基于WebRTC的时时交互直播系统、P2P呼叫系统、会议系统等。快捷集成SDK，便可让你的应用拥有时时通话功能。欢迎您的来电~

## License

RTCPEngine is available under the MIT license. See the LICENSE file for more info.

