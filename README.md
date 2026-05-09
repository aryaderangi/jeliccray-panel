<div align="center">

<img src="https://github.com/aryaderangi/jeliccray-panel/blob/main/preview.jpg?raw=true" width="100%" alt="Jeliccray Panel Preview"/>

# ⚡ JELICCRAY Panel Template
### Powered by [Gravityzone](https://t.me/gravityyzone)

[![Telegram](https://img.shields.io/badge/Channel-@jeliccray-0099ff?style=for-the-badge&logo=telegram)](https://t.me/jeliccray)
[![Telegram](https://img.shields.io/badge/Topic-@gravityyzone-0077cc?style=for-the-badge&logo=telegram)](https://t.me/gravityyzone)
[![GitHub](https://img.shields.io/badge/Dev-@Arjeliicc-181717?style=for-the-badge&logo=github)](https://github.com/aryaderangi)

> تمپلیت اشتراک **آبی/مشکی** با طراحی Cyberpunk برای پنل‌های Rebecca، Marzban و Pasarguard  
> راهنما هست تو خود کد و میتونید راحت شخصی‌سازی کنید ❤️

</div>

---

## 🔵 مرزبان

ابتدا قالب را با لینک زیر دانلود کنید

```bash
sudo wget -N -P /var/lib/marzban/templates/subscription/ https://raw.githubusercontent.com/aryaderangi/jeliccray-panel/main/index.html
```

سپس دستور زیر را بزنید تا تمپلیت ست شود

```bash
echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/marzban/templates/"' | sudo tee -a /opt/marzban/.env
echo 'SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"' | sudo tee -a /opt/marzban/.env
```

سپس با دستور زیر پنل خودتون رو ری‌استارت کنید

```bash
marzban restart
```

---

## 🔵 ربکا

ابتدا قالب را با لینک زیر دانلود کنید

```bash
sudo wget -N -P /var/lib/rebecca/templates/subscription/ https://raw.githubusercontent.com/aryaderangi/jeliccray-panel/main/index.html
```

سپس دستور زیر را بزنید تا تمپلیت ست شود

```bash
echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/rebecca/templates/"' | sudo tee -a /opt/rebecca/.env
echo 'SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"' | sudo tee -a /opt/rebecca/.env
```

سپس با دستور زیر پنل خودتون رو ری‌استارت کنید

```bash
rebecca restart
```

---

## 🔵 پاسارگارد

ابتدا قالب را با لینک زیر دانلود کنید

```bash
sudo wget -N -P /var/lib/pasarguard/templates/subscription/ https://raw.githubusercontent.com/aryaderangi/jeliccray-panel/main/index.html
```

سپس دستور زیر را بزنید تا تمپلیت ست شود

```bash
echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/pasarguard/templates/"' | sudo tee -a /opt/pasarguard/.env
echo 'SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"' | sudo tee -a /opt/pasarguard/.env
```

سپس با دستور زیر پنل خودتون رو ری‌استارت کنید

```bash
pasarguard restart
```

---

## ✨ ویژگی‌ها

- 🎨 تم آبی/مشکی Cyberpunk
- 🌙 پشتیبانی از تم روشن و تاریک
- 🌐 چندزبانه: فارسی، English، العربية، Русский
- 📱 کاملاً Responsive
- 📶 فونت embed شده (بدون نیاز به اینترنت)
- 📋 کپی لینک اشتراک و QR Code
- 📦 کپی همه کانفیگ‌ها با یک کلیک
- 📥 بخش دانلود اپلیکیشن‌ها

---

<div align="center">

**Made with ❤️ by [@Arjeliicc](https://github.com/aryaderangi)**  
**[Jeliccray](https://t.me/jeliccray) × [Gravityzone](https://t.me/gravityyzone)**

</div>
