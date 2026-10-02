⚡ PabloPanel

🎮 Dark Neon VPN Control Panel — Built for Gaming

PabloPanel یک پنل مدیریت VPN با رابط کاربری مدرن Dark Neon Blue است؛ ساخته شده برای مدیریت ساده کاربران، ترافیک، Subscription و کانفیگ‌ها.

«🚀 Fork → Deploy on Railway → Expose port "8080" → Open PabloPanel

چند مرحله ساده و پنل آماده استفاده است.»

---

✨ Features

| 
👤 User Management| ساخت و مدیریت کاربران
📊 Traffic Statistics| نمایش مصرف و باقی‌مانده ترافیک
⏳ Expiration| نمایش زمان باقی‌مانده اشتراک
🔗 Subscription| لینک Subscription اختصاصی برای هر کاربر
📦 Config Management| نمایش تمام کانفیگ‌های کاربر
📋 Copy Config| کپی سریع کانفیگ‌ها
📋 Copy All| کپی تمام کانفیگ‌ها با یک کلیک
📱 QR Code| ساخت QR برای هر کانفیگ
🎨 Neon UI| رابط کاربری Dark Neon Blue
📱 Responsive| مناسب موبایل و دسکتاپ
🚂 Railway Ready| آماده Deploy روی Railway

---

🖥️ Dashboard

پنل مدیریت شامل بخش‌های اصلی برای مدیریت کاربران و مشاهده وضعیت سرویس است.

Dashboard

- تعداد کل کاربران
- کاربران فعال
- حجم کل ترافیک
- میزان مصرف
- وضعیت سرور
- نمودار مصرف
- مدیریت کاربران

---

👤 Users

برای هر کاربر می‌توانید اطلاعات زیر را مدیریت کنید:

Username
Status
Traffic Limit
Used Traffic
Remaining Traffic
Expiration
Subscription
Configs

همچنین امکان فعال/غیرفعال کردن و حذف کاربر وجود دارد.

---

🔗 Subscription

هر کاربر یک صفحه Subscription اختصاصی دریافت می‌کند.

صفحه Subscription شامل:

Username
Total Traffic
Used Traffic
Remaining Traffic
Days Left
Subscription Link
Configs

و امکانات:

COPY SUBSCRIPTION
OPEN WEB
COPY ALL
COPY CONFIG
QR CODE

را در اختیار کاربر قرار می‌دهد.

---

🚀 Deploy on Railway

راه‌اندازی PabloPanel روی Railway بسیار ساده است.

1. Fork

ابتدا این Repository را Fork کنید تا یک نسخه از پروژه داخل GitHub خودتان داشته باشید.

---

2. Railway

وارد Railway شوید و یک پروژه جدید ایجاد کنید:

New Project
      ↓
Deploy from GitHub Repo
      ↓
Select your fork
      ↓
Deploy

Railway پروژه را Build و اجرا می‌کند.

---

3. Generate Domain

بعد از Deploy شدن:

Settings
   ↓
Networking
   ↓
Generate Domain

را انتخاب کنید.

Railway برای شما یک Domain ایجاد می‌کند.

---

4. Port

PabloPanel روی پورت زیر اجرا می‌شود:

8080

بنابراین پورت سرویس را روی:

8080

قرار دهید.

«⚠️ فقط پورت "8080" برای دسترسی به پنل استفاده می‌شود.»

---

5. Open PabloPanel

بعد از ساخته شدن Domain، آن را باز کنید.

مثلاً:

https://your-panel.up.railway.app

صفحه Login نمایش داده می‌شود.

---

🔐 Default Login

اطلاعات ورود پیش‌فرض:

Username: admin
Password: admin

«⚠️ توصیه می‌شود بعد از اولین ورود، رمز عبور پیش‌فرض را تغییر دهید.»

---

🇮🇷 آموزش نصب فارسی

اگر با Railway آشنایی ندارید، نگران نباشید؛ مراحل خیلی ساده است.

مرحله ۱ — Fork

در بالای صفحه GitHub روی:

Fork

بزنید.

با این کار پروژه وارد GitHub شما می‌شود.

---

مرحله ۲ — Railway

وارد Railway شوید.

یک پروژه جدید بسازید و گزینه:

Deploy from GitHub Repo

را انتخاب کنید.

Repository مربوط به PabloPanel که Fork کرده‌اید را انتخاب کنید.

---

مرحله ۳ — Deploy

روی Deploy بزنید و صبر کنید تا پروژه Build شود.

وقتی Deploy با موفقیت انجام شد، سرویس شما Online می‌شود.

---

مرحله ۴ — Domain

وارد:

Settings → Networking

شوید.

سپس:

Generate Domain

را بزنید.

---

مرحله ۵ — Port

پورت پروژه را روی:

8080

قرار دهید.

---

مرحله ۶ — ورود

حالا Domain ساخته‌شده را باز کنید.

در صفحه Login از اطلاعات زیر استفاده کنید:

Username
admin

Password
admin

🎉 تمام شد!

حالا PabloPanel شما آماده استفاده است.

---

⚙️ Project Structure

PabloPanel/
│
├── static/
│   └── ...
│
├── templates/
│   ├── login.html
│   ├── dashboard.html
│   └── subscription.html
│
├── app.py
├── Dockerfile
├── requirements.txt
└── README.md

---

🛠️ Configuration

پروژه برای اجرای ساده روی Railway طراحی شده است.

پورت اصلی:

8080

است.

ساختار پروژه به شکلی است که می‌توانید ظاهر پنل، Dashboard و Subscription را مطابق نیاز خودتان تغییر دهید.

---

🎮 Gaming UI

PabloPanel با تمرکز روی یک رابط کاربری مدرن و گیمینگ طراحی شده است.

ویژگی‌های ظاهری:

- 🌌 Dark Background
- 🔵 Neon Blue
- 💠 Glass Cards
- ⚡ Neon Effects
- 📱 Mobile Friendly
- 🎮 Gaming Style

---

📱 Mobile Friendly

پنل برای نمایش روی موبایل نیز بهینه شده است.

بنابراین کاربران می‌توانند Subscription خود را مستقیماً با گوشی باز کنند و:

مشاهده مصرف
مشاهده زمان باقی‌مانده
کپی کانفیگ
دریافت QR
کپی Subscription

را انجام دهند.

---

❤️ Credits

Created with ❤️ for the PabloPanel project.

⚡ PabloPanel

Dark • Neon • Gaming • Simple

---

⭐ Support

اگر PabloPanel برای شما مفید بود، می‌توانید Repository را ⭐ Star کنید.

برای گزارش مشکل یا پیشنهاد قابلیت جدید نیز می‌توانید از بخش Issues استفاده کنید.
