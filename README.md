# AllStream Depin
挖掘数据，驱动AI，获取奖励 - 加入Stream AI革命
![alt text](image-2.png)

- 官网 [https://app.allstream.ai/](https://app.allstream.ai/index?referralCode=FlGQxaTO)
- Twitter/X [@allstream_ai](https://x.com/allstream_ai)

## 功能特性

- **自动创建连接**
- **支持多账户**
- **支持代理** 格式：`http://ip:port` 或 `http://用户名:密码@ip:port`

## 环境要求

- **Node.js**: 请确保已安装Node.js
- **NPM**: 请确保已安装npm
- **AiStream ID**: 按以下步骤获取
- 在此创建AiStream账号: [https://app.allstream.ai/](https://app.allstream.ai/index?referralCode=FlGQxaTO)
- 按F12打开开发者工具（如果已登录）
- 在Network标签中找到MyInfo并复制您的ID
   ![uid](image-1.png)


## 安装步骤

1. 克隆本仓库：
   ```bash
   git clone git@github.com:huaguihai/AllStreamAIBot.git
   cd AllStreamAIBot
   ```
2. 安装依赖：
   ```bash
   npm install
   ```
3. 配置：将用户ID粘贴到`userIds.txt`，每行一个账号
   ```bash
   nano userIds.txt
   ```
4. 配置：将代理粘贴到`proxies.txt`，每行一个代理
   ```bash
   nano proxies.txt
   ```
5. 运行脚本：
   ```bash
   npm run start
   ```


## ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

本项目采用 [MIT 许可证](LICENSE)。
