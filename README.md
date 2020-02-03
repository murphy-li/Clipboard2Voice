## Clipboard2Voice
[![license](https://img.shields.io/badge/license-Apache%20License%202.0-brightgreen.svg?style=flat)](https://github.com/murphy-li/Clipboard2Voice/blob/master/LICENSE)
[![Release Version](https://img.shields.io/badge/release-v1.0.1-red.svg)](https://github.com/murphy-li/Clipboard2Voice/releases)

主要提供给文盲家人使用，只需要复制文字，app就会自动后台转语音，并且读出来（based on Google TTS Engine)。

<a href="https://996.icu"><img src="https://img.shields.io/badge/link-996.icu-red.svg"></a>
虽然目前公司应该不是996icu，但是前公司是9 11 6.我也算是个受害者中的幸存者吧。
## Getting started
好像没啥好介绍，项目很Easy。

## Guide

1. 请到[![Release Version](https://img.shields.io/badge/release-v1.0.1-red.svg)](https://github.com/murphy-li/Clipboard2Voice/releases)下载软件。其中Clipboard2Voice.apk是软件本体，GoogleTTS.apk是谷歌语音转文字插件，只需要下载这两个文件就可以了，
2. 在安装完软件之后，在系统设置中将谷歌TTS设置为默认语音转文字插件，然后把该给的权限都给上。
3. 然后按home键，打开其他app，选中文字，然后长按，点击复制，然后软件会自动读出对应的语音。

## Auto Boot
因为使用者是文盲，所以方便第一，流氓不流氓就另说，我妈妈是文盲，所以直接开机自启动方便，同时监听了网络状态自启动。所以本app支持：

1. 开机自启动
2. 网络状态改变自启动

## Known Issues

1. 暂时不支持其他自动启动方式，如果被kill掉了，可能需要你手动启动应用，所以请告知使用者如果无效就需要重新打开软件。
2. ~~如果你是流氓安卓软件开发者，麻烦帮帮忙加个充电之类的后台自启动（可能会比较耗电）。暂时想不到其他的自启动方式了。~~
3. 貌似放久了会出现用不了的问题。
4. ~~暂时在我的小米5S和我妈妈的红米Note 4上正常运行，但是在一加7(based on Android Q)上不能正常运行。可能是版本太高原因，暂时懒得解决。~~
问题已确认：安卓10除了输入法，其他第三方应用都不能在后台获取剪切板内容。然后解决方案参考[这里](https://blog.csdn.net/qq_37891456/article/details/103383116)。但是Activity也会内存泄漏，本来他们用的手机就比较卡，所以暂时不采用！

## Contributing
暂时只有我一个。

## License
本软件使用Apache License 2.0. 看这里[LICENSE](https://github.com/murphy-li/Clipboard2Voice/blob/master/LICENSE) 获取更多细节。

## Secret

偷偷告诉你们，模板是[这里](https://github.com/Tencent/tinker/edit/dev/README.md)抄的。
