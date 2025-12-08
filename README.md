# cross-platform-ecommerce

![image-20251208153513884](https://s2.loli.net/2025/12/08/dpc6mj7Hbr3XInl.png)

learning material: https://www.youtube.com/watch?v=umcQU9iGDok&list=PLDn5_2K0bUmePOhs7TVTpn6_pLCtodBe3&index=9

Hubstack Simple Auth Starter Kit

https://hubstack-simple-auth.vercel.app/

Next.js 15 Starter Kit

https://nextjs-clerkelements-starter.vercel.app/

Mobile UI Starter Kit

Hono API Starter Kit
会自动生成一个接口文档 with scalar
https://hono-api-starterkit-vercel-edge.vercel.app/

Expo mobile App

https://www.youtube.com/watch?v=cxuKXepj-vM

prisma free trial: https://console.prisma.io/cmik0qszf0cw629gzkqu6lprl/cmik0s5ko0cwq29gztspixa8b/cmik0s5kn0cwo29gzrbmios1q/dashboard

postgress: https://neon.com/ also has free trail. 

clerk publish key

httpie

episode 2 : 2:20:06

✅ Complete Project Setup - React Native app, Next.js web app, and Hono API
✅ Environment Configuration - All necessary env variables and secrets
✅ Database Design - Comprehensive Prisma schema for ecommerce
✅ API Development - RESTful endpoints with TypeScript and Zod validation
✅ Seed Data Creation - Realistic test data for development
✅ Initial Deployment - Get API and web app live on the internet
✅ App Integration - Connect mobile and web apps to our backend

faker

nextjs honojs prisma authentication login

https://www.youtube.com/watch?v=I1V9YWqRIeI&t=254s

https://www.youtube.com/watch?v=Zq5fmkH0T78

wanna build a cross platform e-commerce web / app 

nextjs prisma hono expo zod
live demo: https://ecommerce-pro-web.vercel.app/

✅ Complete product catalog management 
✅ Multi-brand & category organization
✅ Secure authentication (Google + Credentials) 
✅ Role-based access control (Admin/User) 
✅ Full checkout & payment processing 
✅ Order management system 🌟
✅ Dashboard analytics & metrics 🌟
✅ Invoice downloads & Excel exports 🌟
✅ Infinite scroll & optimized search 🌟
✅ Responsive cross-platform design 🌟

tracking
seo

0. next.js crash course
   1. https://www.youtube.com/watch?v=I1V9YWqRIeI&t=281s
1. 搭建前端，画图
2. 搭建后端，和前端基础ping


todo:

1. honojs + prisma -> project - todo list crud - backend
2. authentication clerk: https://www.youtube.com/watch?v=cxuKXepj-vM&t=16s

**按用途分类的 Auth Provider 清单**，包含现在主流可用的第三方登录方式（OAuth / OIDC / SAML / 社交登录 / 企业登录）。
 你可以按 **“你想让用户用什么账号登录”** 来选。

------

# ✅ **最常见的 Auth Providers（社交登录 / OAuth / OIDC）**

这些是几乎所有网站都会支持的一线 Provider：

### **🌐 世界级通用**

- **Google**
- **Apple Sign-In**
- **Microsoft / Azure AD**
- **GitHub**
- **Twitter (X)**
- **Facebook**
- **LinkedIn**

### **📱 移动 & 短信登录系**

- **Auth0 Passwordless（Email / SMS）**
- **Firebase Phone Auth**
- **Twilio Verify / SMS OTP**
- **Magic.link（Email Magic Link）**

------

# 🧧 **亚洲市场常用的登录方式**

按地区整理，非常实用：

### 🇨🇳 中国 / 大陆

- **微信登录（Weixin OAuth）**
- **QQ 登录**
- **微博登录**
- **抖音授权登录**
- **Bilibili OAuth（B站登录）**

### 🇯🇵 日本

- **LINE Login**
- **Yahoo! Japan Login**
- **Rakuten Login**
- （Google / Apple 在日本也很常用）

### 🇰🇷 韩国

- **Kakao Login**
- **Naver Login**
- **LINE（部分韩区也有）**

------

# 🔧 **开发者向登录（Dev 社区常用）**

适合 B2B / 开发工具平台：

- **GitHub**
- **GitLab**
- **Bitbucket**
- **StackOverflow OAuth**
- **Twitch**
- **Discord**
- **Reddit**
- **Steam**

------

# 🏢 **企业级 Identity Providers（OAuth / SAML / OIDC）**

适合 B2B SaaS、公司内部系统：

### **IDaaS（Identity as a Service）**

这些是“一站式 Auth 服务”，可以同时接多个 provider：

- **Okta**
- **Auth0**
- **Clerk**
- **Supabase Auth**
- **Firebase Authentication**
- **Cognito（AWS）**
- **Keycloak**
- **FusionAuth**

### **企业身份（SAML / OIDC）**

- **Azure Active Directory（Azure AD）**
- **Microsoft Entra ID**
- **Google Workspace / Google Cloud Identity**
- **Okta Workforce**
- **Ping Identity**
- **OneLogin**
- **Salesforce Identity**
- **Oracle Identity**
- **IBM Security Verify**

------

# 🎮 游戏 / 平台生态

- **PlayStation Network OAuth（部分地区仍需审批）**
- **Xbox Live**
- **Nintendo Account Login**
- **Epic Games OAuth**
- **Unity ID Login**

------

# 🪪 Web3 / Crypto 登录（钱包登录类）**

如果你需要“钱包即身份”：

- **MetaMask**
- **WalletConnect**
- **Coinbase Wallet**
- **Phantom（Solana）**
- **Rainbow / Argent / Zerion**
- **Magic.link Web3 Login**
- **Privy**
- **Web3Auth**

------

# ✉️ **无密码（Passwordless）Provider**

这些是“发邮件 / 发短信”的登录方式，不需要密码：

- **Magic Link（Email）**
- **One-Time Password (OTP)**
  - Email OTP
  - SMS OTP
- **Passkeys（FIDO2 / WebAuthn）**
  - Touch ID / Face ID
  - Windows Hello
  - Android Passkey
- **Auth0 Passwordless**
- **Clerk Magic Link**
- **Supabase OTP / Magic Link**

例如 **NextAuth.js** 支持超过 70+ Provider：
 GitHub / Google / Twitter / Apple / Auth0 / Cognito / Keycloak / Reddit / Discord / LINE / Kakao / Slack / Spotify / etc.