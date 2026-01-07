# onepage-site - One Page 产品官网
HTML + CSS + GitHub Pages

## Philosophy

原研哉式美学：温暖纸质背景 #faf9f7，极简排版，留白呼吸
双语支持：中文主站 + 英文镜像
零依赖：纯静态 HTML，无构建流程

## Directory

```
onepage-site/
├── CLAUDE.md           # L1 项目宪法
├── README.md           # 部署说明
├── images/             # [待填充] 截图、图标资源
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

- **Host**: GitHub Pages
- **URL**: https://unclej-h.github.io/onepage-site/
- **Branch**: main
- **Build**: 无需构建，直接部署静态文件

## Design Tokens

```css
--bg: #faf9f7;           /* 温暖纸质背景 */
--text: #2c2c2c;         /* 主文字 */
--text-light: #666;      /* 次要文字 */
--border: #e0ded8;       /* 分割线 */
--font-cn: "Songti SC";  /* 中文宋体 */
--font-en: Georgia;      /* 英文衬线 */
```

## Related Repos

- **One Page**: 私有 iOS App 源代码仓库
  - Repo: https://github.com/UncleJ-h/onepage

[PROTOCOL]: 页面增删时更新此文档，保持目录结构同步
