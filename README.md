# AppErrorsTracking

[![GitHub license](https://img.shields.io/github/license/KitsunePie/AppErrorsTracking?color=blue)](https://github.com/KitsunePie/AppErrorsTracking/blob/master/LICENSE)
[![GitHub CI](https://img.shields.io/github/actions/workflow/status/KitsunePie/AppErrorsTracking/commit_ci.yml?label=CI%20builds)](https://github.com/KitsunePie/AppErrorsTracking/actions/workflows/commit_ci.yml)
[![GitHub release](https://img.shields.io/github/v/release/KitsunePie/AppErrorsTracking?display_name=release&logo=github&color=green)](https://github.com/KitsunePie/AppErrorsTracking/releases)
![GitHub all releases](https://img.shields.io/github/downloads/KitsunePie/AppErrorsTracking/total?label=downloads)
![GitHub all releases](https://img.shields.io/github/downloads/Xposed-Modules-Repo/com.fankes.apperrorstracking/total?label=LSPosed%20downloads&labelColor=F48FB1)

[![Telegram CI](https://img.shields.io/badge/CI%20builds-Telegram-blue.svg?logo=telegram)](https://t.me/AppErrorsTracking_CI)
[![Telegram](https://img.shields.io/badge/discussion-Telegram-blue.svg?logo=telegram)](https://t.me/XiaofangInternet)
[![QQ](https://img.shields.io/badge/discussion-QQ-blue.svg?logo=tencent-qq&logoColor=red)](https://qm.qq.com/cgi-bin/qm/qr?k=dp2h5YhWiga9WWb_Oh7kSHmx01X8I8ii&jump_from=webapi&authKey=Za5CaFP0lk7+Zgsk2KpoBD7sSaYbeXbsDgFjiWelOeH4VSionpxFJ7V0qQBSqvFM)
[![QQ 频道](https://img.shields.io/badge/discussion-QQ%20频道-blue.svg?logo=tencent-qq&logoColor=red)](https://pd.qq.com/s/44gcy28h)

<img src="https://github.com/KitsunePie/AppErrorsTracking/blob/master/img-src/icon.png?raw=true" width = "100" height = "100" alt="LOGO"/>

中文用户请向下滑动以查看简体中文版自述文件内容。

## Introduction

**AppErrorsTracking**

Added more features to app's errors dialog, fixed custom rom deleted dialog, the best experience to Android developer.

This project is an Xposed Module that can be used in any Android system, currently only tested in **LSPosed**.

This Xposed Module is specially designed for Android developers.

When it is possible that the computer cannot be connected and ADB cannot be performed, this module can be used to quickly capture any exception
of any installed apps, so as to quickly locate the problem.

The error log of apps crashing is an invaluable asset for developers. If you are not a developer, you can still install this module to provide
developers with more exception information to quickly solve problems.

> Minimum support Android 7.0

## Release Channel

| <img src="https://avatars.githubusercontent.com/in/15368?s=64&v=4" width = "30" height = "30" alt="LOGO"/> | [GitHub CI](https://github.com/KitsunePie/AppErrorsTracking/actions/workflows/commit_ci.yml) | CI automatic build (test version) |
|------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------|-----------------------------------|

| <img src="https://github.com/peter-iakovlev/Telegram/blob/public/Icon.png?raw=true" width = "30" height = "30" alt="LOGO"/> | [Telegram CI Channel](https://t.me/AppErrorsTracking_CI) | CI automatic build (test version) |
|-----------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------|-----------------------------------|

| <img src="https://avatars.githubusercontent.com/in/15368?s=64&v=4" width = "30" height = "30" alt="LOGO"/> | [GitHub Releases](https://github.com/KitsunePie/AppErrorsTracking/releases) | Formal edition (stable version) |
|------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------|---------------------------------|

| <img src="https://avatars.githubusercontent.com/u/78217009?s=200&v=4?raw=true" width = "30" height = "30" alt="LOGO"/> | [Xposed-Modules-Repo](https://github.com/Xposed-Modules-Repo/com.fankes.apperrorstracking/releases) | Formal edition (stable version) |
|------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|---------------------------------|

The releases of this Xposed Module is limited to the urls listed above.

We have nothing to do with versions downloaded from other informal channels or any impact on you.

## Promotion

If you are looking for a Gradle plugin that can automatically manage Gradle project dependencies,
you can check out the [SweetDependency](https://github.com/HighCapable/SweetDependency) project.

If you are looking for a Gradle plugin that can automatically generate properties key-values,
you can check out the [SweetProperty](https://github.com/HighCapable/SweetProperty) project.

This project also uses **SweetDependency** and **SweetProperty**.

## Contribution

This Xposed Module is built using [YukiHookAPI](https://github.com/HighCapable/YukiHookAPI)

YukiHookAPI is an efficient Hook API and Xposed Module solution built in Kotlin, making your Xposed Module development easier.

Copyright © 2017-2023 Fankes Studio(qzmmcn@163.com)

## 介绍

**异常跟踪**

为原生 FC 对话框增加更多功能并修复国内定制 ROM 删除 FC 对话框的问题，给 Android 开发者带来更好的体验。

此项目为 Xposed 模块，可用在任何 Android 系统中，目前仅在 **LSPosed** 中测试通过。

此模块专为 Android 开发者而打造。

在可能的无法连接电脑，不能进行 ADB 调试的时候，可通过此模块来快速捕获任意已安装应用的任意异常，以便快速定位问题。

应用发生崩溃的错误日志对开发者来说是无价的财富，若你不是开发者，你依然可以安装此模块，以便给开发者提供更多异常信息快速解决问题。

> 最低支持 Android 7.0

## 发行渠道

| <img src="https://avatars.githubusercontent.com/in/15368?s=64&v=4" width = "30" height = "30" alt="LOGO"/> | [GitHub CI](https://github.com/KitsunePie/AppErrorsTracking/actions/workflows/commit_ci.yml) | CI 自动构建 (测试版) |
|------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------|---------------|

| <img src="https://github.com/peter-iakovlev/Telegram/blob/public/Icon.png?raw=true" width = "30" height = "30" alt="LOGO"/> | [Telegram CI 频道](https://t.me/AppErrorsTracking_CI) | CI 自动构建 (测试版) |
|-----------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------|---------------|

| <img src="https://avatars.githubusercontent.com/in/15368?s=64&v=4" width = "30" height = "30" alt="LOGO"/> | [GitHub Releases](https://github.com/KitsunePie/AppErrorsTracking/releases) | 正式版 (稳定版) |
|------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------|-----------|

| <img src="https://avatars.githubusercontent.com/u/78217009?s=200&v=4?raw=true" width = "30" height = "30" alt="LOGO"/> | [Xposed-Modules-Repo](https://github.com/Xposed-Modules-Repo/com.fankes.apperrorstracking/releases) | 正式版 (稳定版) |
|------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|-----------|

本模块发布地址仅限于上述所列出的地址，从其他非正规渠道下载到的版本或对您造成任何影响均与我们无关。

## 项目推广

如果你正在寻找一个可以自动管理 Gradle 项目依赖的 Gradle 插件，你可以了解一下 [SweetDependency](https://github.com/HighCapable/SweetDependency) 项目。

如果你正在寻找一个可以自动生成属性键值的 Gradle 插件，你可以了解一下 [SweetProperty](https://github.com/HighCapable/SweetProperty) 项目。

本项目同样使用了 **SweetDependency** 和 **SweetProperty**。

## 捐赠支持

工作不易，无意外情况此项目将继续维护下去，提供更多可能，欢迎打赏。

<img src="https://github.com/fankes/fankes/blob/main/img-src/payment_code.jpg?raw=true" width = "500" alt="Payment Code"/>

## 贡献

本模块使用 [YukiHookAPI](https://github.com/HighCapable/YukiHookAPI) 构建

YukiHookAPI 是一个使用 Kotlin 重构的高效 Hook API 构建工具，让你的 Xposed 模块开发变得更加简单。

版权所有 © 2017-2023 Fankes Studio(qzmmcn@163.com)
