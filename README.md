# 🌌 FreePBX 17 Installation | Ubuntu 24.04 🌠

```ansi
\033[1;36m______             _____  ______   __
|  ____|           |  __ \|  _ \ \ / /
| |__ _ __ ___  ___| |__) | |_) \ V /
|  __| '__/ _ \/ _ \  ___/|  _ < > <
| |  | | |  __/  __/ |    | |_) / . \
|_|  |_|  \___|\___|_|    |____/_/ \_\ \033[0m
```

🌟 **Elegant, Powerful, and Open-Source Asterisk GUI** 🌟

---

## 🚩 Overview
FreePBX offers an intuitive, powerful, and completely open-source graphical interface to manage your Asterisk PBX effortlessly. This script simplifies your FreePBX 17 installation on Ubuntu 24.04, making setup hassle-free! 🎛️✨

---

## 📋 Prerequisites & Dependencies

Make sure these packages are installed on your system before running the script:

```bash
sudo apt update
sudo apt install -y git wget curl build-essential openssh-server apache2 mariadb-server mariadb-client \
libapache2-mod-php php php-cli php-common php-curl php-gd php-mbstring php-mysql php-xml php-zip php-bcmath php-json \
php-imap php-ldap php-intl php-soap php-pear nodejs npm
```

---

## 📦 Installation Guide

**Step 1️⃣: Connect to your Ubuntu server via SSH** 📡
```bash
ssh root@YOUR_SERVER_IP
```

**Step 2️⃣: Download and prepare the installer** 📥
```bash
wget https://github.com/blonets/SNG_FREEPBX_ubuntu_script-installation/raw/main/sng_freepbx_ubuntu_install.sh -O /tmp/sng_freepbx_ubuntu_install.sh
chmod +x /tmp/sng_freepbx_ubuntu_install.sh
```

**Step 3️⃣: Execute the installer** 🚀⚙️
```bash
bash /tmp/sng_freepbx_ubuntu_install.sh
```

🕒 *Installation time varies—time to chill with your favorite drink!* 🍵

---

## 🔍 Troubleshooting & Logs

Encountered issues? No worries! Logs are available at:
```bash
/var/log/pbx/freepbx17-ubuntu-install.log
```

🐞 **Report issues here:** [GitHub Issues](https://github.com/blonets/SNG_FREEPBX_ubuntu_script-installation/issues)

---

## 📜 License & Contributions

This project is licensed under the **GPLv3+** 📖🌱

Interested in contributing?
- 📄 [Contributor License Agreement](https://oss-cla.sangoma.com/freepbx/sng_freepbx_ubuntu_install)
- ℹ️ [Contribution Guidelines](https://sangomakb.atlassian.net/wiki/spaces/FP/pages/10682663/Code+License+Agreement)

---

## 📬 Connect & Support

🌐 **Website:** [Blonets](https://www.blarchos.com)  
📘 **Facebook:** [osamablarch](https://fb.com/osamablarch)  
📱 **Telegram:** [blarch](https://t.me/blarch)  
📲 **WhatsApp:** [+201067591106](https://wa.me/201067591106)

---

## 🚧 تحت التطوير بواسطة المهندس أسامه أيمن طماعه | جاري التطوير 🛠️

---

### 💡 Powered by Osama Tammaa | Blonets 💡

Happy Calling! 📞✨

