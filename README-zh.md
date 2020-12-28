# 涂鸦智能Android SDK

---

## 功能概述

涂鸦智能APP SDK提供了与硬件设备、涂鸦云通讯的接口封装，加速应用开发过程，主要包括了以下功能：

- 硬件设备相关（配网、控制、状态上报、定时任务、群组、固件升级、共享）
- 账户体系（手机号、邮箱的注册、登录、重置密码等通用的账户功能）
- 家庭体系 （家庭管理，房间管理等功能）
- 涂鸦云HTTP API接口封装 (参见[涂鸦云api调用](https://docs.tuya.com/cn/cloudapi/appAPI/index.html))

## 心路历程
我是一名普通的打工人   之前参加过涂鸦和立创的关于电路设计的训练营 学会了用立创eda来画电路和pcb
后面听说涂鸦有关于软件来控制智能设备的训练营就来参加了
先是运行demo  之前要下载android studio 来构建环境   但是在用虚拟设备来运行的builded apk文件总是失败
后面投机取巧直接在真机上安装才运行demo成功。之后在群里听到小乐说了关于这个问题，他是怎么解决的  是在Android
sdk选项的package中把关于x86和x64的包选上再重新编译就没问题   我才在虚拟机上运行成功。
当收到涂鸦科技提供的灯泡和灯座时  距离deadeline所剩无几  然后我就简单的又重新编译了demo lamp然后第一次注册了
GitHub的账户上传了这个demo的源代码   希望之后可以把这个 app完善好，后面接入更多的智能设备  去打造智能家居吧。
最后感谢涂鸦智能为我这样的小白提供的学习机会！和通过app和实物的联动这样有意思的学习方式。


## 增加曝光
This project is developed using Tuya App SDK, which enables you to quickly develop branded apps
 connecting and controlling smart scenarios of many devices.

For more information, please check [Tuya Developer Website]
(https://developer.tuya.com/en/docs/iot/app-development/sdk-development/app-sdk-instruction?id=K9kjstc7t376p).



更多文档请参考：[涂鸦智能Android SDK](https://tuyainc.github.io/tuyasmart_home_android_sdk_doc/zh-hans/)
