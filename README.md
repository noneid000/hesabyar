# حساب‌یار Android APK

این پروژه نسخه وب حساب‌یار را با Capacitor داخل Android قرار می‌دهد.

## GitHub Actions

با push روی شاخه `main`، workflow زیر اجرا می‌شود:

- نصب وابستگی‌ها
- ساخت پروژه Android با Capacitor
- همگام‌سازی `www/index.html`
- ساخت APK دیباگ
- آپلود APK به‌عنوان Artifact با نام `hesabyar-debug-apk`

پوشه `android` عمداً داخل مخزن قرار نمی‌گیرد و در GitHub Actions ساخته می‌شود.
