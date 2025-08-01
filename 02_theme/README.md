# قالب مدرن احراز هویت (تم ۲)

قالب مدرن احراز هویت با طراحی شیشه‌ای و افکت‌های زیبا برای استفاده در پروژه‌های وب. این قالب با Tailwind CSS پیاده‌سازی شده و دارای انیمیشن‌های ظریف است.

## صفحات موجود

- **صفحه ورود (login.html)**: صفحه ورود کاربران با طراحی مدرن
- **صفحه ثبت نام (register.html)**: صفحه ثبت نام کاربران جدید با فرم چندمرحله‌ای
- **فراموشی رمز عبور (forgot-password.html)**: صفحه درخواست بازیابی رمز عبور
- **بازنشانی رمز عبور (reset-password.html)**: صفحه تنظیم رمز عبور جدید
- **قالب ایمیل (email-template.html)**: قالب HTML برای ارسال ایمیل‌های تأیید و بازیابی رمز عبور

## ویژگی‌ها

- طراحی مدرن با افکت شیشه‌ای (Glassmorphism)
- انیمیشن‌های روان و زیبا
- پشتیبانی کامل از RTL برای زبان فارسی
- کاملاً ریسپانسیو برای نمایش در تمامی دستگاه‌ها
- استفاده از Tailwind CSS برای استایل‌دهی
- فونت وزیرمتن برای نمایش مناسب متون فارسی
- اعتبارسنجی فرم‌ها با استفاده از HTML5 و JavaScript
- رنگ‌بندی آبی بنفش با گرادیانت زیبا
- پس‌زمینه انیمیشنی

## نحوه استفاده

1. فایل‌های HTML مورد نیاز را در پروژه خود کپی کنید
2. فایل `styles.css` را نیز به پروژه خود اضافه کنید
3. محتوای فرم‌ها و متون را مطابق با نیاز خود تغییر دهید
4. آدرس‌های ارسال فرم (action) را به API یا سرور خود تغییر دهید
5. در صورت نیاز، فایل‌های جاوااسکریپت مرتبط با انیمیشن‌ها را شخصی‌سازی کنید

## سفارشی‌سازی

### تغییر رنگ‌بندی
رنگ اصلی قالب در فایل `styles.css` تعریف شده است. می‌توانید متغیرهای رنگ را مطابق با نیاز خود تغییر دهید:

```css
:root {
  --primary-color: #6366F1;
  --primary-light: #818CF8;
  --primary-dark: #4F46E5;
}
```

### تغییر افکت‌های شیشه‌ای
برای تغییر میزان شفافیت و محوشدگی افکت‌های شیشه‌ای، می‌توانید مقادیر `backdrop-filter` و `background-color` را در کلاس‌های مربوطه تغییر دهید:

```css
.glass-effect {
  background-color: rgba(255, 255, 255, 0.1);
  backdrop-filter: blur(10px);
}
```

### تغییر انیمیشن‌ها
انیمیشن‌های این قالب در فایل `styles.css` تعریف شده‌اند. می‌توانید مدت زمان، تأخیر و نوع انیمیشن‌ها را تغییر دهید.

### تغییر پس‌زمینه
می‌توانید تصویر یا الگوی پس‌زمینه را در فایل `styles.css` تغییر دهید.

## فناوری‌های استفاده شده

- HTML5
- CSS3
- Tailwind CSS
- FontAwesome
- JavaScript (برای انیمیشن‌ها و اعتبارسنجی فرم‌ها)

## سازگاری با مرورگرها

این قالب با تمامی مرورگرهای مدرن سازگار است:
- Chrome
- Firefox
- Safari
- Edge
- Opera

**نکته**: برخی از افکت‌های شیشه‌ای ممکن است در مرورگرهای قدیمی به درستی نمایش داده نشوند.

## پشتیبانی و مشکلات

برای گزارش مشکلات یا درخواست ویژگی‌های جدید، لطفاً در GitHub مشکل (Issue) ایجاد کنید.

## مجوز

این قالب تحت مجوز MIT منتشر شده است. 