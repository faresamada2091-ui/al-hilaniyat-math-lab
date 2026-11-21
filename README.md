# مختبر الرياضيات الذكي — مدرسة الحلانيات (GitHub Pages)

هذه نسخة **ثابتة** جاهزة للنشر على GitHub Pages، ولا تحتاج إلى Python أو Flask على الخادم. واجهة الصفحات تستخدم HTML وCSS وJavaScript.

## النشر على GitHub Pages
1. أنشئ مستودعًا جديدًا على GitHub، مثل `al-hilaniyat-math-lab`.
2. فك ضغط الملف على جهازك.
3. ارفع **كل محتويات المجلد** إلى جذر المستودع، بحيث يظهر `index.html` في الصفحة الرئيسية للمستودع.
4. افتح المستودع ثم **Settings → Pages**.
5. في **Build and deployment** اختر **Deploy from a branch**.
6. اختر الفرع `main` والمجلد `/ (root)` ثم اضغط **Save**.
7. انتظر اكتمال النشر؛ سيظهر رابط الموقع في صفحة Pages.

## روابط الصفوف بعد النشر
إذا كان اسم المستخدم `USERNAME` واسم المستودع `REPOSITORY`:
- الصفحة الرئيسية: `https://USERNAME.github.io/REPOSITORY/`
- الصف الأول: `https://USERNAME.github.io/REPOSITORY/grade-1/`
- الصف الثاني: `https://USERNAME.github.io/REPOSITORY/grade-2/`
- ... حتى الصف الثاني عشر: `https://USERNAME.github.io/REPOSITORY/grade-12/`

## الملفات
- `index.html`: الصفحة الرئيسية.
- `grade-1/` إلى `grade-12/`: صفحة مستقلة لكل صف.
- `assets/style.css`: التنسيق.
- `assets/app.js`: التفاعلات.
- `LICENSE`: رخصة MIT.

## ملاحظة
هذه نسخة أولية تعليمية قابلة للتعديل والتطوير. موضوعات الصفوف مقترحة، وينبغي مراجعتها مقابل توزيع المنهج العُماني المعتمد قبل اعتمادها رسميًا. جميع صفحات العرض تعمل على GitHub Pages، ولا يُشغّل GitHub Pages تطبيقات Flask أو Python على الخادم.
