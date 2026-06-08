
<div dir="rtl" align="center">

# ✨ مبدل مارک‌داون (Markdown Converter) ✨

[![فارسی](https://img.shields.io/badge/lang-fa-blue.svg)](https://github.com/NarimanKhaleghi/Markdown_Converter/blob/main/README_FA.md)
[![English](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/NarimanKhaleghi/Markdown_Converter)

---

[![GitHub stars](https://img.shields.io/github/stars/NarimanKhaleghi/Markdown_Converter?style=social)](https://github.com/NarimanKhaleghi/Markdown_Converter/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/NarimanKhaleghi/Markdown_Converter?style=social)](https://github.com/NarimanKhaleghi/Markdown_Converter/forks)
[![GitHub watchers](https://img.shields.io/github/watchers/NarimanKhaleghi/Markdown_Converter?style=social)](https://github.com/NarimanKhaleghi/Markdown_Converter/watchers)
[![GitHub last commit](https://img.shields.io/github/last-commit/NarimanKhaleghi/Markdown_Converter)](https://github.com/NarimanKhaleghi/Markdown_Converter/commits/main)
[![GitHub license](https://img.shields.io/badge/license-MIT-green)](https://github.com/NarimanKhaleghi/Markdown_Converter/blob/main/LICENSE)
[![PWA](https://img.shields.io/badge/PWA-Enabled-purple)](https://md.thepm.ir)
[![TypeScript](https://img.shields.io/badge/TypeScript-96.5%25-blue)](https://www.typescriptlang.org/)
[![React](https://img.shields.io/badge/React-19.0-blue)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-6.2-green)](https://vitejs.dev/)

</div>

<div dir="rtl">

## 🌟 درباره پروژه

احتمالاً برای شما هم پیش اومده که یک متن رو از ابزارهای هوش مصنوعی کپی میکنید و ناگهان با کلی `*`، `#`، `-` و... روبه‌رو میشوید. این‌ها علائم **زبان مارک‌داون (Markdown)** هستند که هوش مصنوعی برای قالب‌بندی متن‌هاش ازش استفاده میکنه.

**مبدل مارک‌داون** یک **برنامه وب مدرن و کاملاً رایگان** هست که این مشکل رو برای همیشه حل میکنه. کافیه متن مارک‌داون خودتون رو کپی کنید، فایل مربوطه رو آپلود کنید یا حتی یک لینک به برنامه بدید تا همه کارهاتون رو تمیز و مرتب به فرمت‌های مختلف دریافت کنید.

[![لینک دسترسی به برنامه](https://img.shields.io/badge/🌐%20دسترسی%20آنلاین-md.thepm.ir-blue?style=for-the-badge)](https://md.thepm.ir)

## 🎯 قابلیت‌های کلیدی

| ویژگی | توضیحات |
|:------|:---------|
| 🔄 **تبدیل فرمت‌ها** | تبدیل فوری متن به فرمت‌های **HTML**، **Word**، **TXT** و **کپی متن خام** بدون علائم مارک‌داون |
| 📂 **ورودی‌های متنوع** | امکان کپی/پیست ساده، آپلود فایل‌های مرتبط و وارد کردن متن از طریق **لینک** |
| ✍️ **ویرایشگر مارک‌داون حرفه‌ای** | یک محیط کامل برای **نت‌نویسی (Note Taking)** با زبان مارک‌داون که مجهز به ابزارهای ویرایش است |
| 🖥️ **پیش‌نمایش زنده دو پنجره‌ای (Split View)** | در حالت دسکتاپ، می‌توانید همزمان کد مارک‌داون و خروجی نهایی را در دو پنجره مجزا ببینید |
| 📱 **واکنش‌گرا (Responsive) و PWA** | طراحی کاملاً واکنش‌گرا برای تمام دستگاه‌ها و قابلیت **نصب به عنوان یک برنامه وب پیشرفته (PWA)** برای استفاده کاملاً آفلاین |
| 🌗 **حالت شب و روز** | پشتیبانی از تم‌های روشن و تاریک برای تجربه بصری بهتر |
| 🌐 **پشتیبانی هوشمند از زبان فارسی و انگلیسی** | تشخیص خودکار جهت متن (RTL یا LTR) برای نمایش دقیق و بدون مشکل |

## ⚙️ تکنولوژی‌های به‌کار رفته

| بخش | تکنولوژی |
|:----|:----------|
| **Core Framework** | [React 19.0.1](https://reactjs.org/)  &  [TypeScript 5.8](https://www.typescriptlang.org/) |
| **Build Tool** | [Vite 6.2](https://vitejs.dev/) |
| **Styling & UI** | [Tailwind CSS 4.1](https://tailwindcss.com/) (via `@tailwindcss/vite`), [Lucide React](https://lucide.dev/), [Motion](https://motion.dev/) برای انیمیشن‌ها |
| **Markdown Processing & Export** | موتورهای سفارشی خروجی‌گیری برای HTML, Word, و TXT, [Mammoth.js](https://github.com/mwilliamson/mammoth.js) برای پردازش فایل‌های Word |
| **PWA (Progressive Web App)** | پیکربندی کامل PWA برای استفاده آفلاین و نصب روی دستگاه |
| **DevOps & Backend (برای حالت سرور)** | [Express 4.21](https://expressjs.com/) برای اجرای سرور, [dotenv](https://github.com/motdotla/dotenv), [esbuild](https://esbuild.github.io/) |
| **Testing & Linting** | TypeScript Compiler (`tsc --noEmit`) |
| **Hosting & Domain** | [GitHub Pages](https://pages.github.com/) (با تنظیمات CNAME برای دامنه `md.thepm.ir`) |

## 💻 نحوه نصب و راه‌اندازی (برای اجرای محلی)

برای اجرای پروژه روی سیستم خودتون، کافیست مراحل زیر را دنبال کنید:

1.  **پیش‌نیازها:** مطمئن شوید [Node.js](https://nodejs.org/) روی سیستم شما نصب باشد.
2.  **کلون کردن مخزن:**
    ```bash
    git clone https://github.com/NarimanKhaleghi/Markdown_Converter.git
    ```
3.  **ورود به پوشه پروژه:**
    ```bash
    cd Markdown_Converter
    ```
4.  **نصب وابستگی‌ها:**
    ```bash
    npm install
    ```
5.  **تنظیم متغیرهای محیطی (در صورت نیاز):**
    یک فایل `.env.local` در روت پروژه ایجاد کرده و کلید API خود را برای سرویس Gemini (در صورت استفاده از قابلیت‌های هوش مصنوعی) در آن قرار دهید:
    ```
    GEMINI_API_KEY="YOUR_GEMINI_API_KEY"
    ```
6.  **اجرای برنامه در حالت توسعه:**
    ```bash
    npm run dev
    ```
    برنامه روی آدرس `http://localhost:3000` در دسترس خواهد بود.

7.  **ساخت نسخه نهایی برای部署 (Deployment):**
    ```bash
    npm run build
    ```

## 📊 آمار و وضعیت مخزن

بر اساس آخرین اطلاعات دریافتی از GitHub:

*   **ستاره‌ها:** 0
*   **فورک‌ها:** 0
*   **واچرها:** 0
*   **آخرین کامیت:** [Update App.tsx](https://github.com/NarimanKhaleghi/Markdown_Converter/commit/69c0a5a3f73087884b876290aecff416a52cd93e) (8 ژوئن 2026)
*   **تعداد کامیت‌ها:** 23
*   **زبان‌های اصلی:** TypeScript (96.5%), JavaScript (1.4%), HTML (1.2%), CSS (0.9%)
*   **تعداد مشارکت‌کنندگان:** [1 مشارکت‌کننده](https://github.com/NarimanKhaleghi/Markdown_Converter/graphs/contributors) (NarimanKhaleghi)

## 🤝 مشارکت در توسعه

این پروژه با ❤️ توسعه داده شده و **کاملاً متن‌باز (Open Source)** است. اگر ایده، پیشنهاد یا بهبودی مدنظر دارید:

1.  Fork کنید
2.  Branch جدید بسازید (`git checkout -b feature/AmazingFeature`)
3.  Commit کنید (`git commit -m 'Add some AmazingFeature'`)
4.  Push کنید (`git push origin feature/AmazingFeature`)
5.  Pull Request ارسال کنید

همچنین می‌توانید با **ثبت Issue** یا **ایجاد Discussion** در صفحه مخزن، ما را در بهتر شدن این ابزار یاری کنید.

## ⭐ حمایت

اگر این پروژه براتون مفید بوده و خوشتون اومده، لطفاً با **زدن یک ستاره ⭐ در گیتهاب** از ما حمایت کنید. این کار انرژی مضاعفی برای ادامه توسعه پروژه به ما میده.

[![GitHub stars](https://img.shields.io/github/stars/NarimanKhaleghi/Markdown_Converter?style=social)](https://github.com/NarimanKhaleghi/Markdown_Converter)

---

**لینک‌های مفید:**

*   **دسترسی آنلاین به برنامه:** [md.thepm.ir](https://md.thepm.ir)
*   **مخزن پروژه در گیتهاب:** [github.com/NarimanKhaleghi/Markdown_Converter](https://github.com/NarimanKhaleghi/Markdown_Converter)

</div>
