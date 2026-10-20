<div align="center">

<img src="assets/logo.svg" alt="Crew Mic – utilisez votre smartphone comme micro sans fil pour PC et Mac" width="128" height="128">

# Crew Mic — Transformez Votre Smartphone en Micro Sans Fil pour Mac et Windows

**Utilisez plusieurs téléphones Android et iPhone comme micros Wi-Fi à faible latence. Mixez-les sur votre ordinateur et envoyez le résultat vers Zoom, OBS, Discord, Google Meet ou Teams.**

[![Télécharger Crew Mic](https://img.shields.io/badge/Télécharger-crewmic.codelumix.com-38bdf8?style=for-the-badge)](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=hero_fr)

![macOS](https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?style=flat-square&logo=ios&logoColor=white)
![Latence](https://img.shields.io/badge/latence-40--100_ms-0ea5e9?style=flat-square)
![Audio](https://img.shields.io/badge/audio-48_kHz_PCM-6366f1?style=flat-square)

[English](README.md) · [Tiếng Việt](README.vi.md) · [Español](README.es.md) · [Português](README.pt-BR.md) · **Français** · [Deutsch](README.de.md) · [Русский](README.ru.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Bahasa Indonesia](README.id.md) · [ไทย](README.th.md)

</div>

---

## Pourquoi Crew Mic ?

Enregistrer un podcast avec trois invités, animer un live avec un co-animateur ou rejoindre une réunion hybride depuis une pièce bruyante implique souvent d'acheter des kits de micros sans fil à plusieurs centaines d'euros.

**Pourtant, vous possédez déjà les micros : vos téléphones.**

Crew Mic connecte **plusieurs smartphones** à un seul ordinateur via votre Wi-Fi local. Chaque téléphone devient un canal micro à part entière, avec **réduction de bruit par IA**, **synchronisation automatique entre les micros** et **protection contre la saturation**. Le mix final apparaît comme un **micro virtuel** que n'importe quelle application peut sélectionner.

> 🎙️ Pas de câbles. Pas de récepteurs. Aucun matériel supplémentaire. Installez l'app, ouvrez-la sur vos téléphones et parlez.

---

## ✨ Fonctionnalités clés

| | Fonctionnalité | Ce qu'elle vous apporte |
|---|---|---|
| 📱 | **Plusieurs téléphones à la fois** | Connectez simultanément plusieurs Android et iPhone. Chacun dispose de sa propre tranche de console. |
| ⚡ | **Audio Wi-Fi faible latence** | Audio 48 kHz non compressé via UDP, en trames de 10 ms. Latence totale typique de **40–100 ms**. |
| 🔇 | **Réduction de bruit IA sur 4 niveaux** | Le réseau neuronal RNNoise (Désactivé / Léger / Moyen / Fort avec noise gate) supprime ventilateurs, climatisation et bruit de circulation. Changer de niveau ne produit aucun clic. |
| 🎯 | **Synchronisation multi-sources** | Aligne chaque téléphone sur l'instant réel de captation, à ≤ 5 ms près (p95). Fini le son creux, « de tunnel », qui apparaît quand deux micros se décalent. |
| 🛡️ | **Limiteur master** | Limiteur look-ahead (≤ 1 ms, plafond −1 dBFS) qui évite la distorsion quand tout le monde rit en même temps. |
| 🎛️ | **Console de mixage sur ordinateur** | Gain, mute, décalage temporel (±100 ms) et VU-mètres à 30 Hz par canal, plus un bus master. |
| 🎧 | **Retour casque** | Écoutez le mix en direct sur une sortie séparée : AirPods, DAC USB ou jack 3,5 mm. |
| 🔌 | **Compatible avec toutes les apps** | Sortie vers un micro virtuel (BlackHole sur macOS, VB-CABLE sur Windows) pour Zoom, OBS, Discord, Meet, Teams et les DAW. |
| 🔍 | **Découverte automatique** | Les téléphones trouvent l'ordinateur via mDNS/Bonjour. Vous approuvez chaque appareil avant qu'il ne rejoigne la session. |
| 🔒 | **Reste sur votre réseau** | L'audio passe directement du téléphone à l'ordinateur sur votre réseau local. Rien n'est envoyé dans le cloud. |

---

## 🎬 Pour qui ?

- **Podcasteurs** : enregistrez 2 à 4 personnes, chacune avec son téléphone comme micro-cravate, parfaitement synchronisées.
- **Streamers et youtubeurs** : ajoutez le micro d'un co-animateur ou d'un invité dans OBS sans acheter de kit sans fil.
- **Équipes à distance et hybrides** : disposez des téléphones autour de la table pour que chacun soit bien entendu sur Zoom ou Teams.
- **Enseignants et conférenciers** : déplacez-vous librement avec votre téléphone en poche comme micro sans fil.
- **Intervieweurs et journalistes** : menez des interviews à deux voix avec retour en temps réel.
- **Églises, événements et petites salles** : installez rapidement un système multi-micros pour conférences et tables rondes.

---

## 🚀 Démarrez en 3 étapes

1. **Téléchargez Crew Mic** pour votre ordinateur (macOS / Windows) et vos téléphones (Android / iOS) sur
   👉 **[crewmic.codelumix.com](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=steps_fr)**
2. **Installez un pilote de micro virtuel** (une seule fois) :
   - macOS : [BlackHole 2ch](https://existential.audio/blackhole/) (`brew install --cask blackhole-2ch`)
   - Windows : [VB-CABLE](https://vb-audio.com/Cable/)
3. **Connectez et parlez** : lancez l'app sur l'ordinateur, ouvrez Crew Mic sur chaque téléphone connecté au même Wi-Fi, approuvez les appareils, puis choisissez le micro virtuel dans Zoom, OBS ou Discord.

> 💡 **Astuce :** pour la latence la plus faible, utilisez le Wi-Fi 5 GHz et réglez le périphérique virtuel sur **48 000 Hz**.

---

## ⚙️ Modes de latence

| Mode | Latence totale estimée | Idéal pour |
|---|---|---|
| **Faible** | 40–60 ms | Interviews en direct et conversation en temps réel sur un Wi-Fi 5 GHz puissant |
| **Équilibré** *(par défaut)* | 60–100 ms | La plupart des utilisateurs, sur un Wi-Fi domestique ou de bureau |
| **Stable** | 100–180 ms | Signal faible, longue portée ou réseau encombré |

---

## 🧠 Comment ça marche

```text
 📱 Téléphone 1 (Android) ─┐
 📱 Téléphone 2 (iPhone)  ─┼── Wi-Fi LAN · 48 kHz PCM · UDP ──►  💻 Crew Mic Desktop
 📱 Téléphone N (...)     ─┘                                      │
                                                                  ├─ Tampon de gigue adaptatif
                                                                  ├─ Correction de dérive d'horloge
                                                                  ├─ Réduction de bruit IA RNNoise
                                                                  ├─ Synchronisation multi-sources
                                                                  └─ Limiteur look-ahead
                                                                         │
                                           ┌─────────────────────────────┴───────────────┐
                                           ▼                                             ▼
                              🎙️ Micro virtuel (BlackHole / VB-CABLE)           🎧 Casque de retour
                                           │
                                           ▼
                             Zoom · OBS · Discord · Meet · Teams
```

Le moteur desktop est écrit en **Rust** (Tauri v2) pour l'audio temps réel : mixage lock-free, sans allocation mémoire dans le thread audio. Les apps mobiles utilisent les API audio natives (Android `AudioRecord`, iOS `AVAudioEngine`) pour une captation à latence minimale.

---

## ❓ FAQ

<details>
<summary><b>Puis-je utiliser mon téléphone comme micro pour mon PC ou mon Mac ?</b></summary>

Oui. Installez Crew Mic sur le téléphone et l'ordinateur, connectez-les au même Wi-Fi, et votre téléphone devient un micro sans fil pour n'importe quelle application.
</details>

<details>
<summary><b>Combien de téléphones puis-je connecter en même temps ?</b></summary>

Crew Mic est conçu pour plusieurs micros simultanés. Un podcast ou une table ronde utilise généralement 2 à 4 téléphones, chacun avec son propre canal de gain, mute et réduction de bruit.
</details>

<details>
<summary><b>Est-ce compatible avec Zoom, OBS, Discord et Google Meet ?</b></summary>

Oui. Crew Mic envoie son mix vers un périphérique audio virtuel (BlackHole ou VB-CABLE). Il suffit de le choisir comme micro dans l'application.
</details>

<details>
<summary><b>Faut-il une connexion Internet ?</b></summary>

Non. L'audio circule uniquement sur votre réseau local (Wi-Fi LAN) ; les téléphones et l'ordinateur doivent simplement être sur le même réseau.
</details>

<details>
<summary><b>Puis-je mélanger Android et iPhone ?</b></summary>

Oui. Les appareils Android et iOS rejoignent la même session et sont synchronisés automatiquement.
</details>

<details>
<summary><b>Pourquoi le son devient-il creux avec deux micros ?</b></summary>

C'est un effet de filtre en peigne, causé par des micros décalés dans le temps. Activez la **Synchronisation des sources** dans Crew Mic pour aligner tous les canaux à quelques millisecondes près.
</details>

---

## 📥 Téléchargement

<div align="center">

### Prêt à transformer vos téléphones en système de micros professionnel ?

[![Télécharger Crew Mic maintenant](https://img.shields.io/badge/⬇_Télécharger_Crew_Mic-crewmic.codelumix.com-38bdf8?style=for-the-badge)](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=footer_fr)

⭐ **Si Crew Mic vous est utile, ajoutez une étoile au dépôt** pour aider d'autres créateurs à le découvrir.

</div>

---

## 💬 Retours et support

- 🐛 Signalez un bug ou proposez une fonctionnalité dans les [Issues](../../issues)
- 🌐 Site web : [crewmic.codelumix.com](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=support_fr)
- 🏢 Développé par [CodeLumix](https://codelumix.com/?utm_source=github&utm_medium=readme)

<sub>**Mots-clés :** utiliser son téléphone comme micro, micro sans fil pour PC, application micro Wi-Fi, iPhone comme micro pour Mac, Android comme micro pour Windows, micro pour podcast, micro sans fil OBS, micro pour Zoom, réduction de bruit IA, micro virtuel.</sub>
