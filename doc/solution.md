# TDS 的 Markdown 解决方案 Markdown TDS Solution

## 1. 文档信息

在 Markdown 文档顶部加入 YAML front matter 来实现。

就像这样：

```yaml
---
文档版本: 0.15
控制范围: 公开
编制单位: forw.cc
发布日期: 2025-01-10
---
```

## 2. 编辑器

Visual Studio Code（VSCode）。知名代码编辑器，支持编辑和预览 Markdown 文件，可通过扩展增加各种功能。

## 3. 多级编号维护

VSCode 扩展 markdown-multilevel-numbering。为 Markdown 文档中的标题和段落添加多级编号。支持正文、附录两种编号模式，通过控制指令调整编号模式和深度。

## 4. 不分页浏览

浏览器扩展 Markdown Reader。它可以将本地或网络上的 Markdown 文件渲染为 HTML 页面，适合以不分页方式，直接在浏览器中阅读 Markdown 源文件。

- 支持显示 Markdown 文档的元数据。
- 支持数学公式、图表等。
- 支持侧边栏目录。
- 支持样式自定义。

## 5. 保存为 HTML

浏览器扩展 SingleFile。它可以将当前网页及其样式、图片等资源保存为一个 HTML 文件，便于离线查看、归档和通过 Git 管理。

## 6. 分页浏览、保存为 PDF

浏览器扩展 Markdown to Pages。以分页方式浏览和打印本地 Markdown 文档。文档在浏览器中自动排版分页，可直接打印或输出为 PDF。

- 支持自动分页。
- 支持自动封面。
- 支持显示 Markdown 文档的元数据。
- 支持自动生成传统的带页码目录。
- 支持页眉、页脚。
- 支持在内容中插入分页等指令。
- 支持代码高亮。
- 支持 LaTeX 公式渲染。
- 支持 Mermaid 图表。
- 支持 D2 图表。
- 支持 PlantUML 图表。

Markdown to Pages 生成的 PDF 版 [《技术文档标准》](standard.pdf)。