# جدول جامع کاربردهای PHP به همراه کتابخانه‌ها و ابزارها (نسخه ۲۰۲۶)

| حوزه کاربرد | کتابخانه‌ها / ابزارهای کلیدی | توضیح مختصر کاربرد |
| :--- | :--- | :--- |
| **🚀 توسعه وب (Backend)** | `Laravel`, `Symfony`, `CodeIgniter`, `Slim`, `Laminas` (Zend) | ساخت API، وب‌اپلیکیشن‌های مقیاس‌پذیر، MVC، میکروسرویس‌ها |
| **🗄️ پایگاه داده و ORM** | `Eloquent` (Laravel), `Doctrine` (Symfony), `Propel`, `RedBeanPHP` | مدل‌سازی داده، ارتباط با دیتابیس‌های SQL (MySQL، PostgreSQL، SQLite) |
| **✅ اعتبارسنجی و فرم** | `Respect/Validation`, `Symfony Validator`, `Laravel Validation` | اعتبارسنجی ورودی کاربر، امنیت فرم‌ها، جلوگیری از XSS و SQL Injection |
| **🔐 احراز هویت و امنیت** | `Laravel Sanctum`, `Laravel Passport`, `Symfony Security`, `PHPass` | احراز هویت (JWT، OAuth، Session)، رمزنگاری رمزها، مدیریت نقش‌ها |
| **📧 ایمیل و پیام‌رسانی** | `PHPMailer`, `SwiftMailer`, `Symfony Mailer`, `Laravel Notification` | ارسال ایمیل، نوتیفیکیشن پیامکی، اعلان‌های درون برنامه |
| **🖼️ پردازش فایل و تصویر** | `Intervention Image`, `GD Library`, `Imagick`, `League/Flysystem` | رفع‌اندازی تصاویر، آپلود فایل، ذخیره در ابر (AWS S3، SFTP) |
| **🧪 تست و تضمین کیفیت** | `PHPUnit`, `Pest`, `Codeception`, `Behat`, `Mockery` | تست واحد، یکپارچگی، BDD، تست API و مرورگر |
| **🔧 ابزارهای خط فرمان (CLI)** | `Laravel Artisan`, `Symfony Console`, `Composer`, `Bash wrapper` | ساخت اسکریپت‌های خودکار، مدیریت دیتابیس، تولید کد، اجرای مهاجرت |
| **📊 مانیتورینگ و خطاگیری** | `Laravel Telescope`, `Sentry`, `Ray`, `Whoops`, `Monolog` | اشکال‌زدایی، لاگینگ، monitoring، ردیابی خطا در production |
| **⚡ رندر سمت سرور (SSR)** | `Laravel Blade`, `Twig`, `Smarty`, `Plates` | تمپلیت‌های داینامیک، پشتیبانی از layout و partial، افزایش سرعت رندر |
| **🕸️ Web Scraping** | `Goutte`, `Symfony Panther`, `Simple HTML DOM`, `cURL` | استخراج داده از وب، تعامل با صفحات دینامیک، شبیه‌سازی مرورگر |
| **📦 مدیریت بسته و وابستگی** | `Composer`, `Phing`, `Box` (برای اپلیکیشن‌های standalone) | مدیریت کتابخانه‌ها، autoloading، versioning، بیلد خودکار |
| **☁️ استقرار و PaaS** | `Laravel Forge`, `Envoyer`, `Ploy`, `RunCloud`, `Docker` | استقرار روی سرور، مدیریت پروسه، zero downtime deployment |
| **🔄 صف و پردازش ناهمگام** | `Laravel Horizon`, `Redis`, `Beanstalkd`, `RabbitMQ` | پردازش سنگین در پس‌زمینه، ایمیل‌های انبوه، کاهش زمان پاسخ API |
| **📡 وب‌سوکت و بیدرنگ** | `Laravel Echo`, `Socket.IO` (با Node.js), `Ratchet`, `Mercure` | چت، نوتیفیکیشن لحظه‌ای، نشانگر تایپ کاربران، اعلان‌های push |
| **🏗️ میکروسرویس و API Gateway** | `Lumen`, `Symfony API Platform`, `Laravel Octane` (Swoole) | ساخت APIهای با عملکرد بالا، مدیریت ترافیک میکروسرویس‌ها |
| **📄 تولید اسناد و گزارش** | `DomPDF`, `Barryvdh/laravel-dompdf`, `PhpSpreadsheet`, `TCPDF` | تولید PDF از HTML، ساخت فایل‌های Excel/CSV، گزارش‌های تجاری |
| **🗄️ دیتابیس‌های NoSQL** | `MongoDB PHP Library`, `Predis` (Redis), `Elasticsearch PHP` | اتصال به MongoDB، Redis کش، جستجوی پیشرفته |
| **🧪 ابزارهای کد کیفیت (QA)** | `PHPStan`, `Psalm`, `Rector`, `PHP_CodeSniffer`, `PHP-CS-Fixer` | تحلیل استاتیک، بازسازی خودکار کد، یکسان‌سازی استایل، کاهش باگ |
| **🌐 بین‌المللی‌سازی (i18n)** | `Laravel Localization`, `Symfony Translation`, `gettext` | پشتیبانی از چند زبان، مدیریت فایل‌های ترجمه، تطبیق با منطقه کاربر |
| **🛒 تجارت الکترونیک** | `Laravel Cashier`, `Stripe`, `PayPal SDK`, `WooCommerce API` | درگاه پرداخت، مدیریت اشتراک، فاکتورینگ، سبد خرید |
| **🗓️ برنامه‌ریزی وظایف (Cron)** | `Laravel Task Scheduling`, `Crontab`, `EasyCron` | اجرای خودکار وظایف (بکاپ، ارسال ایمیل، تمیز کردن دیتابیس) |