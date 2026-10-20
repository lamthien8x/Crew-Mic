<div align="center">

<img src="assets/logo.svg" alt="Crew Mic – เปลี่ยนมือถือเป็นไมค์ไร้สายสำหรับ PC และ Mac" width="128" height="128">

# Crew Mic — เปลี่ยนมือถือให้เป็นไมโครโฟนไร้สายสำหรับ Mac และ Windows

**ใช้มือถือ Android และ iPhone หลายเครื่องพร้อมกันเป็นไมค์ Wi-Fi ความหน่วงต่ำ มิกซ์เสียงบนคอมพิวเตอร์ แล้วส่งตรงเข้า Zoom, OBS, Discord, Google Meet หรือ Teams**

[![ดาวน์โหลด Crew Mic](https://img.shields.io/badge/ดาวน์โหลด-crewmic.codelumix.com-38bdf8?style=for-the-badge)](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=hero_th)

![macOS](https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?style=flat-square&logo=ios&logoColor=white)
![Latency](https://img.shields.io/badge/latency-40--100_ms-0ea5e9?style=flat-square)
![Audio](https://img.shields.io/badge/audio-48_kHz_PCM-6366f1?style=flat-square)

[English](README.md) · [Tiếng Việt](README.vi.md) · [Español](README.es.md) · [Português](README.pt-BR.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Русский](README.ru.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Bahasa Indonesia](README.id.md) · **ไทย**

</div>

---

## ทำไมต้อง Crew Mic?

อัดพอดแคสต์กับแขกสามคน ไลฟ์สตรีมกับพิธีกรร่วม หรือเข้าประชุมไฮบริดจากห้องที่เสียงดัง ปกติต้องซื้อชุดไมค์ไร้สายราคาหลายพันถึงหลายหมื่นบาท

**แต่จริง ๆ คุณมีไมค์อยู่แล้ว นั่นคือมือถือของคุณ**

Crew Mic เชื่อมต่อ **สมาร์ทโฟนหลายเครื่อง** เข้ากับคอมพิวเตอร์เครื่องเดียวผ่าน Wi-Fi ในบ้านหรือออฟฟิศ มือถือแต่ละเครื่องกลายเป็นช่องไมค์ของตัวเอง พร้อม **ระบบตัดเสียงรบกวนด้วย AI** **ซิงก์ไมค์อัตโนมัติ** และ **ป้องกันเสียงแตก** เสียงที่มิกซ์แล้วจะแสดงเป็น **ไมค์เสมือน** ที่เลือกใช้ได้ในทุกแอป

> 🎙️ ไม่ต้องใช้สาย ไม่ต้องมีตัวรับสัญญาณ ไม่ต้องซื้ออุปกรณ์เพิ่ม ติดตั้งแอป เปิดบนมือถือ แล้วเริ่มพูดได้เลย

---

## ✨ ฟีเจอร์เด่น

| | ฟีเจอร์ | ประโยชน์ที่คุณได้รับ |
|---|---|---|
| 📱 | **ใช้มือถือหลายเครื่องพร้อมกัน** | เชื่อมต่อ Android และ iPhone หลายเครื่องได้พร้อมกัน แต่ละเครื่องมีช่องสัญญาณของตัวเอง |
| ⚡ | **เสียงผ่าน Wi-Fi ความหน่วงต่ำ** | เสียง 48 kHz แบบไม่บีบอัด ส่งผ่าน UDP ทีละเฟรม 10 ms ความหน่วงรวมปกติเพียง **40–100 ms** |
| 🔇 | **ตัดเสียงรบกวน AI 4 ระดับ** | โครงข่ายประสาทเทียม RNNoise (ปิด / เบา / กลาง / แรง พร้อม noise gate) กำจัดเสียงพัดลม แอร์ และเสียงรถ เปลี่ยนระดับได้โดยไม่มีเสียงคลิก |
| 🎯 | **ซิงก์หลายแหล่งเสียง** | จัดเรียงมือถือทุกเครื่องตามจังหวะที่บันทึกเสียงจริง ให้คลาดเคลื่อนไม่เกิน 5 ms (p95) ป้องกันเสียงกลวงเหมือนพูดใน "อุโมงค์" เมื่อไมค์สองตัวไม่ตรงกัน |
| 🛡️ | **มาสเตอร์ลิมิตเตอร์** | ลิมิตเตอร์แบบ look-ahead (≤ 1 ms, เพดาน −1 dBFS) ป้องกันเสียงแตกเมื่อทุกคนหัวเราะพร้อมกัน |
| 🎛️ | **มิกเซอร์บนเดสก์ท็อป** | ปรับเกน ปิดเสียง ชดเชยเวลา (±100 ms) และ VU มิเตอร์ 30 Hz ในแต่ละช่อง พร้อมบัสมาสเตอร์ |
| 🎧 | **มอนิเตอร์ผ่านหูฟัง** | ฟังเสียงมิกซ์แบบสดผ่านเอาต์พุตแยก เช่น AirPods, USB DAC หรือแจ็ค 3.5 มม. |
| 🔌 | **ใช้ได้กับทุกแอป** | ส่งออกไปยังไมค์เสมือน (BlackHole บน macOS, VB-CABLE บน Windows) สำหรับ Zoom, OBS, Discord, Meet, Teams และ DAW |
| 🔍 | **ค้นหาอัตโนมัติ** | มือถือค้นหาคอมพิวเตอร์เองผ่าน mDNS/Bonjour และต้องได้รับการอนุมัติจากคุณก่อนเชื่อมต่อทุกครั้ง |
| 🔒 | **อยู่ในเครือข่ายของคุณเท่านั้น** | เสียงส่งตรงจากมือถือไปคอมพิวเตอร์ในวง LAN ไม่มีการอัปโหลดขึ้นคลาวด์ |

---

## 🎬 เหมาะกับใคร?

- **พอดแคสเตอร์**: อัดเสียง 2–4 คน แต่ละคนใช้มือถือเป็นไมค์หนีบปกเสื้อ ซิงก์กันสมบูรณ์แบบ
- **สตรีมเมอร์และยูทูบเบอร์**: เพิ่มไมค์พิธีกรร่วมหรือแขกรับเชิญใน OBS โดยไม่ต้องซื้อชุดไมค์ไร้สาย
- **ทีมทำงานทางไกลและไฮบริด**: วางมือถือรอบโต๊ะประชุมให้ทุกคนได้ยินชัดใน Zoom หรือ Teams
- **ครูและวิทยากร**: เดินไปมาในห้องได้อิสระ โดยมีมือถือในกระเป๋าเป็นไมค์ไร้สาย
- **ผู้สัมภาษณ์และนักข่าว**: สัมภาษณ์สองคนพร้อมมอนิเตอร์เสียงแบบเรียลไทม์
- **โบสถ์ งานอีเวนต์ และห้องขนาดเล็ก**: จัดระบบไมค์หลายตัวสำหรับงานสัมมนาและเสวนาได้อย่างรวดเร็ว

---

## 🚀 เริ่มใช้งานใน 3 ขั้นตอน

1. **ดาวน์โหลด Crew Mic** สำหรับคอมพิวเตอร์ (macOS / Windows) และมือถือ (Android / iOS) ที่
   👉 **[crewmic.codelumix.com](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=steps_th)**
2. **ติดตั้งไดรเวอร์ไมค์เสมือน** (ทำครั้งเดียว):
   - macOS: [BlackHole 2ch](https://existential.audio/blackhole/) (`brew install --cask blackhole-2ch`)
   - Windows: [VB-CABLE](https://vb-audio.com/Cable/)
3. **เชื่อมต่อแล้วพูดได้เลย**: เปิดแอปบนคอมพิวเตอร์ เปิด Crew Mic บนมือถือแต่ละเครื่องที่ใช้ Wi-Fi เดียวกัน อนุมัติอุปกรณ์ แล้วเลือกไมค์เสมือนใน Zoom, OBS หรือ Discord

> 💡 **เคล็ดลับ:** เพื่อความหน่วงต่ำที่สุด ให้ใช้ Wi-Fi 5 GHz และตั้งค่าอุปกรณ์เสมือนเป็น **48,000 Hz**

---

## ⚙️ โหมดความหน่วง

| โหมด | ความหน่วงรวมโดยประมาณ | เหมาะสำหรับ |
|---|---|---|
| **ต่ำ** | 40–60 ms | สัมภาษณ์สดและสนทนาแบบเรียลไทม์บน Wi-Fi 5 GHz ที่แรง |
| **สมดุล** *(ค่าเริ่มต้น)* | 60–100 ms | ผู้ใช้ส่วนใหญ่ที่ใช้ Wi-Fi บ้านหรือออฟฟิศทั่วไป |
| **เสถียร** | 100–180 ms | สัญญาณอ่อน ระยะไกล หรือเครือข่ายที่มีอุปกรณ์เยอะ |

---

## 🧠 หลักการทำงาน

```text
 📱 มือถือ 1 (Android) ─┐
 📱 มือถือ 2 (iPhone)  ─┼── Wi-Fi LAN · 48 kHz PCM · UDP ──►  💻 Crew Mic Desktop
 📱 มือถือ N (...)     ─┘                                      │
                                                               ├─ Adaptive jitter buffer
                                                               ├─ Clock-drift resampler
                                                               ├─ RNNoise AI denoise
                                                               ├─ Multi-source sync
                                                               └─ Look-ahead limiter
                                                                      │
                                        ┌─────────────────────────────┴───────────────┐
                                        ▼                                             ▼
                           🎙️ ไมค์เสมือน (BlackHole / VB-CABLE)                 🎧 หูฟังมอนิเตอร์
                                        │
                                        ▼
                          Zoom · OBS · Discord · Meet · Teams
```

เอนจินฝั่งเดสก์ท็อปเขียนด้วย **Rust** (Tauri v2) สำหรับเสียงแบบเรียลไทม์ มิกซ์แบบ lock-free โดยไม่มีการจองหน่วยความจำในเธรดเสียง ส่วนแอปมือถือใช้ API เสียงแบบเนทีฟ (Android `AudioRecord`, iOS `AVAudioEngine`) เพื่อบันทึกเสียงด้วยความหน่วงต่ำที่สุด

---

## ❓ คำถามที่พบบ่อย

<details>
<summary><b>ใช้มือถือเป็นไมค์ให้ PC หรือ Mac ได้ไหม?</b></summary>

ได้ ติดตั้ง Crew Mic บนมือถือและคอมพิวเตอร์ เชื่อมต่อ Wi-Fi เดียวกัน แล้วมือถือจะทำงานเป็นไมค์ไร้สายในทุกแอปบนคอมพิวเตอร์
</details>

<details>
<summary><b>เชื่อมต่อมือถือได้พร้อมกันกี่เครื่อง?</b></summary>

Crew Mic ออกแบบมาเพื่อใช้ไมค์หลายตัวพร้อมกัน พอดแคสต์หรือวงเสวนามักใช้ 2–4 เครื่อง แต่ละเครื่องปรับเกน ปิดเสียง และตัดเสียงรบกวนแยกกันได้
</details>

<details>
<summary><b>ใช้กับ Zoom, OBS, Discord และ Google Meet ได้ไหม?</b></summary>

ได้ Crew Mic ส่งเสียงมิกซ์ไปยังอุปกรณ์เสียงเสมือน (BlackHole หรือ VB-CABLE) แค่เลือกอุปกรณ์นั้นเป็นไมค์ในแอป
</details>

<details>
<summary><b>ต้องต่ออินเทอร์เน็ตไหม?</b></summary>

ไม่ต้อง เสียงส่งผ่านเครือข่ายภายใน (Wi-Fi LAN) เท่านั้น มือถือและคอมพิวเตอร์แค่ต้องอยู่ในเครือข่ายเดียวกัน
</details>

<details>
<summary><b>ใช้ Android กับ iPhone ร่วมกันได้ไหม?</b></summary>

ได้ อุปกรณ์ Android และ iOS เข้าร่วมเซสชันเดียวกันได้และซิงก์กันอัตโนมัติ
</details>

<details>
<summary><b>ทำไมใช้ไมค์สองตัวแล้วเสียงกลวง?</b></summary>

นั่นคือปรากฏการณ์ comb filter ที่เกิดจากไมค์ไม่ตรงจังหวะกัน เปิด **ซิงก์แหล่งเสียง** ใน Crew Mic เพื่อจัดทุกช่องให้ตรงกันภายในไม่กี่มิลลิวินาที
</details>

---

## 📥 ดาวน์โหลด

<div align="center">

### พร้อมเปลี่ยนมือถือให้เป็นระบบไมค์ระดับโปรหรือยัง?

[![ดาวน์โหลด Crew Mic เลย](https://img.shields.io/badge/⬇_ดาวน์โหลด_Crew_Mic-crewmic.codelumix.com-38bdf8?style=for-the-badge)](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=footer_th)

⭐ **ถ้า Crew Mic มีประโยชน์ ฝากกด Star ให้ repo นี้ด้วย** เพื่อให้ครีเอเตอร์คนอื่นค้นเจอมากขึ้น

</div>

---

## 💬 ข้อเสนอแนะและการช่วยเหลือ

- 🐛 แจ้งบั๊กหรือขอฟีเจอร์ได้ที่ [Issues](../../issues)
- 🌐 เว็บไซต์: [crewmic.codelumix.com](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=support_th)
- 🏢 พัฒนาโดย [CodeLumix](https://codelumix.com/?utm_source=github&utm_medium=readme)

<sub>**คำค้นหา:** ใช้มือถือเป็นไมค์, มือถือเป็นไมค์คอม, แอปไมค์ไร้สาย, ไมค์ Wi-Fi, iPhone เป็นไมค์ Mac, Android เป็นไมค์ Windows, ไมค์พอดแคสต์, ไมค์ไร้สาย OBS, ไมค์ Zoom, ตัดเสียงรบกวน AI, ไมค์เสมือน</sub>
