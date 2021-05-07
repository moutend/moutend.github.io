---
title: "Zen Noise"
description: "High Quality Noise Player App"
icon: /products/ZenNoise/images/Icon.svg
layout: product-en
---

[![Download on the AppStore](/images/appstore_us.svg)]()

## About This App

Zen Noise is the application that plays white noise, pink noise, and brownian noise. These noises are good for background music when you need to improve your concentration or meditation. Zen Noise also supports USB audio interfaces connected via Camera Connection Kit. You can use Zen Noise to test your audio equipment.

Coming Soon

## Privacy Policy

1. This application does not collect any personal information about the users.
2. By using this application, you agree to the privacy policy.

## Technical Specifications

- Minimum Playback Sample Rate ... 8 kHz
- Maximum Playback Sample Rate ... 1536 kHz
- Minimum Output Channel ... 1
- Maximum Output Channel ... 16
- Wave Generation Bit Depth ... 32 Bit Float

### Known Issues

Combination of more than two output channels and higher sample rate might cause sound stuttering. For example, if the output device has 16 channels and sample rate is set to 192 kHz, sound stuttering will occur. To prevent this problem, please select a lower sampling rate such as 44.1 kHz or 48 kHz.

### Automatic Sample Rate Selection

If you select a sample rate that is not supported by the output device, it will automatically set the closest sample rate that the output device supports.

### Noise Generation Algorithm

Zen Noise uses the noise generation algorithm based on the following article:

[How to Generate Noise with the Web Audio API - NOISEHACK](https://noisehack.com/generate-noise-web-audio-api/)

## Developer

[Yoshiyuki Koyanagi](https://moutend.github.io/)