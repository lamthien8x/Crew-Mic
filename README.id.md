<div align="center">

<img src="assets/logo.svg" alt="Crew Mic – jadikan HP sebagai mic wireless untuk PC dan Mac" width="128" height="128">

# Crew Mic — Ubah HP Kamu Jadi Mic Wireless untuk Mac & Windows

**Gunakan beberapa HP Android dan iPhone sekaligus sebagai mic Wi-Fi berlatensi rendah. Mixing di komputer, lalu kirim langsung ke Zoom, OBS, Discord, Google Meet, atau Teams.**

[![Unduh Crew Mic](https://img.shields.io/badge/Unduh-crewmic.codelumix.com-38bdf8?style=for-the-badge)](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=hero_id)

![macOS](https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?style=flat-square&logo=ios&logoColor=white)
![Latensi](https://img.shields.io/badge/latensi-40--100_ms-0ea5e9?style=flat-square)
![Audio](https://img.shields.io/badge/audio-48_kHz_PCM-6366f1?style=flat-square)

[English](README.md) · [Tiếng Việt](README.vi.md) · [Español](README.es.md) · [Português](README.pt-BR.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Русский](README.ru.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · **Bahasa Indonesia** · [ไทย](README.th.md)

</div>

---

## Kenapa Crew Mic?

Rekam podcast dengan tiga tamu, live streaming bareng co-host, atau ikut meeting hybrid dari ruangan yang bising. Biasanya kamu harus beli set mic wireless seharga jutaan rupiah.

**Padahal kamu sudah punya mic-nya: HP kamu sendiri.**

Crew Mic menghubungkan **beberapa smartphone** ke satu komputer lewat Wi-Fi lokal. Setiap HP menjadi channel mic tersendiri dengan **peredam bising AI**, **sinkronisasi otomatis antar-mic**, dan **perlindungan dari clipping**. Hasil mixing tampil sebagai **mic virtual** yang bisa dipilih di aplikasi apa pun.

> 🎙️ Tanpa kabel. Tanpa receiver. Tanpa hardware tambahan. Pasang aplikasinya, buka di HP, lalu mulai bicara.

---

## ✨ Fitur Utama

| | Fitur | Manfaatnya untuk kamu |
|---|---|---|
| 📱 | **Banyak HP sekaligus** | Hubungkan beberapa HP Android dan iPhone bersamaan. Masing-masing punya channel sendiri. |
| ⚡ | **Audio Wi-Fi latensi rendah** | Audio 48 kHz tanpa kompresi via UDP dalam frame 10 ms. Latensi total biasanya hanya **40–100 ms**. |
| 🔇 | **Peredam bising AI 4 level** | Jaringan saraf RNNoise (Mati / Ringan / Sedang / Kuat dengan noise gate) menghilangkan suara kipas, AC, dan lalu lintas. Ganti level tanpa bunyi "klik". |
| 🎯 | **Sinkronisasi multi-sumber** | Menyelaraskan semua HP ke momen perekaman yang sebenarnya, dengan selisih ≤ 5 ms (p95). Suara tidak lagi terdengar kosong seperti di "terowongan" saat dua mic tidak sinkron. |
| 🛡️ | **Limiter master** | Limiter look-ahead (≤ 1 ms, batas −1 dBFS) mencegah suara pecah saat semua orang tertawa bersamaan. |
| 🎛️ | **Mixer di desktop** | Gain, mute, offset waktu (±100 ms), dan VU meter 30 Hz per channel, plus bus master. |
| 🎧 | **Monitoring headphone** | Dengarkan hasil mixing secara live lewat output terpisah: AirPods, USB DAC, atau jack 3,5 mm. |
| 🔌 | **Jalan di semua aplikasi** | Output ke mic virtual (BlackHole di macOS, VB-CABLE di Windows) untuk Zoom, OBS, Discord, Meet, Teams, dan DAW. |
| 🔍 | **Deteksi otomatis** | HP menemukan komputer secara otomatis lewat mDNS/Bonjour. Kamu menyetujui setiap perangkat sebelum terhubung. |
| 🔒 | **Tetap di jaringanmu** | Audio dikirim langsung dari HP ke komputer di jaringan lokal. Tidak ada yang diunggah ke cloud. |

---

## 🎬 Cocok untuk Siapa?

- **Podcaster**: rekam 2–4 orang, masing-masing pakai HP sebagai mic klip, sinkron sempurna.
- **Streamer & YouTuber**: tambahkan mic co-host atau tamu ke OBS tanpa beli set wireless.
- **Tim remote & hybrid**: letakkan HP di sekitar meja rapat agar semua orang terdengar jelas di Zoom atau Teams.
- **Guru & pembicara**: bergerak bebas di kelas dengan HP di saku sebagai mic wireless.
- **Pewawancara & jurnalis**: lakukan wawancara dua orang dengan monitoring real-time.
- **Gereja, acara & ruangan kecil**: siapkan sistem multi-mic dengan cepat untuk seminar dan diskusi panel.

---

## 🚀 Mulai dalam 3 Langkah

1. **Unduh Crew Mic** untuk komputer (macOS / Windows) dan HP (Android / iOS) di
   👉 **[crewmic.codelumix.com](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=steps_id)**
2. **Pasang driver mic virtual** (cukup sekali):
   - macOS: [BlackHole 2ch](https://existential.audio/blackhole/) (`brew install --cask blackhole-2ch`)
   - Windows: [VB-CABLE](https://vb-audio.com/Cable/)
3. **Hubungkan & bicara**: jalankan aplikasi desktop, buka Crew Mic di setiap HP pada Wi-Fi yang sama, setujui perangkatnya, lalu pilih mic virtual di Zoom, OBS, atau Discord.

> 💡 **Tips:** untuk latensi terendah, gunakan Wi-Fi 5 GHz dan atur perangkat virtual ke **48.000 Hz**.

---

## ⚙️ Mode Latensi

| Mode | Perkiraan latensi total | Paling cocok untuk |
|---|---|---|
| **Rendah** | 40–60 ms | Wawancara live dan percakapan real-time dengan Wi-Fi 5 GHz yang kuat |
| **Seimbang** *(default)* | 60–100 ms | Kebanyakan pengguna dengan Wi-Fi rumah atau kantor |
| **Stabil** | 100–180 ms | Sinyal lemah, jarak jauh, atau jaringan padat |

---

## 🧠 Cara Kerjanya

```text
 📱 HP 1 (Android) ─┐
 📱 HP 2 (iPhone)  ─┼── Wi-Fi LAN · 48 kHz PCM · UDP ──►  💻 Crew Mic Desktop
 📱 HP N (...)     ─┘                                      │
                                                           ├─ Buffer jitter adaptif
                                                           ├─ Koreksi clock drift
                                                           ├─ Peredam bising AI RNNoise
                                                           ├─ Sinkronisasi multi-sumber
                                                           └─ Limiter look-ahead
                                                                  │
                                    ┌─────────────────────────────┴───────────────┐
                                    ▼                                             ▼
                       🎙️ Mic virtual (BlackHole / VB-CABLE)             🎧 Headphone monitor
                                    │
                                    ▼
                      Zoom · OBS · Discord · Meet · Teams
```

Mesin desktop ditulis dengan **Rust** (Tauri v2) untuk audio real-time: mixing lock-free tanpa alokasi memori di thread audio. Aplikasi mobile memakai API audio native (Android `AudioRecord`, iOS `AVAudioEngine`) untuk perekaman dengan latensi serendah mungkin.

---

## ❓ Pertanyaan Umum

<details>
<summary><b>Bisakah HP dipakai sebagai mic untuk PC atau Mac?</b></summary>

Bisa. Pasang Crew Mic di HP dan komputer, hubungkan keduanya ke Wi-Fi yang sama, dan HP kamu berfungsi sebagai mic wireless di aplikasi desktop apa pun.
</details>

<details>
<summary><b>Berapa banyak HP yang bisa terhubung bersamaan?</b></summary>

Crew Mic dirancang untuk banyak mic sekaligus. Podcast atau diskusi panel biasanya memakai 2–4 HP, masing-masing dengan channel gain, mute, dan peredam bising sendiri.
</details>

<details>
<summary><b>Apakah bisa dipakai di Zoom, OBS, Discord, dan Google Meet?</b></summary>

Bisa. Crew Mic mengirim hasil mixing ke perangkat audio virtual (BlackHole atau VB-CABLE). Cukup pilih perangkat itu sebagai mic di aplikasi.
</details>

<details>
<summary><b>Perlu koneksi internet?</b></summary>

Tidak. Audio hanya lewat jaringan lokal (Wi-Fi LAN); HP dan komputer cukup berada di jaringan yang sama.
</details>

<details>
<summary><b>Bisa campur Android dan iPhone?</b></summary>

Bisa. Perangkat Android dan iOS bisa bergabung di sesi yang sama dan disinkronkan otomatis.
</details>

<details>
<summary><b>Kenapa suara jadi kosong saat pakai dua mic?</b></summary>

Itu efek comb filter karena mic tidak sinkron waktunya. Aktifkan **Sinkronisasi Sumber** di Crew Mic untuk menyelaraskan semua channel dalam hitungan milidetik.
</details>

---

## 📥 Unduh

<div align="center">

### Siap mengubah HP kamu jadi sistem mic profesional?

[![Unduh Crew Mic sekarang](https://img.shields.io/badge/⬇_Unduh_Crew_Mic-crewmic.codelumix.com-38bdf8?style=for-the-badge)](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=footer_id)

⭐ **Kalau Crew Mic bermanfaat, beri bintang untuk repo ini** supaya lebih banyak kreator menemukannya.

</div>

---

## 💬 Masukan & Dukungan

- 🐛 Laporkan bug atau minta fitur di [Issues](../../issues)
- 🌐 Situs web: [crewmic.codelumix.com](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=support_id)
- 🏢 Dibuat oleh [CodeLumix](https://codelumix.com/?utm_source=github&utm_medium=readme)

<sub>**Kata kunci:** HP jadi mic, HP sebagai mic PC, aplikasi mic wireless, mic Wi-Fi, iPhone jadi mic Mac, Android jadi mic Windows, mic podcast, mic wireless OBS, mic Zoom, peredam bising AI, mic virtual.</sub>
