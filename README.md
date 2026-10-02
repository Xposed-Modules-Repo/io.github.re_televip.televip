<div align="center">

<img src=".github/assets/logo.svg" width="128" alt="TeleVip logo">

# Re: TeleVIP

**Privacy, ad blocking and quality-of-life features for Telegram and its forks,<br>as a Vector / Xposed module.**

[![Release](https://img.shields.io/github/v/release/2B-4G10/Re-TeleVIP?label=release&color=FFD500)](../../releases/latest)
[![Downloads](https://img.shields.io/github/downloads/2B-4G10/Re-TeleVIP/total?color=2AABEE)](../../releases)
[![Client watch](https://img.shields.io/github/actions/workflow/status/2B-4G10/Re-TeleVIP/client-watch.yml?label=client%20watch)](../../actions/workflows/client-watch.yml)
[![Xposed API](https://img.shields.io/badge/libxposed-API%20102-4A4D54)](#-getting-started)
[![License](https://img.shields.io/badge/license-GPL--3.0-F99B1C)](LICENSE)

<br>

[![Download the latest APK](https://img.shields.io/badge/Download-latest%20APK-2AABEE?style=for-the-badge&logo=android&logoColor=white)](../../releases/latest)

[Changelog](CHANGELOG.md) · [Telegram channel](https://t.me/t_l0_e) · [Report a problem](../../issues)

</div>

<br>

<div align="center">

## ✨ Features

<table>
<tr>
  <th width="300">🛡️ Privacy</th>
  <th width="300">🎞️ Media & stories</th>
  <th width="300">💬 Chats</th>
</tr>
<tr>
  <td align="center">Ghost Mode: no <i>seen</i>, <i>typing</i> or <i>online</i></td>
  <td align="center">Save protected stories</td>
  <td align="center">Remove content-saving restrictions</td>
</tr>
<tr>
  <td align="center">Hide phone number</td>
  <td align="center">Save voice messages</td>
  <td align="center">Save message edit history</td>
</tr>
<tr>
  <td align="center">Hide story views</td>
  <td align="center">Save secret media</td>
  <td align="center">Hide pinned messages</td>
</tr>
<tr>
  <td align="center">Show deleted messages</td>
  <td align="center">Always allow saving media</td>
  <td align="center">Disable stories</td>
</tr>
<tr>
  <td align="center">Keep secret media from self-destructing</td>
  <td align="center">Faster downloads</td>
  <td align="center">Disable channel / profile swipe-back</td>
</tr>
<tr>
  <td align="center">Show user IDs on profiles</td>
  <td align="center">Local Premium</td>
  <td align="center">Jump to first / any message</td>
</tr>
<tr>
  <td align="center">Block ads: sponsored posts, video and search ads, proxy sponsor</td>
  <td align="center">Hijri and Persian dates</td>
  <td align="center">Hide app update prompts</td>
</tr>
</table>

<sub>…and more in TeleVip's settings, which live inside the client's own <b>Settings</b>.</sub>

<br>

## 🚀 Getting started

<table>
<tr>
  <th width="400">Requirements</th>
  <th width="400">Install</th>
</tr>
<tr>
  <td valign="top">

- **LSPosed 1.10+** or **Vector 2.2+**<br><sub>libxposed API 102. LSPosed 1.9.x, EdXposed and LSPatch are not supported.</sub>
- Any Zygisk provider<br><sub>Magisk, KernelSU, Zygisk Next or NeoZygisk</sub>
- Android 8.1 or newer

  </td>
  <td valign="top">

1. Download `TeleVip-…-release.apk` from the [latest release](../../releases/latest) and install it.
2. In LSPosed / Vector: **Modules** → enable **TeleVip** → tick your Telegram clients.
3. **Force stop** the client and open it again.

<sub>Updating from 1.0.x? The package name changed in 1.1.0: install the new version, uninstall the old <i>TeleVip</i>, and enable it again in LSPosed.</sub>

  </td>
</tr>
</table>

<br>

## 📱 Supported clients

### ✅ Checked every week

Every Monday, each feature's hook points are checked against the latest releases of these clients.<br>
A release that breaks something opens an issue.

<table>
<tr>
  <td align="center" width="140"><img src=".github/assets/clients/telegram.png" width="56" height="56" alt=""><br><b>Telegram</b><br><sub>telegram.org · newest</sub></td>
  <td align="center" width="140"><img src=".github/assets/clients/nekogram.png" width="56" height="56" alt=""><br><b>Nekogram</b><br><sub>GitHub · last 5</sub></td>
  <td align="center" width="140"><img src=".github/assets/clients/cherrygram.png" width="56" height="56" alt=""><br><b>Cherrygram</b><br><sub>GitHub · last 5</sub></td>
  <td align="center" width="140"><img src=".github/assets/clients/nagram.png" width="56" height="56" alt=""><br><b>Nagram</b><br><sub>GitHub · last 5</sub></td>
</tr>
<tr>
  <td align="center" width="140"><img src=".github/assets/clients/nagramx.png" width="56" height="56" alt=""><br><b>NagramX</b><br><sub>GitHub · last 5</sub></td>
  <td align="center" width="140"><img src=".github/assets/clients/forkgram.png" width="56" height="56" alt=""><br><b>Forkgram</b><br><sub>F-Droid · last 5</sub></td>
  <td align="center" width="140"><img src=".github/assets/clients/forkgram-classic.png" width="56" height="56" alt=""><br><b>Forkgram Classic</b><br><sub>F-Droid · last 5</sub></td>
  <td align="center" width="140"><img src=".github/assets/clients/mercurygram.png" width="56" height="56" alt=""><br><b>Mercurygram</b><br><sub>F-Droid · last 5</sub></td>
</tr>
</table>

### ☑️ Supported, not checked automatically

The same Telegram code base, published where the weekly check can't download it.<br>
To check one, run the *Client watch* workflow by hand with a link to its APK.

<sub><b>ON THE PLAY STORE</b></sub>

<table>
<tr>
  <td align="center" width="140"><img src=".github/assets/clients/telegram.png" width="56" height="56" alt=""><br><b>Telegram</b><br><sub>Play Store & Beta</sub></td>
  <td align="center" width="140"><img src=".github/assets/clients/plus.png" width="56" height="56" alt=""><br><b>Plus Messenger</b><br><sub>Play Store</sub></td>
  <td align="center" width="140"><img src=".github/assets/clients/nicegram.png" width="56" height="56" alt=""><br><b>Nicegram</b><br><sub>Play Store</sub></td>
  <td align="center" width="140"><img src=".github/assets/clients/ime.png" width="56" height="56" alt=""><br><b>iMe</b><br><sub>Play Store</sub></td>
</tr>
<tr>
  <td align="center" width="140"><img src=".github/assets/clients/xplus.png" width="56" height="56" alt=""><br><b>X Plus</b><br><sub>Play Store</sub></td>
  <td align="center" width="140"><img src=".github/assets/clients/turrit.png" width="56" height="56" alt=""><br><b>Turrit</b><br><sub>Play Store</sub></td>
  <td align="center" width="140"><img src=".github/assets/clients/telegraph.png" width="56" height="56" alt=""><br><b>Telegraph</b><br><sub>Play Store</sub></td>
  <td align="center" width="140"><img src=".github/assets/clients/tgconnect.png" width="56" height="56" alt=""><br><b>TG Connect</b><br><sub>Play Store</sub></td>
</tr>
</table>

<sub><b>ELSEWHERE</b></sub>

<table>
<tr>
  <td align="center" width="140"><img src=".github/assets/clients/telega.png" width="56" height="56" alt=""><br><b>Telega</b><br><sub>RuStore</sub></td>
  <td align="center" width="140"><img src=".github/assets/clients/momogram.png" width="56" height="56" alt=""><br><b>Momogram</b><br><sub>community fork</sub></td>
  <td align="center" width="140"><img src=".github/assets/clients/nagramx.png" width="56" height="56" alt=""><br><b>Nagram XF</b><br><sub>NagramX variant</sub></td>
  <td align="center" width="140"><img src=".github/assets/clients/forkgram.png" width="56" height="56" alt=""><br><b>ForkClient</b><br><sub>Forkgram beta</sub></td>
  <td align="center" width="140"><img src=".github/assets/clients/nekox.png" width="56" height="56" alt=""><br><b>Nekogram X</b><br><sub>discontinued</sub></td>
</tr>
</table>

### 🟡 Partly works

<table>
<tr>
  <td align="center" width="140"><img src=".github/assets/clients/telegram-foss.png" width="56" height="56" alt=""><br><b>Telegram FOSS</b><br><sub>F-Droid · 10.14.3 (2024)</sub></td>
  <td width="420">Its last release predates the Telegram code behind <i>Block ads</i>, <i>Save edits history</i>, Ghost Mode's paid reactions and a photo-viewer button. Everything else works.</td>
</tr>
</table>

### ⛔ Not supported

TeleVip hooks the Android builds of Telegram's own app. These are separate apps, or not Android.

<sub><b>OTHER TELEGRAM APPS</b></sub>

<table>
<tr>
  <td align="center" width="140"><img src=".github/assets/clients/telegram-x.png" width="56" height="56" alt=""><br><b>Telegram X</b><br><sub>Android · TDLib</sub></td>
  <td align="center" width="140"><img src=".github/assets/clients/telegram-ios.png" width="56" height="56" alt=""><br><b>Telegram</b><br><sub>iPhone & iPad</sub></td>
  <td align="center" width="140"><img src=".github/assets/clients/tdesktop.png" width="56" height="56" alt=""><br><b>Telegram Desktop</b><br><sub>Windows · macOS · Linux</sub></td>
  <td align="center" width="140"><img src=".github/assets/clients/unigram.png" width="56" height="56" alt=""><br><b>Unigram</b><br><sub>Windows</sub></td>
</tr>
</table>

<sub><b>TELEGRAM DESKTOP FORKS</b></sub>

<table>
<tr>
  <td align="center" width="140"><img src=".github/assets/clients/ayugram.png" width="56" height="56" alt=""><br><b>AyuGram</b><br><sub>desktop</sub></td>
  <td align="center" width="140"><img src=".github/assets/clients/64gram.png" width="56" height="56" alt=""><br><b>64Gram</b><br><sub>desktop</sub></td>
  <td align="center" width="140"><img src=".github/assets/clients/kotatogram.png" width="56" height="56" alt=""><br><b>Kotatogram</b><br><sub>desktop</sub></td>
</tr>
</table>

<sub>App icons belong to their respective projects and are shown only to identify them.</sub>

<br>

## ⚙️ How it keeps up

Telegram and its forks rename their code on every release, some almost all of it.<br>
TeleVip doesn't rely on a name table for one version. It works it out on your device.

<table>
<tr>
  <td align="center" width="260">📦<br><b>Reads the client's APK</b><br><sub>once per client update</sub></td>
  <td align="center" width="260">🔍<br><b>Finds each hook by behaviour</b><br><sub>what the code does, not its name</sub></td>
  <td align="center" width="260">🧭<br><b>Leaves out what it can't pin down</b><br><sub>rather than guessing</sub></td>
</tr>
</table>

Details are in the [changelog](CHANGELOG.md).

<br>

## 🙏 Credits

**[Mustafa (@mustafa1dev)](https://github.com/mustafa1dev)** is the original author of TeleVip
([mustafa1dev/TeleVip-LSPosed](https://github.com/mustafa1dev/TeleVip-LSPosed)).<br>
Partly based on [Re-Telegram](https://github.com/Sakion-Team/Re-Telegram).

## 📄 License

[GPL-3.0](LICENSE). This project is for educational use.<br>
Modified clients can put a Telegram account at risk, so use it at your own risk.

</div>
