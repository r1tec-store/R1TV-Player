# R1TV Player — all features / جميع المميزات (v1.4.0)

## English

### Playlists
- First launch opens the playlist setup form directly.
- Add a playlist with an **M3U URL** or **Xtream Codes** (server, username, password) and give it a name.
- Several saved playlists: connection status, connect / disconnect, reload.
- Automatic playlist refresh every 6, 12 (default), 24 or 48 hours; *Reload* on the home screen refreshes on demand.

### Live TV
- Three columns: groups, channels, live preview with channel name and programme info.
- Preview with **rounded corners** and a **rounded focus frame**; OK on the preview or on the playing channel opens fullscreen.
- Fullscreen: DOWN shows the current group's channels over the video, LEFT / RIGHT switch to the previous / next group, OK plays, BACK closes the list.
- Previous / next channel, info bar with resolution, favorites, locked groups, search, catch-up when the provider offers it.
- Hide live groups, channel sort, live stream format, external players.

### Group order (Live, Movies, Series)
- Hold OK on a group → move mode (↕ mark). ▲ ▼ move it; the list scrolls with it, even past the visible rows.
- OK saves at once (no reload, playback continues); BACK cancels and restores the previous order.
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

### البث المباشر
- ثلاثة أعمدة: المجموعات، القنوات، ومعاينة مباشرة مع اسم القناة ومعلومات البرنامج.
- معاينة **بزوايا دائرية** و**إطار تركيز دائري**؛ زر OK على المعاينة أو على القناة المشغّلة يفتح الشاشة الكاملة.
- في الشاشة الكاملة: زر الأسفل يعرض قنوات المجموعة فوق الفيديو، يمين / يسار للمجموعة التالية / السابقة، OK للتشغيل، BACK لإغلاق القائمة.
- القناة السابقة / التالية، شريط معلومات مع الدقة، المفضلة، المجموعات المقفلة، البحث، والإعادة (Catch-up) عند توفرها من المزوّد.
- إخفاء مجموعات المباشر، ترتيب القنوات، صيغة البث المباشر، مشغلات خارجية.

### ترتيب المجموعات (المباشر، الأفلام، المسلسلات)
- اضغط مطولا على OK فوق مجموعة ← وضع التحريك (علامة ↕). ▲ ▼ للتحريك؛ القائمة تتبع المجموعة حتى خارج الصفوف الظاهرة.
- OK يحفظ فورا (بدون إعادة تحميل ودون توقف البث)؛ BACK يلغي ويعيد الترتيب السابق.
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
