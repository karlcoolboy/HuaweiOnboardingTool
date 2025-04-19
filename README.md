# HuaweiOnboardingTool | 华为入职预约自动化工具

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

> 自动化预约华为入职报到时间的Python工具，支持东莞/上海等多地选择

## 📦 功能特性

- **一键预约**：自动循环发送入职预约请求
- **智能配置**：通过配置文件管理HTTP请求头和Cookies
- **多城市支持**：东莞/上海等报到地可选
- **日期定制**：自由选择入职日期（支持自动补零）
- **安全存储**：敏感信息不写死在代码中

## 🚀 快速开始

```bash
# 克隆仓库
git clone https://github.com/karlcoolboy/HuaweiOnboardingTool.git

# 安装依赖
pip install -r requirements.txt

#运行
python huawei.py
```

## 使用方式

一键运行exe程序
[Releases下载](https://github.com/karlcoolboy/HuaweiOnboardingTool/releases)打包好的exe程序双击运行

[HuaweiOnboardingTool-windows-latest-web.exe](https://github.com/karlcoolboy/HuaweiOnboardingTool/releases/download/HuaweiOnboardingTool-release-24/HuaweiOnboardingTool-windows-latest-web.exe)

[HuaweiOnboardingTool-windows-latest-gui.exe](https://github.com/karlcoolboy/HuaweiOnboardingTool/releases/download/HuaweiOnboardingTool-release-24/HuaweiOnboardingTool-windows-latest-gui.exe)

[👉具体配置教程](https://blog.wssss.org.cn/archives/HuaweiOnboardingTool-406.html)

不会使用请联系我：[wssssorg@qq.com](mailto:wssssorg@qq.com) 【个人自用工具，打赏后获取授权码，介意勿扰，抱歉】

## 🌟 打赏支持
如果您觉得这个项目有帮助，欢迎请作者喝杯咖啡：

| 支付宝 | 微信 |
|--------|------|
| ![支付宝二维码](https://blog.wssss.org.cn/usr/uploads/2023/02/2320184992.png) | ![微信二维码](https://blog.wssss.org.cn/usr/uploads/2023/02/3555771655.png) |

## 📄 免责声明 | Disclaimer

本工具仅为**个人自用**开发，旨在**简化华为入职预约流程中的重复步骤**，通过模拟用户已登录状态下的网页请求，自动提交预约申请请求，以提升效率。

- 工具不会存储、收集或上传任何用户的隐私数据，**所有请求标头和 Cookie 信息均由用户本地配置**（如 `config.txt`）；
- 本工具不模拟登录行为，**仅在用户登录后操作**并发起正常的官方预约请求；
- 请勿将本工具用于**任何违反目标平台使用条款或接口规定**的行为；
- **一切使用后果由用户自行承担**，包括但不限于预约失败、账号异常等，开发者不对任何滥用或意外后果负责；
- 本工具开源透明，遵循 [MIT License](LICENSE)，可自由复制、修改、分发，**建议使用前自行审阅代码内容**；
- 使用过程中请注意合理设置请求频率，避免给目标服务器带来不必要压力。

> ⚠️ 本项目为自用学习性质，禁止非法传播。介意者请勿使用。

---

This tool is developed **for personal use only**, designed to **simplify the repetitive steps involved in Huawei onboarding appointment processes**, by automatically submitting requests after the user logs into the official website.

- The tool does **not store, collect, or upload any sensitive user data**. All request headers and cookies must be configured **locally by the user** (e.g., in `config.txt`);
- It does **not simulate login**, and only works **after the user has manually logged in**;
- **Do not use this tool in violation of the target platform's terms of service** or API usage policies;
- The user **takes full responsibility** for all outcomes, including but not limited to appointment failure or account issues. The developer shall not be held liable;
- The project is fully open-source under the [MIT License](LICENSE). Feel free to inspect, use, and modify the code at your own discretion;
- Please ensure reasonable request frequency to avoid putting unnecessary load on the target server.

> ⚠️ For educational and private use only. Unauthorized distribution is strictly prohibited.

