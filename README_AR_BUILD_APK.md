# نظام المراقبة المجدولة متعدد الشاشات (Scheduled Multi-Screen Monitoring) - حزمة أندرويد

يحتوي هذا الأرشيف على المشروع الكامل لتطبيق أندرويد (Android Studio / Gradle) بالإضافة إلى نسخة تطبيق الويب التقدمي الجاهزة للتثبيت الفوري على الهواتف.

## الطريقة الأولى: التثبيت الفوري المباشر على هاتف أندرويد (PWA بدون الحاجة لكمبيوتر)
1. انقل ملف `app/src/main/assets/index.html` (أو افتح ملف `scheduled_multi_screen_monitoring.html`) على هاتف الأندرويد باستخدام متصفح **Google Chrome**.
2. اضغط على قائمة المتصفح **(⋮) ← الإضافة إلى الشاشة الرئيسية (Add to Home Screen / Install App)**.
3. سيعمل التطبيق بملء الشاشة كتطبيق أندرويد مستقل مع دعم كامل للكاميرا الخلفية، واستخراج قراءات الـ OCR، والتنبيهات كل ساعتين، والتصدير إلى Excel و PDF.

## الطريقة الثانية: استخراج ملف `app-debug.apk` عبر Android Studio أو سطر الأوامر
1. افتح هذا المجلد في برنامج **Android Studio**.
2. من القائمة العلوية اختر: **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
3. أو عبر الطرفية (Terminal) نفذ الأمر:
   ```bash
   gradle assembleDebug
   ```
4. ستجد ملف الـ APK الجاهز للتثبيت في المسار:
   `app/build/outputs/apk/debug/app-debug.apk`
