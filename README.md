# Smart Warehouse ERP - Railway Ready

هذه نسخة جاهزة للرفع على GitHub ثم Railway.

## التشغيل على Railway
1. ارفع كل الملفات على GitHub.
2. افتح Railway.
3. New Project → GitHub Repository.
4. اختر المستودع.
5. Railway سيبني Dockerfile ويشغل التطبيق.

## إعدادات جاهزة
- التطبيق يستخدم `PORT` تلقائيًا من Railway.
- التطبيق يستمع على `0.0.0.0`.
- قاعدة البيانات والملفات داخل `/app/data`.

## تنبيه مهم
تخزين Railway المحلي ليس أفضل حل دائم للـ SQLite والـ PDF. الأفضل لاحقًا نعمل Backup خارجي أو Cloud Storage.
