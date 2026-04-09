# وصال | Wesal

منصة رقمية متعددة الأطراف تربط رواد الأعمال والمنشآت الصغيرة والمتوسطة والجمعيات والأفراد المنتجين مع الموردين، ومقدمي التمويل، والمستثمرين، وشركاء الخدمات، واللوجستيات، ضمن تجربة موحدة تشمل الشراء، التمويل، السداد، والتوصيل.

## نظرة عامة

هذا المستودع يحتوي على **نسخة ويب ثابتة (Static Web Version)** مخصصة للعرض العام والتقديم التنفيذي للمشروع.

النسخة الكاملة متعددة المراحل للمشروع تم تطويرها محليًا عبر حزم Sprint مستقلة، وتشمل مراحل أعمق على مستوى:

- الهوية البصرية
- الواجهات العربية RTL
- الـ MVP
- Full-Stack starter
- Auth وRBAC
- Finance applications
- Audit logs
- Password reset flow
- تهيئة انتقال نحو PostgreSQL / Prisma

## محتويات هذا المستودع

- `index.html` الصفحة الرئيسية
- `assets/styles.css` التنسيقات البصرية
- `pages/login.html` صفحة دخول تجريبية
- `.github/workflows/deploy-pages.yml` تهيئة نشر GitHub Pages

## الغرض من هذه النسخة

هذه النسخة مناسبة لـ:

- العرض العام للمشروع
- استعراض الفكرة بصريًا
- مشاركة رابط أولي للمفهوم
- دعم العروض التنفيذية والاستثمارية

وهي **ليست** النسخة التشغيلية الكاملة للإنتاج.

## حالة النشر

تم إعداد المستودع ليدعم **GitHub Pages**.

الرابط المتوقع بعد تفعيل Pages:

```text
https://yehia1002005-bit.github.io/Logistics/
```

> ملاحظة: إذا لم يعمل الرابط، فيجب التأكد من أن GitHub Pages مفعّل من إعدادات المستودع.

## التشغيل المحلي

يمكن فتح الموقع محليًا بشكل مباشر عبر:

- فتح `index.html` في المتصفح

أو عبر أي خادم ملفات ثابتة مثل:

```bash
python -m http.server 8080
```

ثم زيارة:

```text
http://localhost:8080
```

## خارطة الطريق الفنية للمشروع

المراحل التي تم إعدادها خارج هذا المستودع وتشكل الأساس الكامل للمنصة تشمل:

1. Concept Paper
2. Business Model Canvas
3. Pitch Deck
4. Prototype Web
5. Product Delivery Package
6. Engineering Delivery Pack
7. Sprint 1 إلى Sprint 8

## المكونات المستهدفة في النسخة التشغيلية الكاملة

- Auth + Session Management
- RBAC
- Catalog Management
- Orders
- Finance Applications
- Supplier Portal
- Financier Portal
- Admin / Ops Portal
- Notifications
- Document Uploads
- Audit Logs
- PostgreSQL / Prisma
- Production Deployment

## تنبيه مهم

هذا المستودع مخصص حاليًا للنسخة العامة الثابتة. 
أما الحزم البرمجية الأعمق الخاصة بالتطوير المرحلي فهي محفوظة ضمن تسليمات مستقلة خارج هذا المستودع.

## الاسم

**وصال — Wesal**

منصة لتمكين التجارة والتمويل والخدمات متعددة الأطراف.
