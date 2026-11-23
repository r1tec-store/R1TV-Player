# R1TV Player — all features / جميع المميزات

## English

### Playlists
- First launch opens the playlist setup form directly.
- Add a playlist with an **M3U URL** or **Xtream Codes** (server, username, password) and give it a name.
- Several saved playlists: connection status, connect / disconnect, reload.
- Automatic playlist refresh every 6, 12 (default), 24 or 48 hours; *Reload* on the home screen refreshes on demand.

### Today's Matches (home tile)
- Today's football matches from **Fixtures OnSAT** (our own match service, static JSON on GitHub Pages, updated every 30 minutes), in the website's order and grouped by competition; inside a competition: live, upcoming, finished. Live minute and score (ESPN live feed when available, else from the kick-off time), kick-off time, round, team and competition logos, main broadcaster ("watch on") and commentator; auto refresh (1 min with live games, else 5 min).
- **Channels of a match**: every channel name of the service ends with its country ("beIN SPORTS 1 Qatar"); the app splits it into name + country. Matches without a channel list get their channel from the broadcaster logo (Egyptian League: ON Sport 1 / ON Sport Max); STARZPLAY = STARZPLAY SPORTS 1 and 2.
- **Matching with your playlist**: by channel name (case, spaces, punctuation, HD/FHD/4K/HEVC ignored, known aliases such as M+ = Movistar, TNT = BT Sport, ON Sport = ONTIME SPORTS, close spellings) and by country: the channel's own prefix decides, else its group (`ARAB| EGYPT` = Egypt, `ASIA| IRAN` = Iran, `AF| AZAM` = any African country; Arab prefixes are shared by Arab channels, ex-Yugoslav prefixes by ex-Yugoslav channels). Channel numbers must match (beIN 1 ≠ beIN 10; "… 1" also finds the unnumbered channel). **Only sure channels are playable**; the others are listed under **Not Available in Your Playlist**.
- Filter: *With TV channels* (default) / *In my playlist* / *All matches*. OK on a channel plays it fullscreen in the Live player.
- Matches: live first, then upcoming, then finished, each grouped by competition. 15 minutes after the end of a match only its result is shown. BACK from a channel opened here returns straight to the match.

### Live TV
- Three columns: groups, channels, live preview with channel name and programme info.
- Preview with **rounded corners** and a **rounded focus frame**; OK on the preview or on the playing channel opens fullscreen.
- Fullscreen: DOWN shows the current group's channels over the video, LEFT / RIGHT switch to the previous / next group, OK plays, BACK closes the list.
- Previous / next channel, info bar with resolution, favorites, locked groups, search, catch-up when the provider offers it.
- Hide live groups, channel sort, live stream format, external players.

### Group order (Live, Movies, Series)
- Hold OK on a group → move mode (↕ mark). ▲ ▼ move it; the list scrolls with it, even past the visible rows.
- OK saves at once (no reload, playback continues); BACK cancels and restores the previous order.
- Phones and tablets: press and hold a group, drag it, lift your finger to save.
- Fixed rows (Recently viewed, All, Favorites, Locked, Add group) keep their place. Hold OK on one of them to reset to the provider's order.
- The order is saved per section and is included in Export.

### EPG (TV guide)
- Settings → **EPG Sources**: turn sources on / off, *Enable all / Disable all*, add your own XMLTV link (`.xml` or `.xml.gz`), hold OK to delete a custom source.
- Default: the **provider's EPG is on**, the free sources (IPTV-EPG, IPTV-EPG 2, EPGTalk) are off.
- External guides are streamed and cached (only the channels of your playlist, −2 h to +26 h) and matched by EPG id, name, country prefix and group.
- The guide refreshes together with the playlist.

### Movies & Series
- Browse by group, sort (e.g. by date added), search, resume watching, favorites, hide groups.
- Movie and series info pages, seasons and episodes, subtitle settings.

### Language, updates, tips
- The whole app follows the language chosen in Settings → Change Language (English, Arabic, French, Spanish, Italian).
- Settings → **Check for updates**: compares with the latest GitHub release, shows the release notes, downloads `R1TV-Player.apk` from the permanent link and opens the Android installer (settings and playlists are kept). A quiet check also runs every 3 hours; a release marked as required shows a prompt without "Later" until it is installed.
- First-use tips (English + Arabic), shown once: how to reorder groups (Live) and how to open a match's channels (Today's Matches).

### Home screen & exit
- Tiles: Live, Movies, Series, Settings, Playlist, Reload, EXIT; subscription expiry, clock and date.
- **BACK twice** on the home screen exits (the first press shows a hint). The **EXIT** tile closes the app directly, without a yes / no question.

### Backup
- **Export**: one click, saved to `Download/R1TV-Player-backup-<date>.json`.
- **Import**: choose the file with any file-manager app installed on the device.

### Devices
- Android TV, Fire TV, phones and tablets; the device type is detected automatically and can be changed in Settings.
- Phones: touch layouts; the fullscreen player keeps working after pulling down the notification shade or a pop-up.
- Adaptive launcher icon on phones, banner on TV.
- Dark background on all screen edges (no light line at the top).

### Other
- Interface languages: Arabic, French, English, Spanish, Italian.
- VPN controls, format & units, change layout, clear history (channels, movies, series).

---

## العربية

### القوائم
- عند التشغيل الأول يفتح نموذج إضافة القائمة مباشرة.
- إضافة قائمة عبر **رابط M3U** أو **Xtream Codes** (الخادم، اسم المستخدم، كلمة المرور) مع تسميتها.
- عدة قوائم محفوظة: حالة الاتصال، الاتصال / قطع الاتصال، إعادة التحميل.
- تحديث تلقائي للقائمة كل 6 أو 12 (افتراضي) أو 24 أو 48 ساعة، وزر *Reload* في الرئيسية للتحديث عند الطلب.

### مباريات اليوم (مربع في الرئيسية)
- مباريات كرة القدم لليوم من **Fixtures OnSAT** (خدمة المباريات الخاصة بنا، ملفات JSON على GitHub Pages تتحدث كل 30 دقيقة)، بترتيب الموقع ومجمّعة حسب البطولة، وداخل كل بطولة: المباشرة ثم القادمة ثم المنتهية. الدقيقة والنتيجة (من ESPN عند توفرها وإلا حسب وقت الانطلاق)، وموعد الانطلاق والجولة وشعارات الفرق والبطولات والقناة الناقلة والمعلق، مع تحديث تلقائي (كل دقيقة أثناء المباريات المباشرة وإلا كل 5 دقائق).
- **قنوات المباراة**: كل اسم قناة في الخدمة ينتهي ببلدها («beIN SPORTS 1 Qatar») فيقسمه التطبيق إلى اسم + بلد. المباريات بدون قائمة قنوات تأخذ قناتها من شعار القناة الناقلة (الدوري المصري: ON Sport 1 / ON Sport Max)، و STARZPLAY = STARZPLAY SPORTS 1 و 2.
- **المطابقة مع قائمتك**: حسب اسم القناة (حالة الأحرف والمسافات والرموز وHD/FHD/4K/HEVC مُتجاهلة، أسماء بديلة معروفة مثل M+ = Movistar و TNT = BT Sport و ON Sport = ONTIME SPORTS، والأخطاء الإملائية البسيطة) وحسب البلد: بادئة القناة هي الأساس وإلا مجموعتها (`ARAB| EGYPT` = مصر، `ASIA| IRAN` = إيران، `AF| AZAM` = أي بلد إفريقي؛ البادئات العربية مشتركة بين القنوات العربية، وبادئات يوغوسلافيا السابقة كذلك). أرقام القنوات يجب أن تتطابق (beIN 1 ≠ beIN 10، و «… 1» تجد أيضا القناة بدون رقم). **القنوات المؤكدة فقط قابلة للتشغيل**، والباقي تحت **Not Available in Your Playlist**.
- التصفية: *With TV channels* (افتراضي) / *In my playlist* / *All matches*. زر OK على القناة يشغّلها بالشاشة الكاملة في مشغل البث المباشر.
- المباريات: المباشرة أولا ثم القادمة ثم المنتهية، مجمّعة حسب البطولة. بعد 15 دقيقة من نهاية المباراة تبقى النتيجة فقط. زر الرجوع من قناة فُتحت من هنا يعود مباشرة إلى المباراة.

### البث المباشر
- ثلاثة أعمدة: المجموعات، القنوات، ومعاينة مباشرة مع اسم القناة ومعلومات البرنامج.
- معاينة **بزوايا دائرية** و**إطار تركيز دائري**؛ زر OK على المعاينة أو على القناة المشغّلة يفتح الشاشة الكاملة.
- في الشاشة الكاملة: زر الأسفل يعرض قنوات المجموعة فوق الفيديو، يمين / يسار للمجموعة التالية / السابقة، OK للتشغيل، BACK لإغلاق القائمة.
- القناة السابقة / التالية، شريط معلومات مع الدقة، المفضلة، المجموعات المقفلة، البحث، والإعادة (Catch-up) عند توفرها من المزوّد.
- إخفاء مجموعات المباشر، ترتيب القنوات، صيغة البث المباشر، مشغلات خارجية.

### ترتيب المجموعات (المباشر، الأفلام، المسلسلات)
- اضغط مطولا على OK فوق مجموعة ← وضع التحريك (علامة ↕). ▲ ▼ للتحريك؛ القائمة تتبع المجموعة حتى خارج الصفوف الظاهرة.
- OK يحفظ فورا (بدون إعادة تحميل ودون توقف البث)؛ BACK يلغي ويعيد الترتيب السابق.
- الهاتف والجهاز اللوحي: اضغط مطولا على المجموعة واسحبها ثم ارفع الإصبع للحفظ.
- الصفوف الثابتة (المشاهدة الأخيرة، الكل، المفضلة، المقفلة، إضافة مجموعة) لا تتحرك. الضغط المطوّل على أحدها يعيد ترتيب المزوّد الأصلي.
- الترتيب محفوظ لكل قسم ويدخل ضمن التصدير.

### دليل البرامج EPG
- الإعدادات ← **EPG Sources**: تفعيل / تعطيل المصادر، *تفعيل الكل / تعطيل الكل*، إضافة رابط XMLTV خاص (`.xml` أو `.xml.gz`)، والضغط المطوّل لحذف مصدر مضاف.
- الافتراضي: **دليل المزوّد مفعّل**، والمصادر المجانية (IPTV-EPG و IPTV-EPG 2 و EPGTalk) معطّلة.
- الأدلة الخارجية تُقرأ وتُخزّن مؤقتا (قنوات قائمتك فقط، من −2 ساعة إلى +26 ساعة) وتُطابق حسب المعرّف والاسم وبادئة الدولة والمجموعة.
- يتحدث الدليل مع تحديث القائمة.

### الأفلام والمسلسلات
- التصفح حسب المجموعة، الترتيب (مثلا حسب تاريخ الإضافة)، البحث، متابعة المشاهدة، المفضلة، إخفاء المجموعات.
- صفحات معلومات الأفلام والمسلسلات، المواسم والحلقات، إعدادات الترجمة.

### اللغة والتحديث والنصائح
- التطبيق كله يتبع اللغة المختارة في الإعدادات ← تغيير اللغة (العربية، الإنجليزية، الفرنسية، الإسبانية، الإيطالية).
- الإعدادات ← **التحقق من التحديثات**: مقارنة بآخر إصدار على GitHub، عرض الجديد، تنزيل `R1TV-Player.apk` من الرابط الدائم وفتح أداة التثبيت (مع الاحتفاظ بالإعدادات والقوائم). ويتم فحص تلقائي كل 3 ساعات، والإصدار الإلزامي يظهر بدون زر «لاحقا» حتى يُثبَّت.
- نصائح أول استعمال (بالعربية والإنجليزية) تظهر مرة واحدة: كيفية ترتيب المجموعات (البث المباشر) وكيفية فتح قنوات المباراة (مباريات اليوم).

### الشاشة الرئيسية والخروج
- المربعات: Live و Movies و Series و Settings و Playlist و Reload و EXIT، مع مدة الاشتراك والساعة والتاريخ.
- **الضغط مرتين على BACK** في الرئيسية للخروج (الضغطة الأولى تعرض تنبيها). زر **EXIT** يغلق التطبيق مباشرة بدون سؤال نعم / لا.

### النسخ الاحتياطي
- **التصدير**: بضغطة واحدة إلى `Download/R1TV-Player-backup-<date>.json`.
- **الاستيراد**: اختيار الملف عبر أي تطبيق لإدارة الملفات مثبّت على الجهاز.

### الأجهزة
- Android TV و Fire TV والهواتف والأجهزة اللوحية؛ يُكتشف نوع الجهاز تلقائيا ويمكن تغييره من الإعدادات.
- الهاتف: واجهات لمس؛ المشغل بالشاشة الكاملة يواصل العمل بعد إنزال الإشعارات أو ظهور قائمة منسدلة.
- أيقونة تطبيق متكيفة على الهاتف وشعار (Banner) على التلفاز.
- خلفية داكنة على كل أطراف الشاشة (بدون خط فاتح في الأعلى).

### أخرى
- لغات الواجهة: العربية، الفرنسية، الإنجليزية، الإسبانية، الإيطالية.
- أدوات VPN، الصيغ والوحدات، تغيير الواجهة، مسح السجل (القنوات، الأفلام، المسلسلات).
