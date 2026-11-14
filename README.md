# سایت زرین پاپیلا + پیشخوان مدیریت

## دیپلوی روی Netlify
1. پوشه را در یک ریپازیتوری GitHub بگذارید و در Netlify گزینه Import from Git را بزنید (یا `npx netlify deploy --prod`).
2. در Site configuration > Environment variables این سه متغیر را بسازید:
   - ADMIN_USER = نام کاربری دلخواه
   - ADMIN_PASS = رمز قوی
   - SECRET = یک رشته تصادفی طولانی
3. دوباره Deploy کنید. پیشخوان: `/admin/`

داده‌ها و تصاویر در Netlify Blobs ذخیره می‌شوند و نیازی به دیتابیس جدا نیست.
