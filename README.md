# Kairos Docs

Kairos 白皮书与一页简介的中英文源文件，通过 GitBook Git Sync 发布。
Source files for the Kairos whitepaper and one pager in Chinese and English, published with GitBook Git Sync.

## 目录结构 · Layout

```
kairos-docs/
├── whitepaper/
│   ├── zh/          白皮书 · 简体中文
│   └── en/          Whitepaper · English
└── one-pager/
    ├── zh/          一页简介 · 简体中文
    └── en/          One Pager · English
```

每个语言目录都是一个独立的 GitBook 空间，内含 `.gitbook.yaml`、`README.md`（首页）、`SUMMARY.md`（左侧目录）与 `.gitbook/assets/`（图片）。
Each language directory is a standalone GitBook space with its own `.gitbook.yaml`, `README.md` (landing page), `SUMMARY.md` (sidebar) and `.gitbook/assets/` (images).

## GitBook 对应关系 · GitBook mapping

| 站点分区 Section | 语言变体 Variant | Git Sync 项目目录 Project directory |
|---|---|---|
| 白皮书 · Whitepaper | 简体中文 | `whitepaper/zh` |
| 白皮书 · Whitepaper | English | `whitepaper/en` |
| 一页简介 · One Pager | 简体中文 | `one-pager/zh` |
| 一页简介 · One Pager | English | `one-pager/en` |

## 编写约定 · Conventions

- 中英文目录下的文件名保持一致，切换语言时停留在同一页。新增章节时两种语言同时新增同名文件，并各自登记到 `SUMMARY.md`。
  Keep file names identical across languages so the language switcher lands on the same page. Add new chapters to both languages and register them in each `SUMMARY.md`.
- 文件名用英文小写加连字符，文件名即页面网址。
  Use lowercase, hyphenated English file names; the file name becomes the page URL.
- 图片放在同一语言目录的 `.gitbook/assets/` 下，用相对路径引用。
  Put images in the same language directory's `.gitbook/assets/` and reference them with relative paths.

## 官方渠道 · Official channels

- 官网 Website: https://kairosmarkets.online
- X: https://x.com/KairosMkts
- Telegram 公告频道 Announcements: https://t.me/KairosMktsAnn
- Telegram 交流群 Community: https://t.me/KairosMkts
