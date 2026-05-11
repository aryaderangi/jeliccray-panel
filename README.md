<div align="center">

<img src="https://github.com/aryaderangi/gravityzone-panel/blob/main/preview.jpg?raw=true" width="100%" alt="GravityZone Panel Preview"/>

# ⚡ GRAVITYZONE Panel Template
### Powered by [GravityZone](https://t.me/gravityyzone)

[![Telegram](https://img.shields.io/badge/Channel-@gravityyzone-0099ff?style=for-the-badge&logo=telegram)](https://t.me/gravityyzone)
[![Telegram](https://img.shields.io/badge/Community-@gravityyzone-0077cc?style=for-the-badge&logo=telegram)](https://t.me/gravityyzone)
[![GitHub](https://img.shields.io/badge/Dev-@aryaderangi-181717?style=for-the-badge&logo=github)](https://github.com/aryaderangi)

> تمپلیت اشتراک **آبی/مشکی** با طراحی Cyberpunk برای پنل‌های Rebecca، Marzban و Pasarguard  
> راهنما داخل خود کد قرار گرفته و به‌راحتی قابل شخصی‌سازی است ⚡

</div>

---

## 🔵 مرزبان

ابتدا قالب را با لینک زیر دانلود کنید

```bash
sudo wget -N -P /var/lib/marzban/templates/subscription/ https://raw.githubusercontent.com/aryaderangi/gravityzone-panel/main/index.html

سپس دستور زیر را بزنید تا تمپلیت ست شود

echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/marzban/templates/"' | sudo tee -a /opt/marzban/.env
echo 'SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"' | sudo tee -a /opt/marzban/.env

سپس با دستور زیر پنل خود را ری‌استارت کنید

marzban restart


---

🔵 ربکا

ابتدا قالب را با لینک زیر دانلود کنید

sudo wget -N -P /var/lib/rebecca/templates/subscription/ https://raw.githubusercontent.com/aryaderangi/gravityzone-panel/main/index.html

سپس دستور زیر را بزنید تا تمپلیت ست شود

echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/rebecca/templates/"' | sudo tee -a /opt/rebecca/.env
echo 'SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"' | sudo tee -a /opt/rebecca/.env

سپس با دستور زیر پنل خود را ری‌استارت کنید

rebecca restart


---

🔵 پاسارگارد

ابتدا قالب را با لینک زیر دانلود کنید

sudo wget -N -P /var/lib/pasarguard/templates/subscription/ https://raw.githubusercontent.com/aryaderangi/gravityzone-panel/main/index.html

سپس دستور زیر را بزنید تا تمپلیت ست شود

echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/pasarguard/templates/"' | sudo tee -a /opt/pasarguard/.env
echo 'SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"' | sudo tee -a /opt/pasarguard/.env

سپس با دستور زیر پنل خود را ری‌استارت کنید

pasarguard restart


---

✨ ویژگی‌ها

🎨 تم Cyberpunk آبی/مشکی

🌙 پشتیبانی از Dark & Light Mode

🌐 چندزبانه: فارسی، English، العربية، Русский

📱 طراحی کاملاً Responsive

📶 فونت Embed شده بدون نیاز به اینترنت

📋 کپی لینک اشتراک + QR Code

📦 کپی همه کانفیگ‌ها با یک کلیک

📥 دانلود مستقیم اپلیکیشن‌ها

⚡ رابط کاربری Glassmorphism

🚀 افکت‌های Neon و Animated UI



---

<div align="center">Made with ❤️ by @aryaderangi
GravityZone

</div>
```