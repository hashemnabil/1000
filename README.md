# مدرسة عبدالله بن عمر لتعليم القرآن والسنة

نسخة التطوير المحلية بدون Docker.

## المتطلبات
- Node.js 20+
- PostgreSQL 16+ مثبت مباشرة على Windows
- npm

## التشغيل
1. انسخ `.env.example` إلى `.env` داخل `apps/api`.
2. أنشئ قاعدة PostgreSQL باسم `abdullah_quran_school`.
3. عدّل DATABASE_URL.
4. من جذر المشروع:
   `npm install`
5. `npm run db:generate`
6. `npm run db:migrate`
7. `npm run db:seed`
8. `npm run dev`

Frontend: http://localhost:3000
API: http://localhost:4000

حساب الإدارة الأول يتم تحديده من متغيرات البيئة، ولا توجد كلمة مرور ثابتة في الكود.
