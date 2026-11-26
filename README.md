# 深圳乐凯龙国际货运代理有限公司 | LKL International Freight Forwarders Ltd.

> **让世界物流畅快无忧 · 中国跨境快运的高效整合专家**  
> **Making Global Logistics Seamless & Worry-Free · China's Premier Cross-Border Express Integrator**

本项目为 **深圳乐凯龙国际货运代理有限公司**（**Shenzhen Lucky Dragon International Freight Forwarders Ltd.**，简称 **LKL乐凯龙国际**）的中英双语国际化独立宣传落地页，采用零构建依赖的纯静态架构（HTML5 + Modern CSS3 + Vanilla JS I18n），支持一键通过 **GitHub Pages**、**Vercel**、**Netlify** 或 **Cloudflare Pages** 发布上线。

---

## 1. 已核实并集成的企业信息

| 维度 | 官方核实信息 |
|---|---|
| **中文名称** | 深圳乐凯龙国际货运代理有限公司（LKL乐凯龙 · 跨境快运） |
| **英文名称** | Shenzhen Lucky Dragon International Freight Forwarders Ltd. |
| **服务热线 / 传真** | `400-111-5656` |
| **官方邮箱** | `VIC@LKL56.COM` |
| **官方网站** | `http://www.lkl56.com/` |
| **深圳总部地址** | 深圳市宝安区福海街道桥头社区重庆路4号103（万利业工业园A栋1楼103号） |
| **分支机构网络** | 深圳宝安总部 · 深圳坂田营业部 · 广州分公司 · 东莞分公司 · 香港分公司 + 华南/华东/华北三大集运分拨中心（全国 72 个空运网点） |
| **核心业务板块** | 国际快递（DHL/UPS/FedEx/TNT/EMS一级代理）、LKL国际专线（欧美/亚太/中东/俄/印尼/澳洲 40+国）、亚马逊 FBA 头程、海陆空多式联运、中港快件/全球进口/商检报关 |
| **品牌资产** | `assets/logo.png`（深色主LOGO）、`assets/logo2.png`（浅色反白LOGO）、`assets/favicon.ico`（龙标图标） |
| **备案号** | 粤ICP备11041537号 |

---

## 2. 目录结构

```text
html-show/
├── index.html                    # 中英双语主页面
├── styles.css                    # 国际化响应式样式表
├── app.js                        # 中英双语字典 (ZH/EN)、智能航线匹配器与询价邮件生成器
├── assets/
│   ├── logo.png                  # 官网原版高清透明 LOGO
│   ├── logo2.png                 # 页脚深色背景专用 LOGO
│   └── favicon.ico               # 网站图标
└── .github/workflows/deploy.yml  # GitHub Pages 自动化发布流水线
```

---

## 3. Git 发布与 GitHub Pages 上线指南

本仓库已完成 Git 初始化与提交，内置 `.github/workflows/deploy.yml` 自动部署工作流。只需关联您的远程 GitHub 仓库并推送：

```powershell
# 1. 绑定您的 GitHub 远程仓库地址
git remote add origin https://github.com/<您的GitHub账号>/<仓库名>.git

# 2. 推送到 main 分支，自动触发 GitHub Pages 部署
git branch -M main
git push -u origin main
```

在 GitHub 仓库的 **Settings → Pages → Build and deployment** 中，将 **Source** 选择为 **GitHub Actions**，推送后约 30 秒即可生成全球可访问的 HTTPS 独立宣传网址。
