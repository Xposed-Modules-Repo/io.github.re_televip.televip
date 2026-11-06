# Changelog

## 1.5.81 (7 November 2026) — 22 languages, five settings tabs and fixes

**New**

- **Eight more languages: Japanese, Korean, Thai, Vietnamese, Malay, Tamil, Urdu and Ukrainian.** Re: TeleVIP's settings and menus now come in 22 languages. Urdu reads right to left, like Arabic and Persian. Dates in Japanese, Korean and Chinese are written the way those languages write them (3月12日).

**Changed**

- **Clearer texts in every language.** The explanations under the switches were checked in all languages so each one says what the feature really does. For example, "Hide update prompts" now says it hides the reminders to update, not the updates themselves, and the account's age on a profile is called "Account age".
- **Settings: five tabs instead of seven.** All, Privacy, Chats (with media and stories), Appearance and Tools (with About). The "Made in Saudi" line now closes every tab.
- **Settings: a calmer glass header.** The theme and search buttons share one glass pill and the back button sits in a glass circle, as in Telegram's own settings. The search field matches them. The frosted header now fades into the list instead of ending at a hard line.

**Fixed**

- **Edits history in Graph Messenger.** Its message menu takes one more argument, so the Edits history entry never got added there.
- **The photo viewer's save button stays on Telegram 11.x**, which switches photos through an older, shorter method.
- **Ad blocking on iMe 11.2** finds the older sponsored-messages request again.
- **Screenshots in private chats with Disable Sharing are unlocked on Nekogram too**, which renames the parts of Telegram that check it.
- **Screenshots of protected media from bots.** Bots that protect their content (and protected forwards) mark each message, and the photo viewer blocked screenshots for those whatever the chat. With Remove content-saving restrictions on, the viewer opens them without the block.
- **Update check where GitHub is blocked.** When GitHub can't be reached (China), the check reads the latest release from the public changelog through jsDelivr, and Download opens the Re: TeleVIP channel in Telegram.
- **Fewer false alarms in the anonymous hook report.** Methods a build simply doesn't have are now counted as "not in this build", not as broken hooks: the app updater check on Google Play builds (Play updates them), the status-line width on Telegram before 12.10, and the request-type check on Telegram before 11.6.
- **Version numbers are now x.x.xx.** The last part always has two digits, so 1.5.8 counts as 1.5.80: 1.5.81 comes after it, and a later 1.5.9 (1.5.90) is still offered as an update. The weekly automatic release counts the same way.

## 1.5.8 (6 November 2026) — new settings look, 14 languages and more fixes

**New**

- **New look for Re: TeleVIP Settings.** Liquid glass or Material You (it takes its colours from your wallpaper), in light, dark, the system's theme or Telegram's own. The settings are sorted into 7 tabs, with About last, and a search finds any switch.
- **Liquid glass switch** under Appearance. It turns on Telegram's own liquid glass look, on Android 13 and newer. Off by default, it needs a restart, and Telegram hides it on low-end phones.
- **EntinyGram.** Re: TeleVIP now supports EntinyGram (ua.entaytion.entinygram), and the weekly check covers its releases.
- **Spanish, Hindi, French, Bengali, German and Italian.** Re: TeleVIP's settings and menus now come in 14 languages. The language picker lists them under their continent: Asia, Europe and the Americas.

**Fixed**

- **Mentions no longer come back after a restart with Hide "Seen" on.** A mention you scrolled past in a group was only cleared on your phone, so the @ came back the next time the app started. It's now cleared on Telegram's side too. Nobody is told you read anything else.
- **A deleted pinned message is unpinned right away** with Show deleted messages on. The message is still kept, marked deleted, but the pinned bar moves on instead of showing it until the cache was cleared.
- **Edits history for your own messages.** Edit a message you sent and **Edits history** in its menu now shows what it said before. Until now only other people's edits were kept.
- **"Approximate creation date" works without restarting Telegram.** In builds where the chat and the profile share one menu listener, whichever screen you opened first kept the menu clicks, so the profile's entry did nothing until a restart.
- **Topics open where you stopped reading with Hide "Seen" on.** Telegram never heard about your reads, so each time the app reloaded a group's topics it went back to the old position and opened the topic at its first message. Your read position is now kept on your phone and given back to the topics as they load.
- **Read time on Telegram 13.2** shows as soon as the other side reads your message again, instead of the next time the message is drawn.
- **No grey box around the status line on Telegram 13.2** when the user ID is shown. Tapping the ID still copies it.
- **Disable stories now says it also stops you posting stories.** With it on, Telegram tells you posting is for Premium only, which sent people looking for a Premium problem.
- **Screenshots in private chats with Disable Sharing.** Since Telegram 12.5 either side of a private chat can turn on Disable Sharing, and screenshots, copying, saving and forwarding stayed blocked there even with Remove content-saving restrictions on. That chat is now unlocked like protected channels and groups.
- **Forwarding from restricted chats into a forum topic** sends the copy to the topic you picked, not to General.
- **Albums forwarded from restricted chats stay one album** instead of arriving as separate photos and videos.

**Changed**

- **The anonymous daily active-users ping** now also sends the Telegram app's version, the Android version, the Xposed framework's name, the language Re: TeleVIP shows its texts in, which of the module's hooks did not attach, and which Re: TeleVIP switches are on. Still no Telegram account, phone number, contacts or messages, and the server still keeps no IP.

Checked on Telegram 13.2.0, Nekogram 13.1.1, Cherrygram 11.4.0, Nagram 1255, NagramX 1260, Momogram 13.1.1, Forkgram Classic 13.0.2.0 and EntinyGram 13.1.1.

## 1.5.7 (5 November 2026) — works with Telegram 13.2

**Fixed**

- **Telegram 13.2.0.** The new official Telegram rearranged a lot of its insides, and most of Re: TeleVIP stopped working on it. Everything works again: the Re: TeleVIP row in Settings, Show user ID and Hide online on profiles, Approximate creation date in the profile menu, Hide update, read time and Show deleted messages. It's safe to update Telegram now.
- **Show user ID and Hide online on Telegram 13.2's new profile page.** The ID stays under the status as you scroll, and a tap still copies it.
- **Hide update** now also stops Telegram's own "update available" pop-up on 13.2.
- **Read time no longer fills the log with errors** on builds that rename Telegram's internals.

Checked on Telegram 13.2.0 and 13.1.1, Nekogram 13.1.1, Cherrygram 11.4.0, Nagram 1255, NagramX 1260, Momogram 13.1.1 and Forkgram Classic 13.0.2.0.

## 1.5.6 (3 November 2026) — Turkish, tidy polls, and a fix for "Can't downgrade database"

**New**

- **Türkçe.** Re: TeleVIP now speaks Turkish. Pick it under **Language**, or it follows your app when the app is in Turkish.

**Fixed**

- **The Re: TeleVIP row in Forkgram Classic's side menu opens the settings when you tap it** (Forkgram Classic 12.10.7 and newer, 13.0.2 included). Tapping it did nothing. If the side menu can't be closed for some reason, the settings still open.
- **"Can't downgrade database" error.** If an older TeleVip (Re: TeleVIP 1.1 or earlier, or the original TeleVip) was still active next to Re: TeleVIP, or built into an LSPatch-patched app, it could fail or crash on Re: TeleVIP's saved edits. Your edit histories now live in their own file, so the two no longer clash. Nothing is lost.
- **Clear saved data now clears kept deleted messages too.** Messages Show deleted messages kept in your chats are removed from this phone, on every account, and vanish from the open chat at once. Export them first if you want a copy.
- **Auto-delete timers.** In groups that delete messages after a set time, like 24 hours, Show deleted messages could lose them when the group reloaded right after you opened the app. They now stay, marked deleted, like any other deleted message.
- **Polls in channels and their discussion groups.** The views and the author's name under a timed poll were drawn over "ends in …". Re: TeleVIP now measures the poll's footer and its time line as the app laid them out, and moves the time to its own line only when they would touch, with your Re: TeleVIP settings off too.
- **Long author names.** With seconds, the message ID or the read time on, a long author name under a channel post pushed the time line out of the bubble, and under polls even without them. The name is now shortened with "…" so the line fits, as the app does on its own.
- **Music on Nekogram.** The file size Nekogram shows after the duration ran into the views and the author's name. The time now moves below it when they would touch. Other messages (text, photos, files, locations) already make room for a long time line.

## 1.5.5 (2 November 2026) — weekly update

- Build: AGP 9.4.1 → 9.5.0

## 1.5.4 (2 November 2026) — Portuguese, group switches that work, and seconds on Nekogram

**New**

- **Português (Brasil).** Re: TeleVIP now speaks Brazilian Portuguese. Pick it under **Language**, or it follows your app when the app is in Portuguese.

**Fixed**

- **Group switches.** The switch on a group like **Show User ID** or **Hide "Seen" status** now turns all its options off, or all on. Tap the name to open the group as before.
- **Show seconds on Nekogram** and other clients with scrambled names. Seconds now show for everyone who updated from 1.5.2.

**Changed**

- **Licence.** From this version Re: TeleVIP is © Faisal AlDossary, all rights reserved, and the source code is no longer attached to releases. Earlier versions keep their GPL-3.0 licence.
- Large parts of the module were rewritten and tidied up. Everything works as before.

## 1.5.3 (1 November 2026) — deleted messages that stay, a backup for them, and seconds on every message

Thank you for the reports in the group.

**New**

- **Export and import deleted messages.** Two new rows under **Clear saved data**. **Export deleted messages** saves every message Show deleted messages kept, on all your accounts, to one file you choose. **Import deleted messages** puts them back, after a reinstall or on a new phone, into the account they came from. Choose **Merge** to keep what's already here, or **Overwrite** to let the file's messages replace the same ones here. Nothing else is deleted. Restart the app afterwards to see them.
- **Show seconds.** A new switch under **Messages**: every message's time shows its seconds, like 12:41:07.
- **Hide Language Suggestion.** On by default. The "Choose your language" pop-up no longer comes back each time you switch accounts.
- **Say where a copy came from.** A new switch next to **Remove content-saving restrictions**, on by default. A message copied out of a chat that restricts forwarding ends with "Forwarded from" and the chat's name. Turn it off to send just the message.

**Fixed**

- **Deleted messages are kept for good.** They were lost when you came back to a busy group after a while (the app reloads such a group from scratch), when a chat had an auto-delete timer, and when the app's cache or local database was cleared. Messages already lost before this update can't be brought back. Deleting or clearing a chat yourself still removes them.
- **Download Speed Boost works on every account**, not only on accounts with Telegram Premium. Thanks to TeleSpeed for the approach.
- **Turrit translates quickly again with Local Premium on.**
- **The Downloads button only moves while something downloads.** With **Always show Downloads** on, it now shows the full download sign, still, when nothing is downloading.
- **Hidden stories stay hidden after the app restarts.** With **Disable stories** on, stories could come back in the top bar, where they couldn't be opened.
- **Polls stay readable** with the deleted mark, message ID, read time or seconds on: the time moves to its own line instead of covering the votes.

**Good to know**

- **Re: TeleVIP now counts its active users.** Once a day it sends one anonymous message: a random ID made on your phone, the module version and the name of your Telegram app. Never your account, number, contacts or messages, and no IP address is kept. It only tells us how many people use Re: TeleVIP. Details are in the README under **What it sends**.

## 1.5.2 (30 October 2026) — Downloads always at hand, user ID your way, and Bahasa Indonesia

**New**

- **Always show Downloads.** A new switch under **UI**. The Downloads button stays at the top of the chat list, even when nothing is downloading, so your files are one tap away. It still steps aside while you search. Restart the app after turning it on.
- **Show user ID, your way.** **Show user ID** now has two options: **On my profile** and **On other profiles**. Turn on just the one you want. Whatever you had before carries over to both.
- **Bahasa Indonesia.** Re: TeleVIP now speaks Indonesian. Pick it under **Language**, or it follows your app when the app is in Indonesian.

## 1.5.1 (30 October 2026) — fixes from your reports

Thank you for the reports in the group.

**Fixed**

- **Forwarding from chats that restrict saving content works.** With **Remove content-saving restrictions** on, these messages said "forwarded" but then failed with a red mark. They're now sent as your own copy: text and captions as new messages, and photos and files uploaded again from what's already on your phone. If a photo or file isn't downloaded yet, download it first.
- **Turrit stops asking "Open Re: TeleVIP settings now?"** at every start and account switch once the Re: TeleVIP row is in its settings or side menu. The prompt also has a **Don't show again** button.
- **Your own profile stays centred** on Telegram 13's new profile page with **Hide online** or **Show user ID** on, when it opens and after you scroll. **Show user ID** now shows your own ID there too.
- **The Re: TeleVIP row in Forkgram Classic's side menu opens the settings again** (Forkgram Classic 13.0.2). Tapping it did nothing.

## 1.5 (28 October 2026) — read times, stories off for real, and group edits that stick

**New**

- **Show read time.** A new switch under **Messages**. In private chats, each of your messages that was read shows when, like "Read 12:41", with the day if it was read on another day. Checking this never marks anything as read, so Ghost Mode keeps working. Telegram only tells for the last 7 days, and not when either of you hides read times; those messages keep their usual ticks.
- **Support goes straight to Patreon's membership page**, where you can pick a tier: Buy me a Coffee? ($5), Big Fan! ($10) or Super Fan!! ($25).
- **Made in Saudi 🇸🇦 By: i_2B_4G10🚀** now sits at the bottom of the settings.

**Fixed**

- **Disable stories hides the stories row again on Telegram 13.1.** The row at the top of the chat list stayed visible on that version.
- **Edits history works in groups**, including edits made while the group wasn't open or your phone was offline. If a message is edited several times while you're offline, Telegram only delivers the final text, so the versions in between can't be kept.
- **Arabic and Persian dialogs read right to left.** The buttons in **Clear saved data** and other dialogs are now in the right order when Re: TeleVIP is in Arabic or Persian.

## 1.4 (25 October 2026) — a big clean-up: fixes from your reports, privacy, five languages and a new look

Thank you to everyone who reported bugs in the group. Every report was tried on real clients with two accounts, and these are the fixes.

**Fixed**

- **Ghost Mode works again after a restart.** With Hide seen as the only Ghost Mode option on, nothing was hidden after the app restarted, and switching it on did nothing until the next restart.
- **No more "post was removed" on Nekogram.** With Hide seen on, Nekogram 13 couldn't open linked posts. Read receipts stay hidden.
- **Mentions clear once you've seen them.** With Hide seen on, the "@" mark came back every time you opened the chat.
- **Downloads are no longer slowed down.** With Local Premium or Faster downloads on, accounts without real Telegram Premium downloaded slower, because Telegram limits accounts that ask for more connections than they're allowed. Downloads now run at your account's full speed.
- **Secret chats get Save and Delete for both** in the media viewer too. And **Mark as seen** now really tells the sender, even with Hide seen on.
- **Save works with Prevent media off.** The media then expires as it was sent, and you can still keep a copy. The message after saving says which folder it went to.
- **Edits history keeps channel posts' edits** too, not only people's.
- **Show user ID shows the whole ID** on Telegram 13.1, where it was cut off.
- **The calendar is out of beta.** Hijri and Persian dates were checked in light and dark mode.
- **Forum topics: the reactions mark clears** once you've seen the message that was reacted to.
- **Removed a hidden leftover from the original fork:** long-pressing a settings row started an internet radio stream and showed a dialog about it.

**Privacy**

- Ghost Mode now tells you if an option can't work on your client, instead of failing silently.
- **Clear saved data** deletes the saved edit histories and the list of kept secret media in one tap.
- Edit histories are kept per account and chat. Older saved histories are cleared once by this update.

**New**

- **Five languages:** English, فارسی, Русский, العربية and 简体中文. Re: TeleVIP follows your client's language, or pick one under **Language**.
- **Update check:** **Check for updates** in settings, and a daily check you can turn off. It only asks GitHub for the latest release.
- **A new look** for the settings, and a **Support Re: TeleVIP** card if you'd like to help on Patreon.
- **New Telegram channel:** [t.me/Revived_TeleVIP](https://t.me/Revived_TeleVIP). Ask for help in its comments.

## 1.3 (21 October 2026) — Graph Messenger, save secret media, and chats that load with Ghost Mode

- **You decide when the sender sees your secret media as opened.** With Prevent media on,
  opening a self-destructing photo or video tells the sender nothing. Tap **Mark as seen** in
  the viewer when you want them to see it as opened; their copy then expires as usual, and you
  keep yours.
- **Save secret media from the viewer.** A **Save** button puts the photo or video in your
  gallery, next to **Mark as seen** and **Delete for both**.
- **Graph Messenger is supported.** Re: TeleVIP shows up in its settings and its features work
  on Graph's current versions (12.10 and 13.0), which are checked every week like the other
  clients.
- **Hide seen works smoothly on Nekogram 12.10.5.** Reading a chat with Ghost Mode on could
  run into an error there, which got in the way of chats loading. Chats now open normally, and
  the sender still doesn't see that you read them.
- **Save edits history works on Nekogram and Cherrygram.** On these clients it couldn't tell
  which chat an edited message belonged to, so earlier versions weren't kept. The secret media
  viewer had the same trouble there and now finds the right chat too.
- **Re: TeleVIP settings open every time.** After leaving the app with Back and opening it
  again, tapping the settings did nothing until the app was force stopped.

## 1.2.2 (21 October 2026) — Nekogram 12.10.5, fair secret media, and smoother settings

- **Prevent media and Save secret media work on Nekogram 12.10.5.** Nekogram renamed part of
  the chat in that version, so tapping a photo no longer reached Re: TeleVIP. Newer Nekogram
  versions keep working as before.
- **The sender sees your secret photos and videos as opened.** With Prevent media on, you
  still keep your copy, but the sender's copy now expires as usual.
- **"Delete for both" in the secret media viewer.** After you confirm, the photo or video is
  deleted for you and the sender, as the timer would have done.
- **No more photos downloading over and over** in groups while Save secret media is on.
- **Night mode and theme colours work right after closing Re: TeleVIP settings.** Until now
  they did nothing until you restarted the app.
- **Dialogs follow light and dark mode.** No more white text on a white background in the
  calendar and other Re: TeleVIP dialogs.
- **Show deleted messages and Voice messages as music turn off right away**, without a
  restart. Save edits history and Show deleted messages are also gentler on the chat database.

## 1.2.1 (20 October 2026) — no false "incompatible version" warning on Nekogram

- **Fixed: Nekogram showed "Your Telegram client may be an incompatible version"** in the log
  with Prevent media on, after 1.2. Nothing was broken, and the warning is gone.

## 1.2 (20 October 2026) — Ghost Mode fixed, tested on more phones, and no root needed

- **Ghost Mode works again with Block ads on.** With both switched on, Ghost Mode quietly did
  nothing: chats were marked as read and others could see you typing and online. Now your
  "seen", typing and online status stay hidden.
- **Self-destructing photos stay.** On Telegram 13.1, a timed photo still expired after you
  opened it. It now stays, as "Prevent media" promises.
- **Works without root through LSPatch 1.2.** Patch your Telegram client with JingMatrix's
  LSPatch, in Local or Integrated mode, and add Re: TeleVIP to it. The README has the steps.
- **Plus Messenger is supported**, and checked every week like the other clients.
- **Telegram 13.1 and 13.0.3 (Play Store) are supported.** The error about the secret media
  viewer is gone.
- **Save edits history works in Nagram 1253 and Momogram 13**, where it found nothing to hook.
- **Forkgram Classic 13 shows the Re: TeleVIP entry in its side menu again.**
- **No more crash from the edits-history storage** ("Can't downgrade database from version 2
  to 1") after switching from another TeleVip build. Your saved edits are kept.
- **Hide phone number shows "Number hidden"** instead of "+null" in Settings.
- **Hide app update also hides the update pop-up** that Nekogram shows when you open the app.
- **Long setting titles wrap neatly** and no longer cover the line under them, in every
  language.
- **Checked on Android 13 to 16** with Magisk, KernelSU, KernelSU Next, BakaSU and APatch,
  and Vector, in all 12 supported clients. The README shows which ones were tried on each
  Android version.

## 1.1.10 (20 October 2026) — a clearer settings screen

- **Redesigned settings.** Each group (Ghost Mode, Stories, Messages, Connections, Media, UI and
  Other Features) is now its own card with an icon, and every option has a short line under it
  saying what it does, in English, Arabic, Persian and Chinese. "Restart required" sits on its own
  line. Your saved settings are kept.
- **Join the Re: TeleVIP group.** The developer channel button is replaced by the new group,
  [t.me/Revived_TeleVIP](https://t.me/Revived_TeleVIP), shown with the app's logo. The join prompt points
  there too.

## 1.1.9 (16 October 2026) — no more broken hooks on Nagram, Nekogram and Nagram X

- **Block Ads' second barrier works on Nagram and Nekogram.** When an ad request got through
  anyway, Re: TeleVIP couldn't put its "no ads" answer in place of the server's on these
  clients. Now it can, so those ads stay hidden too.
- **No more false "incompatible version" warnings.** Nagram X, some Nagram builds and Nekogram
  leave out a few parts of Telegram on purpose (like search ads). Re: TeleVIP already covered
  each of them another way, but its log still called them missing. They're now listed as "not
  in this build", with the reason.
- The weekly client check and the module's own report now always agree. Checked on Telegram
  13.0.3, Nekogram 13.0.2, Cherrygram 11.3.0, Nagram 1253, Nagram X 1260 and Momogram 12.10.6:
  every feature finds what it needs.

## 1.1.8 (15 October 2026) — Nekogram 13 and Nagram 1253

- **Re: TeleVIP works on Nekogram 13.0.2**, the first Nekogram built on Telegram 13. Save secret
  media, keeping messages forwardable, Voice messages as music and reading secret messages work
  there again.
- **Re: TeleVIP works on Nagram 1253** (12.10.6). Its colours, like the dark theme check and the
  message time, are found again after Nagram renamed them.

## 1.1.7 (12 October 2026) — weekly update

- Updated the build tools.

## 1.1.6 (8 October 2026) — the settings screen on every client, and Momogram

- **Re: TeleVIP Settings no longer opens empty**, with only its title bar (reported on Nagram X
  12.9.2). The screen is now a simple list built by Re: TeleVIP itself, so it no longer depends
  on parts each client changes. A row a client can't show is left out instead of blanking the
  whole screen.
- **Momogram 12.10.x: every feature works.** Save secret media, Show deleted messages, edits
  history and more found nothing to work with there before. Hide app update is no longer
  offered on Momogram, because it updates itself through its own updater.
- **Nagram X's "base" build is supported.**
- The weekly client check now also covers Momogram and Nagram X base: ten clients, the last
  five releases of each.

## 1.1.5 (8 October 2026) — the app is called Re: TeleVIP

- **The module is now named "Re: TeleVIP"** in LSPosed / Vector and in Android's app list (it
  was "TeleVip"), and in the title of the account-age dialog in profile menus. The README, here
  and in the Xposed Modules Repo, uses the new name too. Nothing else changes, and you don't
  need to reinstall.

## 1.1.4 (8 October 2026) — Re: TeleVIP Settings

- **The entry in Settings is now called "Re: TeleVIP Settings 🛸"**, with "Made by: @i_2B_4G10"
  below it. The settings screen and the dialogs use the new name too, in all four languages
  (English, Arabic, Persian and Chinese).

## 1.1.3 (8 October 2026) — its own icon in Settings

- **The entry in Settings shows the app's own icon**, the paper plane on its yellow tile,
  instead of the ghost.
- **Cherrygram 11.3.0 works again.** It had the same problem as Nekogram 12.10.6, fixed in 1.1.2.

## 1.1.2 (8 October 2026) — Nekogram 12.10.6 works again

- **TeleVip works on Nekogram 12.10.6 again.** It did almost nothing there: no entry in
  Settings, ads still shown, and most other features off. It had mistaken that version for an
  older one. It now always reads what it needs from the app you have installed, on every client
  and every version, and that's exactly what the weekly checks test. Cherrygram had the same
  mix-up and is fixed too.
- **The entry is back at the top of Settings, with its ghost icon**, on builds where it had
  lost its icon.

## 1.1.1 (7 October 2026) — ads blocked at every step

- **Block Ads now has three barriers instead of one**, so a sponsored post can't slip through
  if one of them misses:
  1. the request that fetches ads is stopped before it's sent, as before;
  2. if an ad request is sent anyway, the server's answer is read as "no ads";
  3. a chat that asks for its sponsored posts is told there are none, whatever was fetched or
     saved earlier.

  This covers sponsored posts in channels and bot chats, ads in the video player and the "Ad"
  results in chat search. The pinned proxy sponsor channel stays removed as before.
- **Block Ads is on by default.** If you never touched the switch, it's now on. If you turned
  it off, it stays off.

## 1.1.0 (2 October 2026) — a new package name, for the Xposed Modules Repo

- **The module has a new package name, `io.github.re_televip.televip`** (it was
  `com.my.televip`), so it can be listed in the Xposed Modules Repo (modules.lsposed.org).
  Android sees it as a new app, so do this once:
  1. Install this version, then uninstall the old *TeleVip*.
  2. In LSPosed / Vector, enable TeleVip again and tick your Telegram clients.
  3. Force stop the clients and reopen them.

  Your settings are kept, because they're stored inside each Telegram client.
- **Releases also appear in the Xposed Modules Repo**, so LSPosed / Vector can offer you
  updates.

## 1.0.8 (2 October 2026) — Show deleted messages on Nekogram 12.10.5+, Android 17

- **Show deleted messages works on Nekogram 12.10.5 and 12.10.6.** 1.0.7 listened for the wrong
  signal there, and could also catch a profile screen event by mistake. It now finds the right
  one on every version. Checked on all 37 client builds, including Telegram FOSS 10.14.3.
- **Ready for Android 17.** Built with the newest Android tools, which the weekly update now
  keeps current too.
- Under the hood: tidied up, and the weekly check no longer stumbles on clients with a long
  history on F-Droid (Forkgram).
- Checked again on Telegram Web 12.10.6, Nekogram 12.10.6, Cherrygram 11.3.0, Nagram 1248,
  Nagram X 1258, Forkgram 12.10.4 and Forkgram Classic 12.10.8.

## 1.0.7 (1 October 2026) — Nekogram 12.10.5+ and the last five releases of every client

- **Nekogram 12.10.5 and 12.10.6 are supported.** These versions shuffle their insides much
  more than before, which broke the settings entry, Ghost Mode, Block Ads, saving edits, the
  photo viewer and more. Every feature works there again.
- **Mercurygram is supported.**
- **Every feature was checked on the last five releases of each client** you can download,
  36 builds in all:
  - Nekogram 12.9.2–12.10.6, Cherrygram 10.9–11.3, Nagram and Nagram X;
  - Forkgram 12.9.5–12.10.4, Forkgram Classic 12.10.3–12.10.8 and Mercurygram 12.9.0–12.10.5;
  - Telegram 12.10.5 and 12.10.6.
- **The weekly client check now covers the last five releases of each client**, not just the
  newest one. Forkgram, Forkgram Classic and Mercurygram come from F-Droid.
- **Ghost Mode on Nagram:** reading a channel without being seen marked the wrong chat as read.
  Fixed.
- **Fix TL error, Disable number rounding, Save edits history and Hide app updates** keep
  working on builds that change these parts of the app.
- Dialogs now use your phone's own dialog style everywhere.

## 1.0.6 (1 October 2026) — ad blocking that works

- **Hide Proxy Sponsor is now Block Ads**, and your earlier setting carries over. It stops ads
  before they're even downloaded, so nothing is shown:
  - sponsored posts in channels and bot chats, and the ads in the video player;
  - the "Ad" results in chat search;
  - the proxy sponsor / announcement channel pinned to the top of the chat list.
- **The sponsor channel no longer comes back.** It used to be removed only after the app had
  already asked for it, so it popped straight back. It's now never asked for, and one saved from
  before is removed.
- Block Ads was checked on Telegram 12.10.5, Nekogram 12.10.3 and Cherrygram 12.10.1, and the
  weekly client check keeps checking it.

## 1.0.5 (28 September 2026) — every feature reaches its code

Every feature was tried again on Telegram 12.10.5, Nekogram 12.10.3 and Cherrygram 12.10.1, and
the ones that did nothing were fixed:

- **The entry in Settings is back on official Telegram.**
- **The settings page opens again on Telegram and Cherrygram.**
- **Nicegram, Nagram, Turrit, Momogram and Nekogram X:** some features that 1.0.4 quietly turned
  off on these clients work again.
- **Jump to message** and **Hide seen** work on more builds.
- The photo viewer, saving media and the settings list are found on more builds, Nagram and
  Nagram X included.
- **Weekly updates:** dependency updates are applied once they build, and the Monday client
  check releases a new version if anything changed and every client still checks out.

## 1.0.4 (28 September 2026) — official Telegram and Cherrygram

- **Official Telegram, Forkgram and similar clients now get the same treatment as Nekogram.**
  Telegram renames parts of its app in every release, so some features stayed off there. Every
  client is now read from the app you have installed. Every feature works on Telegram 12.10.5.
- **Cherrygram 12.10.1 is supported again.** It renames almost everything, and Re: TeleVIP now
  finds its way around that. Every feature works there.
- More features keep working when a client update changes things around.
- The weekly client check now also makes sure no feature ever latches on to the wrong part of
  an app.

## 1.0.3 (27 September 2026) — release safeguard

- A release is never published without the signed APK. If something goes wrong with signing,
  nothing is released, instead of a release with only the test build.
- Installs over 1.0.2 directly.

## 1.0.2 (27 September 2026) — signed release APK

- **The release APK is now signed**, so it installs directly. It's signed with a different key
  than the test builds, so if you have a test build installed, uninstall it once first.
- If one hook can't be set, the others are still set instead of being skipped.
- Old cached data from earlier client versions is cleaned up when new data is saved.
- Removed unused code and files, and updated the build tools.

## 1.0.1 (27 September 2026) — works on renamed builds, Ghost Mode dialog fixed

Version numbers start again at 1.0.1. It still installs over 3.7.0.

**Fixed**

- **Tapping *Join* in the Ghost Mode dialog crashed Nekogram**, and *Dismiss* left the Ghost
  Mode button dead. Both work now, and a dialog button that runs into a problem no longer takes
  the app down.
- **Survives Telegram updates.** When an update changes something a feature relies on, the
  feature now finds it again instead of quietly turning off, and never latches on to the wrong
  thing.

**Working again on Nekogram 12.10.3 and other clients with scrambled names**

- Hide pinned messages
- Remove content-saving restrictions
- Save edits history
- Show deleted messages
- Save secret media and Prevent media in secret chats
- Save protected stories
- Disable stories
- Always save media
- The chat and profile menu entries: *To the beginning*, *To the message* and *Approximate
  creation date*
- Show user ID and Hide online on profiles
- Menu and settings icons

**Also**

- **A new app icon:** a paper plane.
- The APK is built on GitHub, with install steps in the README.
- A short line in the log at startup says how many features found what they need.
- After this update, Re: TeleVIP takes a moment on first start to look at your client again.

## 3.7.0 (6 September 2026) — new Xposed framework, Vector 2.2, Zygisk Next, Nekogram X

- **Built for the new Xposed framework (API 102).** Re: TeleVIP runs on **Vector 2.2** and works
  with **Zygisk Next**. Older frameworks that only know the old API (LSPosed 1.9.x, EdXposed)
  are no longer supported.
- **Nekogram X is supported.**
- **A clear warning when a client update may break things.** If your Telegram client is a
  different version from the one Re: TeleVIP was checked on, you'll see one warning in the log
  at startup.
- **Official Telegram 12.10.1 checked:** everything works as before.
- Languages load more reliably, and the module description shows in Arabic too.
- Build fixes and updated tools.
