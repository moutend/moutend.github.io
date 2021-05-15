---
title: "Zen Noise"
description: "高质量的噪音播放器应用程序"
icon: /products/ZenNoise/images/AppIcon.png
layout: product-zh-Hans
---

[![Download on the AppStore](/images/AppStoreCN.svg)](https://apps.apple.com/cn/app/zen-noise/id1566647727)

## 关于此应用程序

Zen Noise是播放白噪声、粉红噪声和布朗噪声的应用程序。当你需要提高注意力或冥想时，这些噪音很适合做背景音乐。Zen Noise还支持通过相机连接套件连接的USB音频接口。你可以用Zen Noise来测试你的音频设备。

## 隐私政策

1. 这个应用程序不收集用户的任何个人信息。
2. 使用此应用程序，您同意隐私政策。

## 广告

1. 这个应用程序在屏幕的顶部显示一个横幅广告。
2. 这个应用程序使用谷歌AdMob做广告。
3. 请参阅以下页面了解谷歌AdMob的隐私政策。

[广告 - 隐私和条款 - 谷歌](https://policies.google.com/technologies/ads?hl=zh-Hans)

## 技术规格

- 最小播放采样率 ... 8 kHz
- 最大播放采样率 ... 1536 kHz
- 最小输出通道 ... 1
- 最大输出通道 ... 16
- 波浪产生的比特深度  ... 32 Bit Float

### 已知问题


两个以上的输出通道和更高的采样率的组合可能会导致声音的停顿。例如，如果输出设备有16个通道，而采样率被设置为192 kHz，就会出现声音卡顿。为了防止这个问题，请选择一个较低的采样率，如44.1 kHz或48 kHz。

### 自动选择采样率


如果你选择了一个输出设备不支持的采样率，它将自动设置输出设备支持的最接近的采样率。

### 噪声生成算法


Zen Noise使用基于以下文章的噪声生成算法。

[How to Generate Noise with the Web Audio API - NOISEHACK](https://noisehack.com/generate-noise-web-audio-api/)

## 开发商

[Yoshiyuki Koyanagi](https://moutend.github.io/)
