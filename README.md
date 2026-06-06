# 《东辛农场志》数字阅读版

这是《东辛农场志》的公开数字化阅读项目。项目把整理后的正文、PDF 成品和结构化表格库发布为一个可直接浏览的静态网页，方便在电脑和手机浏览器中阅读、检索和分享。

## 直接打开观看

- [在线阅读入口](https://xixingchao.github.io/dongxin-farm-history/)
- [《东辛农场志》书页](https://xixingchao.github.io/dongxin-farm-history/books/dongxin/)
- [正文阅读版](https://xixingchao.github.io/dongxin-farm-history/books/dongxin/reader.html)
- [结构化表格库](https://xixingchao.github.io/dongxin-farm-history/books/dongxin/tables/index.html)
- [PDF 阅读版](https://xixingchao.github.io/dongxin-farm-history/books/dongxin/pdf/东辛农场志_最终阅读版.pdf)

## 这个项目做什么

本仓库用于托管《东辛农场志》的 GitHub Pages 静态网站。它不是源扫描件仓库，也不是 OCR 工作过程仓库，而是面向公开阅读和分享的发布版。

当前发布内容包括：

- 完整正文阅读版 HTML
- 正文目录和章节锚点
- PDF 阅读版
- 98 张结构化表格
- 独立表格库
- 自动质检报告和版本说明

## 当前版本状态

- 基线交付包：`东辛农场志_交付包_20260601_001759`
- 正文规模：22 章，122 个二级节
- 表格规模：98 张结构化表格
- 自动质检：高优先级问题 0
- 发布方式：GitHub Pages

## 使用方式

普通读者直接访问：

```text
https://xixingchao.github.io/dongxin-farm-history/
```

如果只想看正文，打开：

```text
https://xixingchao.github.io/dongxin-farm-history/books/dongxin/reader.html
```

如果需要查看表格，打开：

```text
https://xixingchao.github.io/dongxin-farm-history/books/dongxin/tables/index.html
```

## 目录说明

```text
.
├─ index.html                 # 文库首页
├─ books/dongxin/index.html   # 《东辛农场志》书页
├─ books/dongxin/reader.html  # 正文阅读版
├─ books/dongxin/pdf/         # PDF 成品
├─ books/dongxin/tables/      # 结构化表格库
└─ books/dongxin/reports/     # 质检报告和版本说明
```

## 后续计划

- 补充 EPUB 电子书版本
- 优化移动端阅读体验
- 增加更清晰的下载入口
- 将这套流程沉淀为可复刻的地方志数字化工作站
