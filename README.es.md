<div align="center">

<img src="assets/logo.svg" alt="Crew Mic – usa tu móvil como micrófono inalámbrico para PC y Mac" width="128" height="128">

# Crew Mic — Convierte Tu Móvil en un Micrófono Inalámbrico para Mac y Windows

**Usa varios teléfonos Android y iPhone como micrófonos Wi-Fi de baja latencia. Mézclalos en tu ordenador y envía el resultado a Zoom, OBS, Discord, Google Meet o Teams.**

[![Descargar Crew Mic](https://img.shields.io/badge/Descargar-crewmic.codelumix.com-38bdf8?style=for-the-badge)](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=hero_es)

![macOS](https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?style=flat-square&logo=ios&logoColor=white)
![Latencia](https://img.shields.io/badge/latencia-40--100_ms-0ea5e9?style=flat-square)
![Audio](https://img.shields.io/badge/audio-48_kHz_PCM-6366f1?style=flat-square)

[English](README.md) · [Tiếng Việt](README.vi.md) · **Español** · [Português](README.pt-BR.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Русский](README.ru.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Bahasa Indonesia](README.id.md) · [ไทย](README.th.md)

</div>

---

## ¿Por qué Crew Mic?

Grabar un pódcast con tres invitados, hacer un directo con un copresentador o unirte a una reunión híbrida desde una sala ruidosa suele obligarte a comprar kits de micrófonos inalámbricos que cuestan cientos de euros.

**Pero ya tienes los micrófonos: tus teléfonos.**

Crew Mic conecta **varios smartphones** a un solo ordenador a través de tu Wi-Fi local. Cada teléfono se convierte en un canal de micrófono propio con **reducción de ruido por IA**, **sincronización automática entre micros** y **protección contra saturación**. La mezcla final aparece como un **micrófono virtual** que cualquier aplicación puede seleccionar.

> 🎙️ Sin cables. Sin receptores. Sin hardware extra. Instala la app, ábrela en tus móviles y empieza a hablar.

---

## ✨ Funciones principales

| | Función | Qué te aporta |
|---|---|---|
| 📱 | **Varios teléfonos a la vez** | Conecta varios Android y iPhone simultáneamente. Cada uno tiene su propio canal. |
| ⚡ | **Audio Wi-Fi de baja latencia** | Audio de 48 kHz sin comprimir por UDP en bloques de 10 ms. Latencia total típica de **40–100 ms**. |
| 🔇 | **Reducción de ruido con IA en 4 niveles** | La red neuronal RNNoise (Apagado / Suave / Medio / Fuerte con puerta de ruido) elimina ventiladores, aire acondicionado y tráfico. Cambiar de nivel no produce clics. |
| 🎯 | **Sincronización multifuente** | Alinea todos los teléfonos al instante real de captura, con una diferencia ≤ 5 ms (p95). Así evitas el sonido hueco, "de túnel", que aparece cuando dos micros se desfasan. |
| 🛡️ | **Limitador maestro** | Limitador look-ahead (≤ 1 ms, techo −1 dBFS) que evita la distorsión cuando todos ríen a la vez. |
| 🎛️ | **Mesa de mezclas en el escritorio** | Ganancia, silencio, ajuste de tiempo (±100 ms) y vúmetros a 30 Hz por canal, más un bus maestro. |
| 🎧 | **Monitorización por auriculares** | Escucha la mezcla en directo por una salida aparte: AirPods, DAC USB o jack de 3,5 mm. |
| 🔌 | **Compatible con cualquier app** | Salida a un micrófono virtual (BlackHole en macOS, VB-CABLE en Windows) para Zoom, OBS, Discord, Meet, Teams y DAW. |
| 🔍 | **Detección automática** | Los teléfonos encuentran tu ordenador vía mDNS/Bonjour. Tú apruebas cada dispositivo antes de que se una. |
| 🔒 | **Se queda en tu red** | El audio va directo del móvil al ordenador por tu red local. Nada se sube a la nube. |

---

## 🎬 ¿Para quién es?

- **Podcasters**: graba a 2–4 personas, cada una con su móvil como micrófono de solapa, perfectamente sincronizadas.
- **Streamers y youtubers**: añade el micro de un copresentador o invitado a OBS sin comprar un kit inalámbrico.
- **Equipos remotos e híbridos**: reparte móviles por la mesa de reuniones para que todos se oigan bien en Zoom o Teams.
- **Profesores y ponentes**: muévete por el aula con el móvil en el bolsillo como micrófono inalámbrico.
- **Entrevistadores y periodistas**: haz entrevistas a dos voces con monitorización en tiempo real.
- **Iglesias, eventos y salas pequeñas**: monta en minutos un sistema multimicro para charlas y mesas redondas.

---

## 🚀 Empieza en 3 pasos

1. **Descarga Crew Mic** para tu ordenador (macOS / Windows) y tus móviles (Android / iOS) en
   👉 **[crewmic.codelumix.com](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=steps_es)**
2. **Instala un controlador de micrófono virtual** (solo una vez):
   - macOS: [BlackHole 2ch](https://existential.audio/blackhole/) (`brew install --cask blackhole-2ch`)
   - Windows: [VB-CABLE](https://vb-audio.com/Cable/)
3. **Conecta y habla**: abre la app de escritorio y Crew Mic en cada móvil conectado a la misma Wi-Fi, aprueba los dispositivos y elige el micrófono virtual en Zoom, OBS o Discord.

> 💡 **Consejo:** para la menor latencia, usa Wi-Fi de 5 GHz y configura el dispositivo virtual a **48 000 Hz**.

---

## ⚙️ Modos de latencia

| Modo | Latencia total estimada | Ideal para |
|---|---|---|
| **Baja** | 40–60 ms | Entrevistas en directo y conversación en tiempo real con Wi-Fi 5 GHz potente |
| **Equilibrado** *(por defecto)* | 60–100 ms | La mayoría de usuarios con Wi-Fi doméstica o de oficina |
| **Estable** | 100–180 ms | Señal débil, largas distancias o redes saturadas |

---

## 🧠 Cómo funciona

```text
 📱 Móvil 1 (Android) ─┐
 📱 Móvil 2 (iPhone)  ─┼── Wi-Fi LAN · 48 kHz PCM · UDP ──►  💻 Crew Mic Desktop
 📱 Móvil N (...)     ─┘                                      │
                                                              ├─ Búfer de jitter adaptativo
                                                              ├─ Corrección de deriva de reloj
                                                              ├─ Reducción de ruido IA RNNoise
                                                              ├─ Sincronización multifuente
                                                              └─ Limitador look-ahead
                                                                     │
                                       ┌─────────────────────────────┴───────────────┐
                                       ▼                                             ▼
                          🎙️ Micro virtual (BlackHole / VB-CABLE)       🎧 Auriculares de monitorización
                                       │
                                       ▼
                         Zoom · OBS · Discord · Meet · Teams
```

El motor de escritorio está escrito en **Rust** (Tauri v2) para audio en tiempo real: mezcla lock-free sin asignaciones de memoria en el hilo de audio. Las apps móviles usan las API de audio nativas (Android `AudioRecord`, iOS `AVAudioEngine`) para capturar con la menor latencia posible.

---

## ❓ Preguntas frecuentes

<details>
<summary><b>¿Puedo usar mi móvil como micrófono para el PC o el Mac?</b></summary>

Sí. Instala Crew Mic en el móvil y en el ordenador, conéctalos a la misma Wi-Fi y el teléfono funcionará como micrófono inalámbrico en cualquier aplicación de escritorio.
</details>

<details>
<summary><b>¿Cuántos móviles puedo conectar a la vez?</b></summary>

Crew Mic está pensado para varios micrófonos simultáneos. Un pódcast o una mesa redonda suele usar 2–4 móviles, cada uno con su propio canal de ganancia, silencio y reducción de ruido.
</details>

<details>
<summary><b>¿Funciona con Zoom, OBS, Discord y Google Meet?</b></summary>

Sí. Crew Mic envía su mezcla a un dispositivo de audio virtual (BlackHole o VB-CABLE). Solo tienes que elegirlo como micrófono en la aplicación.
</details>

<details>
<summary><b>¿Necesito conexión a Internet?</b></summary>

No. El audio viaja solo por tu red local (Wi-Fi LAN); basta con que los móviles y el ordenador estén en la misma red.
</details>

<details>
<summary><b>¿Puedo mezclar Android y iPhone?</b></summary>

Sí. Los dispositivos Android e iOS pueden unirse a la misma sesión y se sincronizan automáticamente.
</details>

<details>
<summary><b>¿Por qué suena hueco cuando uso dos micrófonos?</b></summary>

Es el efecto de filtro de peine, causado por micros desfasados en el tiempo. Activa la **Sincronización de fuentes** en Crew Mic para alinear todos los canales en pocos milisegundos.
</details>

---

## 📥 Descarga

<div align="center">

### ¿Listo para convertir tus móviles en un equipo de micrófonos profesional?

[![Descargar Crew Mic ahora](https://img.shields.io/badge/⬇_Descargar_Crew_Mic-crewmic.codelumix.com-38bdf8?style=for-the-badge)](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=footer_es)

⭐ **Si Crew Mic te resulta útil, dale una estrella al repositorio** para que más creadores lo encuentren.

</div>

---

## 💬 Comentarios y soporte

- 🐛 Informa de errores o pide funciones en [Issues](../../issues)
- 🌐 Web: [crewmic.codelumix.com](https://crewmic.codelumix.com/?utm_source=github&utm_medium=readme&utm_campaign=support_es)
- 🏢 Hecho por [CodeLumix](https://codelumix.com/?utm_source=github&utm_medium=readme)

<sub>**Palabras clave:** usar móvil como micrófono, micrófono inalámbrico para PC, app de micrófono Wi-Fi, iPhone como micrófono para Mac, Android como micrófono para Windows, micrófono para pódcast, micrófono inalámbrico OBS, micrófono para Zoom, reducción de ruido con IA, micrófono virtual.</sub>
