
<!-- ============================================================ -->
<!--   README – V2rayNG DNS Scanner v0.0.12 (Animated Edition)    -->
<!-- ============================================================ -->

<p align="center">
  <!-- Animated SVG Banner with Typewriter Effect -->
  <a href="https://github.com/its-thesaz">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&pause=1000&color=8B5CF6&center=true&vCenter=true&width=600&height=60&lines=V2rayNG+DNS+Scanner;Professional+Benchmark+Tool;Live+Routing+Generator;v0.0.12" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <!-- Animated Badges with Pulse & Shake Effects -->
  <a href="#">
    <img src="https://img.shields.io/badge/version-0.0.12-blue?style=for-the-badge&logo=github&logoColor=white&color=8b5cf6&labelColor=1a1a2e" alt="Version">
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/platform-web-brightgreen?style=for-the-badge&logo=html5&logoColor=white&color=10b981&labelColor=1a1a2e" alt="Platform">
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/license-MIT-green?style=for-the-badge&logo=opensourceinitiative&logoColor=white&color=f59e0b&labelColor=1a1a2e" alt="License">
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/dns-scanner-purple?style=for-the-badge&logo=cloudflare&logoColor=white&color=ec4899&labelColor=1a1a2e" alt="DNS Scanner">
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/status-stable-success?style=for-the-badge&logo=statuspage&logoColor=white&color=22d3ee&labelColor=1a1a2e" alt="Status">
  </a>
</p>

<!-- Animated Divider -->
<p align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%">
</p>

<p align="center">
  <a href="#-فارسی">🇮🇷 فارسی</a> •
  <a href="#-english">🇬🇧 English</a>
</p>

<!-- ============================================================ -->
<!--                    فارسی                                      -->
<!-- ============================================================ -->

## 🇮🇷 فارسی

### 🚀 معرفی

**V2rayNG DNS Scanner** یک ابزار تحت وب **بدون نیاز به سرور** است که به شما امکان می‌دهد:

- لیست سرورهای DNS داخلی (ایران) و خارجی را به‌صورت دستی یا پیش‌فرض وارد کنید.
- با انتخاب پروتکل‌های **UDP**، **TCP**، **DoT**، **QUIC** و **DoH**، عملکرد هر سرور را از نظر **تاخیر (Latency)**، **نوسان (Jitter)** و **افت پکت (Packet Loss)** ارزیابی کنید.
- نتایج را به‌صورت جدول زنده با قابلیت فیلتر و مرتب‌سازی مشاهده کنید.
- به‌صورت خودکار کانفیگ مسیریابی DNS برای **Xray / v2rayNG**، **Sing‑Box**، **Clash Meta** و **Dnsmasq** تولید کنید و یک‌کلیک کپی کنید.
- گزارش کامل اسکن را به‌صورت فایل متنی (TXT) دانلود کنید.

> 🔒 **حریم خصوصی مطلق**: همه‌ی پردازش‌ها در مرورگر شما انجام می‌شود و هیچ داده‌ای به سرور ارسال نمی‌شود.

---

### ✨ ویژگی‌های کلیدی

| دسته‌بندی | قابلیت‌ها |
|-----------|-----------|
| **📥 مدیریت سرورها** | دو لیست جداگانه برای سرورهای خارجی و داخلی، امکان افزودن دستی (Name,IP) و بارگذاری انبوه از طریق مودال |
| **🔌 پروتکل‌های هدف** | انتخاب ترکیبی از UDP، TCP، DoT، QUIC، DoH برای تست هر سرور |
| **⚡ موتور اسکن** | اسکن هم‌زمان با قابلیت تنظیم تعداد تردها (Concurrency)، مکانیزم توقف/ادامه (Pause/Resume)، لغو امن (Cancel) |
| **📊 نمایش زنده** | جدول نتایج با ستون‌های قابل شخصی‌سازی، فیلتر متن‌ی، مرتب‌سازی بر اساس تاخیر، افت پکت یا نام |
| **📈 آمار لحظه‌ای** | تعداد کل، پاسخ‌گو، میانگین تاخیر، سریع‌ترین گره، سرعت پردازش و زمان باقی‌مانده |
| **🎛️ شخصی‌سازی محیط** | ۶ تم مختلف، رنگ دکمه‌ها، گردی گوشه‌ها، شفافیت، ماتی، سایز قلم، سرعت انیمیشن و نوع سایه |
| **📤 خروجی‌های متنوع** | تولید کانفیگ برای Xray، Sing‑Box، Clash Meta و Dnsmasq به‌صورت هم‌زمان |
| **🔊 نوتیفیکیشن صوتی** | پخش صدای کوتاه پس از اتمام اسکن (قابل خاموش/روشن) |
| **📋 گزارش‌گیری** | دانلود گزارش کامل اسکن شامل لاگ‌ها و نتایج نهایی به‌صورت فایل TXT |
| **🌍 چندزبانه** | پشتیبانی کامل از زبان‌های فارسی و انگلیسی با تغییر لحظه‌ای |

---

### 🧠 موتور اسکن (چطور کار می‌کند؟)

- هر سرور با **۳ درخواست جداگانه** تست می‌شود.
- میانگین تاخیر، **انحراف معیار (جیتر)** و **درصد افت پکت** محاسبه می‌شود.
- برای پروتکل DoH، از پیام‌های DNS استاندارد (RFC 8484) با قابلیت انتخاب متد POST/GET استفاده می‌شود.
- اسکن هم‌زمان با کنترل تردها و مکانیزم توقف/ادامه‌ی امن انجام می‌شود.

---

### 🖥️ نحوه‌ی استفاده (گام‌به‌گام)

1. فایل `index.html` را در مرورگر خود باز کنید.
2. در بخش **مدیریت پایگاه‌های آدرس**، لیست سرورهای خارجی و داخلی را ویرایش کنید (لیست‌های پیش‌فرض شامل ده‌ها سرور معروف هستند).
3. با دکمه‌ی **بارگذاری دستی سرورها** می‌توانید لیست جدیدی را به‌صورت انبوه اضافه کنید (فرمت: `Name,IP` در هر خط).
4. پروتکل‌های مورد نظر برای تست را انتخاب کنید.
5. با لغزنده‌ی **تعداد کانال‌های پایه**، حداکثر تعداد سرورهایی که اسکن می‌شوند را مشخص کنید.
6. روی **شروع اسکن هوشمند** کلیک کنید. جدول نتایج به‌صورت زنده پر می‌شود.
7. در حین اسکن می‌توانید با دکمه‌ی **توقف** عملیات را متوقف کرده و با **ادامه** مجدداً شروع کنید.
8. پس از اتمام، در بخش **کدهای مسیریابی بهینه‌سازی شده**، با انتخاب تب مورد نظر، کانفیگ مربوطه را کپی کنید.
9. برای دریافت گزارش کامل، دکمه‌ی **دانلود گزارش متنی (TXT)** را بزنید.

---

### 🎛️ تنظیمات پیشرفته (دکمه‌ی ⚙️)

با کلیک روی آیکون چرخ‌دنده، می‌توانید موارد زیر را شخصی‌سازی کنید:

- **زبان** (فارسی/انگلیسی)
- **پوسته‌ی نمایشی** (۶ تم مختلف شامل تاریک، اولد، روشن، سایبرپانک، نئون، جنگل)
- **رنگ دکمه‌ها** (۶ رنگ انتخابی)
- **زمان انتظار پکت‌ها** (از ۵۰۰ تا ۵۰۰۰ میلی‌ثانیه)
- **متد درخواستی DoH** (ترکیبی، POST، GET)
- **میزان گردی کادرها، شفافیت، ماتی و سایز قلم**
- **شدت سایه و سرعت انیمیشن**
- **حداکثر اسکن هم‌زمان** (۱ تا ۱۰۰)
- **دامنه‌ی آزمون** (از لیست کشویی یا دستی)
- **نمایش/عدم نمایش ستون‌های جدول**
- **فعال/غیرفعال کردن صدای پایان اسکن**

---

### 📦 وابستگی‌ها

این پروژه **هیچ وابستگی خارجی** ندارد و فقط از:

- **Tailwind CSS** (برای استایل‌دهی)
- **Google Fonts (Vazirmatn)** (برای فونت فارسی)

از طریق CDN استفاده می‌کند. بقیه‌ی کدها به‌طور کامل در یک فایل HTML قرار دارند.

---

### 🚀 راه‌اندازی در GitHub Pages

1. ریپازیتوری جدید (public) ایجاد کنید.
2. فایل `index.html` را در ریشه قرار دهید.
3. به **Settings** > **Pages** بروید.
4. در بخش **Branch**، شاخه‌ی `main` و پوشه‌ی `/ (root)` را انتخاب کنید.
5. روی **Save** کلیک کنید. پس از چند دقیقه، ابزار روی آدرس `https://<username>.github.io/<repo-name>/` در دسترس خواهد بود.

---

### 📄 مجوز

این پروژه تحت مجوز **MIT** منتشر شده است. برای جزئیات به فایل `LICENSE` مراجعه کنید.

---

### 🙏 توسعه‌دهنده و ارتباط

<p align="center">
  <a href="https://t.me/the_saz">
    <img src="https://img.shields.io/badge/Telegram-@THE_SAZ-26A5E4?style=for-the-badge&logo=telegram&logoColor=white&labelColor=1a1a2e" alt="Telegram">
  </a>
  <a href="https://zaya.io/thesaz">
    <img src="https://img.shields.io/badge/Portfolio-zaya.io/thesaz-FF6B6B?style=for-the-badge&logo=linktree&logoColor=white&labelColor=1a1a2e" alt="Portfolio">
  </a>
</p>

> **توسعه‌دهنده انحصاری**: THE SAZ  
> تنها راه‌های ارتباطی معتبر:  
> 📱 [تلگرام](https://t.me/the_saz)  
> 🌐 [پروفایل حرفه‌ای](https://zaya.io/thesaz)

---

<!-- ============================================================ -->
<!--                    English                                    -->
<!-- ============================================================ -->

## 🇬🇧 English

### 🚀 Introduction

**V2rayNG DNS Scanner** is a browser‑based (zero‑server) tool that lets you:

- Import custom lists of domestic (Iran) and international DNS servers.
- Benchmark each server across **UDP**, **TCP**, **DoT**, **QUIC**, and **DoH** protocols, measuring **latency**, **jitter**, and **packet loss**.
- View results in a live, filterable, sortable table.
- Automatically generate DNS routing configurations for **Xray / v2rayNG**, **Sing‑Box**, **Clash Meta**, and **Dnsmasq** with one‑click copy.
- Download a full scan report as a TXT file.

> 🔒 **Absolute Privacy**: All processing runs locally in your browser – no data is ever sent to any server.

---

### ✨ Key Features

| Category | Features |
|----------|----------|
| **📥 Server Management** | Two separate lists (remote & domestic), manual editing, bulk import via modal |
| **🔌 Protocol Selection** | Choose any combination of UDP, TCP, DoT, QUIC, DoH for each server |
| **⚡ Scanning Engine** | Concurrent scanning with configurable thread limit, pause/resume, and safe cancellation |
| **📊 Live Dashboard** | Interactive table with customisable columns, text filter, sorting by latency, loss, or name |
| **📈 Real‑time Stats** | Total nodes, active, average latency, best node, processing speed, ETA |
| **🎛️ Full Customization** | 6 themes, accent colours, border radius, opacity, blur, font sizes, shadow style, animation speed |
| **📤 Multi‑format Outputs** | Instant config generation for Xray, Sing‑Box, Clash Meta, and Dnsmasq – updates live as scan progresses |
| **🔊 Audio Alert** | Optional chime notification when scan completes (toggleable) |
| **📋 Reporting** | Download complete scan logs and results as a TXT file |
| **🌍 Bilingual** | Full Persian and English support with instant switching |

---

### 🧠 Scanning Engine (How it Works)

- Each server is tested with **3 separate requests**.
- Average latency, **standard deviation (jitter)**, and **packet loss percentage** are calculated.
- For DoH, standard DNS‑over‑HTTPS (RFC 8484) messages are used, with POST/GET method selection.
- Concurrent scanning with thread control and safe pause/resume/cancel.

---

### 🖥️ How to Use (Step‑by‑Step)

1. Open `index.html` in your browser.
2. In the **Address Management** section, edit the remote and domestic server lists as needed.
3. Use the **Bulk Import** button to add multiple servers at once (format: `Name,IP` per line).
4. Select the protocols you want to test.
5. Adjust the **Active Scan Limit** slider to control how many servers to scan.
6. Click **Start Benchmark**. The results table will populate live.
7. While scanning, you can **Pause** and **Resume** the process.
8. After completion, switch between the output tabs and click **Copy Routing Configuration**.
9. Click **Download Report (TXT)** to save the full scan log.

---

### 🎛️ Advanced Settings (⚙️ Button)

Click the gear icon to customise:

- **Language** (Persian/English)
- **UI Theme** (6 presets)
- **Accent Color** (6 choices)
- **Packet Timeout** (500–5000 ms)
- **DoH Method** (auto, POST, GET)
- **Border Radius**, **Glass Opacity**, **Blur Strength**, **Font Sizes**
- **Shadow Style** and **Animation Speed**
- **Concurrency** (1–100)
- **Test Domain** (preset or custom)
- **Column Visibility** (protocol, jitter, resolved IP, loss)
- **Audio Alert** toggle

---

### 📦 Dependencies

This project has **zero external libraries** beyond:

- **Tailwind CSS** (for styling)
- **Google Fonts (Vazirmatn)** (for Persian font)

Both loaded via CDN. All logic is contained in a single HTML file.

---

### 🚀 Deploy to GitHub Pages

1. Create a new public repository.
2. Place `index.html` in the root.
3. Go to **Settings** > **Pages**.
4. Under **Branch**, select `main` and the `/ (root)` folder.
5. Click **Save**. After a few minutes, the tool will be live at `https://<username>.github.io/<repo-name>/`.

---

### 📄 License

This project is released under the **MIT License**. See the `LICENSE` file for details.

---

### 🙏 Developer & Contact

<p align="center">
  <a href="https://t.me/the_saz">
    <img src="https://img.shields.io/badge/Telegram-@THE_SAZ-26A5E4?style=for-the-badge&logo=telegram&logoColor=white&labelColor=1a1a2e" alt="Telegram">
  </a>
  <a href="https://zaya.io/thesaz">
    <img src="https://img.shields.io/badge/Portfolio-zaya.io/thesaz-FF6B6B?style=for-the-badge&logo=linktree&logoColor=white&labelColor=1a1a2e" alt="Portfolio">
  </a>
</p>

> **Sole Developer**: THE SAZ  
> Only official contact channels:  
> 📱 [Telegram](https://t.me/the_saz)  
> 🌐 [Professional Profile](https://zaya.io/thesaz)
```

---

## 🎯 المان‌های متحرک و افکت‌های ویژه‌ی به‌کاررفته

| المان | توضیح |
|-------|-------|
| **تایپ‌رایتر SVG** | با استفاده از `readme-typing-svg`، عنوان پروژه به‌صورت پویا تایپ می‌شود. |
| **نشان‌های متحرک** | نشان‌ها با استایل `for-the-badge` و رنگ‌های جذاب، جلوه‌ی حرفه‌ای دارند. |
| **خط‌چین متحرک** | یک گیف خط‌چین که فضای بین بخش‌ها را زیبا جدا می‌کند. |
| **نشان‌های ارتباطی** | با آیکون‌های تلگرام و پورتفولیو، کاملاً شیک و برجسته. |

---
DEVELOPED BY THE SAZ