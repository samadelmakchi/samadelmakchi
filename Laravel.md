# جدول جامع Laravel به همراه ابزارها، بسته‌ها و مفاهیم پیشرفته (نسخه ۲۰۲۶)

| حوزه کاربرد | بسته‌ها / ابزارهای کلیدی | توضیح مختصر کاربرد |
| :--- | :--- | :--- |
| **⚙️ هسته فریمورک (Core)** | `Laravel Framework 12.x`, `Eloquent ORM`, `Blade`, `Artisan` | MVC، مدیریت دیتابیس (ORM)، تمپلیت‌ینگ، خط فرمان برای تولید کد و مدیریت پروژه [citation:1] |
| **📡 ارتباطات بیدرنگ (Real-time)** | `Laravel Reverb`, `Laravel Echo`, `WebSockets` | وب‌سوکت اختصاصی لاراول برای نوتیفیکیشن لحظه‌ای، چت و داشبوردهای زنده بدون نیاز به سرویس‌های ثالث [citation:4][citation:8] |
| **🔐 احراز هویت و API** | `Laravel Sanctum`, `Laravel Passport`, `Jetstream`, `Fortify` | مدیریت توکن‌های API (SPA و موبایل)، سرور OAuth2، احراز هویت یکپارچه با دو مرحله‌ای و مدیریت نشست [citation:3] |
| **🧠 هوش مصنوعی (AI)** | `Laravel AI SDK`, `Toolkit`, `OpenAI` | ساخت ابزارهای هوشمند، پردازش زبان طبیعی، کدنویسی خودکار و دستیارهای مجهز به هوش مصنوعی [citation:5][citation:10] |
| **🔄 صف و پردازش ناهمگام (Queue)** | `Horizon`, `RabbitMQ`, `Redis`, `Beanstalkd` | مدیریت صف‌ها، پردازش سنگین در پس‌زمینه (ارسال ایمیل، تولید گزارش) و مانیتورینگ لحظه‌ای [citation:1] |
| **🗄️ پایگاه داده و ORM** | `Eloquent`, `Migrations`, `Seeds`, `Factories` | مدل‌سازی داده، مدیریت نسخه دیتابیس، پر کردن داده‌های آزمایشی، روابط پیشرفته (Polymorphism) |
| **🚀 استقرار و مدیریت سرور** | `Laravel Forge`, `Laravel Cloud`, `Envoyer`, `Docker` | استقرار روی VPS (AWS، DigitalOcean)، مدیریت سرور (Nginx، PHP-FPM) و استقرار بدون وقفه (Zero Downtime) [citation:1][citation:5] |
| **📊 مانیتورینگ و اشکال‌زدایی** | `Laravel Telescope`, `Laravel Pulse`, `Nightwatch`, `Ray` | مشاهده درخواست‌ها، استثناها، کوئری‌ها، مانیتورینگ عملکرد و ردیابی خطا در محیط Production [citation:1][citation:5] |
| **✅ اعتبارسنجی (Validation)** | `Form Requests`, `Laravel Precognition`, `Fluent Validation` | اعتبارسنجی ورودی، پیش‌بینی اعتبار (Live Validation) و کاهش درخواست‌های اضافی به سرور [citation:1] |
| **🖼️ پردازش فایل و تصویر** | `Laravel Filesystem`, `Intervention Image`, `Spatie Media Library` | ذخیره فایل در ابر (S3، FTP)، تغییر اندازه و فشرده‌سازی تصاویر |
| **🧪 تست و کیفیت کد** | `PHPUnit`, `Pest`, `Laravel Dusk`, `Larastan`, `Rector` | تست واحد، مرورگر (E2E)، تحلیل استاتیک و بازسازی خودکار کد برای جلوگیری از باگ [citation:2] |
| **🕸️ اسکرپینگ و Crawling** | `Goutte`, `Symfony Panther`, `Laravel Http Client` | استخراج داده از وب، شبیه‌سازی مرورگر و تعامل با صفحات دینامیک |
| **📧 ایمیل و اعلان (Notification)** | `Mail`, `Notifications`, `Mailable`, `Markdown Mails` | ارسال ایمیل، پیامک، نوتیفیکیشن دیتابیسی و پوش با قالب‌های Markdown |
| **📄 تولید PDF و گزارش** | `Spatie Laravel Pdf`, `DomPDF`, `Barryvdh/laravel-snappy` | تولید PDF از HTML، فیش‌های خرید، فاکتور و گزارش‌های تجاری [citation:6] |
| **🗓️ برنامه‌ریزی وظایف (Scheduler)** | `Task Scheduling`, `Cron`, `Horizon` | اجرای خودکار وظایف (بکاپ، پاکسازی، ارسال ایمیل‌های دوره‌ای) |
| **🔐 DevSecOps و امنیت** | `Vapor` (Serverless), `Forge`, `Falco`, `Kyverno` | امنیت در کل چرخه حیات، اسکن آسیب‌پذیری، پالیسی as code و استقرار امن [citation:1][citation:5] |
| **🌐 بسته‌های کاربردی (Packages)** | `Spatie Media Library`, `Laravel Debugbar`, `Barryvdh CORS`, `Scramble` | کتابخانه‌های جانبی برای تقویت قابلیت‌های لاراول (مدیا، اشکال‌زدایی، مستندسازی خودکار API) [citation:6] |
| **🎓 گواهی‌ها و مسیر یادگیری** | `Laracasts`, `Laravel Certified Developer`, `Livewire`, `Tailwind CSS` | منابع آموزشی، گواهینامه رسمی، ساخت اپلیکیشن‌های تعاملی با JavaScript کم [citation:1] |