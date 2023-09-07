# Laragon Turbo: The Portable WAMP Stack for Happy Devs 🚀

Kickstart your local development environment with Laragon Turbo. It comes packed with Apache, PHP, MariaDB, and a Mail Catcher. Everything you need to develop like a pro, but without the fuss.

## Quick Start 🏃‍♂️

To dive in, all you gotta do is:

```bash
git clone https://github.com/velome/laragon-turbo
```

And you're ready to roll! 🎉

## What's Inside? 📦

Here's the tech stack you'll get out of the box:

| Component             | Version                | Canonical Identifier             |
| --------------------- | ---------------------- | -------------------------------- |
| **Apache HTTP Server**| **2.4.41**             | *httpd-2.4.41-win64-VC14*        |
| **PHP**               | **8.2.10**             | *php-8.2.10-nts-Win32-vs16-x64*  |
| **MariaDB**           | **10.11.5**            | *mariadb-10.11.5-winx64*         |
| **phpMyAdmin**        | **5.2.1**              | *phpMyAdmin-5.2.1-all-languages* |

## Setting Up Your Project 🛠

### Before You Launch:
1. Create a folder for your app in the `www` subfolder.
2. Run Laragon Turbo.

Your folder will automatically be added to your Windows host config, allowing you to access your project at `http://folderName.test`.

### MariaDB Details 🗃
- Default root account have no password (leave empty).
- Access phpMyAdmin at `http://localhost/phpmyadmin`.

## Why Laragon Turbo? 💡

Many developers love the original Laragon for its ease of use, but let's face it, the default Laragon portable setup comes with Nginx, MySQL, and an old PHP version. While those are solid choices, Laragon Turbo is here.

Laragon Turbo swaps out Nginx for Apache, upgrades MySQL to MariaDB, and bumps up the PHP version to a fresher release. It's the same Laragon experience you know and love, but fine-tuned to offer a ready-to-go environment for those who want to stay on the cutting edge without the hassle.

## Acknowledgments 🙏

Big ups to Leo Khoa and all the contributors to the original Laragon project. This is a custom version, and all due credit goes to them!

---

Now go build something awesome! 🚀
