<div align="center">

<img src="https://github.com/aryaderangi/gravityzone-panel/blob/main/preview.jpg?raw=true" width="100%" alt="GravityZone Panel Preview"/>

# ⚡ GRAVITYZONE Panel Template
### Powered by GravityZone

[![Telegram](https://img.shields.io/badge/Channel-@gravityyzone-0099ff?style=for-the-badge&logo=telegram)](https://t.me/gravityyzone)
[![GitHub](https://img.shields.io/badge/Dev-@aryaderangi-181717?style=for-the-badge&logo=github)](https://github.com/aryaderangi)

> تمپلیت اشتراک Cyberpunk برای Marzban / Rebecca / Pasarguard

</div>

---

# 🔵 Marzban

## دانلود تمپلیت

```bash
sudo mkdir -p /var/lib/marzban/templates/subscription/

sudo wget -O /var/lib/marzban/templates/subscription/index.html \
https://raw.githubusercontent.com/aryaderangi/gravityzone-panel/main/index.html
```

## ست کردن تمپلیت

```bash
echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/marzban/templates/"' | sudo tee -a /opt/marzban/.env

echo 'SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"' | sudo tee -a /opt/marzban/.env
```

## ری‌استارت

```bash
marzban restart
```

---

# 🔵 Rebecca

## دانلود تمپلیت

```bash
sudo mkdir -p /var/lib/rebecca/templates/subscription/

sudo wget -O /var/lib/rebecca/templates/subscription/index.html \
https://raw.githubusercontent.com/aryaderangi/gravityzone-panel/main/index.html
```

## ست کردن تمپلیت

```bash
echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/rebecca/templates/"' | sudo tee -a /opt/rebecca/.env

echo 'SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"' | sudo tee -a /opt/rebecca/.env
```

## ری‌استارت

```bash
rebecca restart
```

---

# 🔵 Pasarguard

## دانلود تمپلیت

```bash
sudo mkdir -p /var/lib/pasarguard/templates/subscription/

sudo wget -O /var/lib/pasarguard/templates/subscription/index.html \
https://raw.githubusercontent.com/aryaderangi/gravityzone-panel/main/index.html
```

## ست کردن تمپلیت

```bash
echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/pasarguard/templates/"' | sudo tee -a /opt/pasarguard/.env

echo 'SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"' | sudo tee -a /opt/pasarguard/.env
```

## ری‌استارت

```bash
pasarguard restart
```

---

# ✨ Features

- 🎨 Cyberpunk UI
- 🌙 Dark / Light Mode
- 🌐 Multi Language
- 📱 Fully Responsive
- 📋 Copy Subscription Link
- 📦 Copy All Configs
- 📥 Apps Downloader
- ⚡ Neon Effects
- 🚀 Glassmorphism Design

---

<div align="center">

Made with ❤️ by Arya Derangi  
GravityZone

</div>