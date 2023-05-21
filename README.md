---
home: true
modules:
  - BannerBrand
  - Blog
  - MdContent
  - Footer
bannerBrand:
  bgImage: '/bg.svg'
  title: 我的个人博客
  description: 记录个人思考和学习
  tagline: 决定练习书法，于是重金购买文房四宝。一日，饭后突生雅兴，一番磨墨拟纸，点上上好檀香。定神片刻，泼墨挥毫。郑重地写下一行字：Hello World!

  buttons:
    - { text: Guide, link: '/docs/guide/introduce' }
    - { text: Default Style, link: '/docs/style-default-api/introduce', type: 'plain' }
  socialLinks:
    - { icon: 'LogoGithub', link: 'https://github.com/vuepress-reco/vuepress-theme-reco' }
blog:
  socialLinks:
    - { icon: 'LogoGithub', link: 'https://github.com/recoluan' }
isShowTitleInHome: true
actionText: About
actionLink: /views/other/about
---

## 快速开始

**npx**

```bash
# 初始化，并选择 2.x
npx @vuepress-reco/theme-cli init
```

**npm**

```bash
# 初始化，并选择 2.x
npm install @vuepress-reco/theme-cli@1.0.7 -g
theme-cli init
```

**yarn**

```bash
# 初始化，并选择 2.x
yarn global add @vuepress-reco/theme-cli@1.0.7
theme-cli init
```
