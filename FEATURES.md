# R1TV Player — all features / جميع المميزات

## English

### Playlists
- First launch opens the playlist setup form directly.
- Add a playlist with an **M3U URL** or **Xtream Codes** (server, username, password) and give it a name.
- Several saved playlists: connection status, connect / disconnect, reload.
- Automatic playlist refresh every 6, 12 (default), 24 or 48 hours; *Reload* on the home screen refreshes on demand.

### Today's Matches (home tile)
- Today's football matches from the 365Scores web API, grouped by competition (most popular first); inside a competition: live, upcoming, finished. Live minute, score, kick-off time, round, team logos; auto refresh (1 min with live games, else 5 min).
- **Broadcast Regions** (Settings or the *Regions* button): any of the API's countries; default Brazil, Canada, Cyprus, Czechia, Denmark, England, Finland, France, Germany, Greece, Hungary, Italy, Kuwait, Morocco, Netherlands, Poland, Portugal, Saudi Arabia, Spain, Turkiye, USA. Select all / deselect all / restore defaults; selected first, A–Z.
- One API query per region (the API supports one country per request), channels merged per match: the same channel from several regions is shown once with all its regions; different channels with similar names stay separate. A region that fails is reported with *Retry*; the others are still shown.
- **Match Competitions** (Settings or the *Competitions* button): all national-team competitions (incl. friendlies) and a chosen list of club competitions; option to show every competition. Only selected competitions are loaded.
- **Matching with your playlist**: by channel name (case, spaces, punctuation, HD/FHD/4K/HEVC ignored, known aliases such as M+ = Movistar, TNT = BT Sport, close spellings) and by country: the channel prefix or its group (FR, UK, DE/GER, SP/ESP/ES, MA/AR, SA/AR, TR/TUR, IT/ITA, NL, US/USA, CA/CAN, PT/POR, PL/POL, BR/BRA …). Channel numbers must match (beIN 1 ≠ beIN 10). Each match has a confidence score: only strong matches are playable, weaker ones are shown as "possible", the rest under **Not Available in Your Playlist**.
- Filter: *With TV channels* (default) / *In my playlist* / *All matches*. OK on a channel plays it fullscreen in the Live player.

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
- مباريات كرة القدم لليوم من واجهة 365Scores، مجمّعة حسب البطولة (الأشهر أولا)، وداخل كل بطولة: المباشرة ثم القادمة ثم المنتهية. الدقيقة والنتيجة وموعد الانطلاق والجولة وشعارات الفرق، مع تحديث تلقائي (كل دقيقة أثناء المباريات المباشرة وإلا كل 5 دقائق).
- **مناطق البث** (من الإعدادات أو زر *Regions*): أي دولة تدعمها الواجهة؛ الافتراضي البرازيل، كندا، قبرص، التشيك، الدنمارك، إنجلترا، فنلندا، فرنسا، ألمانيا، اليونان، المجر، إيطاليا، الكويت، المغرب، هولندا، بولندا، البرتغال، السعودية، إسبانيا، تركيا، أمريكا. تحديد الكل / إلغاء الكل / استعادة الافتراضي؛ المختار أولا ثم ترتيب أبجدي.
- طلب واحد لكل منطقة (الواجهة تقبل دولة واحدة في كل طلب)، ثم دمج القنوات لكل مباراة: القناة نفسها من عدة مناطق تظهر مرة واحدة مع مناطقها، والقنوات المختلفة ذات الأسماء المتشابهة تبقى منفصلة. المنطقة التي يفشل تحميلها تظهر مع زر *Retry* وتبقى نتائج باقي المناطق.
- **بطولات المباريات** (من الإعدادات أو زر *Competitions*): كل بطولات المنتخبات (مع الودية) وقائمة مختارة من بطولات الأندية، مع خيار عرض كل البطولات. لا تُحمّل إلا البطولات المختارة.
- **المطابقة مع قائمتك**: حسب اسم القناة (حالة الأحرف والمسافات والرموز وHD/FHD/4K/HEVC مُتجاهلة، أسماء بديلة معروفة مثل M+ = Movistar و TNT = BT Sport، والأخطاء الإملائية البسيطة) وحسب الدولة: بادئة القناة أو مجموعتها (FR، UK، DE/GER، SP/ESP/ES، MA/AR، SA/AR، TR/TUR، IT/ITA، NL، US/USA، CA/CAN، PT/POR، PL/POL، BR/BRA …). أرقام القنوات يجب أن تتطابق (beIN 1 ≠ beIN 10). لكل مطابقة درجة ثقة: القوية فقط قابلة للتشغيل، والأضعف تظهر كـ"محتملة"، والباقي تحت **Not Available in Your Playlist**.
- التصفية: *With TV channels* (افتراضي) / *In my playlist* / *All matches*. زر OK على القناة يشغّلها بالشاشة الكاملة في مشغل البث المباشر.

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
