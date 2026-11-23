<div align="center">

<a href="https://re-televip.cc"><img src="https://raw.githubusercontent.com/Dream1Works/Re-TeleVIP/main/.github/assets/logo.svg" width="128" alt="Re: TeleVIP logo"></a>

# Re: TeleVIP

**Privacy, ad blocking and quality-of-life features for Telegram and its forks,<br>as a Vector / Xposed module.**

[![Release](https://img.shields.io/github/v/release/Dream1Works/Re-TeleVIP?label=release&color=FFD500)](https://github.com/Dream1Works/Re-TeleVIP/releases/latest)
[![Downloads](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2F2B-4G10%2FRe-TeleVIP%2Fbadges%2Fdownloads.json)](https://github.com/Dream1Works/Re-TeleVIP/releases)
[![Users](https://img.shields.io/endpoint?url=https%3A%2F%2Fre-televip.cc%2Fbadge%2Fusers)](https://re-televip.cc)
[![Website](https://img.shields.io/badge/website-re--televip.cc-8B5CF6)](https://re-televip.cc)
[![Xposed API](https://img.shields.io/badge/libxposed-API%20102-4A4D54)](#-getting-started)
[![License](https://img.shields.io/badge/license-All%20rights%20reserved-F99B1C)](https://github.com/Dream1Works/Re-TeleVIP/blob/main/LICENSE)
[![Patreon](https://img.shields.io/badge/Patreon-support-FF424D?logo=patreon&logoColor=white)](https://www.patreon.com/Dossary)

<br>

[![Download the latest APK](https://img.shields.io/badge/Download-latest%20APK-2AABEE?style=for-the-badge&logo=android&logoColor=white)](https://github.com/Dream1Works/Re-TeleVIP/releases/latest)
[![Visit the website](https://img.shields.io/badge/Website-re--televip.cc-8B5CF6?style=for-the-badge&logo=googlechrome&logoColor=white)](https://re-televip.cc)

[Changelog](https://github.com/Dream1Works/Re-TeleVIP/blob/main/CHANGELOG.md) · [Telegram channel](https://t.me/Revived_TeleVIP) · [Report a problem](https://github.com/Dream1Works/Re-TeleVIP/issues)

<br>

<a href="https://re-televip.cc"><img src="https://raw.githubusercontent.com/Dream1Works/Re-TeleVIP/main/.github/assets/website.jpg" width="820" alt="The Re: TeleVIP website, re-televip.cc"></a>

<sub>👆 <b><a href="https://re-televip.cc">re-televip.cc</a></b>: features, Premium, prices and install guide, in English, 中文 and العربية.</sub>

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
  <td align="center">Save self-destructing media ⭐</td>
  <td align="center">Save edit history</td>
</tr>
<tr>
  <td align="center">Phone number protection</td>
  <td align="center">Save voice messages</td>
  <td align="center">Unlock saving in restricted chats ⭐</td>
</tr>
<tr>
  <td align="center">Block ads</td>
  <td align="center">Faster downloads (Beta)</td>
  <td align="center">Hide pinned messages</td>
</tr>
<tr>
  <td align="center">Show user and message IDs</td>
  <td align="center">Liquid glass look</td>
  <td align="center">Hijri & Persian dates</td>
</tr>
<tr>
  <td align="center">Show read time</td>
  <td align="center">Disable stories</td>
  <td align="center">Message details ⭐</td>
</tr>
</table>

<sub>⭐ = Premium. Everything else is free. All settings sit in <b>Re: TeleVIP Settings 🛸</b> at the top of the client's own <b>Settings</b>, in 22 languages.</sub>

<br>

## 💎 Premium

An **optional** subscription for extras. Everything free stays free.

<table>
<tr><th>💎 Premium</th><th>💵 Price</th></tr>
<tr><td>

- ☁️ Encrypted cloud backup of deleted messages and edit history
- 📰 Live ad & scam list, plus your own ad keywords
- 🗂️ Unlimited storage for kept deleted messages (free: 50 MB)
- 🙈 Hide my number and exposure warnings
- 🔥 Save self-destructing media and from restricted chats
- ⭐ Local Telegram Premium, 🎨 my colours and emoji
- 🔎 Message details, 📅 creation date on profiles
- 💾 Settings export, 📏 album file sizes, 🌐 proxy button

</td><td>

📆 **$1.99** / month<br>
🗓️ **$19.99** / year<br>
🧾 **$19.99** one year, paid once

<sub>Card, PayPal, Apple Pay, Google Pay<br>and WeChat Pay via Paddle, or USDT (TRC20).</sub>

</td></tr>
</table>

Buy in **Re: TeleVIP → Premium** or on **[re-televip.cc](https://re-televip.cc/#pricing)**. One plan = one phone, with every Telegram app and account on it; move it any time with your code.<br>
Cancel any time · full refund within 14 days · works only in the official builds from our releases.

📄 [Terms](https://re-televip.cc/terms) · [Privacy](https://re-televip.cc/privacy) · [Refunds](https://re-televip.cc/refunds)

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

1. Download `TeleVip-…-release.apk` from the [latest release](https://github.com/Dream1Works/Re-TeleVIP/releases/latest) and install it.
2. In Vector: **Modules** → enable **Re: TeleVIP** → tick your Telegram clients.
3. **Force stop** the client and open it again.

<sub><b>Vector doesn't list Telegram from Google Play, or loads nothing into it?</b> Google Play can install it as a streamed ("incremental") install, which Vector does not load modules into. Use Telegram from <a href="https://telegram.org/android">telegram.org</a>, or install the same files again the normal way: copy the paths from <code>adb shell pm path org.telegram.messenger</code> to your computer with <code>adb pull</code>, then <code>adb install-multiple -r --no-incremental</code> them. Your chats and login stay. A later Play update can bring it back.</sub>

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

<br>

## 📱 Supported apps

The same list as in the app, live: each badge shows the newest version that passed our checks.<br>
Every app is checked against its new releases twice a week, and after every Re: TeleVIP release.

<table>
<tr>
  <td align="center" valign="top" width="150"><img src="https://raw.githubusercontent.com/Dream1Works/Re-TeleVIP/main/.github/assets/clients/telegram.png" width="56" height="56" alt=""><br><b>Telegram</b><br><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fre-televip.cc%2Fbadge%2Fapp%2Forg.telegram.messenger" alt="newest version checked"></td>
  <td align="center" valign="top" width="150"><img src="https://raw.githubusercontent.com/Dream1Works/Re-TeleVIP/main/.github/assets/clients/nekogram.png" width="56" height="56" alt=""><br><b>Nekogram</b><br><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fre-televip.cc%2Fbadge%2Fapp%2Ftw.nekomimi.nekogram" alt="newest version checked"></td>
  <td align="center" valign="top" width="150"><img src="https://raw.githubusercontent.com/Dream1Works/Re-TeleVIP/main/.github/assets/clients/cherrygram.png" width="56" height="56" alt=""><br><b>Cherrygram</b><br><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fre-televip.cc%2Fbadge%2Fapp%2Fuz.unnarsx.cherrygram" alt="newest version checked"></td>
  <td align="center" valign="top" width="150"><img src="https://raw.githubusercontent.com/Dream1Works/Re-TeleVIP/main/.github/assets/clients/nagram.png" width="56" height="56" alt=""><br><b>Nagram</b><br><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fre-televip.cc%2Fbadge%2Fapp%2Fxyz.nextalone.nagram" alt="newest version checked"></td>
</tr>
<tr>
  <td align="center" valign="top" width="150"><img src="https://raw.githubusercontent.com/Dream1Works/Re-TeleVIP/main/.github/assets/clients/nagramx.png" width="56" height="56" alt=""><br><b>Nagram X</b><br><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fre-televip.cc%2Fbadge%2Fapp%2Fnu.gpu.nagram" alt="newest version checked"></td>
  <td align="center" valign="top" width="150"><img src="https://raw.githubusercontent.com/Dream1Works/Re-TeleVIP/main/.github/assets/clients/forkgram.png" width="56" height="56" alt=""><br><b>Forkgram</b><br><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fre-televip.cc%2Fbadge%2Fapp%2Forg.forkgram.messenger" alt="newest version checked"></td>
  <td align="center" valign="top" width="150"><img src="https://raw.githubusercontent.com/Dream1Works/Re-TeleVIP/main/.github/assets/clients/forkgram-classic.png" width="56" height="56" alt=""><br><b>Forkgram Classic</b><br><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fre-televip.cc%2Fbadge%2Fapp%2Forg.forkgram.classic" alt="newest version checked"></td>
  <td align="center" valign="top" width="150"><img src="https://raw.githubusercontent.com/Dream1Works/Re-TeleVIP/main/.github/assets/clients/mercurygram.png" width="56" height="56" alt=""><br><b>Mercurygram</b><br><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fre-televip.cc%2Fbadge%2Fapp%2Fit.belloworld.mercurygram" alt="newest version checked"></td>
</tr>
<tr>
  <td align="center" valign="top" width="150"><img src="https://raw.githubusercontent.com/Dream1Works/Re-TeleVIP/main/.github/assets/clients/momogram.png" width="56" height="56" alt=""><br><b>Momogram</b><br><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fre-televip.cc%2Fbadge%2Fapp%2Fmomo.gram" alt="newest version checked"></td>
  <td align="center" valign="top" width="150"><img src="https://raw.githubusercontent.com/Dream1Works/Re-TeleVIP/main/.github/assets/clients/plus.png" width="56" height="56" alt=""><br><b>Plus Messenger</b><br><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fre-televip.cc%2Fbadge%2Fapp%2Forg.telegram.plus" alt="newest version checked"></td>
  <td align="center" valign="top" width="150"><img src="https://raw.githubusercontent.com/Dream1Works/Re-TeleVIP/main/.github/assets/clients/graph.png" width="56" height="56" alt=""><br><b>Graph Messenger</b><br><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fre-televip.cc%2Fbadge%2Fapp%2Fir.ilmili.telegraph" alt="newest version checked"></td>
  <td align="center" valign="top" width="150"><img src="https://raw.githubusercontent.com/Dream1Works/Re-TeleVIP/main/.github/assets/clients/entinygram.png" width="56" height="56" alt=""><br><b>EntinyGram</b><br><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fre-televip.cc%2Fbadge%2Fapp%2Fua.entaytion.entinygram" alt="newest version checked"></td>
</tr>
</table>

<sub>The full list: [COMPATIBILITY.md](https://github.com/Dream1Works/Re-TeleVIP/blob/main/COMPATIBILITY.md), also at the end of every release's notes. App icons belong to their respective projects and are shown only to identify them.</sub>

<br>

## 🔒 What it sends

Re: TeleVIP talks to the internet for these things only:

- **Update check.** Once a day it asks GitHub for the latest release (or reads the changelog through jsDelivr where GitHub is blocked). **Download** fetches the APK from GitHub, or from jsDelivr when GitHub doesn't answer, or opens the release's post in our Telegram channel. You can turn the daily check off under **Updates**.
- **Client compatibility list.** Once a week it downloads [compat.json](https://github.com/Dream1Works/Re-TeleVIP/blob/main/compat.json) from GitHub (or jsDelivr where GitHub is blocked): which client versions the weekly check found working. It sends nothing about you.
- **Premium (only if you subscribe).** Your Premium pass, a random phone ID and which official build is asking go to our server to turn Premium on and renew it, and for the Premium features that need the server. See the [privacy policy](https://re-televip.cc/privacy).
- **Active users count.** Once a day it sends one anonymous message so we know how many people use Re: TeleVIP. It holds a random ID made on your phone, the module version and the name of your Telegram app. It never sends your Telegram account, phone number, contacts or messages, and your IP address is not stored.

<br>

<br>

## 💛 Support

Re: TeleVIP is free (with optional [💎 Premium](#-premium)), and coded in squeezed-in time ☕<br>
Your support on Patreon makes up for it!

[![Support on Patreon](https://img.shields.io/badge/Support%20on-Patreon-FF424D?style=for-the-badge&logo=patreon&logoColor=white)](https://www.patreon.com/Dossary)

## 🙏 Credits

**[Mustafa (@mustafa1dev)](https://github.com/mustafa1dev)** is the original author of TeleVip
([mustafa1dev/TeleVip-LSPosed](https://github.com/mustafa1dev/TeleVip-LSPosed)), which Re: TeleVIP continues.<br>
Partly based on [Re-Telegram](https://github.com/Sakion-Team/Re-Telegram).<br>
Some feature ideas came from [Gramsieve](https://github.com/Xposed-Modules-Repo/com.tianqianguai.gramsieve) (Idea Inspiration).<br>
The kept deleted messages menu, the Hide seen read fix and My colours and emoji were inspired by ideas from [Telegami](https://github.com/aoya111/Telegami) by [aoya111](https://github.com/aoya111) (Idea Inspiration).<br>
Download Speed Boost follows the approach of [TeleSpeed](https://github.com/Xposed-Modules-Repo/io.github.tehcneko.telespeed) by [tehcneko](https://github.com/tehcneko).<br>
The settings' glass lens is adapted from [AndroidLiquidGlass](https://github.com/Kyant0/AndroidLiquidGlass) by [Kyant](https://github.com/Kyant0) (Apache License 2.0).<br>
The Telegram glass sliders and sharp wallpaper follow ideas from [TG-Liquid-Glass](https://github.com/YuanhaoBei/TG-Liquid-Glass) by [YuanhaoBei](https://github.com/YuanhaoBei) (Apache License 2.0).

## 📄 License

© 2026 Faisal AlDossary. All rights reserved: see [LICENSE](https://github.com/Dream1Works/Re-TeleVIP/blob/main/LICENSE) and [NOTICE](https://github.com/Dream1Works/Re-TeleVIP/blob/main/NOTICE.md). From 1.5.4 the source code is not published, and copying, modifying or re-uploading the app needs permission. Versions up to 1.5.3 stay under GPL-3.0.<br>
The name **Re: TeleVIP** and its logo belong to Faisal AlDossary. Nobody may use them for another app.<br>
This project is for educational use.<br>
Modified clients can put a Telegram account at risk, so use it at your own risk.

<br>

---

Made in Saudi 🇸🇦 By: i_2B_4G10🚀

</div>
