<div align="center">

<img src="assets/logo.svg" alt="Crew Mic logo – turn your phone into a wireless microphone for PC and Mac" width="128" height="128">

# Crew Mic — Turn Any Phone Into a Wireless Microphone for Mac & Windows

**Use several Android and iPhone devices as low-latency Wi-Fi microphones. Mix them on your computer and send the result into Zoom, OBS, Discord, Google Meet or Teams.**

[![Download Crew Mic](https://img.shields.io/badge/Download-crewmic.codelumix.com-38bdf8?style=for-the-badge)](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=hero_en)

![macOS](https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?style=flat-square&logo=ios&logoColor=white)
![Latency](https://img.shields.io/badge/latency-40--100_ms-0ea5e9?style=flat-square)
![Audio](https://img.shields.io/badge/audio-48_kHz_PCM-6366f1?style=flat-square)

**English** · [Tiếng Việt](README.vi.md) · [Español](README.es.md) · [Português](README.pt-BR.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Русский](README.ru.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Bahasa Indonesia](README.id.md) · [ไทย](README.th.md)

</div>

---

## Why Crew Mic?

Recording a podcast with three guests, running a livestream with a co-host, or joining a hybrid meeting from a loud room usually means buying wireless mic kits that cost hundreds of dollars.

**You already own the microphones: your phones.**

Crew Mic connects **multiple smartphones** to one computer over your local Wi-Fi. Each phone becomes its own mic channel with **AI noise suppression**, **automatic sync between mics** and **clip protection**. The final mix appears as a **virtual microphone** that any app can pick.

> 🎙️ No cables. No receivers. No extra hardware. Install the app, open it on your phones, and start talking.

---

## ✨ Key Features

| | Feature | What it does for you |
|---|---|---|
| 📱 | **Multi-phone microphones** | Connect several Android and iPhone devices at once. Each one gets its own channel strip. |
| ⚡ | **Low-latency Wi-Fi audio** | Uncompressed 48 kHz audio over UDP, sent in 10 ms frames. Typical total latency is **40–100 ms**. |
| 🔇 | **AI noise suppression in 4 levels** | RNNoise neural denoiser (Off / Light / Medium / Strong with noise gate) removes fans, AC hum and traffic noise. Switching levels causes no clicks. |
| 🎯 | **Multi-source sync** | Aligns every phone to the actual moment of capture, keeping mics within ≤ 5 ms (p95) of each other. This prevents the hollow, "tunnel" sound you get when two mics drift apart. |
| 🛡️ | **Master peak limiter** | Look-ahead limiter (≤ 1 ms, −1 dBFS ceiling) stops distortion when everyone laughs at once. |
| 🎛️ | **Desktop mixing console** | Gain, mute, timing offset (±100 ms) and live 30 Hz VU meters per channel, plus a master bus. |
| 🎧 | **Headphone monitoring** | Listen to the live mix on a separate output, such as AirPods, a USB DAC or a 3.5 mm jack. |
| 🔌 | **Works with any app** | Outputs to a virtual mic (BlackHole on macOS, VB-CABLE on Windows) for Zoom, OBS, Discord, Meet, Teams and DAWs. |
| 🔍 | **Zero-config discovery** | Phones find your computer automatically through mDNS/Bonjour. You approve each device before it joins. |
| 🔒 | **Stays on your network** | Audio goes straight from phone to computer on your LAN. Nothing is uploaded to the cloud. |

---

## 🎬 Who Is It For?

- **Podcasters**: record 2–4 people with one phone each as a lav mic, perfectly in sync.
- **Streamers & YouTubers**: add a co-host or guest mic to OBS without buying a wireless kit.
- **Remote & hybrid teams**: put phones around the meeting table so everyone is heard clearly on Zoom or Teams.
- **Teachers & presenters**: walk around the classroom with your phone in your pocket as a wireless mic.
- **Interviewers & journalists**: run two-person interviews with real-time monitoring.
- **Churches, events & small venues**: get a quick multi-mic setup for talks and panels.

---

## 🚀 Get Started in 3 Steps

1. **Download Crew Mic** for your computer (macOS / Windows) and phones (Android / iOS) at
   👉 **[crewmic.codelumix.com](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=steps_en)**
2. **Install a virtual mic driver** (one time only):
   - macOS: [BlackHole 2ch](https://existential.audio/blackhole/) (`brew install --cask blackhole-2ch`)
   - Windows: [VB-CABLE](https://vb-audio.com/Cable/)
3. **Connect & talk**: start the desktop app, open Crew Mic on each phone on the same Wi-Fi, approve the devices, then choose the virtual mic in Zoom, OBS or Discord.

> 💡 **Tip:** For the lowest latency, use 5 GHz Wi-Fi and set the virtual device to **48,000 Hz**.

---

## ⚙️ Latency Modes

| Mode | Estimated total latency | Best for |
|---|---|---|
| **Low** | 40–60 ms | Live interviews and real-time conversation on strong 5 GHz Wi-Fi |
| **Balanced** *(default)* | 60–100 ms | Most users on everyday home or office Wi-Fi |
| **Stable** | 100–180 ms | Weak signal, long range or crowded networks |

---

## 🧠 How It Works

```text
 📱 Phone 1 (Android) ─┐
 📱 Phone 2 (iPhone)  ─┼── Wi-Fi LAN · 48 kHz PCM · UDP ──►  💻 Crew Mic Desktop
 📱 Phone N (...)     ─┘                                      │
                                                              ├─ Adaptive jitter buffer
                                                              ├─ Clock-drift resampler
                                                              ├─ RNNoise AI denoise
                                                              ├─ Multi-source sync
                                                              └─ Look-ahead limiter
                                                                     │
                                       ┌─────────────────────────────┴───────────────┐
                                       ▼                                             ▼
                          🎙️ Virtual mic (BlackHole / VB-CABLE)            🎧 Monitor headphones
                                       │
                                       ▼
                         Zoom · OBS · Discord · Meet · Teams
```

The desktop engine is written in **Rust** (Tauri v2) for real-time audio: lock-free mixing with no memory allocations on the audio thread. The mobile apps use native audio APIs (Android `AudioRecord`, iOS `AVAudioEngine`) for the lowest possible capture latency.

---

## ❓ FAQ

<details>
<summary><b>Can I use my phone as a microphone for my PC or Mac?</b></summary>

Yes. Install Crew Mic on your phone and computer, connect both to the same Wi-Fi, and your phone works as a wireless mic in any desktop app.
</details>

<details>
<summary><b>How many phones can I connect at the same time?</b></summary>

Crew Mic is built for multiple simultaneous mics. A typical podcast or panel uses 2–4 phones. Each phone gets its own channel with separate gain, mute and noise suppression.
</details>

<details>
<summary><b>Does it work with Zoom, OBS, Discord and Google Meet?</b></summary>

Yes. Crew Mic sends its mix to a virtual audio device (BlackHole or VB-CABLE). Pick that device as the microphone in any app.
</details>

<details>
<summary><b>Do I need internet access?</b></summary>

No. Audio travels only over your local network (Wi-Fi LAN), so the phones and the computer just need to be on the same network.
</details>

<details>
<summary><b>Can I mix Android phones and iPhones?</b></summary>

Yes. Android and iOS devices can join the same session and are synced together automatically.
</details>

<details>
<summary><b>Why does my audio sound hollow when using two mics?</b></summary>

That is comb filtering, caused by mics drifting out of time. Turn on **Source Sync** in Crew Mic to align all channels within a few milliseconds.
</details>

---

## 📥 Download

<div align="center">

### Ready to turn your phones into a pro mic setup?

[![Download Crew Mic now](https://img.shields.io/badge/⬇_Download_Crew_Mic-crewmic.codelumix.com-38bdf8?style=for-the-badge)](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=footer_en)

⭐ **If Crew Mic helps you, please star this repo** so more creators can find it.

</div>

---

## 💬 Feedback & Support

- 🐛 Report bugs or request features in [Issues](../../issues)
- 🌐 Website: [crewmic.codelumix.com](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=support_en)
- 🏢 Made by [CodeLumix](https://codelumix.com/?utm_source=github&utm_medium=readme)

<sub>**Keywords:** phone as microphone, wireless microphone app, use phone as mic for PC, iPhone as microphone for Mac, Android mic for Windows, multi-mic podcast, OBS wireless mic, Zoom microphone app, WiFi microphone, virtual microphone, RNNoise noise cancellation, low-latency audio streaming.</sub>
