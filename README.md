# Microsoft OAuth2 纯前端授权工具

纯 HTML/CSS/JS 版本，无需后端服务器，直接浏览器打开即可使用。

## 使用方法

1. 下载 `index.html`
2. 双击打开（或拖到浏览器）
3. （可选）展开 ⚙️ 高级配置，填写你的 Client ID 和 Secret
4. 点击「获取授权code」
5. 完成 Microsoft 授权，复制 code
6. 粘贴 code，点击「交换获取 Token」

## 功能

- 🔐 公开客户端 / 机密客户端 自动兼容
- 📧 Mail.Read / Mail.Send 权限
- 🔄 获取 Access Token 和 Refresh Token

## 注意

- 公开客户端：Client ID 和 Secret 都留空
- 机密客户端：填写你自己的 Client ID 和 Secret

