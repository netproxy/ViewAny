# ViewAny - Office, HTML & PDF WYSIWYG Suite for VS Code

<div align="center">

<img src="media/icon.png" alt="ViewAny Logo" width="128" height="128" />

### All-in-One Office, HTML & Document Suite for VS Code
**Typora-like WYSIWYG Markdown • Word (DOCX) • HTML Webpages • Excel (XLSX/CSV) • PDF Annotator**

[![VS Code Extension](https://img.shields.io/badge/VS_Code-Extension-007ACC?logo=visualstudiocode&logoColor=white)](https://marketplace.visualstudio.com/)
[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://marketplace.visualstudio.com/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey.svg)](https://marketplace.visualstudio.com/)

---

### 🌐 Language Navigation / 语言切换
**[ 🇬🇧 English Edition ](#-english-edition)** &nbsp;|&nbsp; **[ 🇨🇳 简体中文版 ](#-中文版-chinese-edition)** &nbsp;|&nbsp; **[ 📄 独立中文文档 (README_ZH.md)](./README_ZH.md)**

---

</div>

---

<a id="-english-edition"></a>
## 🇬🇧 English Edition

### 💡 Why ViewAny?

Are you tired of switching between multiple standalone apps and installing several heavyweight extensions just to view or edit office files in VS Code?
- ❌ Opening Word / Excel files requires leaving VS Code to launch MS Office or WPS.
- ❌ Previewing and debugging HTML files requires constantly switching to external browsers without responsive device simulation.
- ❌ Editing Markdown in pure source code lacks real-time styling, while side-by-side preview wastes screen space. You miss the **seamless Typora-like WYSIWYG experience**.
- ❌ Reading PDFs in VS Code is inconvenient without high-fidelity rendering, pen drawing, text markup, and highlighters.
- ❌ Converting documents between Markdown, Word, Excel, HTML, and PDF requires unreliable third-party online converters.

✨ **ViewAny is your ultimate all-in-one document solution for VS Code!**  
Experience native, high-performance viewing and WYSIWYG editing for **Markdown (`.md`), Word (`.docx`, `.doc`), HTML (`.html`, `.htm`, `.xhtml`), Excel (`.xlsx`, `.xls`, `.csv`), and PDF (`.pdf`)** directly within your workspace.

---

### 🚀 Key Features

#### 1. 📝 Markdown WYSIWYG Editor (`.md`, `.markdown`)
- **Typora-like Rich-Text Experience**: What you see is what you get. Write formatted text naturally without syntax distraction.
- **Triple-View Switcher**: Seamlessly switch between **WYSIWYG**, **Split View (Real-time sync)**, and **Source Code**.
- **Advanced Markdown Support**:
  - Full support for Headers, Bold, Italic, Strikethrough, Underline, and Highlight.
  - **KaTeX Math Formula**: Inline `$E=mc^2$` and block `$$\int_{-\infty}^\infty e^{-x^2} dx = \sqrt{\pi}$$.
  - **Mermaid Diagrams**: Interactive flowcharts, sequence diagrams, state diagrams, and class diagrams.
  - **Interactive Tables & Task Lists**: Insert, delete, and modify rows/columns with one click.
- **Bi-directional Live Sync**: Content edited in rich-text mode is instantly and losslessly synchronized to the underlying `.md` source file.

#### 2. 📄 Word (DOCX/DOC) Visual Editor (`.docx`, `.doc`)
- **A4 Document Pagination**: Accurately parses Word document structure and styles, rendering in authentic A4 paper layout.
- **Rich Formatting Controls**: Font family, font size, paragraph line-height, text indent, alignment, lists, table formatting, and page breaks.
- **Preserved Line Spacing**: Accurate line-box calculation for empty paragraphs to maintain original document spacing.
- **Direct Save to DOCX**: Edits are saved directly back into standard binary `.docx` format.

#### 3. 🌐 HTML Multi-Viewport WYSIWYG Editor (`.html`, `.htm`, `.xhtml`)
- **Responsive Viewport Simulation**: Easily switch between **Responsive**, **Laptop (1024px)**, **Tablet (768px)**, **Mobile (375px)**, and **Print (A4 paper simulation)**.
- **Triple-View Workflow**: Seamless toggle between **WYSIWYG**, **Split-Screen**, and **Source Code**.
- **Intelligent Outline Tree (TOC)**: Automatically extracts H1~H6 heading hierarchy with real-time keyword search and instant jump navigation.
- **Rich-Text Styling & Inlining**: Apply typography styles, colors, alignments, images, tables, horizontal rules, and lists with real-time bidirectional HTML sync.
- **Paper Themes & Zoom**: Classic white paper, dark theme, and eye-care sepia mode with 75%~150% continuous zooming.

#### 4. 📊 Excel & CSV Spreadsheet Editor (`.xlsx`, `.xls`, `.csv`)
- **Full Spreadsheet Grid Interaction**: Cell selection, drag-and-drop, dynamic row/column insert and delete, column width resizing.
- **Multi-Sheet Tabs**: Easily switch between sheets, add new sheets, or rename existing ones.
- **Formulas & Auto-Calculation**: Built-in calculation engine supporting formulas like `=SUM(A1:A10)`, `=AVERAGE(...)`, `=MAX(...)`, `=COUNT(...)`, etc.
- **Bidirectional Save**: Re-packages and saves seamlessly back into standard `.xlsx` or `.csv` files.

#### 5. 📑 PDF HD Viewer & Professional Annotator (`.pdf`)
- **Crystal Clear PDF Rendering**: Powered by Mozilla PDF.js with smooth scrolling, page-fit, page-width, and continuous zoom.
- **Sidebar Thumbnail Navigation**: Rapidly scan page thumbnails and jump to any target page.
- **Comprehensive Annotation Suite**:
  - 🖌️ **Pen Tool**: Freehand drawing with custom colors and stroke width.
  - 🖍️ **Highlighter Tool**: Semi-transparent highlighter for marking critical text.
  - 💬 **Text Annotations**: Add custom text notes anywhere on the document.
  - 🧹 **Eraser**: Quickly remove annotations.
- **Export Annotated PDF**: Save and export clean or annotated high-resolution PDFs.

#### 6. 🔄 Multi-Format Export & Document Conversion
Convert and export documents instantly between major formats:
- **Markdown** $\rightarrow$ PDF / Word (.docx) / HTML / Markdown
- **Word** $\rightarrow$ PDF / Word (.docx) / HTML / Markdown
- **HTML** $\rightarrow$ PDF / Word (.docx) / Markdown / HTML
- **Excel / CSV** $\rightarrow$ Excel (.xlsx) / CSV / HTML / PDF
- **PDF** $\rightarrow$ PDF (with annotations) / Word (.docx) / HTML

---

### 📋 Format Support Matrix

| Document Type | File Extensions | Viewer | WYSIWYG Editor | Key Highlights | Export Formats |
| :--- | :--- | :---: | :---: | :--- | :--- |
| **Markdown** | `.md`, `.markdown` | ✅ | ✅ (Typora-like) | KaTeX Math, Mermaid, Live Sync | PDF, Word, HTML, Markdown |
| **Word Document** | `.docx`, `.doc` | ✅ | ✅ (A4 Visual) | Binary DOCX Save, Accurate Spacing | PDF, Word, HTML, Markdown |
| **HTML Webpages** | `.html`, `.htm`, `.xhtml` | ✅ | ✅ (Multi-Viewport) | Mobile/Tablet/Laptop Viewports, TOC | PDF, Word, Markdown, HTML |
| **Spreadsheets** | `.xlsx`, `.xls`, `.csv` | ✅ | ✅ (Formulas / Multi-sheet) | Formulas, Multi-Sheet Tabs | Excel, CSV, HTML, PDF |
| **PDF Document** | `.pdf` | ✅ (HD Zoom) | ✅ (Pen / Highlight / Note) | Thumbnails, Vector Drawing, Notes | PDF (Annotated), Word, HTML |

---

### ⌨️ How to Use

1. **Default Editor**: Click any `.md`, `.docx`, `.html`, `.xlsx`, `.csv`, or `.pdf` file in the VS Code File Explorer to open with ViewAny.
2. **Right-Click Menu**: Right-click any supported file in the Explorer and choose **"ViewAny: Switch to WYSIWYG Editor"**.
3. **Title Bar Icon**: When viewing source files, click the **"👁️"** icon in the editor tab header to toggle WYSIWYG view.
4. **Export**: Click the **"📤 Export..."** button in the ViewAny top toolbar to convert documents into PDF, Word, HTML, Markdown, or Excel.

---

### ❓ Frequently Asked Questions (FAQ)

<details>
<summary><b>Q: Can ViewAny completely replace Typora?</b></summary>
Yes! ViewAny brings a seamless Typora-like WYSIWYG editing experience directly into VS Code, equipped with KaTeX math formula rendering, Mermaid diagrams, interactive tables, and code syntax highlighting.
</details>

<details>
<summary><b>Q: What are the benefits of the HTML Visual Editor?</b></summary>
It allows you to inspect and edit HTML templates, exported reports, and static web pages directly inside VS Code across multiple simulated viewport sizes (Mobile, Tablet, Laptop, Responsive) with an interactive table of contents.
</details>

<details>
<summary><b>Q: Does opening and editing Word (.docx) corrupt formatting?</b></summary>
No. ViewAny uses OpenXML standards to parse and preserve headings, paragraphs, typography, colors, and tables, ensuring 100% interoperability with Microsoft Word and WPS Office.
</details>

<details>
<summary><b>Q: Does ViewAny support offline use and data privacy?</b></summary>
ViewAny runs 100% locally on your computer. All parsing, rendering, and conversion happen within your local IDE process. No files or private data are ever uploaded to any external server.
</details>

<div align="right">

[▲ Back to Top](#viewany---office-html--pdf-wysiwyg-suite-for-vs-code) &nbsp;|&nbsp; [🇨🇳 Switch to Chinese](#-中文版-chinese-edition)

</div>

---

<a id="-中文版-chinese-edition"></a>
## 🇨🇳 中文版 (Chinese Edition)

## 💡 为什么选择 ViewAny？

在日常开发与办公中，你是否经常遇到以下痛点：
- ❌ **想看 Word / Excel 文档**：每次都必须离开 VS Code 打开笨重的 Office 或 WPS？
- ❌ **想预览与调试 HTML 网页**：每次修改都要打开外置浏览器，缺乏集成在 VS Code 内的多视口所见即所得编辑环境？
- ❌ **编辑 Markdown 极其痛苦**：纯源码没有富文本实时感，分屏预览又占屏幕，想要 **Typora 般丝滑**的所见即所得编辑？
- ❌ **阅读与批注 PDF 繁琐**：无法直接在 VS Code 里划线、涂鸦、做笔记？
- ❌ **格式转换困难**：想要把 Markdown / Word / Excel / HTML / PDF 互相导出，需要到处找在线转换工具？

✨ **ViewAny 专为解决上述痛点而生！**  
无需安装多个零散插件，**一个插件全面接管 Markdown、Word (`.docx`, `.doc`)、Excel (`.xlsx`, `.xls`, `.csv`)、HTML (`.html`, `.htm`, `.xhtml`) 与 PDF (`.pdf`)**，带来极致流畅的原生级文档办公体验！

---

## 🚀 核心功能一览

### 1. 📝 Markdown 所见即所得编辑 (`.md`, `.markdown`)
- **媲美 Typora 的沉浸式富文本编辑**：输入即排版，告别传统源码与预览窗口割裂的体验。
- **三重视图自由切换**：支持「所见即所得」、「双栏实时对照」与「纯源码」一键切换。
- **丰富的排版扩展**：
  - 完整支持多级标题、粗体/斜体/下划线/删除线、高亮标记。
  - **KaTeX 数学公式**（行内 `$E=mc^2$` 与独立块 `$$\sum_{i=1}^n x_i$$`）。
  - **Mermaid 流程图与时序图**实时可视化渲染与编辑。
  - **交互式表格增删改查**与任务清单 (Task Lists)。
- **双向无损实时同步**：富文本修改后与底层 Markdown 纯文本实时同步，绝不丢失任何格式。

### 2. 📄 Word 可视化编辑与排版 (`.docx`, `.doc`)
- **A4 拟真排版渲染**：自动解析 Word 文档的层级、段落、样式并以标准化页面呈现。
- **富文本排版工具栏**：支持字号、字体族、段落行距、段落缩进、对齐方式、无序/有序列表、表格插入与分页符。
- **精准还原空行与行框**：完美还原 Word 原文段落行高与空行排版，不塌陷、不挤压。
- **直接保存为 DOCX**：在编辑器中修改保存后，直接写入标准的二进制 `.docx` 格式文件。

### 3. 📊 Excel & CSV 电子表格编辑器 (`.xlsx`, `.xls`, `.csv`)
- **完整电子表格交互**：支持单元格拖拽、区域选取、行列动态插入/删除/调整宽高。
- **多工作表 (Multi-Sheet Tabs)**：支持多 Sheet 标签自由切换、新建、重命名。
- **公式计算与统计分析**：内置 `=SUM(A1:A10)`、`=AVERAGE(...)`、`=COUNT(...)` 等常用公式，支持自动计算与快速求和。
- **数据无缝互通**：支持修改后一键保存回标准的 `.xlsx` 或 `.csv` 文件。

### 4. 🌐 HTML 网页多视口可视化预览与编辑 (`.html`, `.htm`, `.xhtml`)
- **多视口响应式设备模拟**：一键在「自适应 (Responsive)」、「笔记本 (Laptop 1024px)」、「平板 (Tablet 768px)」、「手机 (Mobile 375px)」及「A4 打印拟真 (Print)」之间切换。
- **三重视图协同工作**：支持「所见即所得 (WYSIWYG)」、「左右双栏实时分屏 (Split)」与「纯源码 (Source)」无缝切换。
- **智能文档大纲树 (TOC)**：自动提取 HTML 页面全部 H1~H6 标题层级，支持关键词过滤搜索与一键跳转定位。
- **富文本可视化排版**：支持直接在页面上调整字体、字号、颜色、对齐、插入图片、表格、分割线与列表，并与底层 HTML 源码双向实时同步。
- **多样化纸张主题**：支持经典白纸、沉浸深色、护眼浅黄三种主题模式与 75%~150% 页面缩放。

### 5. 📑 PDF 高清阅读与专业批注器 (`.pdf`)
- **高清平滑渲染**：基于 Mozilla PDF.js 核心引擎，支持页面连续滚动、双页并排、适应页宽与任意比例缩放。
- **侧边栏缩略图导航**：快速预览页面结构，一键跳转到指定页。
- **全套批注与标注工具**：
  - 🖌️ **涂鸦画笔 (Pen)**：自定义颜色与线条粗细，自由圈画重点。
  - 🖍️ **荧光高亮笔 (Highlighter)**：半透明高亮标记关键文字。
  - 💬 **文字批注 (Text Note)**：在文档任意位置添加富文本注释。
  - 🧹 **橡皮擦 (Eraser)**：一键擦除笔迹。
- **含批注导出**：批注完成后可直接导出带有完整批注的高清 PDF。

### 6. 🔄 跨格式自由导出与转换
支持一键在多种文档格式之间自由互转：
- **Markdown** $\rightarrow$ PDF / Word (.docx) / HTML / Markdown
- **Word** $\rightarrow$ PDF / Word (.docx) / HTML / Markdown
- **HTML** $\rightarrow$ PDF / Word (.docx) / Markdown / HTML
- **Excel / CSV** $\rightarrow$ Excel (.xlsx) / CSV / HTML / PDF
- **PDF** $\rightarrow$ PDF (含批注) / Word (.docx) / HTML

---

## 📋 格式支持对照表

| 文档类型 | 支持后缀 | 查看模式 | 所见即所得编辑 | 特色功能 | 导出格式支持 |
| :--- | :--- | :---: | :---: | :--- | :--- |
| **Markdown** | `.md`, `.markdown` | ✅ | ✅ (Typora 级体验) | KaTeX 公式、Mermaid 图表、双向同步 | PDF, Word, HTML, Markdown |
| **Word 文档** | `.docx`, `.doc` | ✅ | ✅ (A4 可视化排版) | 二进制 DOCX 保存、精准空行还原 | PDF, Word, HTML, Markdown |
| **HTML 网页** | `.html`, `.htm`, `.xhtml` | ✅ | ✅ (多视口所见即所得) | 手机/平板/电脑视口切换、大纲树 (TOC) | PDF, Word, Markdown, HTML |
| **电子表格** | `.xlsx`, `.xls`, `.csv` | ✅ | ✅ (公式/多Sheet) | 常用算术公式计算、多工作表标签 | Excel, CSV, HTML, PDF |
| **PDF 文件** | `.pdf` | ✅ (高清缩放) | ✅ (画笔/高亮/批注) | 缩略图大纲、矢量涂鸦、富文本便签 | PDF (含批注), Word, HTML |

---

## ⌨️ 快捷操作与使用指南

### 打开方式
1. **默认打开**：安装扩展后，在 VS Code 资源管理器中单击任意 `.md`、`.docx`、`.html`、`.xlsx`、`.csv`、`.pdf` 文件，将自动以 ViewAny 专属编辑器打开。
2. **右键菜单**：在文件列表上右键点击，选择 **「ViewAny: 切换为所见即所得编辑器」**。
3. **顶部导航图标**：在打开文本源码时，点击右上角导航栏的 **「👁️」** 图标随时切换所见即所得视图。

### 导出与转换
- 在 ViewAny 编辑器顶部工具栏点击 **「📤 导出」** 按钮，选择目标格式（PDF / Word / HTML / Markdown / Excel / CSV），一键导出转换。

---

## ❓ 常见问题解答 (FAQ)

<details>
<summary><b>Q1: ViewAny 可以完全替代 Typora 吗？</b></summary>
答：是的！ViewAny 提供了与 Typora 极度相似的 Markdown 所见即所得富文本编辑体验，并且直接集成在 VS Code 工作区中，支持数学公式 (KaTeX)、Mermaid 流程图、表格与代码高亮，不需要在两个软件之间来回切换。
</details>

<details>
<summary><b>Q2: 打开和保存 Word (.docx) 会破坏原本的排版吗？</b></summary>
答：ViewAny 采用标准 OpenXML 解析引擎，保留了标题层级、正文段落、粗体斜体、颜色及标准表格结构，保存时生成标准二进制 DOCX 文件，能与 Microsoft Office 及 WPS 100% 兼容互通。
</details>

<details>
<summary><b>Q3: HTML 可视化编辑器适合什么使用场景？</b></summary>
答：非常适合查看富文本 HTML 报告、静态网页模版、导出的合同文档以及邮件模版。支持在移动端 (375px)、平板 (768px)、电脑端 (1024px) 以及自适应视口间快速切换排版测试，并支持智能大纲树定位与一键转为 PDF / Word / Markdown。
</details>

<details>
<summary><b>Q4: Excel 电子表格支持公式计算吗？</b></summary>
答：支持！ViewAny 内置了公式计算引擎，支持 SUM、AVERAGE、MAX、MIN、COUNT 等常用算术公式，并支持多 Sheet 标签切换和 CSV 文件编辑。
</details>

<details>
<summary><b>Q5: 是否支持完全离线使用？是否有数据隐私泄露风险？</b></summary>
答：ViewAny 纯本地运行，所有文档解析、渲染与编辑均在本地 IDE 进程内完成，绝对不会将任何文档上传到外部服务器，安全可靠。
</details>

---


---

## 📄 许可证 (License)

本项目采用 [MIT License](LICENSE) 授权许可。
