⚡ PabloPanel

🎮 Dark Neon Gaming VPN Control Panel

PabloPanel یک پنل مدیریت VPN با طراحی مدرن Dark Neon Blue است که برای مدیریت کاربران، ترافیک، کانفیگ‌ها و Subscription طراحی شده است.

پنل دارای رابط کاربری ریسپانسیو و مناسب موبایل و دسکتاپ است و بخش Subscription اختصاصی برای هر کاربر دارد.

---

✨ Features

- 🎮 Dark Neon Gaming UI
- 📱 Responsive Design
- 👤 User Management
- 📊 Traffic Usage Statistics
- 📦 Traffic Limit Management
- ⏳ Subscription Expiration
- 🔗 Personal Subscription Link
- 📋 Copy Config
- 📋 Copy All Configs
- 📱 QR Code برای کانفیگ‌ها
- ⚡ Live User Status
- 🌐 Railway Deployment
- 🔐 Admin Login
- 💎 اختصاصی‌سازی کامل پنل
- 🎨 PabloPanel Branding

---

🚀 Deploy on Railway

راه‌اندازی PabloPanel بسیار ساده است.

فقط چند مرحله زیر را انجام دهید:

1️⃣ Fork کردن پروژه

ابتدا روی دکمه Fork در بالای همین صفحه کلیک کنید تا پروژه داخل GitHub شما کپی شود.

---

2️⃣ ساخت پروژه در Railway

وارد Railway شوید و یک پروژه جدید بسازید.

سپس:

New Project
↓
Deploy from GitHub Repo
↓
انتخاب Repository
↓
Deploy

Railway پروژه را به صورت خودکار Build و Deploy می‌کند.

---

3️⃣ ساخت Domain

بعد از Deploy شدن پروژه وارد تنظیمات سرویس شوید.

از قسمت:

Settings
↓
Networking
↓
Generate Domain

یک Domain برای پنل ایجاد کنید.

---

4️⃣ تنظیم Port

پورت پنل:

8080

است.

بنابراین سرویس Railway باید روی پورت 8080 اجرا شود.

---

5️⃣ ورود به پنل

بعد از Deploy شدن، Domain ساخته‌شده توسط Railway را باز کنید.

صفحه Login برای شما نمایش داده می‌شود.

🔐 اطلاعات ورود پیش‌فرض

Username: admin
Password: admin

«⚠️ بعد از اولین ورود، حتماً رمز پیش‌فرض را تغییر دهید.»

---

🇮🇷 آموزش فارسی

اگر برای اولین بار است که با Railway کار می‌کنید، مراحل زیر را انجام دهید:

مرحله اول

Repository را Fork کنید.

یعنی پروژه را به GitHub خودتان منتقل کنید.

---

مرحله دوم

وارد Railway شوید و از قسمت:

New Project

گزینه:

Deploy from GitHub Repo

را انتخاب کنید.

Repository که Fork کرده‌اید را انتخاب کنید.

---

مرحله سوم

منتظر بمانید تا Railway پروژه را Build و Deploy کند.

اگر Build با موفقیت انجام شود، سرویس شما Online می‌شود.

---

مرحله چهارم

به قسمت Networking بروید و یک Domain بسازید.

پورت پروژه را روی:

8080

قرار دهید.

---

مرحله پنجم

Domain ساخته‌شده را داخل مرورگر باز کنید.

مثلاً:

https://your-panel.up.railway.app

سپس با اطلاعات زیر وارد شوید:

Username: admin
Password: admin

---

🎉 تمام شد!

حالا PabloPanel شما آماده استفاده است.

می‌توانید:

- 👤 کاربر جدید بسازید
- 📊 مصرف ترافیک کاربران را مشاهده کنید
- ⏳ مدت اعتبار کاربران را مدیریت کنید
- 🔗 Subscription کاربران را دریافت کنید
- 📋 کانفیگ‌ها را کپی کنید
- 📱 QR Code کانفیگ‌ها را دریافت کنید
- 🌐 لینک Subscription را در اختیار کاربر قرار دهید

---

📱 Subscription Panel

هر کاربر می‌تواند صفحه Subscription اختصاصی خودش را داشته باشد.

در این صفحه اطلاعاتی مانند:

Username
Total Traffic
Used Traffic
Remaining Traffic
Days Left
Number of Configs
Subscription Link

نمایش داده می‌شود.

همچنین کاربر می‌تواند کانفیگ‌ها را مستقیماً Copy کند یا QR Code آن‌ها را دریافت کند.

---

🛠️ Project Structure

ساختار اصلی پروژه:

PabloPanel/
│
├── static/
│
├── templates/
│
├── app.py
├── Dockerfile
├── requirements.txt
└── README.md

---

🌐 Railway

PabloPanel برای اجرای ساده روی Railway آماده شده است.

پورت اصلی:

8080

است.

---

💙 Support

اگر از پروژه استفاده کردید و پروژه برای شما مفید بود، می‌توانید Repository را ⭐ Star کنید.

اگر مشکلی پیدا کردید، از قسمت Issues گیت‌هاب گزارش دهید.

---

⚡ PabloPanel

Dark. Fast. Simple.

🎮 Built for Gaming & VPN Management.
