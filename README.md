<p align="center">
  <img src="https://www.hyperion-studio.xyz/assets/proximity-chat.png" width="140" alt="Proximity Chat"/>
</p>

<h1 align="center">Proximity Chat</h1>

<p align="center">
  <b>Habla con quien tienes cerca. Nada más. Nada menos.</b><br/>
  Chat de voz por proximidad con overlay flotante para <b>Emergency Response: Libre County</b>.
</p>

<p align="center">
  <a href="https://github.com/AchitoRD/proximity-chat-releases/releases/latest"><img src="https://img.shields.io/github/v/release/AchitoRD/proximity-chat-releases?style=for-the-badge&color=8b5cf6&labelColor=1a1033&label=versi%C3%B3n" alt="Versión"/></a>
  <a href="https://github.com/AchitoRD/proximity-chat-releases/releases"><img src="https://img.shields.io/github/downloads/AchitoRD/proximity-chat-releases/total?style=for-the-badge&color=a855f7&labelColor=1a1033&label=descargas" alt="Descargas"/></a>
  <img src="https://img.shields.io/badge/Linux-.deb-7c3aed?style=for-the-badge&logo=linux&logoColor=white&labelColor=1a1033" alt="Linux"/>
  <img src="https://img.shields.io/badge/Windows-.exe-6d28d9?style=for-the-badge&logo=windows&logoColor=white&labelColor=1a1033" alt="Windows"/>
  <img src="https://img.shields.io/badge/macOS-.dmg-7c3aed?style=for-the-badge&logo=apple&logoColor=white&labelColor=1a1033" alt="macOS"/>
</p>

<p align="center">
  <a href="https://github.com/AchitoRD/proximity-chat-releases/releases/latest">
    <img src="https://img.shields.io/badge/%E2%AC%87%20DESCARGAR%20%C3%9ALTIMA%20VERSI%C3%93N-8b5cf6?style=for-the-badge&labelColor=5b21b6" alt="Descargar"/>
  </a>
</p>

<p align="center">
  <a href="https://www.hyperion-studio.xyz">Web</a> ·
  <a href="https://www.hyperion-studio.xyz/terminos">Términos</a> ·
  <a href="https://www.hyperion-studio.xyz/privacidad">Privacidad</a> ·
  <a href="https://github.com/AchitoRD/proximity-chat-releases/releases">Changelog</a>
</p>

---

## <img src="https://api.iconify.design/solar/microphone-3-bold-duotone.svg?color=%238b5cf6" width="28" height="28" align="absmiddle" alt=""/> ¿Qué es?

**Proximity Chat** es una app externa que se sienta sobre tu partida como un overlay y conecta tu voz con los jugadores que tienes cerca en el juego. Te acercas, se escucha. Te alejas, se apaga. Así de simple, como debe ser el roleplay.

> [!NOTE]
> Proximity Chat funciona **aparte** de Roblox. No modifica el juego ni cambia nada de tu cliente.

<br/>

## <img src="https://api.iconify.design/solar/stars-bold-duotone.svg?color=%238b5cf6" width="28" height="28" align="absmiddle" alt=""/> Características

<table>
  <tr>
    <td width="33%" valign="top" align="center">
      <img src="https://api.iconify.design/solar/soundwave-bold-duotone.svg?color=%23a855f7" width="48" height="48" alt=""/>
      <h3>Voz por proximidad</h3>
      <p>Solo escuchas a quien está cerca de ti. Inmersión real, sin ruido de fondo de todo el servidor.</p>
    </td>
    <td width="33%" valign="top" align="center">
      <img src="https://api.iconify.design/solar/layers-bold-duotone.svg?color=%23a855f7" width="48" height="48" alt=""/>
      <h3>Overlay flotante</h3>
      <p>Vive encima del juego. Sin alt-tab, sin cambiar de ventana, sin perder el hilo del rol.</p>
    </td>
    <td width="33%" valign="top" align="center">
      <img src="https://api.iconify.design/solar/shield-check-bold-duotone.svg?color=%23a855f7" width="48" height="48" alt=""/>
      <h3>Identidad verificada</h3>
      <p>Login con Discord y verificación de tu cuenta de Roblox vía RoVer.</p>
    </td>
  </tr>
</table>

<br/>

## <img src="https://api.iconify.design/solar/routing-2-bold-duotone.svg?color=%238b5cf6" width="28" height="28" align="absmiddle" alt=""/> Cómo funciona

```mermaid
flowchart LR
    A([Inicias sesión con Discord]) --> B([RoVer verifica tu Roblox])
    B --> C([Abres el juego])
    C --> D([Aparece el overlay])
    D --> E([Hablas con quien está cerca])
    style A fill:#5b21b6,stroke:#8b5cf6,color:#fff
    style B fill:#6d28d9,stroke:#8b5cf6,color:#fff
    style C fill:#7c3aed,stroke:#a78bfa,color:#fff
    style D fill:#8b5cf6,stroke:#c4b5fd,color:#fff
    style E fill:#a855f7,stroke:#d8b4fe,color:#fff
```

<br/>

## <img src="https://api.iconify.design/solar/download-minimalistic-bold-duotone.svg?color=%238b5cf6" width="28" height="28" align="absmiddle" alt=""/> Descarga

Entra a la **[última release](https://github.com/AchitoRD/proximity-chat-releases/releases/latest)** y baja el instalador de tu sistema:

| | Archivo | Sistema | Estado |
|:-:|---|---|:-:|
| <img src="https://api.iconify.design/logos/linux-tux.svg" width="22" alt=""/> | `Proximity.Chat_*_amd64.deb` | Linux (Debian, Ubuntu, Deepin y derivadas) | ✅ Disponible |
| <img src="https://api.iconify.design/logos/microsoft-windows-icon.svg" width="22" alt=""/> | `Proximity.Chat_*_x64-setup.exe` | Windows 10 / 11 (64 bits) | ✅ Disponible |
| <img src="https://api.iconify.design/logos/apple.svg" width="22" alt=""/> | `Proximity.Chat_*_universal.dmg` | macOS (Intel y Apple Silicon) | ✅ Disponible |

### <img src="https://api.iconify.design/solar/terminal-bold-duotone.svg?color=%23a855f7" width="24" height="24" align="absmiddle" alt=""/> Instalación en Linux

```bash
sudo dpkg -i "Proximity.Chat_1.0.2_amd64.deb"
```

> [!TIP]
> Si `dpkg` reporta dependencias faltantes, ejecuta:
> ```bash
> sudo apt-get install -f
> ```

### <img src="https://api.iconify.design/solar/desktop-bold-duotone.svg?color=%23a855f7" width="24" height="24" align="absmiddle" alt=""/> Instalación en Windows

Abre el `*-x64-setup.exe` y sigue el asistente. Si Windows SmartScreen avisa que la app no es conocida, haz clic en **Más información → Ejecutar de todos modos**.

### <img src="https://api.iconify.design/solar/laptop-bold-duotone.svg?color=%23a855f7" width="24" height="24" align="absmiddle" alt=""/> Instalación en macOS

Abre el `*.dmg`, arrastra **Proximity Chat** a **Aplicaciones** y lánzala. Al abrirlo la primera vez, **clic derecho → Abrir** (la app aún no tiene certificado de Apple).

<br/>

## <img src="https://api.iconify.design/solar/rocket-2-bold-duotone.svg?color=%238b5cf6" width="28" height="28" align="absmiddle" alt=""/> Primeros pasos

<table>
  <tr>
    <td align="center" width="25%"><h1>1</h1><b>Instala</b><br/>la app desde la release</td>
    <td align="center" width="25%"><h1>2</h1><b>Inicia sesión</b><br/>con tu cuenta de Discord</td>
    <td align="center" width="25%"><h1>3</h1><b>Verifica</b><br/>tu identidad de Roblox con RoVer</td>
    <td align="center" width="25%"><h1>4</h1><b>Juega</b><br/>y habla con los que tengas cerca</td>
  </tr>
</table>

<br/>

## <img src="https://api.iconify.design/solar/map-arrow-right-bold-duotone.svg?color=%238b5cf6" width="28" height="28" align="absmiddle" alt=""/> Roadmap

- [x] 🔊 Chat de voz por proximidad
- [x] 🎮 Overlay flotante
- [x] 🔑 Login con Discord + verificación RoVer
- [x] 🐧 Instalador para Linux (`.deb`)
- [x] 🪟 Instalador para Windows (`.exe`)
- [x] 🍎 Instalador para macOS (`.dmg`, Intel + Apple Silicon)
- [x] 🔄 Actualizaciones desde la app (aviso con un clic)

<br/>

## <img src="https://api.iconify.design/solar/history-bold-duotone.svg?color=%238b5cf6" width="28" height="28" align="absmiddle" alt=""/> Versiones

Todas las versiones publicadas, con sus notas de cambio, viven en la pestaña **[Releases](https://github.com/AchitoRD/proximity-chat-releases/releases)**.

---

<p align="center">
  <img src="https://api.iconify.design/solar/code-square-bold-duotone.svg?color=%238b5cf6" width="32" height="32" alt=""/><br/>
  <b>Hecho con 💜 por Hyperion Studio</b><br/>
  <sub>© Hyperion Studio — Todos los derechos reservados.</sub>
</p>
