# onepage-site - One Page 产品官网
HTML + CSS + GitHub Pages

## Philosophy

黑橙宋刻美学：黑色背景、暖白文字、橙色重点，极简排版
双语支持：中文主站 + 英文镜像
零依赖：纯静态 HTML，无构建流程

## Directory

```
onepage-site/
├── CLAUDE.md           # L1 项目宪法
├── README.md           # 部署说明
├── images/             # App 截图、分享海报资源
│
├── index.html          # 中文落地页 - 产品介绍、定价、隐私承诺
├── index-en.html       # 英文落地页 - English landing page
│
├── privacy.html        # 中文隐私政策 - 极简无数据收集声明
├── privacy-en.html     # 英文隐私政策
│
├── support.html        # 中文支持页 - FAQ、联系方式
├── support-en.html     # 英文支持页
│
├── terms.html          # 中文服务条款 - 购买、退款、免责
└── terms-en.html       # 英文服务条款
```

## Pages

| 页面 | 中文 | 英文 | 用途 |
|------|------|------|------|
| Landing | index.html | index-en.html | 产品介绍、App Store 入口 |
| Privacy | privacy.html | privacy-en.html | App Store 审核必需 |
| Support | support.html | support-en.html | FAQ、联系方式 |
| Terms | terms.html | terms-en.html | 服务条款 |

## Deployment

- **Host**: GitHub Pages + Cloudflare DNS
- **URL**: https://onepage.theunclej.com/
- **Branch**: main
- **Build**: 无需构建，直接部署静态文件
- **CNAME**: `onepage.theunclej.com`

## Design Tokens

```css
--bg: #000;                              /* 黑色背景 */
--text: #f7f4ec;                         /* 暖白主文字 */
--text-light: rgba(247, 244, 236, 0.72); /* 次要文字 */
--text-muted: rgba(247, 244, 236, 0.46); /* 弱化文字 */
--border: rgba(242, 109, 20, 0.28);      /* 橙色边线 */
--accent: #f26d14;                       /* 橙色重点 */
--font-cn: "Songti SC";                  /* 中文宋体 */
--font-en: Georgia;                      /* 英文衬线 */
```

## Related Repos

- **One Page**: 私有 iOS App 源代码仓库
  - Repo: https://github.com/UncleJ-h/onepage

[PROTOCOL]: 页面增删时更新此文档，保持目录结构同步
