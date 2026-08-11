# تشغيل Windows بدون Docker

## 1. PostgreSQL
ثبّت PostgreSQL 16+ مباشرة على Windows، وأنشئ قاعدة:
`abdullah_quran_school`

## 2. البيئة
انسخ `.env.example` إلى `.env` وضع كلمة مرور PostgreSQL.

## 3. تثبيت
من جذر المشروع:
`npm install`

## 4. Prisma
`npm run db:generate`
`npm run db:migrate`
`npm run db:seed`

## 5. التشغيل
`npm run dev`

ثم افتح http://localhost:3000

> لا يوجد Docker أو docker-compose في هذه النسخة.
