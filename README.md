# كأس المعامل - Android TWA

تطبيق Android يعمل عبر Trusted Web Activity (TWA) يفتح موقع كأس المعامل.

## طريقة البناء عبر GitHub Actions

1. ارفع هذا المجلد على GitHub (مستودع جديد)
2. اذهب إلى Settings → Secrets and variables → Actions
3. أضف هذه الـ Secrets:
   - `KEYSTORE_PASSWORD` : أي كلمة مرور (مثلاً: `KaasApp2026`)
   - `KEY_PASSWORD` : نفس كلمة المرور
4. اذهب إلى Actions → Build Android AAB → Run workflow
5. انتظر 5 دقائق ثم حمّل ملف AAB من Artifacts
