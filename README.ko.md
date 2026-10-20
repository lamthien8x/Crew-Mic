<div align="center">

<img src="assets/logo.svg" alt="Crew Mic – 스마트폰을 PC·Mac용 무선 마이크로" width="128" height="128">

# Crew Mic — 스마트폰을 Mac·Windows용 무선 마이크로 바꾸세요

**여러 대의 Android와 iPhone을 저지연 Wi-Fi 마이크로 동시에 사용하세요. 컴퓨터에서 믹싱한 소리를 Zoom, OBS, Discord, Google Meet, Teams로 바로 보낼 수 있습니다.**

[![Crew Mic 다운로드](https://img.shields.io/badge/다운로드-crewmic.codelumix.com-38bdf8?style=for-the-badge)](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=hero_ko)

![macOS](https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?style=flat-square&logo=ios&logoColor=white)
![지연](https://img.shields.io/badge/지연-40--100_ms-0ea5e9?style=flat-square)
![오디오](https://img.shields.io/badge/오디오-48_kHz_PCM-6366f1?style=flat-square)

[English](README.md) · [Tiếng Việt](README.vi.md) · [Español](README.es.md) · [Português](README.pt-BR.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Русский](README.ru.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · **한국어** · [Bahasa Indonesia](README.id.md) · [ไทย](README.th.md)

</div>

---

## 왜 Crew Mic인가요?

게스트 세 명과 팟캐스트 녹음, 공동 진행자와 라이브 방송, 시끄러운 방에서 하이브리드 회의 참여. 보통은 수십만 원짜리 무선 마이크 세트가 필요합니다.

**하지만 마이크는 이미 갖고 계십니다. 바로 스마트폰입니다.**

Crew Mic는 로컬 Wi-Fi로 **여러 대의 스마트폰**을 한 대의 컴퓨터에 연결합니다. 각 스마트폰이 독립된 마이크 채널이 되어 **AI 노이즈 제거**, **마이크 간 자동 동기화**, **클리핑 방지** 기능을 갖춥니다. 최종 믹스는 **가상 마이크**로 출력되어 어떤 앱에서든 선택할 수 있습니다.

> 🎙️ 케이블도, 수신기도, 추가 장비도 필요 없습니다. 앱을 설치하고 스마트폰에서 열고 말하기만 하세요.

---

## ✨ 주요 기능

| | 기능 | 이런 점이 좋아요 |
|---|---|---|
| 📱 | **여러 대 동시 연결** | 여러 대의 Android와 iPhone을 한 번에 연결하고, 기기마다 전용 채널을 제공합니다. |
| ⚡ | **저지연 Wi-Fi 오디오** | 48 kHz 무압축 오디오를 UDP로 10 ms 프레임 단위 전송. 전체 지연은 보통 **40–100 ms**입니다. |
| 🔇 | **4단계 AI 노이즈 제거** | RNNoise 신경망(끔 / 약 / 중 / 강 + 노이즈 게이트)이 선풍기, 에어컨, 차 소음을 제거합니다. 단계를 바꿔도 '틱' 소리가 나지 않습니다. |
| 🎯 | **멀티 소스 동기화** | 실제 녹음 시점을 기준으로 모든 스마트폰을 정렬해 오차를 ≤ 5 ms(p95)로 유지합니다. 두 마이크가 어긋날 때 생기는 텅 빈 '터널' 소리를 막아 줍니다. |
| 🛡️ | **마스터 리미터** | 룩어헤드 리미터(≤ 1 ms, 상한 −1 dBFS)로 모두가 동시에 크게 웃어도 소리가 찢어지지 않습니다. |
| 🎛️ | **데스크톱 믹싱 콘솔** | 채널별 게인, 음소거, 타이밍 오프셋(±100 ms), 30 Hz VU 미터, 그리고 마스터 버스. |
| 🎧 | **헤드폰 모니터링** | AirPods, USB DAC, 3.5 mm 단자 등 별도 출력으로 믹스를 실시간으로 들을 수 있습니다. |
| 🔌 | **모든 앱과 호환** | 가상 마이크(macOS는 BlackHole, Windows는 VB-CABLE)로 출력해 Zoom, OBS, Discord, Meet, Teams, DAW에서 사용합니다. |
| 🔍 | **자동 검색** | 스마트폰이 mDNS/Bonjour로 컴퓨터를 자동으로 찾습니다. 각 기기는 사용자가 승인해야 연결됩니다. |
| 🔒 | **네트워크 안에서만** | 오디오는 로컬 네트워크에서 스마트폰에서 컴퓨터로 직접 전송되며, 클라우드에 업로드되지 않습니다. |

---

## 🎬 이런 분께 추천합니다

- **팟캐스터**: 2–4명이 각자 스마트폰을 핀 마이크처럼 사용해 완벽하게 동기화된 녹음을 할 수 있습니다.
- **스트리머·유튜버**: 무선 마이크 세트 없이 OBS에 공동 진행자나 게스트 마이크를 추가하세요.
- **원격·하이브리드 팀**: 회의 테이블에 스마트폰을 놓아 Zoom이나 Teams에서 모두의 목소리가 또렷하게 들리게 하세요.
- **교사·발표자**: 스마트폰을 주머니에 넣고 무선 마이크처럼 교실을 자유롭게 오가세요.
- **인터뷰어·기자**: 실시간 모니터링과 함께 2인 인터뷰를 진행하세요.
- **교회·행사·소규모 공연장**: 강연과 패널 토론용 멀티 마이크 시스템을 빠르게 구성하세요.

---

## 🚀 3단계로 시작하기

1. **Crew Mic를 다운로드**하세요. 컴퓨터용(macOS / Windows)과 스마트폰용(Android / iOS):
   👉 **[crewmic.codelumix.com](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=steps_ko)**
2. **가상 마이크 드라이버 설치** (최초 1회):
   - macOS: [BlackHole 2ch](https://existential.audio/blackhole/) (`brew install --cask blackhole-2ch`)
   - Windows: [VB-CABLE](https://vb-audio.com/Cable/)
3. **연결하고 말하기**: 데스크톱 앱을 실행하고, 같은 Wi-Fi의 각 스마트폰에서 Crew Mic를 연 뒤 기기를 승인하고, Zoom·OBS·Discord에서 가상 마이크를 선택하세요.

> 💡 **팁:** 가장 낮은 지연을 원한다면 5 GHz Wi-Fi를 사용하고 가상 장치를 **48,000 Hz**로 설정하세요.

---

## ⚙️ 지연 모드

| 모드 | 예상 전체 지연 | 추천 상황 |
|---|---|---|
| **낮음** | 40–60 ms | 강한 5 GHz Wi-Fi 환경의 라이브 인터뷰·실시간 대화 |
| **균형** *(기본값)* | 60–100 ms | 일반적인 가정·사무실 Wi-Fi를 쓰는 대부분의 사용자 |
| **안정** | 100–180 ms | 약한 신호, 먼 거리, 혼잡한 네트워크 |

---

## 🧠 작동 방식

```text
 📱 스마트폰 1 (Android) ─┐
 📱 스마트폰 2 (iPhone)  ─┼── Wi-Fi LAN · 48 kHz PCM · UDP ──►  💻 Crew Mic Desktop
 📱 스마트폰 N (...)     ─┘                                      │
                                                                 ├─ 적응형 지터 버퍼
                                                                 ├─ 클럭 드리프트 보정
                                                                 ├─ RNNoise AI 노이즈 제거
                                                                 ├─ 멀티 소스 동기화
                                                                 └─ 룩어헤드 리미터
                                                                        │
                                          ┌─────────────────────────────┴───────────────┐
                                          ▼                                             ▼
                             🎙️ 가상 마이크 (BlackHole / VB-CABLE)              🎧 모니터 헤드폰
                                          │
                                          ▼
                            Zoom · OBS · Discord · Meet · Teams
```

데스크톱 엔진은 실시간 오디오를 위해 **Rust**(Tauri v2)로 작성되었습니다. 오디오 스레드에서 메모리 할당 없이 lock-free로 믹싱합니다. 모바일 앱은 네이티브 오디오 API(Android `AudioRecord`, iOS `AVAudioEngine`)를 사용해 최소 지연으로 녹음합니다.

---

## ❓ 자주 묻는 질문

<details>
<summary><b>스마트폰을 PC나 Mac의 마이크로 쓸 수 있나요?</b></summary>

네. 스마트폰과 컴퓨터에 Crew Mic를 설치하고 같은 Wi-Fi에 연결하면, 스마트폰이 모든 데스크톱 앱에서 무선 마이크로 작동합니다.
</details>

<details>
<summary><b>몇 대까지 동시에 연결할 수 있나요?</b></summary>

Crew Mic는 여러 마이크의 동시 사용을 위해 설계되었습니다. 팟캐스트나 패널 토론에서는 보통 2–4대를 사용하며, 기기마다 게인·음소거·노이즈 제거를 따로 조절할 수 있습니다.
</details>

<details>
<summary><b>Zoom, OBS, Discord, Google Meet에서 쓸 수 있나요?</b></summary>

네. Crew Mic는 믹스를 가상 오디오 장치(BlackHole 또는 VB-CABLE)로 내보냅니다. 앱에서 그 장치를 마이크로 선택하기만 하면 됩니다.
</details>

<details>
<summary><b>인터넷 연결이 필요한가요?</b></summary>

아니요. 오디오는 로컬 네트워크(Wi-Fi LAN)로만 전송되므로, 스마트폰과 컴퓨터가 같은 네트워크에 있기만 하면 됩니다.
</details>

<details>
<summary><b>Android와 iPhone을 함께 쓸 수 있나요?</b></summary>

네. Android와 iOS 기기가 같은 세션에 참여하고 자동으로 동기화됩니다.
</details>

<details>
<summary><b>마이크 두 개를 쓰면 왜 소리가 텅 빈 것처럼 들리나요?</b></summary>

마이크 간 시간 차로 생기는 콤 필터 현상입니다. Crew Mic의 **소스 동기화**를 켜면 모든 채널이 몇 밀리초 이내로 정렬됩니다.
</details>

---

## 📥 다운로드

<div align="center">

### 스마트폰을 프로급 마이크 시스템으로 바꿀 준비가 되셨나요?

[![지금 Crew Mic 다운로드](https://img.shields.io/badge/⬇_Crew_Mic_다운로드-crewmic.codelumix.com-38bdf8?style=for-the-badge)](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=footer_ko)

⭐ **Crew Mic가 도움이 되었다면 저장소에 Star를 눌러 주세요.** 더 많은 크리에이터가 찾을 수 있습니다.

</div>

---

## 💬 피드백 및 지원

- 🐛 버그 신고나 기능 요청은 [Issues](../../issues)에 남겨 주세요
- 🌐 웹사이트: [crewmic.codelumix.com](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=support_ko)
- 🏢 개발: [CodeLumix](https://codelumix.com/?utm_source=github&utm_medium=readme)

<sub>**키워드:** 스마트폰 마이크, 휴대폰을 PC 마이크로, 무선 마이크 앱, Wi-Fi 마이크, 아이폰 맥 마이크, 안드로이드 윈도우 마이크, 팟캐스트 마이크, OBS 무선 마이크, 줌 마이크, AI 노이즈 제거, 가상 마이크.</sub>
