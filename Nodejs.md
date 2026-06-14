# جدول جامع کاربردهای Node.js به همراه کتابخانه‌ها و ابزارها (نسخه ۲۰۲۶)

| حوزه کاربرد | کتابخانه‌ها / ابزارهای کلیدی | توضیح مختصر کاربرد |
| :--- | :--- | :--- |
| **🚀 توسعه وب (Backend)** | `Express.js`, `Fastify`, `NestJS`, `Koa`, `AdonisJS` | ساخت APIهای RESTful، وب‌اپلیکیشن‌های مقیاس‌پذیر، MVC، میکروسرویس‌ها [citation:4][citation:6] |
| **💬 ارتباطات بیدرنگ (Real-time)** | `Socket.IO`, `ws`, `µWebSockets` | چت، نوتیفیکیشن لحظه‌ای، بازی‌های آنلاین، همکاری زنده (مثل Google Docs) [citation:4][citation:6] |
| **🗄️ پایگاه داده و ORM/ODM** | `Prisma`, `Mongoose`, `Sequelize`, `TypeORM`, `Knex.js` | ارتباط با دیتابیس‌های SQL/NoSQL، مدل‌سازی داده، query builder [citation:6] |
| **✅ اعتبارسنجی (Validation)** | `Zod`, `Joi`, `Yup`, `class-validator` | اعتبارسنجی ورودی کاربر، تضمین امنیت، کاهش خطاهای runtime با TypeScript-first [citation:6] |
| **🔐 احراز هویت و امنیت** | `Passport.js`, `Helmet.js`, `jsonwebtoken`, `bcrypt`, `CORS` | احراز هویت (local، OAuth، JWT)، امنیت HTTP headers، رمزنگاری رمزها [citation:6] |
| **📡 اینترنت اشیا (IoT)** | `MQTT.js`, `SerialPort`, `johnny-five`, `Node-RED` | ارتباط با سنسورها، دستگاه‌های صنعتی، رباتیک، خانه هوشمند [citation:7][citation:10] |
| **🖥️ اپلیکیشن دسکتاپ (Cross-platform)** | `Electron.js`, `NW.js`, `Tauri` | ساخت اپلیکیشن دسکتاپ با HTML/CSS/JS (مثل VSCode، Slack، Discord) [citation:7] |
| **🧠 هوش مصنوعی و یادگیری ماشین** | `TensorFlow.js`, `Brain.js`, `OpenAI API`, `LangChain.js` | اجرای مدل‌های ML در Node.js، پردازش زبان طبیعی، ربات‌های هوشمند [citation:7] |
| **🎮 توسعه بازی (سرور)** | `Socket.IO`, `Colyseus`, `PlayCanvas` | ساخت سرور بازی‌های آنلاین چندنفره، مدیریت اتاق‌ها و وضعیت بازی [citation:7] |
| **🔧 ابزارهای خط فرمان (CLI)** | `Commander.js`, `Yargs`, `Inquirer.js`, `Chalk`, `Ora` | ساخت ابزارهای خودکارسازی، اسکریپت‌های deployment، CLIهای حرفه‌ای [citation:7] |
| **📊 مانیتورینگ و مشاهده‌پذیری** | `PM2`, `Winston`, `Pino`, `Bunyan`, `OpenTelemetry` | مدیریت فرآیند، لاگینگ ساختاریافته، monitoring، distributed tracing [citation:6][citation:8] |
| **⚙️ پردازش و اتوماسیون** | `Lodash`, `RxJS`, `Bull` (Queue), `Agenda` (Job scheduling) | عملیات روی آرایه/آبجکت، برنامه‌ریزی وظایف، صف‌سازی، reactive programming [citation:6] |
| **🖼️ پردازش فایل و تصویر** | `Sharp`, `Multer`, `pdfkit`, `ExcelJS`, `Node Canvas` | رفع‌اندازی تصاویر، آپلود فایل، تولید PDF/Excel، پردازش گرافیکی [citation:6] |
| **🧪 تست و تضمین کیفیت (QA)** | `Jest`, `Mocha`, `Chai`, `Supertest`, `Vitest`, `Test-It` | تست واحد، یکپارچگی، E2E، snapshot testing، تست API با پشتیبانی DOM واقعی [citation:4][citation:9] |
| **🏗️ میکروسرویس و Serverless** | `AWS Lambda`, `Google Cloud Functions`, `Azure Functions`, `Seneca` | توابع ابری بدون سرور، معماری رویدادمحور، مقیاس‌پذیری خودکار |
| **🌐 پروکسی معکوس و Gateway** | `Express Gateway`, `Fastify Gateway`, `http-proxy-middleware` | مسیریابی درخواست‌ها، rate limiting، API composition |
| **📦 مدیریت بسته و بیلد** | `npm`, `yarn`, `pnpm`, `Webpack`, `Vite`, `esbuild` | مدیریت وابستگی‌ها، bundle کردن، build و publish پکیج‌ها |
| **⚡ رندر سمت سرور (SSR)** | `Next.js`, `Nuxt.js`, `Remix`, `Angular Universal` | رندر React/Vue/Angular در سرور، بهبود SEO و سرعت بارگذاری |
| **🕸️ Web Scraping و Crawling** | `Puppeteer`, `Playwright`, `Cheerio`, `Axios` | استخراج داده از وب، تست خودکار، گرفتن اسکرین‌شات، شبیه‌سازی مرورگر |
| **📨 پیام‌رسانی و ناتیفیکیشن** | `Nodemailer`, `node-telegram-bot-api`, `discord.js`, `Slack SDK` | ارسال ایمیل، ساخت ربات تلگرام/دیسکورد، نوتیفیکیشن درون‌سازمانی |
| **🧩 توسعه پلاگین و افزونه** | `Yeoman`, `Plop.js`, `node-lumino` | تولید خودکار کد، ساخت پلاگین برای فریمورک‌ها، معماری پلاگین‌محور [citation:1] |
| **☁️ استقرار و PaaS (Self-hosted)** | `Dokploy`, `PM2`, `Docker`, `systemd`, `Forever` | استقرار روی VPS، جایگزین Vercel/Heroku، مدیریت کانتینر [citation:5] |
| **📊 DevOps و CI/CD یکپارچه** | `GitHub Actions`, `GitLab CI`, `Jenkins`, `Prometheus`, `Grafana` | ساخت لوله‌های استقرار خودکار، مانیتورینگ اپلیکیشن Node.js [citation:3][citation:8] |