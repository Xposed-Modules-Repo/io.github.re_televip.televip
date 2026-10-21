<div align="center">

<img src="https://raw.githubusercontent.com/2B-4G10/Re-TeleVIP/main/.github/assets/logo.svg" width="128" alt="Re: TeleVIP logo">

# Re: TeleVIP

**Privacy, ad blocking and quality-of-life features for Telegram and its forks,<br>as a Vector / Xposed module.**

[![Release](https://img.shields.io/github/v/release/2B-4G10/Re-TeleVIP?label=release&color=FFD500)](https://github.com/2B-4G10/Re-TeleVIP/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/2B-4G10/Re-TeleVIP/total?color=2AABEE)](https://github.com/2B-4G10/Re-TeleVIP/releases)
[![Client watch](https://img.shields.io/github/actions/workflow/status/2B-4G10/Re-TeleVIP/client-watch.yml?label=client%20watch)](https://github.com/2B-4G10/Re-TeleVIP/actions/workflows/client-watch.yml)
[![Xposed API](https://img.shields.io/badge/libxposed-API%20102-4A4D54)](#-getting-started)
[![License](https://img.shields.io/badge/license-GPL--3.0-F99B1C)](https://github.com/2B-4G10/Re-TeleVIP/blob/main/LICENSE)

<br>

[![Download the latest APK](https://img.shields.io/badge/Download-latest%20APK-2AABEE?style=for-the-badge&logo=android&logoColor=white)](https://github.com/2B-4G10/Re-TeleVIP/releases/latest)

[Changelog](https://github.com/2B-4G10/Re-TeleVIP/blob/main/CHANGELOG.md) · [Telegram group](https://t.me/Re_TeleVIP) · [Report a problem](https://github.com/2B-4G10/Re-TeleVIP/issues)

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
  <td align="center">Ghost Mode</td>
  <td align="center">Save protected stories</td>
  <td align="center">Show deleted messages</td>
</tr>
<tr>
  <td align="center">Hide story views</td>
  <td align="center">Save secret media</td>
  <td align="center">Save edit history</td>
</tr>
<tr>
  <td align="center">Hide phone number</td>
  <td align="center">Save voice messages</td>
  <td align="center">Remove saving limits</td>
</tr>
<tr>
  <td align="center">Block ads</td>
  <td align="center">Faster downloads</td>
  <td align="center">Hide pinned messages</td>
</tr>
<tr>
  <td align="center">Show user IDs</td>
  <td align="center">Local Premium</td>
  <td align="center">Hijri & Persian dates</td>
</tr>
</table>

<sub>…and more in <b>Re: TeleVIP Settings 🛸</b>, at the top of the client's own <b>Settings</b>.</sub>

<br>

## 🚀 Getting started

<table>
<tr>
  <th width="400">Requirements</th>
  <th width="400">Install</th>
</tr>
<tr>
  <td valign="top">

- **Vector 2.2+**<br><sub>Re: TeleVIP uses the new Xposed API (102). LSPosed 1.9.x and EdXposed only run older modules, and LSPosed doesn't start on Android 16.</sub>
- A root manager with Zygisk<br><sub>Magisk has it built in. With KernelSU, KernelSU Next, BakaSU or APatch, add NeoZygisk or Zygisk Next.</sub>
- No root? **[LSPatch 1.2](https://github.com/JingMatrix/LSPatch/releases/latest)** by JingMatrix<br><sub>Android 9 or newer. See <i>Without root</i> below.</sub>
- Android 8.1 or newer
- On Android 17: Magisk 31.0+ and a Vector canary (3112 or newer)<br><sub>Magisk 30.7 and Vector 2.2 stable don't load modules on Android 17.</sub>

  </td>
  <td valign="top">

1. Download `TeleVip-…-release.apk` from the [latest release](https://github.com/2B-4G10/Re-TeleVIP/releases/latest) and install it.
2. In Vector: **Modules** → enable **Re: TeleVIP** → tick your Telegram clients.
3. **Force stop** the client and open it again.

<sub>Updating from 1.0.x? The package name changed in 1.1.0: install the new version, uninstall the old <i>TeleVip</i> (<code>com.my.televip</code>), and enable <i>Re: TeleVIP</i> in Vector.</sub>

  </td>
</tr>
</table>

<details>
<summary><b>Without root (LSPatch)</b></summary>
<br>

<div align="left">

1. Install **Re: TeleVIP** and the **LSPatch** manager.
2. In LSPatch, tap **+**, pick your Telegram client and choose a patch mode:
   - **Local**: LSPatch serves the module. Updating Re: TeleVIP only needs a restart of the client.
   - **Integrated**: tick **Embed modules** → **Re: TeleVIP**. The patched app runs on its own, but every Re: TeleVIP update means patching again.
3. Patch, then install the result. In Local mode, also tick Re: TeleVIP on the client's page in LSPatch.

<sub>The patched client is signed by LSPatch, so Android has to uninstall the original one first. That deletes what the client keeps on the phone, Re: TeleVIP's settings and secret chats included: you'll sign in again and your cloud chats come back. Updates from the Play Store or the client's own updater won't install over it; patch each new version instead.</sub>

</div>

</details>

<br>

## 📱 Supported clients

### ✅ Checked every week

Every Monday, each feature's hook points are checked against the latest releases of these clients.<br>
A release that breaks something opens an issue.

<table>
<tr>
  <td align="center" valign="top" width="150"><img src="https://raw.githubusercontent.com/2B-4G10/Re-TeleVIP/main/.github/assets/clients/telegram.png" width="56" height="56" alt=""><br><b>Telegram</b><br><sub>telegram.org</sub></td>
  <td align="center" valign="top" width="150"><img src="https://raw.githubusercontent.com/2B-4G10/Re-TeleVIP/main/.github/assets/clients/nekogram.png" width="56" height="56" alt=""><br><b>Nekogram</b><br><sub>GitHub</sub></td>
  <td align="center" valign="top" width="150"><img src="https://raw.githubusercontent.com/2B-4G10/Re-TeleVIP/main/.github/assets/clients/cherrygram.png" width="56" height="56" alt=""><br><b>Cherrygram</b><br><sub>GitHub</sub></td>
  <td align="center" valign="top" width="150"><img src="https://raw.githubusercontent.com/2B-4G10/Re-TeleVIP/main/.github/assets/clients/nagram.png" width="56" height="56" alt=""><br><b>Nagram</b><br><sub>GitHub</sub></td>
  <td align="center" valign="top" width="150"><img src="https://raw.githubusercontent.com/2B-4G10/Re-TeleVIP/main/.github/assets/clients/nagramx.png" width="56" height="56" alt=""><br><b>Nagram X</b><br><sub>GitHub · full + base</sub></td>
</tr>
<tr>
  <td align="center" valign="top" width="150"><img src="https://raw.githubusercontent.com/2B-4G10/Re-TeleVIP/main/.github/assets/clients/forkgram.png" width="56" height="56" alt=""><br><b>Forkgram</b><br><sub>F-Droid</sub></td>
  <td align="center" valign="top" width="150"><img src="https://raw.githubusercontent.com/2B-4G10/Re-TeleVIP/main/.github/assets/clients/forkgram-classic.png" width="56" height="56" alt=""><br><b>Forkgram Classic</b><br><sub>F-Droid</sub></td>
  <td align="center" valign="top" width="150"><img src="https://raw.githubusercontent.com/2B-4G10/Re-TeleVIP/main/.github/assets/clients/mercurygram.png" width="56" height="56" alt=""><br><b>Mercurygram</b><br><sub>F-Droid</sub></td>
  <td align="center" valign="top" width="150"><img src="https://raw.githubusercontent.com/2B-4G10/Re-TeleVIP/main/.github/assets/clients/momogram.png" width="56" height="56" alt=""><br><b>Momogram</b><br><sub>GitHub</sub></td>
  <td align="center" valign="top" width="150"><img src="https://raw.githubusercontent.com/2B-4G10/Re-TeleVIP/main/.github/assets/clients/plus.png" width="56" height="56" alt=""><br><b>Plus Messenger</b><br><sub>APKPure</sub></td>
</tr>
<tr>
  <td align="center" valign="top" width="150"><img src="https://raw.githubusercontent.com/2B-4G10/Re-TeleVIP/main/.github/assets/clients/graph.png" width="56" height="56" alt=""><br><b>Graph Messenger</b><br><sub>APKPure</sub></td>
</tr>
</table>

<sub>Telegram: its newest build. The others: their last five releases.</sub>

<sub>App icons belong to their respective projects and are shown only to identify them.</sub>

<br>

## 🧪 Tested on

Every release is tried on Android emulators with each root manager and Vector, in every client above.<br>
Android 13 to 16 were checked for 1.2. 1.3's new features were tried on Android 14 with Nekogram 12.10.5 and on Android 17 with Telegram 13.1:

<table>
<tr>
  <th width="120">Android</th>
  <th width="420">Works with</th>
  <th width="260">Notes</th>
</tr>
<tr>
  <td align="center"><b>17</b></td>
  <td align="center">
    <img src="https://raw.githubusercontent.com/2B-4G10/Re-TeleVIP/main/.github/assets/root/magisk.png" width="36" height="36" alt="Magisk" title="Magisk">&nbsp;
    <img src="https://raw.githubusercontent.com/2B-4G10/Re-TeleVIP/main/.github/assets/root/kernelsu.png" width="36" height="36" alt="KernelSU" title="KernelSU">&nbsp;
    <img src="https://raw.githubusercontent.com/2B-4G10/Re-TeleVIP/main/.github/assets/root/kernelsu-next.png" width="36" height="36" alt="KernelSU Next" title="KernelSU Next">&nbsp;
    <img src="https://raw.githubusercontent.com/2B-4G10/Re-TeleVIP/main/.github/assets/root/bakasu.png" width="36" height="36" alt="BakaSU" title="BakaSU">&nbsp;
    <img src="https://raw.githubusercontent.com/2B-4G10/Re-TeleVIP/main/.github/assets/root/apatch.png" width="36" height="36" alt="APatch" title="APatch">
  </td>
  <td><sub>Works with Magisk 31.0+ and a current Vector build. 1.3 was tried here with Telegram 13.1; the other root managers are expected to work as on Android 16.</sub></td>
</tr>
<tr>
  <td align="center"><b>16</b></td>
  <td align="center">
    <img src="https://raw.githubusercontent.com/2B-4G10/Re-TeleVIP/main/.github/assets/root/magisk.png" width="36" height="36" alt="Magisk" title="Magisk">&nbsp;
    <img src="https://raw.githubusercontent.com/2B-4G10/Re-TeleVIP/main/.github/assets/root/kernelsu.png" width="36" height="36" alt="KernelSU" title="KernelSU">&nbsp;
    <img src="https://raw.githubusercontent.com/2B-4G10/Re-TeleVIP/main/.github/assets/root/kernelsu-next.png" width="36" height="36" alt="KernelSU Next" title="KernelSU Next">&nbsp;
    <img src="https://raw.githubusercontent.com/2B-4G10/Re-TeleVIP/main/.github/assets/root/bakasu.png" width="36" height="36" alt="BakaSU" title="BakaSU">&nbsp;
    <img src="https://raw.githubusercontent.com/2B-4G10/Re-TeleVIP/main/.github/assets/root/apatch.png" width="36" height="36" alt="APatch" title="APatch">
  </td>
  <td><sub>Magisk, KernelSU, KernelSU Next, BakaSU and APatch</sub></td>
</tr>
<tr>
  <td align="center"><b>15</b></td>
  <td align="center">
    <img src="https://raw.githubusercontent.com/2B-4G10/Re-TeleVIP/main/.github/assets/root/magisk.png" width="36" height="36" alt="Magisk" title="Magisk">&nbsp;
    <img src="https://raw.githubusercontent.com/2B-4G10/Re-TeleVIP/main/.github/assets/root/apatch.png" width="36" height="36" alt="APatch" title="APatch">
  </td>
  <td><sub>Magisk and APatch. KernelSU wasn't checked: it can't run on this emulator's kernel*</sub></td>
</tr>
<tr>
  <td align="center"><b>14</b></td>
  <td align="center">
    <img src="https://raw.githubusercontent.com/2B-4G10/Re-TeleVIP/main/.github/assets/root/magisk.png" width="36" height="36" alt="Magisk" title="Magisk">&nbsp;
    <img src="https://raw.githubusercontent.com/2B-4G10/Re-TeleVIP/main/.github/assets/root/apatch.png" width="36" height="36" alt="APatch" title="APatch">
  </td>
  <td><sub>Magisk and APatch. KernelSU wasn't checked: it can't run on this emulator's kernel*</sub></td>
</tr>
<tr>
  <td align="center"><b>13</b></td>
  <td align="center">
    <img src="https://raw.githubusercontent.com/2B-4G10/Re-TeleVIP/main/.github/assets/root/magisk.png" width="36" height="36" alt="Magisk" title="Magisk">
  </td>
  <td><sub>Magisk</sub></td>
</tr>
</table>

<sub>* The Android 14 and 15 emulators ship kernels that KernelSU, KernelSU Next and BakaSU can't load into. That is a limit of the emulator, not of these root managers or of Re: TeleVIP: on a phone whose kernel they support, they work as on Android 16.<br>
Logos belong to their respective projects and are shown only to identify them.</sub>

<br>

## ⚙️ How it keeps up

Telegram and its forks rename their code on every release, some almost all of it.<br>
Re: TeleVIP doesn't rely on a name table for one version. It works it out on your device.

<table>
<tr>
  <td align="center" width="260">📦<br><b>Reads the client's APK</b><br><sub>once per client update</sub></td>
  <td align="center" width="260">🔍<br><b>Finds each hook by behaviour</b><br><sub>what the code does, not its name</sub></td>
  <td align="center" width="260">🧭<br><b>Leaves out what it can't pin down</b><br><sub>rather than guessing</sub></td>
</tr>
</table>

Details are in the [changelog](https://github.com/2B-4G10/Re-TeleVIP/blob/main/CHANGELOG.md).

<br>

## 🙏 Credits

**[Mustafa (@mustafa1dev)](https://github.com/mustafa1dev)** is the original author of TeleVip
([mustafa1dev/TeleVip-LSPosed](https://github.com/mustafa1dev/TeleVip-LSPosed)), which Re: TeleVIP continues.<br>
Partly based on [Re-Telegram](https://github.com/Sakion-Team/Re-Telegram).

## 📄 License

[GPL-3.0](https://github.com/2B-4G10/Re-TeleVIP/blob/main/LICENSE). This project is for educational use.<br>
Modified clients can put a Telegram account at risk, so use it at your own risk.

</div>
