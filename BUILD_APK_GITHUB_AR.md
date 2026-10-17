# بناء APK عبر GitHub Actions (بدون Android Studio)

1. أنشئ مستودعًا جديدًا على GitHub باسم `JOYROOM-Bluetooth-Explorer` واختر Public أو Private.
2. فك ضغط ملف المشروع، ثم ارفع **محتويات مجلد** `JOYROOM_Bluetooth_Explorer` إلى جذر المستودع. تأكد من ظهور `app` و`build.gradle` و`settings.gradle` و`.github/workflows/build-apk.yml` في الجذر.
3. افتح تبويب Actions في المستودع، واختر `Build JOYROOM Explorer APK` ثم `Run workflow`.
4. افتح عملية التشغيل التي بدأت وانتظر حتى تظهر علامة النجاح.
5. في أسفل صفحة التشغيل، تحت Artifacts، نزّل `JOYROOM-Bluetooth-Explorer-APK` ثم فك ضغطه لتحصل على ملف APK.

ملاحظات: البناء يحتاج الإنترنت على خوادم GitHub. ملف APK الناتج نسخة debug للاختبار. لا ترفع كلمات مرور أو مفاتيح خاصة إلى المستودع. لا تضمن أداة الفحص كشف عنوان MAC مخفي أو تجاوز قيود الساعة/Android.
