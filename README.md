# R1TV Player

**مشغّل IPTV لنظام Android مع واجهة مهيّأة للتلفاز والهاتف.**  
**An Android IPTV player with an interface designed for TVs and phones.**

> Latest version: **v1.8.1** — download the APK from the [Releases](https://github.com/r1tec-store/R1TV-Player/releases/latest) page.  
> آخر إصدار: **v1.8.1** — نزّل ملف APK من صفحة [Releases](https://github.com/r1tec-store/R1TV-Player/releases/latest).

## Screenshots / لقطات الشاشة

| Home / الرئيسية | Live TV / البث المباشر |
|---|---|
| ![Home screen](screenshots/home-screen.png) | ![Live TV with rounded preview](screenshots/live-tv.png) |

| Today's Matches / مباريات اليوم | Match channels / قنوات المباراة |
|---|---|
| ![Today's matches grouped by competition](screenshots/todays-matches.png) | ![Channels of a match from your playlist](screenshots/match-channels.png) |

| Match competitions / البطولات | |
|---|---|
| ![Choose competitions](screenshots/match-competitions.png) | |

| Group order / ترتيب المجموعات | EPG sources / مصادر دليل البرامج |
|---|---|
| ![Moving a group](screenshots/group-order.png) | ![EPG sources](screenshots/epg-sources.png) |

| Settings / الإعدادات | Playlist form / إضافة قائمة |
|---|---|
| ![Settings](screenshots/settings.png) | ![Add playlist form](screenshots/add-playlist.png) |

| Playlist status / حالة القائمة | Phone icon / أيقونة الهاتف |
|---|---|
| ![Connected playlist](screenshots/playlist-connected.png) | ![Phone launcher icon](screenshots/phone-icon.png) |

## Features / المميزات

The full list is in [FEATURES.md](FEATURES.md). / القائمة الكاملة في [FEATURES.md](FEATURES.md).

### English

- **Playlists** — add an **M3U URL** or **Xtream Codes** login, name it, manage several playlists, see connection status, reload.
- **Auto-update** — the playlist refreshes every 6, 12 (default), 24 or 48 hours; the EPG is refreshed with it.
- **Today's Matches** — today's football matches grouped by competition (most popular first): live minute and score, kick-off times, team logos. For each match the app asks the 365Scores football API which TV channels broadcast it in every **Broadcast Region** you enable (one query per region, results merged and de-duplicated), then finds those channels in **your own playlist** (country prefix or group: FR, UK, DE, AR …, quality HD/FHD/4K ignored, confidence score). OK on a channel plays it fullscreen. Channels that are not in your playlist are listed separately and are never shown as playable.
- **Match Competitions** — default: all national-team competitions (World Cup, qualifiers, friendlies…) plus the major club competitions (Premier League, LaLiga, Bundesliga, Serie A, Ligue 1, cups and super cups, Champions/Europa/Conference League, Libertadores, CAF/AFC Champions League, Saudi League, Botola Pro…); add or remove any competition in Settings.
- **Live TV** — groups, channels and a live preview with rounded corners and a rounded focus frame; OK = fullscreen.
- **Fullscreen channel list** — DOWN shows the group's channels over the video; LEFT / RIGHT switch groups; OK plays.
- **Group order** — hold OK on a group in Live, Movies or Series, move it with ▲ ▼ (the list follows it past the screen), OK saves instantly, BACK cancels. On phones: press and hold, then drag the group. Hold OK on a fixed row to reset to the provider's order.
- **EPG (TV guide)** — provider EPG on by default; optional free XMLTV sources and your own `.xml` / `.xml.gz` links, with smart channel matching by name and country.
- **Movies & Series** — browse by group, sort, search, resume watching, favorites, catch-up where the provider supports it.
- **Import / Export** — one-click backup to the Download folder; restore from any file-manager app.
- **TV remote first** — full D-pad navigation; double BACK on the home screen exits, the EXIT tile closes the app directly.
- **Phones too** — touch layouts, fullscreen player that keeps playing after the notification shade, adaptive launcher icon.
- **Languages** — Arabic, French, English, Spanish and Italian. VPN controls in Settings.

Match data and broadcaster names come from the public 365Scores web service (unofficial; it can change without notice). Channels named by the service are never shown as playable: only channels of your own playlist can be played.

The app is a player. This repository does not provide IPTV subscriptions, channels, movies, series, playlist URLs, or login credentials. Add only playlists and services you are authorized to use.

### العربية

- **القوائم** — إضافة **رابط M3U** أو **بيانات Xtream Codes** مع تسمية القائمة، وإدارة عدة قوائم ومعرفة حالة الاتصال وإعادة التحميل.
- **التحديث التلقائي** — تحديث القائمة كل 6 أو 12 (افتراضي) أو 24 أو 48 ساعة، مع تحديث دليل البرامج معها.
- **مباريات اليوم** — مباريات كرة القدم لليوم مجمّعة حسب البطولة (الأشهر أولا) مع الدقيقة والنتيجة المباشرة وموعد الانطلاق وشعارات الفرق. لكل مباراة يسأل التطبيق واجهة 365Scores عن القنوات الناقلة في كل **منطقة بث** مفعّلة (طلب لكل منطقة، ثم دمج النتائج وإزالة التكرار)، ثم يبحث عن هذه القنوات في **قائمتك أنت** (حسب بادئة الدولة أو المجموعة: FR و UK و DE و AR …، مع تجاهل HD/FHD/4K ودرجة ثقة للمطابقة). زر OK على القناة يشغّلها بالشاشة الكاملة. القنوات غير الموجودة في قائمتك تظهر في قسم منفصل ولا تُعرض كقنوات قابلة للتشغيل.
- **بطولات المباريات** — الافتراضي: كل بطولات المنتخبات (كأس العالم والتصفيات والمباريات الودية…) وأهم بطولات الأندية (الدوري الإنجليزي والإسباني والألماني والإيطالي والفرنسي والكؤوس والسوبر، دوري الأبطال والدوري الأوروبي ودوري المؤتمر، ليبرتادوريس، أبطال إفريقيا وآسيا، الدوري السعودي، البطولة الاحترافية…)؛ يمكن إضافة أو حذف أي بطولة من الإعدادات.
- **البث المباشر** — المجموعات والقنوات ومعاينة مباشرة بزوايا دائرية وإطار تركيز دائري؛ زر OK للشاشة الكاملة.
- **قائمة القنوات في الشاشة الكاملة** — زر الأسفل يعرض قنوات المجموعة فوق الفيديو، ويمين / يسار للتنقل بين المجموعات، وOK للتشغيل.
- **ترتيب المجموعات** — اضغط مطولا على OK فوق مجموعة في المباشر أو الأفلام أو المسلسلات، وحرّكها بـ ▲ ▼ (القائمة تتبعها حتى خارج الشاشة)، وOK يحفظ فورا وBACK يلغي. على الهاتف: اضغط مطولا ثم اسحب المجموعة. الضغط المطوّل على صف ثابت يعيد ترتيب المزوّد الأصلي.
- **دليل البرامج EPG** — دليل المزوّد مفعّل افتراضيا، مع مصادر XMLTV مجانية اختيارية وإمكانية إضافة روابط `.xml` أو `.xml.gz` خاصة، ومطابقة ذكية للقنوات حسب الاسم والدولة.
- **الأفلام والمسلسلات** — تصفح حسب المجموعة والترتيب والبحث ومتابعة المشاهدة والمفضلة والإعادة (Catch-up) عند توفرها من المزوّد.
- **الاستيراد والتصدير** — نسخة احتياطية بضغطة واحدة إلى مجلد Download والاستعادة من أي تطبيق لإدارة الملفات.
- **مصمم لجهاز التحكم** — تنقل كامل بالأسهم؛ الضغط مرتين على BACK في الرئيسية للخروج، وزر EXIT يغلق التطبيق مباشرة.
- **للهاتف أيضا** — واجهات لمس، ومشغل بشاشة كاملة يواصل العمل بعد إنزال الإشعارات، وأيقونة تطبيق متكيفة.
- **اللغات** — العربية والفرنسية والإنجليزية والإسبانية والإيطالية. أدوات VPN ضمن الإعدادات.

التطبيق مشغّل فقط. لا يوفر هذا المستودع اشتراكات IPTV أو قنوات أو أفلاما أو مسلسلات أو روابط قوائم أو بيانات دخول. أضف فقط القوائم والخدمات التي تملك حق استخدامها.

## What's new in v1.8.1 / الجديد في الإصدار 1.8.1

- **Today's Matches** tile on the home screen (matches, live scores, TV channels found in your playlist, one-click play). — مربع **مباريات اليوم** في الشاشة الرئيسية (المباريات والنتائج المباشرة والقنوات الموجودة في قائمتك والتشغيل بضغطة).
- **Broadcast Regions** and **Match Competitions** in Settings (selected items first, A–Z by country). — **مناطق البث** و**بطولات المباريات** في الإعدادات (المختار أولا ثم ترتيب أبجدي حسب الدولة).
- Channel search per region uses the channel and group prefixes (FR, UK, DE/GER, SP/ESP/ES, MA/AR, SA/AR, TR, IT, NL, US, CA, PT, PL, BR …). — البحث عن القنوات حسب المنطقة يعتمد على بادئة القناة والمجموعة.
- Phones: drag to reorder groups. — الهاتف: ترتيب المجموعات بالسحب.
- Phones: Today's Matches is full screen, edge to edge (v1.8.1). — الهاتف: مباريات اليوم بملء الشاشة بدون أشرطة جانبية (1.8.1).
- Since v1.4: double BACK to exit, provider EPG by default, rounded live preview, no black screen after reordering, phone player fix, new phone icon. — منذ 1.4: الخروج بالضغط مرتين على BACK، دليل المزوّد افتراضيا، معاينة بزوايا دائرية، إصلاح الشاشة السوداء بعد الترتيب، إصلاح مشغل الهاتف، أيقونة جديدة.

## App details / معلومات التطبيق

| | |
|---|---|
| App name / اسم التطبيق | R1TV Player |
| Version / الإصدار | 1.8.1 (versionCode 19) |
| Android package / معرّف الحزمة | `com.r1tv.player2` |
| Minimum Android / الحد الأدنى لأندرويد | Android 5.0, API 21 |
| Target SDK / إصدار الاستهداف | API 34 |
| Test device / جهاز الاختبار | Android TV (Android 11) |

## Download and install / التنزيل والتثبيت

Download `R1TV-Player-v1.8.1.apk` from the [Releases](https://github.com/r1tec-store/R1TV-Player/releases/latest) page and install it on an Android device or Android TV. It updates an installed v1.x over the top — playlists and settings are kept. Android may ask you to allow installation from the app used to open the APK. Review the requested permissions before accepting.

نزّل `R1TV-Player-v1.8.1.apk` من صفحة [Releases](https://github.com/r1tec-store/R1TV-Player/releases/latest) وثبّته على جهاز Android أو Android TV. يتم التحديث فوق الإصدار المثبّت مع الاحتفاظ بالقوائم والإعدادات. قد يطلب Android السماح بالتثبيت من التطبيق الذي فتح ملف APK؛ راجع الأذونات المطلوبة قبل الموافقة.

## Backups and privacy / النسخ الاحتياطي والخصوصية

Backup files can contain playlist URLs, Xtream usernames and passwords, and app settings. Keep backup files private and do not commit them to GitHub. Never publish real account credentials, private server addresses, device keys, or personal screenshots.

قد تحتوي ملفات النسخ الاحتياطي على روابط القوائم وأسماء المستخدمين وكلمات المرور وإعدادات التطبيق. احتفظ بها بشكل خاص ولا ترفعها إلى GitHub. لا تنشر بيانات دخول حقيقية أو عناوين خوادم خاصة أو مفاتيح الأجهزة أو صورا شخصية.

## License and redistribution / الترخيص وإعادة التوزيع

No open-source license is granted by this repository. Confirm that you have permission to redistribute the APK and all included third-party components and assets. Details are in [NOTICE.md](NOTICE.md).
