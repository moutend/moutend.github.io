---
title: "Zen Noise"
description: "고품질 노이즈 플레이어 앱"
icon: /products/ZenNoise/images/AppIcon.png
layout: product-ko
---

[![Download on the AppStore](/images/AppStoreKR.svg)](https://apps.apple.com/kr/app/zen-noise/id1566647727)

## 이 앱에 대해

Zen Noise는 화이트 노이즈, 핑크 노이즈 및 브라운 노이즈를 재생하는 응용 프로그램입니다. 이 소음은 집중력이나 명상을 향상시켜야 할 때 배경 음악에 좋습니다. Zen Noise는 카메라 연결 키트를 통해 연결된 USB 오디오 인터페이스도 지원합니다. Zen Noise를 사용하여 오디오 장비를 테스트 할 수 있습니다.

## 개인 정보 정책

1. 이 응용 프로그램은 사용자에 대한 개인 정보를 수집하지 않습니다.
2. 이 응용 프로그램을 사용하면 개인 정보 보호 정책에 동의하는 것입니다.

## 광고

1. 이 응용 프로그램은 화면 상단에 배너 광고를 표시합니다.
2. 이 애플리케이션은 광고에 Google AdMob을 사용합니다.
3. Google AdMob 개인 정보 보호 정책은 다음 페이지를 참조하세요.

[광고 – 개인 정보 보호 및 약관 – Google](https://policies.google.com/technologies/ads?hl=ko)

## 기술 사양

- 최소 재생 샘플 속도 ... 8 kHz
- 최대 재생 샘플 속도 ... 1536 kHz
- 최소 출력 채널 ... 1
- 최대 출력 채널 ... 16
- 웨이브 생성 비트 깊이 ... 64 Bit Float

### 알려진 문제

세 개 이상의 출력 채널과 더 높은 샘플 속도를 결합하면 사운드가 끊길 수 있습니다. 예를 들어, 출력 장치에 16 개의 채널이 있고 샘플 속도가 192kHz로 설정된 경우 사운드 끊김이 발생합니다. 이 문제를 방지하려면 44.1kHz 또는 48kHz와 같이 더 낮은 샘플링 속도를 선택하십시오.

### 자동 샘플 속도 선택

출력 장치에서 지원하지 않는 샘플 속도를 선택하면 출력 장치가 지원하는 가장 가까운 샘플 속도가 자동으로 설정됩니다.

### 노이즈 생성 알고리즘

Zen Noise는 다음 기사를 기반으로하는 노이즈 생성 알고리즘을 사용합니다.

[How to Generate Noise with the Web Audio API - NOISEHACK](https://noisehack.com/generate-noise-web-audio-api/)

## 개발자

[Yoshiyuki Koyanagi](https://moutend.github.io/)
