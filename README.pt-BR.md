<div align="center">

<img src="assets/logo.svg" alt="Crew Mic – use o celular como microfone sem fio no PC e no Mac" width="128" height="128">

# Crew Mic — Transforme Seu Celular em um Microfone Sem Fio para Mac e Windows

**Use vários celulares Android e iPhone como microfones Wi-Fi de baixa latência. Mixe tudo no computador e envie direto para Zoom, OBS, Discord, Google Meet ou Teams.**

[![Baixar Crew Mic](https://img.shields.io/badge/Baixar-crewmic.codelumix.com-38bdf8?style=for-the-badge)](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=hero_pt)

![macOS](https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?style=flat-square&logo=ios&logoColor=white)
![Latência](https://img.shields.io/badge/latência-40--100_ms-0ea5e9?style=flat-square)
![Áudio](https://img.shields.io/badge/áudio-48_kHz_PCM-6366f1?style=flat-square)

[English](README.md) · [Tiếng Việt](README.vi.md) · [Español](README.es.md) · **Português** · [Français](README.fr.md) · [Deutsch](README.de.md) · [Русский](README.ru.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Bahasa Indonesia](README.id.md) · [ไทย](README.th.md)

</div>

---

## Por que Crew Mic?

Gravar um podcast com três convidados, fazer uma live com um co-apresentador ou entrar numa reunião híbrida de uma sala barulhenta normalmente exige kits de microfone sem fio que custam centenas de reais.

**Mas você já tem os microfones: seus celulares.**

O Crew Mic conecta **vários smartphones** a um único computador pelo Wi-Fi local. Cada celular vira um canal de microfone próprio, com **redução de ruído por IA**, **sincronização automática entre os microfones** e **proteção contra distorção**. A mixagem final aparece como um **microfone virtual** que qualquer aplicativo pode usar.

> 🎙️ Sem cabos. Sem receptores. Sem hardware extra. Instale o app, abra nos celulares e comece a falar.

---

## ✨ Principais recursos

| | Recurso | O que ele faz por você |
|---|---|---|
| 📱 | **Vários celulares ao mesmo tempo** | Conecte vários Android e iPhone simultaneamente. Cada um ganha seu próprio canal. |
| ⚡ | **Áudio Wi-Fi de baixa latência** | Áudio de 48 kHz sem compressão via UDP, em quadros de 10 ms. Latência total típica de **40–100 ms**. |
| 🔇 | **Redução de ruído por IA em 4 níveis** | A rede neural RNNoise (Desligado / Leve / Médio / Forte com noise gate) remove ventilador, ar-condicionado e trânsito. Trocar de nível não gera estalos. |
| 🎯 | **Sincronização de múltiplas fontes** | Alinha todos os celulares ao momento real da captura, com diferença ≤ 5 ms (p95). Isso evita o som oco, "de túnel", que surge quando dois microfones saem de sincronia. |
| 🛡️ | **Limitador master** | Limitador look-ahead (≤ 1 ms, teto de −1 dBFS) que evita distorção quando todos riem ao mesmo tempo. |
| 🎛️ | **Mesa de som no desktop** | Ganho, mudo, ajuste de tempo (±100 ms) e medidores VU a 30 Hz por canal, além de um bus master. |
| 🎧 | **Retorno no fone de ouvido** | Ouça a mixagem ao vivo por uma saída separada: AirPods, DAC USB ou P2 de 3,5 mm. |
| 🔌 | **Funciona com qualquer app** | Saída para microfone virtual (BlackHole no macOS, VB-CABLE no Windows) para Zoom, OBS, Discord, Meet, Teams e DAWs. |
| 🔍 | **Descoberta automática** | Os celulares encontram o computador via mDNS/Bonjour. Você aprova cada dispositivo antes de ele entrar. |
| 🔒 | **Fica na sua rede** | O áudio vai direto do celular para o computador pela rede local. Nada é enviado para a nuvem. |

---

## 🎬 Para quem é?

- **Podcasters**: grave 2–4 pessoas, cada uma com o celular como microfone de lapela, perfeitamente sincronizadas.
- **Streamers e youtubers**: adicione o microfone de um co-apresentador ou convidado ao OBS sem comprar kit sem fio.
- **Equipes remotas e híbridas**: espalhe celulares pela mesa de reunião para que todos sejam ouvidos com clareza no Zoom ou Teams.
- **Professores e palestrantes**: circule pela sala com o celular no bolso como microfone sem fio.
- **Entrevistadores e jornalistas**: conduza entrevistas a dois com retorno em tempo real.
- **Igrejas, eventos e pequenos espaços**: monte rapidamente um sistema com vários microfones para palestras e painéis.

---

## 🚀 Comece em 3 passos

1. **Baixe o Crew Mic** para o computador (macOS / Windows) e para os celulares (Android / iOS) em
   👉 **[crewmic.codelumix.com](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=steps_pt)**
2. **Instale um driver de microfone virtual** (apenas uma vez):
   - macOS: [BlackHole 2ch](https://existential.audio/blackhole/) (`brew install --cask blackhole-2ch`)
   - Windows: [VB-CABLE](https://vb-audio.com/Cable/)
3. **Conecte e fale**: abra o app no computador e o Crew Mic em cada celular na mesma rede Wi-Fi, aprove os dispositivos e escolha o microfone virtual no Zoom, OBS ou Discord.

> 💡 **Dica:** para a menor latência, use Wi-Fi de 5 GHz e configure o dispositivo virtual em **48.000 Hz**.

---

## ⚙️ Modos de latência

| Modo | Latência total estimada | Ideal para |
|---|---|---|
| **Baixa** | 40–60 ms | Entrevistas ao vivo e conversa em tempo real com Wi-Fi 5 GHz forte |
| **Equilibrado** *(padrão)* | 60–100 ms | A maioria dos usuários em Wi-Fi doméstico ou de escritório |
| **Estável** | 100–180 ms | Sinal fraco, longas distâncias ou redes congestionadas |

---

## 🧠 Como funciona

```text
 📱 Celular 1 (Android) ─┐
 📱 Celular 2 (iPhone)  ─┼── Wi-Fi LAN · 48 kHz PCM · UDP ──►  💻 Crew Mic Desktop
 📱 Celular N (...)     ─┘                                      │
                                                                ├─ Buffer de jitter adaptativo
                                                                ├─ Correção de deriva de clock
                                                                ├─ Redução de ruído IA RNNoise
                                                                ├─ Sincronização multifonte
                                                                └─ Limitador look-ahead
                                                                       │
                                         ┌─────────────────────────────┴───────────────┐
                                         ▼                                             ▼
                            🎙️ Microfone virtual (BlackHole / VB-CABLE)       🎧 Fone de retorno
                                         │
                                         ▼
                           Zoom · OBS · Discord · Meet · Teams
```

O motor do desktop é escrito em **Rust** (Tauri v2) para áudio em tempo real: mixagem lock-free sem alocação de memória na thread de áudio. Os apps móveis usam APIs de áudio nativas (Android `AudioRecord`, iOS `AVAudioEngine`) para capturar com a menor latência possível.

---

## ❓ Perguntas frequentes

<details>
<summary><b>Posso usar o celular como microfone no PC ou no Mac?</b></summary>

Sim. Instale o Crew Mic no celular e no computador, conecte os dois à mesma rede Wi-Fi e o celular funciona como microfone sem fio em qualquer aplicativo de desktop.
</details>

<details>
<summary><b>Quantos celulares posso conectar ao mesmo tempo?</b></summary>

O Crew Mic foi feito para vários microfones simultâneos. Um podcast ou painel costuma usar 2–4 celulares, cada um com canal próprio de ganho, mudo e redução de ruído.
</details>

<details>
<summary><b>Funciona com Zoom, OBS, Discord e Google Meet?</b></summary>

Sim. O Crew Mic envia a mixagem para um dispositivo de áudio virtual (BlackHole ou VB-CABLE). Basta escolhê-lo como microfone no aplicativo.
</details>

<details>
<summary><b>Preciso de internet?</b></summary>

Não. O áudio trafega apenas pela rede local (Wi-Fi LAN); celulares e computador só precisam estar na mesma rede.
</details>

<details>
<summary><b>Posso misturar Android e iPhone?</b></summary>

Sim. Dispositivos Android e iOS entram na mesma sessão e são sincronizados automaticamente.
</details>

<details>
<summary><b>Por que o som fica oco quando uso dois microfones?</b></summary>

É o efeito de filtro pente, causado por microfones fora de sincronia. Ative a **Sincronização de fontes** no Crew Mic para alinhar todos os canais em poucos milissegundos.
</details>

---

## 📥 Download

<div align="center">

### Pronto para transformar seus celulares em um sistema de microfones profissional?

[![Baixar Crew Mic agora](https://img.shields.io/badge/⬇_Baixar_Crew_Mic-crewmic.codelumix.com-38bdf8?style=for-the-badge)](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=footer_pt)

⭐ **Se o Crew Mic te ajudou, deixe uma estrela no repositório** para que mais criadores o encontrem.

</div>

---

## 💬 Feedback e suporte

- 🐛 Relate bugs ou peça recursos em [Issues](../../issues)
- 🌐 Site: [crewmic.codelumix.com](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=support_pt)
- 🏢 Feito por [CodeLumix](https://codelumix.com/?utm_source=github&utm_medium=readme)

<sub>**Palavras-chave:** usar celular como microfone, microfone sem fio para PC, app de microfone Wi-Fi, iPhone como microfone no Mac, Android como microfone no Windows, microfone para podcast, microfone sem fio OBS, microfone para Zoom, redução de ruído com IA, microfone virtual.</sub>
