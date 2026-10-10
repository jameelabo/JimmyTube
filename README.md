# Jimmy Tube

Download videos or MP3 audio from YouTube and public TikTok links on Android. English is the default, with Arabic available from the Language button.

## Download

**[Download Jimmy Tube 2.2 for Android](https://raw.githubusercontent.com/jameelabo/JimmyTube/main/JimmyTube-v2.2.apk)**

Requires Android 10 or newer. Download and open the APK; allow installation from the app opening it if Android asks. Install updates over your existing copy without uninstalling to preserve your library index.

## Features

- MP4 video and real MP3 audio at 192 kbps.
- YouTube playlists: select videos and download them in order.
- Files saved to Download/JimmyTube; playlists have their own named folder.
- Embedded artwork without separate thumbnail files.
- Original YouTube audio preferred when the source identifies it.
- Local library with ten items per page, playback and sharing.
- Download progress, notifications and cancellation.
- English/Arabic interface with a saved language choice.

## Limits

Internet is required. Private or login-required content, live streams and Instagram are not supported. Extraction can fail if a platform changes or restricts access. Playlist selection covers loaded items, up to 500; interrupted queues do not resume after the process is killed.

## Source and licenses

[Download the version 2.2 source bundle](JimmyTube-source-v2.2.zip?raw=true). It includes application sources, build scripts, dependency artifacts, JLAME sources and upstream sources for NewPipeExtractor, nanojson, Rhino, jsoup, protobuf and JSR305. Dependency source URLs and checksums are included in upstream-source/manifest.json. Build instructions are in the bundle's README.md. Build tools are fetched by tools/fetch-build-tools.py; Android SDK/JDK paths are configured by build.ps1. A local signing key is generated for your build; private release keys are not distributed. A differently signed build must be installed separately from the official release.

Jimmy Tube is distributed under [GPL-3.0-or-later](LICENSE), without warranty. See [third-party notices](licenses/NOTICE.txt) and the license files in licenses/. This release is dated October 10, 2026 and adds English/Arabic localization to the 1.9 YouTube/TikTok edition. It uses package com.jimmy.tube, version code 13. No account credentials or user downloads are included in this repository.

---

## العربية

Jimmy Tube لتنزيل الفيديو أو الصوت MP3 من يوتيوب وروابط تيك توك العامة. الإنجليزية افتراضية والعربية متاحة من زر Language.

**[تحميل Jimmy Tube 2.2](https://raw.githubusercontent.com/jameelabo/JimmyTube/main/JimmyTube-v2.2.apk)**

يحتاج Android 10 أو أحدث. ثبّت التحديث فوق نسختك الحالية دون حذف التطبيق للحفاظ على فهرس المكتبة.

يدعم قوائم يوتيوب، التنزيل المتتابع، صوت MP3 بجودة192 kbps، الفيديو MP4، الغلاف المضمّن دون صور منفصلة، ومكتبة بعشرة ملفات في الصفحة. تحفظ الملفات في Download/JimmyTube، وكل بلايليست داخل مجلد باسمها.

لا يدعم إنستغرام أو المحتوى الخاص أو الذي يحتاج تسجيل دخول. قد تتغير خدمات المواقع ويتعذر استخراج بعض الروابط. حزمة المصدر والتراخيص متاحة أعلاه.
