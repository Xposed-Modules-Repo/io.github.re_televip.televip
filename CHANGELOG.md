# Changelog

## Unreleased

## 1.8.1 (28 November 2026) — Hotfix: Translate and Play-blocked groups work again, Telegram 13.4 and Nicegram 1.64+

**Fixed**

- **Translate works again after 1.8.** With Premium (and the free week) and **Local Telegram Premium** on, the **Translate bar in chats** and **Translate in the message menu** switches hid Telegram's own Translate buttons while they were off, and Telegram's own switches in its Language settings showed off and could not be turned on. Off now leaves Telegram's own setting as it is; on still shows the button.
- **Open Play-blocked groups works on chats you already have.** Groups, channels and bots the Google Play build of Telegram blocks now open right after you turn the switch on, also the ones Telegram had already loaded, with no restart.
- **Works with Telegram 13.4 and Nicegram 1.64+.** Telegram 13.4 (beta) moved and reordered parts the module hooks, and Nicegram changed the shape of its message menu and notifications; ad blocking, kept deleted messages, edit history, read time and the photo viewer's save button now find them again.
- **No false "missing" warnings when Telegram is patched with LSPatch and also ticked in Vector.** The module loaded twice; the Vector copy found nothing and filled the log and the hook health line with missing classes. It now steps aside and leaves the work to LSPatch's copy.

**New**

- **Developer logo in About.** The About card in the Tools tab now ends with the developer's logo; tap it to open the developer's GitHub page (github.com/2B-4G10).
- **Support us on Patreon or Ko-fi.** The Help & support card at the end of the Tools tab now ends with a **Support us** line over two buttons of the same size, **Patreon** and **Ko-fi**, each opening its page in your browser. Every language, Arabic right-to-left included, and any font size.

### 中文

**修复**

- **1.8 之后翻译恢复正常。** 有 Premium（包括免费周）并开启“本地 Telegram Premium”时，“聊天中的翻译栏”和“消息菜单中的翻译”两个开关在关闭状态下会隐藏 Telegram 自带的翻译按钮，Telegram 语言设置里的开关也显示为关闭且无法打开。现在关闭即沿用 Telegram 自己的设置；开启仍会显示按钮。
- **“打开被 Google Play 屏蔽的群组”对已有聊天生效。** 打开开关后，Google Play 版 Telegram 屏蔽的群组、频道和机器人立即可以打开，包括 Telegram 已加载的聊天，无需重启。
- **支持 Telegram 13.4 和 Nicegram 1.64 及以上。** Telegram 13.4（测试版）移动并调整了模块挂钩的部分，Nicegram 也改变了消息菜单和通知的结构；屏蔽广告、保留已删除消息、编辑记录、已读时间以及图片查看器的保存按钮现在都能重新找到它们。
- **用 LSPatch 修补且同时在 Vector 中勾选的 Telegram 不再误报“缺失”。** 模块会被加载两次；Vector 那一份什么也找不到，日志和挂钩状态里满是缺失的类。现在它会自动让出，由 LSPatch 内置的那一份工作。

**新增**

- **关于 中的开发者标志。** 工具 标签页的“关于”卡片底部现在显示开发者标志，点按即可打开开发者的 GitHub 页面（github.com/2B-4G10）。
- **在 Patreon 或 Ko-fi 上支持我们。** 工具 标签页最后的“帮助与支持”卡片底部新增“支持我们”一行，下方是两个同样大小的按钮 **Patreon** 和 **Ko-fi**，点按即在浏览器中打开对应页面。支持所有语言（包括从右到左的阿拉伯语）和任意字号。

## 1.8 (27 November 2026) — Major release: Premium free for 7 days, auto-translate chats, ads disappear completely

**Fixed**

- **Hidden ads come back when you turn ad blocking off.** Turning off **Block ads**, the live ad list or **Hide ads by keywords and links** now shows the messages they hid straight away, right where they are, with no restart and no need to reopen the chat. **Block ads** is now the main switch of the Ads card: with it off, the ad lists hide nothing either. Changing your keyword list or refreshing the live list shows the ones they no longer catch too.
- **Blocked ads disappear completely.** A message the ad blocking catches is now removed from the chat entirely: no "Ad hidden" line, no pictures and no row of link buttons left behind, and no empty gap where it was.
- **The pinned-message bar follows too.** When a pinned ad shows again after you turn ad blocking off, the bar at the top of the chat shows that message straight away instead of "Ad hidden" until you reopen the chat.
- **Ads shown again keep their photo or video.** A photo or video ad that comes back after you turn ad blocking off shows with its picture straight away, not as text only until the chat is reopened.

**New**

- **🎁 Premium free for 7 days.** Update to this version and every Premium feature is free for everyone for 7 days (cloud backup stays with paid plans). Already a member? 7 days are added to your plan. Please test it all and report any bug to @FogSourcebot or in our group @Revived_TeleVIP.
- **🌐 Auto-translate chats (Premium).** Messages in other languages show translated in every chat, by Telegram's own translator, with nothing to tap in each chat. Turn on **Local Telegram Premium**, then pick **Auto-translate chats** in the Tools tab: **Same as Telegram** or a language of your choice. **Show original** in a chat keeps that chat as it is; the same row can translate every chat again.
- **Simpler settings.** Fewer rows on first open, and nothing taken away. Fine-tuning rows show once their switch is on: the glass sliders under **Liquid glass in Telegram**, the live-list refresh and the keyword list under their ad switches. Long cards keep the rarely used rows under one **More options** row (Deleted messages and backups, Interface, Settings look). The Ads card now sits in the Privacy tab, beside the scam protection. Search still finds every setting, and your choices stay as they were.
- **💎 Open groups Google Play blocks.** With **Open Play-blocked groups** on (Messages card), groups, channels and bots that only the Google Play version of Telegram refuses ("violated Google Play's rules") open as they do in the telegram.org version. Chats blocked for every app stay blocked. Needs a restart after switching.
- **💎 Your own "last seen".** With **Appear online less** on, your profile can show your "last seen" as others see it ("last seen recently") instead of "You are currently offline". Turn on **Show my last seen** under it.
- **Appear online less, explained.** Its note (tap to open) now says simply that "You are currently offline" is shown only to you, and why a contact can show "last seen recently": Telegram hides others' last seen from you while you hide yours, unless you have real Telegram Premium.
- **💎 Local Telegram Premium is now a drop-down** with three Premium extras that switch on with it the first time:
  - **More than 5 pinned chats**: pin more than 5 chats. The extra pins are kept on this phone, under the ones Telegram keeps.
  - **Translate bar in chats**: show or hide the Translate bar at the top of a chat in another language.
  - **Translate in the message menu**: show or hide Translate when you hold a message.

**Changed**

- **Settings without emojis by default.** Re: TeleVIP's settings and menus now show as plain text, without emojis, unless you want them. To bring them back, turn off **Hide emojis in menus** in **Appearance → Settings look → More options** (or search "emoji"). If you already turned that switch on or off yourself, your choice stays.
- **Search stays open when you change a setting from it.** Switching **Hide emojis in menus**, the theme or the language from search results no longer closes the search and jumps back to a tab: the results stay, with what you typed.

**Coming soon**

- **🔑 Log in without a paid code (Premium)** is harder to build than we expected, so it gets its own update within a week at most.

### 中文

**修复**

- **关闭广告屏蔽后，被屏蔽的广告会恢复显示。** 关闭 **屏蔽广告**、实时广告名单或 **按关键词和链接隐藏广告** 后，它们隐藏的消息会立即在原位置显示，无需重启，也无需重新打开聊天。**屏蔽广告** 现在是广告卡片的总开关：关闭它后，广告名单也不再隐藏任何消息。修改你的关键词名单或刷新实时名单后，不再匹配的消息也会立即显示。
- **被屏蔽的广告会完全消失。** 被广告屏蔽拦下的消息现在会从聊天中完全移除：不再留下“已屏蔽广告”提示、图片或那一排链接按钮，也不会留下空白。
- **置顶消息栏也会同步更新。** 关闭广告屏蔽后，被置顶的广告重新显示时，聊天顶部的置顶栏会立即显示该消息，不再显示“已屏蔽广告”直到重新打开聊天。
- **恢复显示的广告会保留图片或视频。** 关闭广告屏蔽后重新显示的图片或视频广告会立即带着图片显示，不再只剩文字直到重新打开聊天。

**新增**

- **🎁 Premium 免费 7 天。** 更新到此版本，所有人可免费使用全部 Premium 功能 7 天（云备份仍仅限付费套餐）。已经是会员？你的套餐会额外增加 7 天。请多多测试，发现问题请发给 @FogSourcebot 或在我们的群组 @Revived_TeleVIP 里告诉我们。
- **🌐 自动翻译聊天（Premium）。** 其他语言的消息会在每个聊天中以 Telegram 自带的翻译显示，无需在每个聊天中手动点按。先开启 **本地 Telegram Premium**，再在“工具”页选择 **自动翻译聊天**：**与 Telegram 相同** 或你选择的语言。在某个聊天中点 **显示原文** 会让该聊天保持原样；同一设置项可以让所有聊天重新翻译。
- **更简洁的设置。** 打开时显示的行更少，但没有删除任何功能。细调选项会在其开关打开后才显示：**Telegram 液态玻璃** 下的玻璃滑块，以及广告开关下的实时名单刷新和关键词名单。较长的卡片把不常用的项目收进一行 **更多选项**（已删除消息与备份、界面、设置外观）。广告卡片移到“隐私”标签，与防诈骗保护放在一起。搜索仍能找到每一项设置，你的选择保持不变。
- **💎 打开被 Google Play 屏蔽的群组。** 开启 **打开被 Google Play 屏蔽的群组**（消息卡片）后，只有 Google Play 版 Telegram 拒绝显示的群组、频道和机器人（“违反了 Google Play 的规则”）会像 telegram.org 版一样正常打开。对所有应用都屏蔽的聊天仍保持屏蔽。切换后需要重启。
- **💎 你自己的“最后上线时间”。** 开启 **减少显示在线** 后，你的个人资料可以显示别人看到的“最后上线时间”（例如“最近上线”），而不是“你当前处于离线状态”。在“减少显示在线”下方开启 **显示我的最后上线时间**。
- **“减少显示在线”说明更清楚。** 它的说明（点按展开）现在简单说明：“你当前处于离线状态”只有你自己能看到；以及为什么联系人会显示“最近上线”：当你隐藏自己的最后上线时间时，Telegram 也会对你隐藏别人的，除非你拥有真正的 Telegram Premium。
- **💎 本地 Telegram Premium 现在是一个下拉菜单**，包含三个 Premium 附加功能，第一次开启时会一起打开：
  - **超过 5 个置顶聊天**：置顶超过 5 个聊天。额外的置顶保存在本机，排在 Telegram 保存的置顶之下。
  - **聊天中的翻译栏**：显示或隐藏其他语言聊天顶部的翻译栏。
  - **消息菜单中翻译**：显示或隐藏长按消息时的“翻译”。

**改动**

- **设置默认不显示表情符号。** Re: TeleVIP 的设置和菜单现在默认以纯文字显示，不带表情符号。想要恢复表情符号，请在 **外观 → 设置外观 → 更多选项** 中关闭 **隐藏菜单中的表情符号**（也可以搜索“表情”）。如果你之前自己切换过这个开关，你的选择保持不变。
- **在搜索结果中更改设置后，搜索保持打开。** 在搜索结果中切换 **隐藏菜单中的表情符号**、主题或语言后，搜索不再关闭并跳回某个标签页：结果和你输入的文字都会保留。

**即将推出**

- **🔑 无需付费验证码登录（Premium）** 比预想的更难实现，所以会单独更新，最多 1 周内推出。

## 1.7.2 (25 November 2026) — Hotfix: hidden ads are fully hidden

**Fixed**

- **Hidden ads hide their pictures too.** A message caught by the ad list showed "Ad hidden" in place of its text, but its photo, video or link preview still showed. Now the whole ad is hidden, and so are the other photos of its album, also when the album loads with the chat.
- **The ad list catches more ads.** It now also looks at the links of the buttons under a post, and an "@name" or "t.me/name" entry also hides posts forwarded from that channel or sent by it in a group.
- **The live ad list asks our server less often when it can't reach it.** After a failed update it waits half an hour before trying again by itself; "Refresh the live list now" still works straight away.

### 中文

**修复**

- **被屏蔽的广告连图片一起隐藏。** 被广告列表拦下的消息以前只把文字换成“已屏蔽广告”，图片、视频或链接预览仍然显示。现在整条广告都会隐藏，同一相册里的其他图片也一起隐藏，聊天刚打开时载入的相册也是如此。
- **广告列表能拦下更多广告。** 现在也会检查帖子下方按钮里的链接；列表里的“@用户名”或“t.me/用户名”也会隐藏从该频道转发来的帖子，以及它在群里发的消息。
- **连不上服务器时，实时广告名单不再频繁重试。** 更新失败后会等半小时再自动重试；“立即刷新实时名单”仍可马上使用。

## 1.7.1 (25 November 2026) — Tidier Tools tab, a Help & support card, and the message time line stays in its bubble

**Changed**

- **Help & support card.** The Patreon card at the end of Settings → Tools is now a Help & support card, in the Premium card's night-blue look with the logo: **Report an issue on GitHub** opens a new issue on our public page, and **Licence problem? Group chat** opens our group chat, where licence and activation problems can always be reported directly. The settings close as the chat opens, so it shows straight away. Every language, Arabic right-to-left included, and any font size.
- **Updates and About cards.** The Updates and About cards in Settings → Tools now share the Help & support card's night-blue look. Updates shows the installed version, how often it looks (tap to change), a **Check for updates** button and when it last looked. About has the channel button, **Restart App**, and what a restart is for.
- **One look for the whole Tools tab.** The Extras card and the Supported clients card at the end of Settings → Tools now share the same night-blue look as Premium, Updates, About and Help & support: a badge, title and a short line on what is inside, the switches on frosted glass with a glass switch in the logo's colours, and the clients' grid on frosted glass with its versions in cyan. The switches work exactly as before, and search still shows the plain rows. Every language, Arabic right-to-left included, and any font size.
- **Local Telegram Premium explains itself.** Its description now says what it opens (up to 4 accounts, folder tags, profile colours and emoji status only you see) and what it can't do because Telegram's servers check it (voice-to-text, faster downloads, 4 GB uploads, Premium stickers or reactions others see, higher limits).

**Fixed**

- **Message time line stays inside its bubble.** With Show message ID, read time or Deleted on, the line under a message (author name, ID and time) could run out of the bubble to the left, over the avatar or off the screen, most of all under polls with a long author name, in channels and in their discussion groups. The author's name is now shortened to fit the bubble as it really is, and if even that isn't enough the read time and then the ID are left out for that message. In a discussion group, the channel's posts kept their ID and author also when you run the channel. Works with reactions, pinned messages, every font size and language, Arabic right-to-left included.
- **Search finds settings by their English and older names too.** Searching "alert" finds **Hide language suggestion** again, and every setting can be found by its English name whatever language Re: TeleVIP is in.
- **“Re: TeleVIP” stays on one line in Arabic, Persian and Urdu.** When a line broke inside the name, it read “:Re” on one line and “TeleVIP” on the next.
- **“Last checked” in your language.** The Updates card and the ad list said when they last looked in the phone's language, so with Re: TeleVIP in Arabic and the phone in English it read “2 minutes ago” inside an Arabic line, turned round. It now follows Re: TeleVIP's language.
- **No app icon unless you use LSPatch.** Since 1.7 Re: TeleVIP had an icon in the phone's app list for everyone. Now it shows only when LSPatch is on the phone (its manager, or a Telegram patched with it), where it opens **Fix for this phone**. With Vector the icon goes away again the first time you open Telegram after updating; Re: TeleVIP opens from Vector as before.

### 中文

**改动**

- **帮助与支持卡片。** 设置 → 工具 最后的 Patreon 卡片改为“帮助与支持”卡片，采用与高级版卡片相同的深蓝外观和标志：**在 GitHub 上报告问题** 会在我们的公开页面新建问题，**许可证问题？群聊** 会打开我们的群聊，许可证和激活问题随时可以直接在那里反馈。打开群聊时设置会关闭，群聊马上就能看到。支持所有语言（包括从右到左的阿拉伯语）和任意字号。
- **更新与关于卡片。** 设置 → 工具 中的“更新”和“关于”卡片现在与“帮助与支持”卡片采用相同的深蓝外观。“更新”卡片显示已安装的版本、检查频率（点按可更改）、**检查更新** 按钮以及上次检查的时间。“关于”卡片包含频道按钮、**重启应用**，并说明重启的用途。
- **工具页整体统一外观。** 设置 → 工具 末尾的“额外功能”卡片和“支持的客户端”卡片现在与高级版、更新、关于、帮助与支持卡片采用同一种深蓝外观：带徽标、标题和一句内容简介，开关放在磨砂玻璃上并使用标志配色的玻璃开关，客户端网格也在磨砂玻璃上，版本号为青色。开关的行为完全不变，搜索时仍显示普通列表行。支持所有语言（包括从右到左的阿拉伯语）和任意字号。
- **本地 Telegram Premium 说明更清楚。** 说明里写明它能开放什么（最多 4 个账号、文件夹标签、只有你能看到的资料颜色和表情状态），以及因为需要 Telegram 服务器检查而做不到什么（语音转文字、更快的下载、4 GB 上传、别人能看到的 Premium 贴纸或回应、更高的上限）。

**修复**

- **消息时间行不再超出气泡。** 开启“显示消息 ID”、“已读时间”或“已删除”标记后，消息下方的那一行（作者名、ID 和时间）可能向左超出气泡，盖住头像或跑出屏幕，尤其是作者名较长的投票，在频道及其讨论组中最明显。现在作者名会按气泡的实际宽度缩短；如果仍然放不下，该条消息会省略已读时间，再省略 ID。在讨论组中，即使你是频道管理员，频道帖子也会保留 ID 和作者。适用于带表情回应、置顶的消息，所有字号和语言，包括从右到左的阿拉伯语。
- **搜索也能按英文名和旧名称找到设置。** 搜索“alert”会再次找到**隐藏语言建议**；无论 Re: TeleVIP 使用哪种语言，每个设置都可以用英文名称搜到。
- **在阿拉伯语、波斯语和乌尔都语中，“Re: TeleVIP”保持在同一行。** 以前名称在中间换行时，会显示成一行“:Re”、下一行“TeleVIP”。
- **“上次检查”跟随语言。** 更新卡片和广告列表显示上次检查时间时用的是手机的语言，所以 Re: TeleVIP 设为阿拉伯语、手机为英语时，阿拉伯语句子里会出现英文的“2 minutes ago”，而且顺序颠倒。现在它跟随 Re: TeleVIP 的语言。
- **不用 LSPatch 就没有桌面图标。** 从 1.7 起，所有人的应用列表里都会出现 Re: TeleVIP 图标。现在只有手机上装了 LSPatch（它的管理器，或用它修补过的 Telegram）时才显示，用来打开 **为这台手机修复**。使用 Vector 时，更新后第一次打开 Telegram 图标就会消失，仍像以前一样从 Vector 打开 Re: TeleVIP。

## 1.7 (24 November 2026) — Major release: Local Telegram Premium and saving in restricted chats go free, new Premium and Updates cards, a 3-month plan, USDT on TON

**New**

- **A new Premium card.** The Premium section at the top of Re: TeleVIP Settings is now its own card, with the Re: TeleVIP logo, your subscription's status, and one button to subscribe or manage. It works in the glass and Material You looks, light and dark, and in every language, Arabic right-to-left included.
- **Updates get their own card, and you choose how often.** Settings → Tools → Updates: look for a new version every time the app starts, every hour, every 12 hours, once a day (as before), once a week, or only when you tap Check for updates. The card shows when it last looked. If you had turned "Tell me about new versions" off, it is set to "Only when I check".
- **Ads card (Premium):** the live ad and scam list says how many entries it has and when it was last updated, and a new **Refresh the live list now** row fetches the newest list right away.
- **Update notes in Chinese.** When your Telegram (or the language picked in Re: TeleVIP) is Chinese, the update pop-up shows what's new in Chinese. The release page on GitHub and the channel post show both languages.
- **A 3-month Premium plan: $5.49 for 90 days.** Pick it on the Premium page next to the month and the year, by card or with USDT.
- **Pay with USDT on TON too.** "Pay with USDT" now has a TRON / TON switch: send USDT on either network, from Trust Wallet, Tonkeeper, Telegram Wallet or any other wallet. Premium still turns on by itself within a minute or two.
- **Hide emojis in menus.** A new switch in **Appearance → Settings look** shows Re: TeleVIP's settings and menus as plain text, without emojis, in every language. Free, and off until you turn it on.
- **Local Telegram Premium and Unlock saving in restricted chats are free now.** You voted, and these two were the top picks: both work without Premium, for everyone. Turn them on in Re: TeleVIP's settings. Say where a copy came from stays with Premium.

**Fixed**

- **No root (LSPatch): Telegram that closed right away on newer phones.** On phones with 16 KB memory pages, a patched Telegram could close as soon as it opened. Tap the new Re: TeleVIP icon → **Fix for this phone**: it updates in place, and your chats and settings stay.
- **Screen readers:** TalkBack reads the tabs at the top of Re: TeleVIP Settings and says which one is selected.
- **Premium, smoother:** a wrong or refused activation code keeps the code box open with the reason, so you can fix it in place. "Check again" now says whether the payment arrived. A renewal bought while Premium is still on is picked up by itself. No extra "Copied" popup on Android 13 and later.
- **Updates:** after you install a new version while Telegram is open, Re: TeleVIP now tells you the old version is still running and offers **Restart app** to load the new one. Before, it kept showing the old version, so the update looked like it had failed.
- **Voice-to-text with Local Telegram Premium:** instead of "No words recognized", it now says that voice-to-text needs real Telegram Premium (Telegram's server only transcribes for real Premium).
- **Side menu:** the "Re: TeleVIP Settings" row works again after you change Re: TeleVIP's language.
- **Disable stories:** the stories row no longer comes back at the top of the chat list after Telegram is closed and reopened when you have a story of your own.
- **Folder tags (Local Telegram Premium):** the folder tags switch and the coloured tags stay on after you reopen folder settings, on an account without Telegram Premium.
- **Premium on one phone:** every Telegram app on the same phone now counts as that one phone. Before, some phones (such as recent Pixels) gave each Telegram app its own ID, so a second app was refused as a second phone. Apps already on your code move over by themselves.
- **Glass with pattern wallpapers:** with **Sharp wallpaper** on, the glass now shows Telegram's pattern wallpapers, lines and all, also in dark mode. Before, it showed a flat grey there.
- **Manage subscription (Premium):** on Premium from a gift code or paid with USDT, the button now goes straight to the payment options to renew, instead of showing "Couldn't reach the Premium server". Extra taps while it opens do nothing, and later taps open it at once.

### 中文

**新功能**

- **全新的高级版卡片。** Re: TeleVIP 设置顶部的高级版区域现在是一张独立卡片，带有 Re: TeleVIP 标志、订阅状态，以及一个用于订阅或管理的按钮。支持玻璃和 Material You 外观、浅色和深色主题，以及所有语言（包括阿拉伯语从右到左显示）。
- **更新有了自己的卡片，频率由你决定。** 设置 → 工具 → 更新：可以选择每次启动应用时、每小时、每 12 小时、每天一次（与之前相同）、每周一次检查新版本，或仅在点击“检查更新”时检查。卡片会显示上次检查的时间。如果之前关闭了“新版本提醒”，会自动设为“仅手动检查”。
- **广告卡片（高级版）：** 实时广告和诈骗名单会显示条目数量和上次更新时间，新增 **立即刷新实时名单** 一项，可马上获取最新名单。
- **中文更新说明。** 当你的 Telegram（或在 Re: TeleVIP 中选择的语言）是中文时，更新提示会用中文显示更新内容。GitHub 的发布页面和频道公告会同时显示中英文。
- **新增 3 个月高级版：90 天 5.49 美元。** 在高级版页面中与月付、年付并列，可用银行卡或 USDT 支付。
- **也可用 TON 网络的 USDT 支付。** “用 USDT 支付”现在有 TRON / TON 切换：可在任一网络发送 USDT，支持 Trust Wallet、Tonkeeper、Telegram 钱包等任意钱包。高级版仍会在一两分钟内自动开通。
- **隐藏菜单中的表情符号。** 在 **外观 → 设置外观** 中新增开关，让 Re: TeleVIP 的设置和菜单以纯文字显示，不带表情符号，支持所有语言。免费，默认关闭。
- **本地 Telegram Premium 和解锁受限聊天的保存现在免费。** 投票结果出来了，这两项最受欢迎：现在所有人无需高级版即可使用。在 Re: TeleVIP 设置中开启即可。“注明副本来源”仍属高级版。

**修复**

- **免 Root（LSPatch）：新手机上 Telegram 一打开就关闭。** 在使用 16 KB 内存页的手机上，修补后的 Telegram 可能一打开就退出。点按新的 Re: TeleVIP 图标 → **为这台手机修复**：会直接原地更新，聊天和设置都会保留。
- **读屏功能：** TalkBack 现在会读出 Re: TeleVIP 设置顶部的标签页，并说明当前选中的是哪一个。
- **高级版体验更顺畅：** 激活码错误或被拒绝时，输入框会保留并显示原因，可直接修改；「再次检查」会告诉你付款是否已到账；高级版仍有效时购买的续费会自动生效；Android 13 及以上不再多弹一次「已复制」。
- **更新：** 在 Telegram 打开时安装新版本后，Re: TeleVIP 现在会提示旧版本仍在运行，并提供 **重启应用** 来加载新版本。以前会一直显示旧版本，看起来像更新失败了。
- **本地 Telegram Premium 的语音转文字：** 不再显示"未识别到文字"，而是说明语音转文字需要真正的 Telegram Premium（Telegram 服务器只为真正的 Premium 转写）。
- **侧边栏：** 更改 Re: TeleVIP 的语言后，"Re: TeleVIP 设置"一行可以正常打开了。
- **关闭动态：** 当你自己发过动态时，关闭并重新打开 Telegram 后，聊天列表顶部的动态栏不会再出现。
- **文件夹标签（本地 Telegram Premium）：** 在没有 Telegram Premium 的账号上，重新打开文件夹设置后，文件夹标签开关和彩色标签会保持开启。
- **高级版一台手机：** 同一台手机上的所有 Telegram 应用现在都算作这一台手机。以前部分手机（如较新的 Pixel）会给每个 Telegram 应用不同的 ID，导致第二个应用被当作第二台手机而被拒绝。已在你的兑换码上的应用会自动迁移。
- **图案壁纸上的玻璃：** 开启 **清晰壁纸** 后，玻璃现在会显示 Telegram 的图案壁纸及其线条，深色模式下也一样。以前在这里只显示一片灰色。
- **管理订阅（高级版）：** 使用礼品码或 USDT 付款的高级版，按钮现在会直接打开付款方式以便续费，而不再显示"无法连接高级版服务器"。打开过程中多次点击不会重复操作，之后再点会立即打开。

## 1.6.12 (24 November 2026) — One Premium code for your whole phone

**Fixed**

- **One Premium code covers your whole phone.** Every Telegram app on your phone (the official app or a fork, under Vector or LSPatch) and every account in them can use the same code: just enter it in each app. Before, a second Telegram app on the same phone counted as another phone and was refused. Updating Re: TeleVIP or Telegram keeps Premium on, as before, and you can move Premium to a new phone once every 30 days.

## 1.6.11 (23 November 2026) — Pay with USDT, and buying from China fixed

**New**

- **Pay for Premium with USDT, on any plan.** On the Premium page, tap "Pay with USDT" to pay for a month ($1.99) or a year ($19.99) in USDT on TRON (TRC20), from any wallet or exchange (Binance, OKX, imToken, TronLink, Trust Wallet and more). The page shows the exact amount to send; once it arrives, Premium turns on by itself, usually within a minute or two, with no screenshots or waiting for support. Works in mainland China too.

**Fixed**

- **The Premium page opens in your browser.** Subscribe and Manage subscription now open in your phone's own browser instead of the Telegram app's in-app window, where one swipe or the Back button could close a payment halfway. If the page is opened in an in-app browser anyway (WeChat, QQ and others), it offers to move to your browser first.
- **WeChat Pay on a computer works again.** In China the card checkout never opened on a computer, so WeChat Pay couldn't be chosen. Pick China as the country in the checkout and WeChat Pay shows.
- **Mainland China:** on re-televip.cc, paying with USDT comes first (the card checkout's address is blocked there), support links open the Telegram app, and Download comes from a mirror that works in China.
- **Checkout tidy-up:** the checkout asks for your email first, the USDT order code has its own Copy button, and copying works in in-app browsers.
- **Update pop-up:** the release notes no longer show a stray line of page code.

## 1.6.1 (22 November 2026) — Premium in mainland China, Telegram's proxy

**Fixed**

- **Premium works in mainland China again.** Activating a code, buying Premium and keeping it switched on failed there, because the server's old address is blocked. Re: TeleVIP now uses a new address that works in China, falls back to the old one elsewhere, and waits longer and tries again by itself when a connection is slow to start.
- **Uses Telegram's proxy.** If you reach Telegram through a SOCKS5 proxy set in Telegram (Settings → Data and Storage → Proxy), Premium now goes through the same proxy, so it works without switching your VPN to global mode.
- **Momogram 13.2.2:** the photo viewer's gallery button is found again.
- **Ad lists no longer hide messages from look-alike usernames.** An entry like @name or t.me/name now hides only that exact channel, bot or user, not longer names that start the same way (so t.me/kuai no longer hides t.me/kuaishou).

## 1.6 (22 November 2026) — Re: TeleVIP Premium, brand-new settings and a menu that works on deleted messages

**New (free)**

- **Settings, rewritten and reorganized.** Every switch has a clear new name, an emoji and a short explanation, in all 22 languages. Features now sit in cards by what they do: new **Deleted messages and backups**, **Ads**, **Liquid glass** and **Profiles** cards, and all the Telegram liquid glass controls are together in one card with a note on how to turn them on. Premium features carry a ⭐ Premium mark in the card where they belong. Your saved choices stay as they were.

**New: Re: TeleVIP Premium**

Premium is an optional subscription that unlocks extra features. You subscribe from **Re: TeleVIP → Premium**, and Premium turns on by itself once the payment goes through. One subscription works on one phone. Changing phones? Tap **Remove from this phone** on the old one, then enter your code on the new one.

- **Encrypted cloud backup.** Back up kept deleted messages and edit history to the cloud, by hand or once a day, and restore them on any phone with your code. The backup is encrypted on your phone with your activation code, so only you can open it.
- **Live ad and scam list.** Hides messages from ad and scam channels, bots and links on a list we keep up to date.
- **Hide ads by keywords and links.** Make your own list of words and links (right below **Block ads**), and messages that contain them show a short "Ad hidden" line instead. Comes with a ready list of about 270 known Chinese ad channels, bots and shops, which you can edit or clear.
- **Bigger storage for deleted messages.** Without Premium the newest 50 MB of kept deleted messages stay. With Premium, pick 512 KB, 1, 5, 10, 50 or 100 MB, 1 GB or unlimited.
- **Hide my number, Warn me if my number is exposed and Privacy check,** **Save self-destructing media,** **Unlock saving in restricted chats** (with Say where a copy came from) and **Local Telegram Premium** are Premium features now.
- **Message details.** A folded details line and who reacted, right under a message.
- **Creation date on profiles.** A user's approximate creation date shows under their name. The profile menu entry has its own switch now too (free, on as before).
- **Always show the proxy button,** next to Downloads at the top of the chat list.
- **Export and import your settings.** In **Deleted messages and backups**: every Re: TeleVIP setting (switches, look, glass, language) saved to one file, and brought back on a new phone or after a reinstall. Your subscription is never put in the file, and an import leaves it as it is.
- **My colours and emoji.** Pick your own name colour and profile emoji, even without Telegram Premium. They show on your phone, in every chat and on your profile.
- **File sizes in albums.** In **Media**: the real size on each photo and video of an album, in a small label at its corner.
- **Turn off pull up to the next channel,** so pulling up at the end of a channel no longer jumps to the next one.

Liquid glass, glass bubbles and the sharp wallpaper stay free.

**Improved**

- **Kept deleted messages get a menu that works.** Long-pressing a message someone deleted (kept by Show deleted messages) no longer offers Reply, Forward, Edit, Pin, Copy link, Report and other actions that need the message on Telegram's servers, which only failed. Copy, Delete, Save, Share and Translate stay. Nekogram's and Nagram's own server actions (their Forward menus, Repeat, Copy link in private chats and the like) go too, and so does the reaction bar, since a reaction is sent to the server as well.
- **Supported apps list stays current.** Opening it fetches the newest list when yours is over an hour old, and the clients are now checked twice a week (Monday and Thursday) and after every release, so a client update that works shows its new version within days. Every release's notes now end with the newest supported version of each client, kept up to date on their own.
- **View-once voice and round videos:** with Prevent media on, the player's "Delete and Close" button now says "Close", since the message is kept.
- **The once-a-day anonymous count** now also says whether Premium is on (yes or no) and which Premium features could not start in your Telegram app, so a client update that breaks one gets fixed fast.
- **Hide seen in channels, groups' comments and secret chats:** a stopped read receipt there is no longer answered with a made-up reply of the wrong kind, which some clients could trip over. It is simply not sent, like a hidden typing status.

## 1.5.93 (21 November 2026) — Telegram 13.3, phone number protection and glass message bubbles

**New**

- **Phone number protection.** A new card in Privacy settings. Telegram's hidden number can't be read by any app; "number finder" tools get it by tricking you into sharing it, by guessing numbers through contact sync, or from old leaked lists. Re: TeleVIP now closes the first two:
  - **Privacy check** shows who can see your number, who can find you by it and who sees your IP in calls, and sets all three safe in one tap (Nobody, My contacts, Nobody). It also checks once after start and tells you if anyone can see or find your number.
  - **Ask before my number is shared**: a bot's "Share contact" button, a mini app asking for your number, "Add contact" with "Share my phone number" ticked, the "Share my phone number" bar and a message with your number typed in now ask first.
    "Don't send" on a typed message puts it back in the typing box, ready to edit, instead of leaving a failed message in the chat.
  - **Warn before installing apps from chats**: an APK or Xposed module opened from a chat shows what it is before it goes to the installer. Your client's own update and Re: TeleVIP's own release pass without asking.

- **Glass message bubbles** (Appearance, off by default): message bubbles are see-through, so your wallpaper shows behind them instead of a solid colour. Text, photos and everything else in a message stay fully visible.

**Fixed**

- **Telegram 13.3 patched with LSPatch no longer crash-loops in the background.** Telegram 13.3 starts a second widget service in a separate process with the app. A patched app can't run those processes, so Android started it again and again, which filled the phone's usage records and on some phones made the system restart. Re: TeleVIP now switches those services off in a patched app (they can't work there anyway). With Vector nothing changes.
- **Graph Messenger 13.2.2: Prevent media, Save edit history and keeping deleted messages work again.** Graph kept an old part's name while moving to Telegram 13.2's new one, so Re: TeleVIP looked in the wrong place. It now follows the one Graph really uses.

**Checked**

- **Telegram 13.3.0** (telegram.org build 73419): every feature finds its code, with full hook health on the emulator.

## 1.5.92 (16 November 2026) — weekly update

- Build: Gradle 9.9.0 → 9.9.1

## 1.5.91 (14 November 2026) — the glass tab bar from the start, Save on every story

**Fixed**

- **Telegram glass: the tab bar is liquid glass as soon as the app opens.** It stayed plain until you opened a chat and came back, also after leaving with Back and reopening, and with a chat list too short to reach the bar. 1.5.90 drew the bar again, which was not the cause: Telegram records the picture under the bar once, before the chat list has said where the bar is, and keeps it. That picture is now recorded again after the app opens and whenever the chat list moves its glass areas.
- **Saving stories: "Save to Gallery" on every story.** Telegram only offers it on stories posted to Everyone, so stories posted to contacts, close friends or selected people had no Save at all. With Enable Saving Stories on, they now have it, with Copy Link and Share. Telegram keeps Save locked for accounts without Premium; Local Premium unlocks it.
- **Supported apps in settings showed old versions.** The list was only written once a week, so a client released midweek kept its old version until the next Monday. It is now refreshed after every release.

## 1.5.90 (14 November 2026) — secret chats keep deleted messages, forwards download first, and more fixes

**New**

- **Save and Mark as seen for view-once voice and round video messages.** They play in a small player of their own, so the secret media buttons never showed for them. With Prevent media or Secret media save on, that player now has Save (voice messages go to Music/Telegram) and, with Prevent media, Mark as seen.

**Fixed**

- **Forwarding from restricted chats no longer stops at "download first".** A video that plays while it streams looks downloaded and isn't, and big files wait for a tap. Re: TeleVIP now downloads what is missing and then sends the whole forward by itself, in order and with albums kept together.
- **Messages the other side deletes in a secret chat are kept.** With Show deleted messages on, they vanished there: a secret chat's deletions don't come through Telegram's server like the others. They are now kept and marked deleted, as in every other chat.
- **A secret chat the other side deletes for both stays on your phone.** With Show deleted messages on, the chat is shown as cancelled with its messages still in it, until you delete it yourself.
- **Nagram 13.2.1: Remove content-saving restrictions works again.** Nagram added a look-alike of the check Re: TeleVIP switches off, so the feature did not start there: restricted chats still blocked copying, saving and forwarding. It now finds the right one, and a part one client lacks no longer stops the feature's other parts.
- **Saving protected stories.** The story's "no forwards" mark is now cleared where the story is read, so screenshots, Save to Gallery and Share follow Enable saving stories.
- **Telegram glass: the tab bar is drawn again after the app starts.** On some phones it stayed plain until you opened a chat and came back, because it was drawn once before the chat list under it existed.

**Changed**

- **Edit history is easier to read.** Each version has its own heading and a blank line before it, instead of running together as one block of text.

**Good to know**

- **Vector and Telegram from Google Play.** If Vector does not list Telegram or loads no module into it, the cause is how Google Play installed it (a streamed "incremental" install), not Re: TeleVIP. Use Telegram from telegram.org, or install the Play build's files again by hand; see the README.

## 1.5.89 (13 November 2026) — no list crashes on Telegram 13.2.2, and fixes for Nekogram and Forkgram

**Fixed**

- **Lists no longer crash on Telegram 13.2.2.** A rare layout error ("trying to unhide a view that was not hidden") could bring down a chat or the chat list while messages animated. Re: TeleVIP now catches that one error and lets the list carry on — on official Telegram and on the forks that rename their internals.
- **Nekogram 13.2.2: menu actions, the Downloads shortcut and the secret-media buttons work again.** Telegram 13.2 added new parts to its screens that Re: TeleVIP mistook for the toolbar, so those buttons did nothing there. It now finds the real one.
- **Forkgram 13.2.1.0: opening links, the "Forwarded from" note on copies, and reply detection work again.** Forkgram renamed and moved these parts; Re: TeleVIP follows them on 13.2.1.0.

**Changed**

- **A tidier Supported clients list.** Telegram now shows once, simply as "Telegram", and NagramX shows once instead of twice. Both builds are still checked every week and keep working as before.
- **Supported clients shows the newest versions sooner.** The list of checked versions is now picked up within a day of each weekly check instead of up to a week later, and Telegram shows the newest Telegram that passed (for example 13.2.1 from telegram.org, before Google Play has it).

## 1.5.88 (10 November 2026) — Telegram glass on more phones, sharp wallpaper and fixes

**New**

- **Sharp wallpaper in Telegram glass.** In Appearance, with the glass look: the tab bar, top bar and message field bend a clear picture of your photo wallpaper instead of a blurred colour wash. Off by default; it applies to chats opened after you turn it on.
- **Preload the Profile tab** (Appearance, off by default): the bottom bar's Profile tab is built while the app is idle, so the first switch to it doesn't stutter.
- **Use glass on this phone anyway** (Appearance, with the glass look; off by default): Telegram draws no glass on phones it rates as low performance, and this draws it there too. The glass switch now says when Telegram won't draw glass on your phone, and why.
- **Supported clients in About.** The end of the Tools tab lists the clients Re: TeleVIP is checked with every week, each with the newest version that works; tap one to open its official download page.
- **Liquid glass top bar buttons.** In the settings' glass look, the back button and the theme and search buttons are liquid glass like the tab bar: on Android 13 and later the list bends under their rims as it scrolls by.
- **Make the glass tab bar your own.** In Appearance → Look, with the glass look: Tab bar size (compact, standard or large) and Tab bar glass (clear, standard or frosted). Standard is the bar as before.
- **Springy glass buttons.** With the glass look, the settings' top bar buttons give under your finger, stretch a little as you drag, and spring back like liquid glass (Appearance → Look; on by default, and off whenever the phone's animations are off).

**Fixed**

- **Edit history, approximate creation date and "go to message" open every time.** After leaving the app and coming back (without closing it), their window did not open until Telegram was restarted; Android 16 refuses it outright.
- **Posting to your profile or stories works with Local Premium on.** The post went out with Premium-only settings (how long it stays, splitting long videos), which Telegram refuses for accounts without Premium. A 6, 12 or 48 hour period picked from the menu is now sent as 24 hours.
- **Download Speed Boost says what it can't do.** Telegram's servers cap download speed for accounts without Premium; past the cap the boost can't go faster ("Download speed limited"). It now steps back to the client's own settings for a minute after each limit, so it doesn't cause extra waits, and its note explains the cap.
- **Telegram's glass no longer goes away on battery saver, or with chat blur off in power saving.** The glass needs Telegram's chat blur under it; it now keeps that on with the glass.
- **Deleted messages stay in groups and channels when older history is cleared.** When a channel or group's history was cleared up to a message (by its admins, or hidden for new members), or a forum topic was removed, the messages Show deleted messages had kept went with it. They now stay; clearing a chat yourself still empties it.

## 1.5.87 (9 November 2026) — weekly update

**Fixed**

- **Telegram 13.2.1:** the channel, support and update links in Re: TeleVIP open again.

## 1.5.86 (9 November 2026) — Telegram glass sliders, four tabs, and fixes

**New**

- **Telegram glass clarity and blur sliders.** In Appearance, with the glass look: make the client's own glass on the tab bar, top bar and message field clearer or more frosted, and its blur softer or stronger. In the middle (the default) nothing changes.

**Changed**

- **The settings' tab bar is real liquid glass on Android 13 and later:** the list bends under its rounded edge as it scrolls by, like through a drop of water.
- **Settings have four tabs: Privacy, Chats, Appearance and Tools.** The All tab is gone; search still looks through every tab.

**Fixed**

- **Scrolling the settings no longer moves a slider** when the finger starts on one. A slider moves when you slide it sideways or tap it.
- **Imported deleted messages now show in their chat**, also in chats you never scrolled through on the new phone.
- **Settings no longer jump** while you drag the glass clarity or blur slider.
- **Dialog buttons are readable on MIUI and HyperOS** (the Done button was the same colour as its fill).
- **Steadier first start after installing or updating**, on slow phones.
- **Download speed boost works again on Forkgram and Fork Client 13.2.**
- **Importing deleted messages counts only the new ones**, so importing the same backup again with Merge says 0.
- **No square box behind the settings tab bar's rounded ends.**
- **Picking a file that isn't a backup says so** instead of "Could not read or write the file".
- **The Telegram glass clarity slider works on official Telegram 13.2.** It was changing the wrong colour there.

## 1.5.85 (8 November 2026) — updates where GitHub is blocked, and settings fixes

**New**

- **Updates work where GitHub is blocked.** Download tries GitHub, then jsDelivr, then the release's post in our Telegram channel.

**Changed**

- **Telegram's liquid glass stays on when the battery is low.**
- **Liquid glass switch stays visible in Material You**, dimmed, with a note on how to use it.
- **LSPatch users are told how to update**: patch the app again, or use LSPatch's local mode.
- **Import's Merge and Overwrite options show their full explanation.**

**Fixed**

- **Seconds no longer show twice** in message times (14:42:51:51).
- **Settings tab bar no longer sits on the bare list** after the keyboard or another screen.
- **No dark box behind the selected settings tab.**
- **Importing deleted messages works on Nagram** and similar forks.
- **Approximate creation date works without a restart.**
- **Ads stay blocked on older Telegram versions** (before 11.3).
- **Fewer false "hook did not attach" reports.**

## 1.5.84 (7 November 2026) — colours of your own, and a Liquid glass switch that turns off

**New**

- **Accent colour**, as in KernelSU's manager: in Settings → Appearance → Look, pick your wallpaper's colour, one of 15 others, or the last circle for any colour you like (hue, saturation and brightness, or type its hex code). It colours both looks.
- **Colour style**, also from KernelSU: Tonal spot, Neutral, Vibrant, Expressive, Rainbow, Fruit salad, Monochrome, Fidelity or Content, for how the other colours are made from the accent.
- **Black (AMOLED) theme** for the settings, with pure black behind everything.
- **Glass clarity and Glass blur** sliders for the liquid glass look: how much of the list shows through, and how strongly it is blurred.

**Changed**

- **The glass at the top of the settings blurs more at the top and less towards the list**, so the frost thins out gradually.
- **Settings text follows your phone's font size.**
- **Material You turns the liquid glass off**, and hides its switch, since the two looks don't go together. Restart the app after changing the look for Telegram's glass to follow.
- The settings keep their place when you change a colour or slider.

**Fixed**

- **Liquid glass stayed on with its switch off.** Telegram saves its power-saving settings again whenever one of them changes, and that kept the glass saved as on. Turning the switch off now turns the glass off (after a restart).

## 1.5.83 (7 November 2026) — a compatibility check on the client's Update button, and forwards from Disable Sharing chats

**New**

- **The client's Update button checks compatibility first.** When you tap Telegram's own update, a message tells you what the weekly client check found about that version: green **Success! ✅** when it was tested with your Re: TeleVIP, red **Compatibility is Broken ⛓️‍💥💔** when it doesn't work, or orange **Compatibility Unknown ⚠️** when it hasn't been checked yet. You can still update anyway, or cancel. This works whether or not Suspend client updates is on.

**Changed**

- **Download Speed Boost is marked Beta**, with an orange warning under it: Telegram's servers punish it if you don't have real Telegram Premium, so try your client's own speed booster first.

**Fixed**

- **Forwarding from private chats with Disable Sharing** failed with a red "!". Those chats are protected through the profile rather than each message, so forwards went out as real forwards and Telegram refused them. They now go out as copies, like other protected messages.
- **Suspend client updates** now also clears an update the client had already saved, so its prompt doesn't come back after a restart.

## 1.5.82 (7 November 2026) — settings that fit every screen, and Suspend updates

**Changed**

- **Suspend client updates** (was Hide update prompts). The client's update prompt stays away until the weekly client check finds the new version working with your Re: TeleVIP; then it shows again for that version. The check's results are fetched once a week from GitHub, or through jsDelivr where GitHub is blocked. Builds updated by a store, or by their own updater (Nekogram), stay quiet as before.

**Fixed**

- **Settings tabs always fit.** On narrow screens, with a large font or long words (German, Tamil) the tabs move closer and then shrink, so all five stay in view and centred.
- **The settings title shows in full.** It shrinks to fit between the buttons, or takes two lines, on any screen size, density and font size.
- **Disable Sharing chats on Telegram 13.2 (Google Play).** Copy, Forward and Save were gone from the menu and screenshots blocked again: 13.2 marks every message of such a chat as protected and, in builds compiled ahead of time, folds its small checks into the code that calls them. Re: TeleVIP now clears those marks where the messages and profiles are read, so the menu and screenshots are back; forwards still go out as copies.
- **The Ghost Mode note opens again** when tapped; 1.5.81 left it folded at two lines.

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
