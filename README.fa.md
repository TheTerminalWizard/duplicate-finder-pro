[🇮🇷 فارسی](https://github.com/TheTerminalWizard/duplicate-finder-pro/blob/main/README.fa.md) | [🇬🇧 English](https://github.com/TheTerminalWizard/duplicate-finder-pro/blob/main/README.md)

🔎 Duplicate Finder Pro

برنامه‌ای مبتنی بر Python برای پیدا کردن و مدیریت فایل‌های تکراری در اندروید، با استفاده از Termux و Termux:GUI و رابط گرافیکی.

🎯 هدف پروژه

هدف Duplicate Finder Pro این است که پیدا کردن فایل‌های تکراری و مدیریت آن‌ها را در محیط اندروید ساده‌تر کند. این پروژه از Python و ابزارهای Termux استفاده می‌کند و دارای رابط گرافیکی است.

✨ قابلیت‌ها

- 🖥️ رابط گرافیکی: کار با برنامه از طریق رابط گرافیکی.
- 🔎 پیدا کردن فایل‌های تکراری: اسکن فایل‌ها برای شناسایی نسخه‌های تکراری.
- 📂 مدیریت فایل‌ها: بررسی نتایج اسکن و انتخاب فایل‌ها.
- ⚙️ تنظیمات: امکان استفاده از تنظیمات موجود در برنامه.
- 🗑️ مدیریت حذف فایل‌ها: ابزارهای مربوط به حذف فایل‌های انتخاب‌شده.
- ♻️ بازیابی فایل‌ها: پشتیبانی از قابلیت‌های سطل زباله و بازیابی موجود در برنامه.
- 📋 گزارش‌ها: دسترسی به گزارش‌های برنامه برای بررسی عملیات.

«قابلیت‌های قابل‌استفاده ممکن است به نسخه برنامه، مجوزهای اندروید و دسترسی به مسیر فایل‌ها بستگی داشته باشند.»

📥 نصب پیش‌نیازهای Duplicate Finder Pro

مرحله ۱ — نصب برنامه‌ها

۱. نصب Termux

دانلود از F-Droid:

[Termux from F-Droid](https://f-droid.org/packages/com.termux/)

دانلود از GitHub:

[Termux from GitHub](https://github.com/termux/termux-app)

۲. نصب Termux:GUI

دانلود از F-Droid:

[Termux:GUI from F-Droid](https://f-droid.org/packages/com.termux.gui/)

دانلود از GitHub:

[Termux:GUI from GitHub](https://github.com/termux/termux-gui)

✅ هر دو برنامه باید روی دستگاه اندرویدی شما نصب باشند.

---

مرحله ۲ — نصب پکیج‌های پیش‌نیاز در Termux

Termux را باز کنید و دستورات زیر را به‌ترتیب اجرا کنید.

۱. به‌روزرسانی مخازن و پکیج‌ها

pkg update && pkg upgrade -y

۲. نصب Python

pkg install python -y

۳. بررسی نصب بودن pip

pip --version

اگر دستور "pip" پیدا نشد، پکیج مربوط به آن را نصب کنید:

pkg install python-pip -y

پس از نصب، دوباره بررسی کنید:

pip --version

۴. نصب کتابخانه موردنیاز

pip install termuxgui

این کتابخانه برای ارتباط برنامه Python با Termux:GUI موردنیاز است.

---

🔐 مجوزهای دسترسی

برای اسکن و مدیریت فایل‌ها، ممکن است لازم باشد مجوزهای دسترسی به فایل‌ها را در اندروید یا Termux تنظیم کنید. دسترسی واقعی برنامه به فایل‌ها به نسخه اندروید و مجوزهای اعطاشده بستگی دارد.

🛠️ فناوری‌های استفاده‌شده

- Python — زبان برنامه‌نویسی
- Termux — محیط اجرای ابزارها و برنامه‌های خط فرمان در اندروید
- Termux:GUI — فراهم‌کردن قابلیت‌های رابط گرافیکی برای برنامه

📄 مجوز پروژه

برای اطلاع از شرایط استفاده، تغییر و انتشار مجدد پروژه، فایل "LICENSE" موجود در مخزن را بررسی کنید.

🔗 پیوندهای پروژه

- "مخزن Duplicate Finder Pro در GitHub" (https://github.com/TheTerminalWizard/duplicate-finder-pro)
- "نسخه فارسی README" (https://github.com/TheTerminalWizard/duplicate-finder-pro/blob/main/README.fa.md)
- "نسخه انگلیسی README" (https://github.com/TheTerminalWizard/duplicate-finder-pro/blob/main/README.md)
