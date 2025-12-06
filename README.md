# 🌐 cloudflare-auto-protection - Protect Your Site Automatically

[![Download](https://img.shields.io/badge/Download%20Latest%20Release-Cloudflare%20Auto%20Protection-brightgreen)](https://github.com/TianTheHacker/cloudflare-auto-protection/releases)

## 📦 Overview

cloudflare-auto-protection automatically activates Cloudflare's "Under Attack" mode when your server's CPU usage is high. Once the load returns to normal, it disables this mode. With additional Telegram notifications, you will always know the status of your site.

## 🚀 Getting Started

This guide will help you download and run the software. Follow the steps below to get started.

## 📋 System Requirements

- **Operating System**: This software runs on any UNIX-based system (like Linux or macOS).
- **Memory**: At least 512 MB of RAM.
- **Disk Space**: Approximately 10 MB of free space.

Make sure your system meets these requirements to ensure smooth operation.

## 📥 Download & Install

To download the software, visit the Releases page:

[Download Latest Release](https://github.com/TianTheHacker/cloudflare-auto-protection/releases)

1. Click the link above to open the releases page.
2. Look for the latest version listed at the top.
3. Download the file appropriate for your operating system. 

Each release includes detailed notes about what is new or fixed.

## 💻 Running the Application

After downloading, follow these steps to run the application:

1. **Open Terminal**: Use Ctrl + Alt + T or search for "Terminal" in your applications.
2. **Navigate to the Download Folder**: 
   ```
   cd ~/Downloads
   ```
3. **Extract the Files**: If you downloaded a compressed file:
   ```
   tar -xzf cloudflare-auto-protection.tar.gz
   ```
4. **Change Directory** to the extracted folder:
   ```
   cd cloudflare-auto-protection
   ```
5. **Run the Script**: 
   ```
   ./start.sh
   ```

The application will now monitor your CPU usage. When it detects high usage, it automatically activates Cloudflare's protection.

## 📬 Notifications via Telegram

To receive notifications on your Telegram:

1. Create a bot using [BotFather](https://core.telegram.org/bots#botfather).
2. Note down your bot token.
3. In your terminal, set the token by running:
   ```
   export TELEGRAM_BOT_TOKEN='YOUR_BOT_TOKEN'
   ```

The bot will now send you messages when the protection is activated or disabled.

## 🌐 Features

- **Automatic Switching**: Activates "Under Attack" mode based on CPU usage.
- **Notifications**: Sends alerts via Telegram for changes in status.
- **Easy Setup**: Quick installation and straightforward usage.

## 👩‍💻 Customizing and Troubleshooting

If you want to make adjustments or run into issues:

1. **Config File**: Open `config.yaml` to edit settings such as CPU thresholds and notification preferences.
2. **Logs**: Check `logs.txt` for any error messages or alerts to diagnose problems.

If you need help, the community is available to offer assistance on GitHub issues.

## 🤝 Community Support

Join our community to connect with other users. You can ask for help or share tips:

- [GitHub Discussions](https://github.com/TianTheHacker/cloudflare-auto-protection/discussions)
- [Telegram Group](https://t.me/joinchat/YourTelegramGroupLink)

## 🛠 Contributing

If you're interested in contributing, feel free to fork the repository and submit a pull request. Your suggestions and improvements are welcome!

## ✈️ License

This software is licensed under the MIT License. You can use, modify, and distribute it with proper attribution.

For more details, refer to the LICENSE file in the repository.

## 📚 Additional Resources

- [Cloudflare API Documentation](https://developers.cloudflare.com/api/)
- [Telegram Bot Documentation](https://core.telegram.org/bots/api)

For more information or if you experience difficulties, refer back to this README or contact the community. 

[Download Latest Release](https://github.com/TianTheHacker/cloudflare-auto-protection/releases)