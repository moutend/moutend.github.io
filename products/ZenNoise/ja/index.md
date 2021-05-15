---
title: "Zen Noise"
description: 高音質なノイズ再生アプリ
icon: /products/ZenNoise/images/AppIcon.png
layout: product-ja
---

[![Download on the AppStore](/images/AppStoreJP.svg)](https://apps.apple.com/jp/app/zen-noise/id1566647727)

## このアプリについて

Zen Noiseはホワイトノイズ・ピンクノイズ・ブラウンノイズを再生するアプリです。これらのノイズは集中力を高めたり迷走するときのBGMとしておすすめです。また、Zen Noiseはカメラコネクションキットを利用したUSBオーディオインターフェースの接続に対応しています。音響機器の試運転にもご利用いただけます。

## 個人情報の取り扱いについて

1. 当アプリケーションは利用者の個人情報を一切収集しません。
2. 当アプリケーションを利用することで個人情報の取り扱いに同意したものと見なされます。

## 広告について

1. 当アプリケーションは画面の上部にバナー広告を表示します。
2. 当アプリケーションは広告としてGoogle AdMobを利用しています。
3. Google AdMobのプライバシーポリシーについては以下のページをご確認ください。

[広告 – ポリシーと規約 – Google](https://policies.google.com/technologies/ads?hl=ja)

## 技術仕様

- 再生サンプリングレート最小値 ... 8 kHz
- 再生サンプリングレート最大値 ... 1536 kHz
- 出力チャネル数の最小値 ... 1
- 出力チャネル数の最大値 ... 16
- 波形生成の量子化ビット数 ... 32 bit float

### 既知の不具合

2チャネル以上のチャネル数と高いサンプリングレートの組み合わせで音声の乱れが発生することがあります。例えば16チャネルの出力を搭載した機器に対してサンプリングレートを192 kHzに設定すると、音声の乱れが発生する場合があります。この問題を防ぐには、44.1kHzや48kHzなどの低いサンプリングレートを選択してください。

### サンプリングレートの自動設定

出力機器が対応していないサンプリングレートを選択すると、自動的にもっとも近いサンプリングレートが設定されます。

### ノイズ生成アルゴリズム

ピンクノイズおよびブラウンノイズ生成アルゴリズムとして以下の方法を利用しています。

[How to Generate Noise with the Web Audio API - NOISEHACK](https://noisehack.com/generate-noise-web-audio-api/)

## 開発元

[Yoshiyuki Koyanagi](https://moutend.github.io/)
