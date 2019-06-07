---
title: "小米MIUI无需root开启 google feed,google assistant"
date: 2019-06-07T09:09:21+08:00
draft: true
tags:
- google feed
- google assistant
---

之前用的酷派S1 刷了`resurrection remix`,搜索真的是太方便了,`feed`内容质量也高.

无奈骁龙 820/821 真的是天生火炉,除了日常应用全部放冰箱里,依旧续航尿崩,打王者平均 15 fps,就比幻灯片切换快一点,3 月份米 9依然不好抢,提升也不大,于是 49 年入国军买了米 8...

拿到手第一件事当然是 root 了了了了了一星期没成功,官方解锁工具死活不好使,可能和 amd 的 ryzen 有问题?

切了英文不用自带应用的话也没啥广告,就是偶尔有个系统App推送.

最不爽的就是负一屏的快捷搜索引擎没有 google,手动装完了google 套件桌面也没有 google 图标,只有一个语音搜索的图标.

上网搜了一下,结果让人无语.MIUI 故意隐藏了 google 图标.我日,还 tm 有这种神操作.

# 进入正题

果断换了 `nova launcher`,有些miui 负一屏的快捷设置可以用 nova 的滑动手势,选 shortcut 的就可以.比如可以设置上划微信图标,直接激活微信扫码支付.

装好了之后虽然开了 fq,但是打开 google 后信息流`google feed`是空的,

提示可能以下其中之一

1. `an error occurred, please try again latet`
2. `it looks like there was an error signing in to your account`
3. `Google Now Can’t Reach your Feed at the Moment`

4. 直接白屏

如果 root 了很简单,直接下载 [google now enabler](<https://forum.xda-developers.com/android/apps-games/app-enable-google-one-click-t3238198>),装上就能用

如果没 root,禁用掉 Google play service 的电话权限,开启飞行模式,连接 wifi(此时电话依然是飞行模式,但是能连 wifi),配置好 fq,打开 google 应用首页就会出现 feed 信息流,语言取决于系统当前语言,然后可以关闭飞行模式了

google assisatant 目前支持中文了,语言选择台湾即可

ssr 开启 pre-app bypass模式,国产软件打钩,这样就可以 ok google 解锁以及搜索,国内直连,国外走代理了

原文参考:[面向小白教程： MIUI 系统原生向调教（内含刷机教程、原生风格桌面配置、Google Feed 开启）](https://www.v2ex.com/t/545485#reply77)

