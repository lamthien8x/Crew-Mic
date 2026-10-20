<div align="center">

<img src="assets/logo.svg" alt="Crew Mic – 把手机变成电脑无线麦克风" width="128" height="128">

# Crew Mic — 把手机变成 Mac 和 Windows 电脑的无线麦克风

**同时把多部 Android 和 iPhone 手机当作低延迟 Wi-Fi 麦克风，在电脑上混音后直接输出到 Zoom、OBS、Discord、Google Meet 或 Teams。**

[![下载 Crew Mic](https://img.shields.io/badge/立即下载-crewmic.codelumix.com-38bdf8?style=for-the-badge)](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=hero_zh)

![macOS](https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?style=flat-square&logo=ios&logoColor=white)
![延迟](https://img.shields.io/badge/延迟-40--100_ms-0ea5e9?style=flat-square)
![音频](https://img.shields.io/badge/音频-48_kHz_PCM-6366f1?style=flat-square)

[English](README.md) · [Tiếng Việt](README.vi.md) · [Español](README.es.md) · [Português](README.pt-BR.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Русский](README.ru.md) · **简体中文** · [日本語](README.ja.md) · [한국어](README.ko.md) · [Bahasa Indonesia](README.id.md) · [ไทย](README.th.md)

</div>

---

## 为什么选择 Crew Mic？

录制三人播客、和搭档一起直播、在嘈杂的房间里参加混合会议，通常需要花上千元购买无线麦克风套装。

**其实你早就拥有麦克风了：你的手机。**

Crew Mic 通过局域网 Wi-Fi 把**多部手机**连接到同一台电脑。每部手机都是一个独立的麦克风通道，带有 **AI 降噪**、**多麦自动同步**和**防爆音保护**。最终混音以**虚拟麦克风**的形式输出，任何软件都能直接选用。

> 🎙️ 无需线缆，无需接收器，无需额外硬件。安装应用，在手机上打开，开口说话即可。

---

## ✨ 核心功能

| | 功能 | 带来的好处 |
|---|---|---|
| 📱 | **多部手机同时连接** | 多部 Android 和 iPhone 同时接入，每部手机拥有独立的通道条。 |
| ⚡ | **低延迟 Wi-Fi 音频** | 48 kHz 无压缩音频，通过 UDP 以 10 ms 帧传输，总延迟通常仅 **40–100 ms**。 |
| 🔇 | **4 档 AI 降噪** | RNNoise 神经网络降噪（关闭 / 轻度 / 中度 / 强力 + 噪声门），去除风扇、空调和车流噪音，切换档位无“咔哒”声。 |
| 🎯 | **多音源同步** | 按真实采集时刻对齐所有手机，误差 ≤ 5 ms（p95），避免两支麦克风错位时产生的“空洞”“隧道”声。 |
| 🛡️ | **主输出限幅器** | Look-ahead 限幅器（≤ 1 ms，上限 −1 dBFS），多人同时大笑也不会破音。 |
| 🎛️ | **桌面调音台** | 每通道增益、静音、时间偏移（±100 ms）和 30 Hz 实时电平表，外加主总线。 |
| 🎧 | **耳机监听** | 通过独立输出实时监听混音：AirPods、USB DAC 或 3.5 mm 耳机孔。 |
| 🔌 | **兼容所有软件** | 输出到虚拟麦克风（macOS 用 BlackHole，Windows 用 VB-CABLE），适用于 Zoom、OBS、Discord、Meet、Teams 和各类 DAW。 |
| 🔍 | **零配置自动发现** | 手机通过 mDNS/Bonjour 自动找到电脑，每台设备需经你批准才能加入。 |
| 🔒 | **数据不出局域网** | 音频从手机直接传到局域网内的电脑，不会上传到云端。 |

---

## 🎬 适用人群

- **播客主**：2–4 人各用一部手机当领夹麦，录音完美同步。
- **主播与 UP 主**：无需购买无线麦套装，即可在 OBS 中加入搭档或嘉宾的麦克风。
- **远程与混合办公团队**：在会议桌上摆放几部手机，让每个人在 Zoom 或 Teams 中都清晰可闻。
- **老师与演讲者**：手机放进口袋当无线麦，在教室里自由走动。
- **采访者与记者**：进行双人采访，并实时监听。
- **教会、活动与小型场地**：快速搭建多麦系统，用于讲座与圆桌讨论。

---

## 🚀 三步上手

1. **下载 Crew Mic**，包括电脑端（macOS / Windows）和手机端（Android / iOS）：
   👉 **[crewmic.codelumix.com](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=steps_zh)**
2. **安装虚拟麦克风驱动**（只需一次）：
   - macOS：[BlackHole 2ch](https://existential.audio/blackhole/)（`brew install --cask blackhole-2ch`）
   - Windows：[VB-CABLE](https://vb-audio.com/Cable/)
3. **连接并开讲**：启动电脑端，在同一 Wi-Fi 下打开各手机上的 Crew Mic，批准设备，然后在 Zoom、OBS 或 Discord 中选择虚拟麦克风。

> 💡 **小贴士：** 想要最低延迟，请使用 5 GHz Wi-Fi，并将虚拟设备设置为 **48,000 Hz**。

---

## ⚙️ 延迟模式

| 模式 | 预估总延迟 | 适用场景 |
|---|---|---|
| **低延迟** | 40–60 ms | 5 GHz 强信号下的直播采访与实时对谈 |
| **均衡**（默认） | 60–100 ms | 大多数使用家庭或办公 Wi-Fi 的用户 |
| **稳定** | 100–180 ms | 信号弱、距离远或网络拥挤 |

---

## 🧠 工作原理

```text
 📱 手机 1 (Android) ─┐
 📱 手机 2 (iPhone)  ─┼── Wi-Fi 局域网 · 48 kHz PCM · UDP ──►  💻 Crew Mic Desktop
 📱 手机 N (...)     ─┘                                         │
                                                                ├─ 自适应抖动缓冲
                                                                ├─ 时钟漂移重采样
                                                                ├─ RNNoise AI 降噪
                                                                ├─ 多音源同步
                                                                └─ Look-ahead 限幅器
                                                                       │
                                         ┌─────────────────────────────┴───────────────┐
                                         ▼                                             ▼
                            🎙️ 虚拟麦克风 (BlackHole / VB-CABLE)                 🎧 监听耳机
                                         │
                                         ▼
                           Zoom · OBS · Discord · Meet · Teams
```

桌面引擎使用 **Rust**（Tauri v2）编写，专为实时音频设计：无锁混音，音频线程中不分配内存。移动端使用原生音频 API（Android `AudioRecord`、iOS `AVAudioEngine`），以尽可能低的延迟采集声音。

---

## ❓ 常见问题

<details>
<summary><b>手机可以当电脑或 Mac 的麦克风吗？</b></summary>

可以。在手机和电脑上安装 Crew Mic，连接到同一个 Wi-Fi，手机就能在任意电脑软件中作为无线麦克风使用。
</details>

<details>
<summary><b>可以同时连接几部手机？</b></summary>

Crew Mic 专为多麦克风同时使用而设计。播客或圆桌讨论通常使用 2–4 部手机，每部都有独立的增益、静音和降噪通道。
</details>

<details>
<summary><b>支持 Zoom、OBS、Discord、Google Meet 吗？</b></summary>

支持。Crew Mic 会把混音输出到虚拟音频设备（BlackHole 或 VB-CABLE），在软件中把它选为麦克风即可。
</details>

<details>
<summary><b>需要联网吗？</b></summary>

不需要。音频只在局域网（Wi-Fi LAN）内传输，手机和电脑处于同一网络即可。
</details>

<details>
<summary><b>Android 和 iPhone 可以混用吗？</b></summary>

可以。Android 和 iOS 设备可以加入同一会话，并自动同步。
</details>

<details>
<summary><b>为什么用两支麦克风时声音发空？</b></summary>

这是麦克风时间错位导致的梳状滤波效应。在 Crew Mic 中开启**音源同步**，即可将所有通道对齐到几毫秒以内。
</details>

---

## 📥 下载

<div align="center">

### 准备好把手机变成专业麦克风系统了吗？

[![立即下载 Crew Mic](https://img.shields.io/badge/⬇_下载_Crew_Mic-crewmic.codelumix.com-38bdf8?style=for-the-badge)](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=footer_zh)

⭐ **觉得 Crew Mic 好用？请给本仓库点个 Star**，让更多创作者发现它。

</div>

---

## 💬 反馈与支持

- 🐛 在 [Issues](../../issues) 中反馈问题或提出功能建议
- 🌐 官网：[crewmic.codelumix.com](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=support_zh)
- 🏢 由 [CodeLumix](https://codelumix.com/?utm_source=github&utm_medium=readme) 开发

<sub>**关键词：** 手机当麦克风、手机做电脑麦克风、无线麦克风 App、Wi-Fi 麦克风、iPhone 当 Mac 麦克风、安卓当 Windows 麦克风、播客麦克风、OBS 无线麦、Zoom 麦克风、AI 降噪、虚拟麦克风。</sub>
