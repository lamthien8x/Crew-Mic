<div align="center">

<img src="assets/logo.svg" alt="Crew Mic – スマホを PC・Mac 用ワイヤレスマイクに" width="128" height="128">

# Crew Mic — スマホを Mac / Windows 用ワイヤレスマイクに変えるアプリ

**複数の Android・iPhone を低遅延の Wi-Fi マイクとして同時に使用。PC でミックスして、そのまま Zoom・OBS・Discord・Google Meet・Teams へ。**

[![Crew Mic をダウンロード](https://img.shields.io/badge/ダウンロード-crewmic.codelumix.com-38bdf8?style=for-the-badge)](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=hero_ja)

![macOS](https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?style=flat-square&logo=ios&logoColor=white)
![遅延](https://img.shields.io/badge/遅延-40--100_ms-0ea5e9?style=flat-square)
![音声](https://img.shields.io/badge/音声-48_kHz_PCM-6366f1?style=flat-square)

[English](README.md) · [Tiếng Việt](README.vi.md) · [Español](README.es.md) · [Português](README.pt-BR.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Русский](README.ru.md) · [简体中文](README.zh-CN.md) · **日本語** · [한국어](README.ko.md) · [Bahasa Indonesia](README.id.md) · [ไทย](README.th.md)

</div>

---

## なぜ Crew Mic？

ゲスト3人とのポッドキャスト収録、相方との配信、騒がしい部屋からのハイブリッド会議。普通なら数万円するワイヤレスマイクセットが必要です。

**でも、マイクはもう持っています。あなたのスマホです。**

Crew Mic はローカル Wi-Fi 経由で**複数のスマホ**を1台の PC に接続します。各スマホが独立したマイクチャンネルになり、**AI ノイズ除去**、**マイク間の自動同期**、**音割れ防止**を備えています。最終ミックスは**仮想マイク**として出力され、どのアプリからでも選択できます。

> 🎙️ ケーブル不要、受信機不要、追加ハードウェア不要。アプリを入れてスマホで開けば、すぐに話せます。

---

## ✨ 主な機能

| | 機能 | メリット |
|---|---|---|
| 📱 | **複数スマホを同時接続** | 複数の Android と iPhone を同時に接続でき、1台ごとに独立したチャンネルになります。 |
| ⚡ | **低遅延 Wi-Fi オーディオ** | 48 kHz 非圧縮音声を UDP・10 ms フレームで伝送。総遅延は通常 **40–100 ms**。 |
| 🔇 | **4段階 AI ノイズ除去** | RNNoise ニューラルネット（オフ / 弱 / 中 / 強＋ノイズゲート）でファン・エアコン・車の音を除去。切り替え時のプチノイズもありません。 |
| 🎯 | **マルチソース同期** | 実際の収音タイミングで全スマホを揃え、ズレを ≤ 5 ms（p95）に抑えます。2本のマイクがズレたときの「こもった」「トンネルのような」音を防ぎます。 |
| 🛡️ | **マスターリミッター** | ルックアヘッドリミッター（≤ 1 ms、上限 −1 dBFS）で、全員が同時に笑っても音割れしません。 |
| 🎛️ | **デスクトップミキサー** | チャンネルごとのゲイン・ミュート・タイミング補正（±100 ms）・30 Hz VU メーター、そしてマスターバス。 |
| 🎧 | **ヘッドホンモニター** | AirPods・USB DAC・3.5 mm ジャックなど、別出力でミックスをリアルタイム確認できます。 |
| 🔌 | **あらゆるアプリに対応** | 仮想マイク（macOS は BlackHole、Windows は VB-CABLE）へ出力し、Zoom・OBS・Discord・Meet・Teams・DAW で使えます。 |
| 🔍 | **自動検出** | mDNS/Bonjour でスマホが PC を自動検出。接続は1台ずつ承認制です。 |
| 🔒 | **ネットワーク内で完結** | 音声はスマホから LAN 内の PC へ直接届き、クラウドにはアップロードされません。 |

---

## 🎬 こんな方に

- **ポッドキャスター**：2〜4人がそれぞれスマホをピンマイク代わりにして、完全同期で収録。
- **配信者・YouTuber**：ワイヤレスセットを買わずに、相方やゲストのマイクを OBS に追加。
- **リモート／ハイブリッドチーム**：会議テーブルにスマホを置けば、Zoom や Teams で全員の声がクリアに。
- **教師・講演者**：スマホをポケットに入れてワイヤレスマイクとして使い、教室を自由に移動。
- **インタビュアー・記者**：リアルタイムモニターしながら2人インタビュー。
- **教会・イベント・小規模会場**：講演やパネルディスカッション向けのマルチマイク環境をすばやく構築。

---

## 🚀 3ステップで開始

1. **Crew Mic をダウンロード**：PC 版（macOS / Windows）とスマホ版（Android / iOS）はこちら
   👉 **[crewmic.codelumix.com](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=steps_ja)**
2. **仮想マイクドライバーをインストール**（初回のみ）：
   - macOS：[BlackHole 2ch](https://existential.audio/blackhole/)（`brew install --cask blackhole-2ch`）
   - Windows：[VB-CABLE](https://vb-audio.com/Cable/)
3. **接続して話すだけ**：PC 版を起動し、同じ Wi-Fi 上の各スマホで Crew Mic を開いて承認。Zoom・OBS・Discord で仮想マイクを選択します。

> 💡 **ヒント：** 遅延を最小にするには 5 GHz の Wi-Fi を使い、仮想デバイスを **48,000 Hz** に設定してください。

---

## ⚙️ 遅延モード

| モード | 推定総遅延 | おすすめ |
|---|---|---|
| **低遅延** | 40–60 ms | 強い 5 GHz Wi-Fi でのライブインタビュー・リアルタイム対談 |
| **バランス**（既定） | 60–100 ms | 一般的な家庭・オフィス Wi-Fi のほとんどのユーザー |
| **安定** | 100–180 ms | 電波が弱い・距離が遠い・混雑したネットワーク |

---

## 🧠 仕組み

```text
 📱 スマホ 1 (Android) ─┐
 📱 スマホ 2 (iPhone)  ─┼── Wi-Fi LAN · 48 kHz PCM · UDP ──►  💻 Crew Mic Desktop
 📱 スマホ N (...)     ─┘                                      │
                                                               ├─ 適応型ジッターバッファ
                                                               ├─ クロックドリフト補正
                                                               ├─ RNNoise AI ノイズ除去
                                                               ├─ マルチソース同期
                                                               └─ ルックアヘッドリミッター
                                                                      │
                                        ┌─────────────────────────────┴───────────────┐
                                        ▼                                             ▼
                           🎙️ 仮想マイク (BlackHole / VB-CABLE)              🎧 モニターヘッドホン
                                        │
                                        ▼
                          Zoom · OBS · Discord · Meet · Teams
```

デスクトップエンジンはリアルタイム音声処理のため **Rust**（Tauri v2）で書かれており、オーディオスレッドでメモリ確保を行わないロックフリーミキシングを採用しています。モバイルアプリはネイティブ音声 API（Android `AudioRecord`、iOS `AVAudioEngine`）で、最小限の遅延で収音します。

---

## ❓ よくある質問

<details>
<summary><b>スマホを PC や Mac のマイクとして使えますか？</b></summary>

はい。スマホと PC に Crew Mic を入れて同じ Wi-Fi に接続すれば、スマホがあらゆるデスクトップアプリのワイヤレスマイクになります。
</details>

<details>
<summary><b>同時に何台まで接続できますか？</b></summary>

Crew Mic は複数マイクの同時使用を前提に設計されています。ポッドキャストやパネルでは通常 2〜4 台を使い、各スマホでゲイン・ミュート・ノイズ除去を個別に調整できます。
</details>

<details>
<summary><b>Zoom・OBS・Discord・Google Meet で使えますか？</b></summary>

はい。Crew Mic はミックスを仮想オーディオデバイス（BlackHole または VB-CABLE）に出力します。アプリでそのデバイスをマイクに選ぶだけです。
</details>

<details>
<summary><b>インターネット接続は必要ですか？</b></summary>

不要です。音声はローカルネットワーク（Wi-Fi LAN）内だけを流れるので、スマホと PC が同じネットワークにあれば動作します。
</details>

<details>
<summary><b>Android と iPhone を混在できますか？</b></summary>

はい。Android と iOS のデバイスが同じセッションに参加でき、自動で同期されます。
</details>

<details>
<summary><b>マイクを2本使うと声がこもるのはなぜ？</b></summary>

マイク間の時間ズレによるコムフィルター現象です。Crew Mic の**ソース同期**をオンにすると、全チャンネルが数ミリ秒以内に揃います。
</details>

---

## 📥 ダウンロード

<div align="center">

### スマホをプロ仕様のマイクシステムに変えませんか？

[![今すぐ Crew Mic をダウンロード](https://img.shields.io/badge/⬇_Crew_Mic_をダウンロード-crewmic.codelumix.com-38bdf8?style=for-the-badge)](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=footer_ja)

⭐ **Crew Mic が役に立ったら、リポジトリに Star をお願いします。** より多くのクリエイターに届きます。

</div>

---

## 💬 フィードバックとサポート

- 🐛 バグ報告や機能リクエストは [Issues](../../issues) へ
- 🌐 ウェブサイト：[crewmic.codelumix.com](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=support_ja)
- 🏢 開発：[CodeLumix](https://codelumix.com/?utm_source=github&utm_medium=readme)

<sub>**キーワード：** スマホをマイクに、スマホ PC マイク、ワイヤレスマイク アプリ、Wi-Fi マイク、iPhone Mac マイク、Android Windows マイク、ポッドキャスト マイク、OBS ワイヤレスマイク、Zoom マイク、AI ノイズ除去、仮想マイク。</sub>
