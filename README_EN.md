# HuaweiOnboardingTool | Huawei Onboarding Automation Tool

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

> A Python tool for automating Huawei onboarding appointment requests, supporting multiple cities such as Dongguan and Shanghai.

## 📦 Features

- **One-click Appointment**: Automatically sends onboarding appointment requests in a loop.
- **Smart Configuration**: Manages HTTP headers and cookies via config files.
- **Multi-City Support**: Allows selection of onboarding locations like Dongguan/Shanghai.
- **Customizable Dates**: Freely select onboarding date (auto zero-padding supported).
- **Secure Storage**: Sensitive information is not hardcoded.

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/karlcoolboy/HuaweiOnboardingTool.git

# Install dependencies
pip install -r requirements.txt

# Run the script
python huawei.py
```

## Usage

Simply run the executable  
Download pre-built `.exe` files from [Releases](https://github.com/karlcoolboy/HuaweiOnboardingTool/releases)

[HuaweiOnboardingTool-windows-latest-web.exe](https://github.com/karlcoolboy/HuaweiOnboardingTool/releases/download/HuaweiOnboardingTool-release-24/HuaweiOnboardingTool-windows-latest-web.exe)

[HuaweiOnboardingTool-windows-latest-gui.exe](https://github.com/karlcoolboy/HuaweiOnboardingTool/releases/download/HuaweiOnboardingTool-release-24/HuaweiOnboardingTool-windows-latest-gui.exe)

[👉 Configuration Tutorial](https://blog.wssss.org.cn/archives/HuaweiOnboardingTool-406.html)

For assistance, contact: [wssssorg@qq.com](mailto:wssssorg@qq.com)  
**[Personal use only, license key required after donation, please do not use if you mind, sorry!]**

## 🌟 Support

If you find this project helpful, consider buying the author a coffee:

| Alipay                                                       | WeChat                                                       |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| ![Alipay QR](https://blog.wssss.org.cn/usr/uploads/2023/02/2320184992.png) | ![WeChat QR](https://blog.wssss.org.cn/usr/uploads/2023/02/3555771655.png) |

## 📄 Disclaimer

This tool is developed for **personal use only**, aiming to **simplify repetitive steps in Huawei onboarding appointment process**. It simulates webpage requests under a logged-in session to submit appointment applications automatically for efficiency.

- The tool **does not store, collect, or upload any user privacy data**. All header and cookie configurations are **provided locally by the user** (e.g., `config.txt`);
- It **does not simulate login behavior**, and only performs actions after the user has logged in, initiating official appointment requests;
- Do not use this tool for **any actions that violate the terms of service or API policies** of the target platform;
- **All consequences of use are the sole responsibility of the user**, including but not limited to failed appointments, account issues, etc. The developer is not liable for any misuse or unforeseen outcomes;
- This tool is open-source and transparent, licensed under the [MIT License](LICENSE), and may be freely copied, modified, and distributed. **It is recommended to review the code before use**;
- Please set a reasonable request frequency to **avoid placing unnecessary load on the target server**.

> ⚠️ This project is for self-learning purposes only and must not be distributed illegally. Do not use if you have concerns.
