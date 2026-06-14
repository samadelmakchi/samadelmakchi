# جدول جامع React به همراه کتابخانه‌ها، ابزارها و مفاهیم (نسخه ۲۰۲۶)

| حوزه کاربرد | کتابخانه‌ها / ابزارهای کلیدی | توضیح مختصر کاربرد |
| :--- | :--- | :--- |
| **⚛️ هسته و بنیان (Core)** | `React`, `React DOM`, `React Hooks` (useState, useEffect, useCallback, useMemo, useContext, useReducer) | ساخت کامپوننت، مدیریت state و lifecycle در کامپوننت‌های تابعی، رندرینگ در DOM |
| **🚀 فریمورک‌های تمام‌استک** | `Next.js`, `Remix`, `Gatsby`, `Vike` | رندر سمت سرور (SSR)، تولید سایت استاتیک (SSG)، مسیریابی مبتنی بر فایل، بهینه‌سازی SEO[citation:1][citation:7] |
| **🧭 مسیریابی (Routing)** | `React Router`, `TanStack Router`, `wouter` | مدیریت ناوبری بین صفحات، مسیرهای پویا، حفاظت از مسیرها، تاریخچه مرورگر[citation:4][citation:7] |
| **📦 مدیریت state (State Management)** | `Redux Toolkit`, `Zustand`, `Jotai`, `Recoil`, `TanStack Query`, `SWR` | state سراسری، کش سمت کلاینت، همگام‌سازی با سرور، state اتمی و مشتق شده[citation:6][citation:7] |
| **🎨 استایل و طراحی (Styling & UI)** | `Tailwind CSS`, `CSS Modules`, `Styled Components`, `Emotion`, `SCSS/SASS` | استایل‌دهی به کامپوننت‌ها، CSS-in-JS، utility-first CSS، scoped styling[citation:6][citation:7] |
| **🧩 کتابخانه‌های کامپوننت (UI Libraries)** | `Material-UI (MUI)`, `Ant Design (antd)`, `shadcn/ui`, `Chakra UI`, `Mantine`, `Semantic UI` | کامپوننت‌های آماده و قابل سفارشی‌سازی (دکمه، فرم، جدول، مودال)[citation:6][citation:7] |
| **📊 مصورسازی داده (Data Visualization)** | `Recharts`, `Victory`, `React Chartjs 2`, `Nivo`, `visx`, `AG Grid`, `TanStack Table` | نمودارهای تعاملی، جدول‌های پیشرفته با sort، filter و pagination[citation:4][citation:9] |
| **📝 فرم‌ها (Forms)** | `React Hook Form`, `Formik`, `react-final-form`, `TanStack Form` | مدیریت state فرم، اعتبارسنجی، کنترل کامپوننت‌های فرم با کارایی بالا[citation:4][citation:7] |
| **🔄 درگ اند دراپ (Drag & Drop)** | `dnd-kit`, `react-beautiful-dnd`, `react-dnd` | قابلیت کشیدن و رها کردن المان‌ها، مرتب‌سازی لیست‌ها[citation:4] |
| **🎬 انیمیشن (Animation)** | `Framer Motion`, `React Spring`, `React Transition Group`, `Auto Animate` | انیمیشن‌های روان، ورود/خروج کامپوننت‌ها، gestureها[citation:4][citation:7] |
| **🌍 بین‌المللی‌سازی (i18n)** | `react-i18next`, `FormatJS`, `LinguiJS` | ترجمه متن‌ها، پشتیبانی از چند زبان، فرمت تاریخ و اعداد[citation:4][citation:7] |
| **🖼️ پردازش تصویر و فایل** | `react-dropzone`, `react-image-crop`, `react-photo-view`, `react-pdf` | آپلود فایل با درگ اند دراپ، برش تصویر، نمایش PDF[citation:4] |
| **🗺️ نقشه (Maps)** | `react-map-gl`, `google-map-react`, `@uiw/react-amap`, `Leaflet` | نمایش نقشه، مکان‌یابی، نمایش مسیر و نشانگرها[citation:4][citation:7] |
| **🎥 ویدیو و صوتی** | `react-player`, `video.js`, `React Audio Player` | پخش ویدیو از یوتیوب، ویمیو، فایل محلی؛ کنترل پخش[citation:4] |
| **🧪 تست (Testing)** | `Jest`, `React Testing Library`, `Vitest`, `Cypress`, `Playwright`, `Puppeteer` | تست واحد، تست یکپارچگی، تست E2E، اسنپ‌شات تست[citation:1][citation:6] |
| **🛠️ ابزارهای توسعه (Dev Tools)** | `React DevTools`, `Storybook`, `React Cosmos`, `ESLint`, `Prettier` | دیباگ کردن، توسعه ایزوله کامپوننت‌ها، linting و فرمت کردن کد[citation:7] |
| **⚙️ بیلد و باندل (Build Tools)** | `Vite`, `Webpack`, `Parcel`, `esbuild`, `Create React App` | ساخت و بسته‌بندی پروژه، hot reload، بهینه‌سازی برای production[citation:1] |
| **📱 اپلیکیشن موبایل (Mobile)** | `React Native`, `Expo`, `React Native Web` | ساخت اپلیکیشن بومی iOS و Android با کد React، اشتراک کد بین وب و موبایل[citation:10] |
| **🖥️ اپلیکیشن دسکتاپ (Desktop)** | `Electron`, `Tauri`, `Neutralino.js` | ساخت اپلیکیشن دسکتاپ کراس پلتفرم با React (مثل VSCode، Discord)[citation:10] |
| **🎮 بازی و سه‌بعدی (3D & Games)** | `React Three Fiber`, `Three.js`, `React Unity WebGL`, `PixiJS` | رندرینگ سه‌بعدی در مرورگر، ساخت بازی و تجربه‌های تعاملی[citation:7] |
| **📄 تولید سند (Document Generation)** | `react-pdf`, `React Print` | تولید فایل PDF از کامپوننت‌های React، چاپ صفحات[citation:4][citation:7] |
| **⚡ برنامه‌های پیشرو وب (PWA)** | `Next.js PWA`, `Workbox`, `Vite PWA` | ساخت برنامه‌های قابل نصب، کار آفلاین، نوتیفیکیشن پوش[citation:10] |
| **🤖 هوش مصنوعی و چت (AI & Chat)** | `Vercel AI SDK`, `Ant Design X`, `LangChain.js`, `OpenAI API` | ساخت چت‌بات و دستیارهای هوشمند، استریم پاسخ‌های AI[citation:4] |
| **📧 ایمیل (Email)** | `React Email`, `MJML React` | طراحی قالب ایمیل با کامپوننت‌های React، ریسپانسیو[citation:4] |
| **🚀 استقرار (Deployment)** | `Vercel`, `Netlify`, `AWS Amplify`, `Cloudflare Pages` | استقرار خودکار اپلیکیشن‌های React، هاستینگ static و serverless[citation:1] |