<div align="center">

# 📑 ViewAny

### The All-in-One Markdown, Office, HTML & PDF WYSIWYG Suite for VS Code
**Typora-like Markdown (MD) • Word (DOCX/DOC) • Excel (XLSX/CSV) • HTML Multi-Viewport • PDF Annotator**

[![Version](https://img.shields.io/badge/version-v3.0.11-blue.svg?style=for-the-badge&logo=visualstudiocode)](https://github.com/netproxy/ViewAny/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-orange.svg?style=for-the-badge)]()
[![VS Code](https://img.shields.io/badge/VS%20Code-%3E%3D1.85.0-blueviolet.svg?style=for-the-badge&logo=visualstudiocode)](https://marketplace.visualstudio.com/)
[![Local-First](https://img.shields.io/badge/Security-100%25%20Local%20%26%20Private-success.svg?style=for-the-badge&logo=shield)]()

<p align="center">
  <a href="#-english-documentation"><b>English</b></a> •
  <a href="#-中文文档-chinese-documentation"><b>简体中文</b></a> •
  <a href="#-繁體中文文檔-traditional-chinese-documentation"><b>繁體中文</b></a> •
  <a href="#-日本語ドキュメント-japanese-documentation"><b>日本語</b></a> •
  <a href="#-한국어-문서-korean-documentation"><b>한국어</b></a> •
  <a href="#-quick-start--installation"><b>Quick Start</b></a> •
  <a href="#-how-to-enable-viewany"><b>How to Enable</b></a> •
  <a href="#-frequently-asked-questions-faq"><b>FAQ</b></a>
</p>

<p align="center">
  <a href="https://www.eycloud.net/" target="_blank">🌐 Official Website</a> &nbsp;|&nbsp;
  <a href="https://github.com/netproxy/ViewAny" target="_blank">🐙 GitHub Repo</a> &nbsp;|&nbsp;
  <a href="https://github.com/netproxy/ViewAny/releases" target="_blank">📦 Releases & VSIX</a> &nbsp;|&nbsp;
  <a href="https://github.com/netproxy/ViewAny/issues" target="_blank">🐛 Report Issue</a>
</p>

<a href="https://www.creem.io/payment/prod_Bhr8PSD0C8p30IbMxcvy8" target="_blank">
  <img src="https://raw.githubusercontent.com/netproxy/images/refs/heads/main/support_us_btn_small.png" alt="Support ViewAny" style="width:160px;height:48px;display:inline-block;margin:12px auto;" />
</a>

</div>

---

> 🔍 **Search Keywords / Marketplace Tags (English):**  
> `markdown` • `wysiwyg` • `typora` • `typora-alternative` • `word` • `docx` • `doc` • `docx-viewer` • `docx-editor` • `excel` • `xlsx` • `csv` • `spreadsheet` • `sheet` • `pdf` • `pdf-viewer` • `pdf-annotator` • `pdf-reader` • `pdf-editor` • `html` • `html-preview` • `html-wysiwyg` • `katex` • `math` • `mermaid` • `split-view` • `document-converter` • `office-suite` • `export-pdf` • `export-word`
>
> 🔍 **简体中文搜索关键词 (Search Tags):**  
> `VS Code 打开 Word` • `VS Code 查看 DOCX` • `VS Code 编辑 Word` • `Typora 替代` • `Markdown 所见即所得` • `VS Code Excel 表格` • `VS Code 查看 PDF` • `PDF 批注划线` • `HTML 响应式多视口预览` • `双分栏双向联动` • `Markdown 导出 Word` • `Markdown 转 PDF` • `本地 Office 办公套件`
>
> 🔍 **繁體中文搜尋關鍵字 (Search Tags):**  
> `VS Code 開啟 Word` • `VS Code 檢視 DOCX` • `VS Code 編輯 Word` • `Typora 替代` • `Markdown 所見即所得` • `VS Code Excel 表格` • `VS Code 檢視 PDF` • `PDF 註解劃線` • `HTML 響應式多視口預覽` • `雙分欄雙向連動` • `Markdown 匯出 Word` • `Markdown 轉 PDF` • `本機 Office 辦公套件`
>
> 🔍 **日本語検索キーワード (Search Tags):**  
> `VS Code Word 閲覧` • `VS Code DOCX 編集` • `Typora 代替` • `Markdown WYSIWYG` • `VS Code Excel 編集` • `VS Code PDF 閲覧` • `PDF 注釈 マーカー` • `HTML レスポンシブ プレビュー` • `2分割画面 リアルタイム同期` • `Markdown Word 変換` • `Markdown PDF 変換` • `ローカル Office スイート`
>
> 🔍 **한국어 검색 키워드 (Search Tags):**  
> `VS Code Word 열기` • `VS Code DOCX 뷰어` • `VS Code Word 편집` • `Typora 대체` • `Markdown 위지윅` • `VS Code Excel 스프레드시트` • `VS Code PDF 뷰어` • `PDF 주석 형광펜` • `HTML 반응형 뷰포트 미리보기` • `2분할 실시간 동기화` • `Markdown Word 변환` • `Markdown PDF 변환` • `로컬 오피스 스위트`

---

## 🌐 Language Navigation / 多语言快速跳转

- 🇬🇧 [**English Documentation**](#-english-documentation)
- 🇨🇳 [**简体中文文档 (Simplified Chinese)**](#-中文文档-chinese-documentation)
- 🇭🇰 [**繁體中文文檔 (Traditional Chinese)**](#-繁體中文文檔-traditional-chinese-documentation)
- 🇯🇵 [**日本語ドキュメント (Japanese)**](#-日本語ドキュメント-japanese-documentation)
- 🇰🇷 [**한국어 문서 (Korean)**](#-한국어-문서-korean-documentation)

---

# 🇬🇧 English Documentation

## 💡 Why ViewAny?

Developers, technical writers, researchers, and project managers often face constant context switching:

* ❌ **Leaving VS Code for Office Apps**: Opening a simple `.docx` specification or `.xlsx` test report forces you to wait for bloated desktop software (MS Office, WPS, LibreOffice) to launch.
* ❌ **Clunky Markdown Workflows**: Raw Markdown source code lacks instant typography feedback, while split-screen previews waste up to 50% of your monitor width. You miss the fluid, **Typora-style inline WYSIWYG experience**.
* ❌ **Cumbersome HTML Previews**: Debugging HTML templates requires firing up an external browser, manually resizing windows to inspect responsive breakpoints, and losing sync with code.
* ❌ **Weak PDF Experience**: Built-in or lightweight PDF viewers in VS Code rarely offer vector highlighters, pen markup, sticky text notes, or proper East Asian font rendering.
* ❌ **Sketchy Online Converters**: Converting documents between Markdown, Word, Excel, HTML, and PDF often drives you to ad-filled, untrusted web converters that compromise your private files.

✨ **ViewAny eliminates every single one of these friction points!**  
ViewAny transforms Visual Studio Code into a **complete, lightweight, 100% local document and office workstation**. Open, edit, annotate, and interconvert **Markdown (`.md`), Microsoft Word (`.docx`, `.doc`), Excel (`.xlsx`, `.xls`, `.csv`), HTML (`.html`, `.htm`), and PDF (`.pdf`)** without leaving your IDE.

---

## 📸 Interface Preview

<div align="center">

<img src="https://raw.githubusercontent.com/netproxy/images/refs/heads/main/sc1.png" alt="ViewAny Markdown WYSIWYG & Diagram Editing" style="max-width:95%;border-radius:8px;box-shadow:0 8px 24px rgba(0,0,0,0.12);margin:14px 0;" />

<img src="https://raw.githubusercontent.com/netproxy/images/refs/heads/main/sc2.png" alt="ViewAny Office, Spreadsheet & PDF Annotator" style="max-width:95%;border-radius:8px;box-shadow:0 8px 24px rgba(0,0,0,0.12);margin:14px 0;" />

</div>

---

## 🚀 Feature Deep Dive

### 1. 📝 Markdown WYSIWYG Editor (`.md`, `.markdown`)
*Transform VS Code into a seamless, distraction-free Typora alternative.*

* **Typora-Grade Inline Rich Text**: Type naturally without wrestling with raw Markdown tags. Headers, inline code, bold, italic, strikethrough, highlights, and quotes render instantly as you type.
* **Triple-Mode Flexibility**: Effortlessly toggle between **WYSIWYG Mode**, **Split View (Bidirectional Sync)**, and **Raw Source Code** with a single click or shortcut.
* **High-Precision Split-View Range Mapping & Smooth Scroll Sync**: An intelligent bidirectional AST mapping engine synchronizes cursor selections and smooth scrolling between visual rich text and raw Markdown source. It gracefully handles block math, quotes, tables, and Mermaid definitions without de-syncing.
* **8-Directional Stepless Image Resizing & Precision Controls**: Click any image to reveal 8 boundary-clamping resize handles with live dimension badges (`W × H px`). Enter explicit width or height in the floating toolbar (`W: ...`, `H: ...`), toggle alignments, add hyperlinks, and enjoy lossless HTML/Markdown serialization.
* **High-Fidelity Image Cut, Copy & Paste (`Ctrl+X / C / V`)**: Enjoy full clipboard integration with automatic size retention (exact pixel dimensions are preserved without fallback resets). Zero-leak lifecycle listeners instantly clean up resize borders and floating toolbars on deletion.
* **Interactive Mermaid Diagrams with Drag Handles**: Render and visually edit flowcharts, sequence diagrams, state machines, class diagrams, and mindmaps. Click any diagram to adjust dimensions via 8 handles or the floating toolbar (25%, 50%, 75%, 100% presets, custom width, alignment). Preferences are saved as standard HTML comments (`<!-- mermaid: width="540px" align="center" -->`), ensuring **100% compatibility with GitHub, Obsidian, and VS Code native previews**.
* **KaTeX Mathematics**: Flawless inline and standalone block math formulas ($\sum$, $\int$, matrices, square roots) with high-contrast presentation and vector clarity during PDF export:
  $$\int_{-\infty}^{+\infty} e^{-x^2} dx = \sqrt{\pi}$$
* **Interactive Tables & GFM Task Lists**: Add, remove, or reorder table rows/columns with one click. Check and toggle task list items interactively.
* **Smart Caret Navigation & Paragraph Breakout**: Click bottom canvas whitespace to jump directly to the end of the document; double-press `Enter` inside quotes, code blocks, or tables to cleanly escape into a fresh paragraph below.

---

### 2. 📄 Word (DOCX / DOC) Visual Editor
*Native A4-paginated viewing and bidirectional binary editing right inside your workspace.*

* **Authentic A4 Paper Pagination**: Accurately parses standard OpenXML structures, styles, margins, headers, and footers into faithful A4 printed pages.
* **Direct Binary `.docx` Saving**: Save your visual edits directly back into standard binary `.docx` files. Guaranteed 100% interoperability with Microsoft Word and WPS Office.
* **Accurate Empty Lines & Line-Box Calculation**: Retains author-defined line heights, indents, and empty paragraphs without collapsing or snowballing blank space on repeated saves.
* **Multi-Page Table Auto-Stitching**: Cross-page tables in A4 view are intelligently tracked and reverse-stitched upon save, preventing tables from being permanently severed into disconnected fragments.
* **Preserved Image Dimensions & Fonts**: Solves common docx-preview bugs by synchronizing CSS pixels with OpenXML EMUs. Font stacks resolve against document themes without reverting East Asian fonts to Western defaults.
* **Legacy `.doc` Extraction**: Seamlessly extracts and previews content from older binary `.doc` files.

---

### 3. 📊 Excel & CSV Spreadsheet Editor (`.xlsx`, `.xls`, `.csv`)
*Full-featured spreadsheet grid with formula calculations and multi-sheet management.*

* **Native Spreadsheet Grid**: Drag and drop cells, select rectangular ranges, adjust column widths and row heights, and insert or delete rows and columns dynamically.
* **Multi-Sheet Tab Navigation**: Switch between worksheets effortlessly, add new sheets, duplicate data, or rename sheet tabs.
* **Interactive Formula Builder & Engine**: Complete support for `=SUM(A1:A20)`, `=AVERAGE(...)`, `=COUNT(...)`, `=MAX(...)`, `=MIN(...)`. Includes toolbar formula dropdowns, auto-sum, click-to-reference, rectangular drag selections, and formula retention on disk save.
* **Lossless Binary `.xlsx` and `.csv` Export**: Edit financial sheets or CSV datasets, and save directly back into standard `.xlsx` or plain `.csv` without corrupting delimiters or encoding.

---

### 4. 🌐 HTML Multi-Viewport WYSIWYG Editor (`.html`, `.htm`, `.xhtml`)
*A built-in responsive studio and visual editor for web templates, emails, and static documents.*

* **5 Simulated Responsive Viewports**: Switch with one click between:
  - 📱 **Mobile** (`375px`)
  - 📟 **Tablet** (`768px`)
  - 💻 **Laptop** (`1024px`)
  - 🖥️ **Responsive** (Free canvas drag)
  - 🖨️ **Print Simulation** (A4 paper layout)
* **Intelligent Document Outline Tree (TOC)**: Automatically indexes all `H1`~`H6` headings. Features instant keyword filtering and smooth jump-to navigation.
* **Bidirectional HTML Source Sync**: Edit text, insert tables, style typography, or paste images in rich-text mode; your underlying HTML source updates in real-time.
* **Theme Tokens & Paper Zoom**: Switch among **Classic White**, **Eye-Care Sepia**, and **Dark Theme**, paired with stepless zooming from `75%` to `150%`.

---

### 5. 📑 PDF HD Viewer & Professional Annotator (`.pdf`)
*High-performance, offline PDF reader and editor with vector burning, page manipulation, and encrypted security.*

* **Mozilla PDF.js & @cantoo/pdf-lib Dual Engine**: High-fidelity vector rendering, continuous scrolling, two-page book view, fit-to-width, continuous zoom, and native byte-level PDF modification.
* **Native In-Place Disk Persistence & Vector Burning**: Doodle pens, highlighters, and sticky notes are burned directly into raw PDF byte streams via `@cantoo/pdf-lib` upon `Ctrl+S` / Save. Reopened files retain full fidelity, and the editor tab accurately tracks dirty state.
* **Undo / Redo Snapshot Stack**: Built-in 20-step deep undo/redo history for PDF annotations, covering drawing, dragging, text editing, erasing, and clearing operations.
* **Full-Fledged PDF Page Management & Operations**:
  - 🗑️ **Page Deletion**: Seamlessly delete single or multiple selected pages (with safety guard preserving the last remaining page) via toolbar or `Delete` key.
  - 🔄 **Page Rotation**: Clockwise and counterclockwise 90° page rotation with real-time viewport and coordinate sync.
  - 🔀 **Drag-and-Drop Reordering**: Intuitively reorder pages by dragging thumbnails in the sidebar with live drop indicators.
  - 📤 **Page Extraction**: Extract single or ranges of pages into a new standalone PDF file.
  - ➕ **Merge & Append**: Merge external PDF files directly into the active document at any designated position.
* **Encrypted PDF Security & Password-Protected Editing**:
  - Automatic `/Encrypt` dictionary detection to identify encrypted documents and user permissions.
  - Interactive password prompt to unlock protected PDFs.
  - Preserves encryption parameters and re-encrypts document upon saving.
  - Read-only fallback protection with banners and tooltips when permissions restrict modifications, alongside digital signature integrity warnings.
* **100% Offline Worker & Full CJK CMaps Support**: Pre-bundled local worker threads and East Asian character maps (CMaps) prevent missing glyphs and garbled text in complex academic formulas and Asian documents without any internet access.
* **Sidebar Page Thumbnails & Boundary Wheel Flipping**: Rapidly scan multi-page books with synchronized thumbnail centering and smooth mouse-wheel page turning when reaching page boundaries.
* **Complete Annotation Suite**:
  - 🖌️ **Pen Tool**: Freehand vector drawing with adjustable stroke width and custom colors.
  - 🖍️ **Highlighter Tool**: Semi-transparent marker to underline and emphasize crucial passages.
  - 💬 **Sticky Text Notes**: Drop rich-text comments and callouts anywhere on the canvas.
  - 🧹 **Precision Eraser**: Remove individual strokes or annotations in one click.
* **Export Annotated PDF**: Flatten and export crisp, high-resolution PDFs containing all your custom annotations.

---

### 6. 🔄 Universal Multi-Format Export & Document Converter
*Say goodbye to dubious online converters. Interconvert documents locally with zero data leakage.*

| Source Document | Target Formats | Features & Fidelity |
| :--- | :--- | :--- |
| **Markdown (`.md`)** | `PDF`, `Word (.docx)`, `HTML`, `Markdown` | Vector KaTeX formulas, syntax-highlighted code blocks, Mermaid diagrams |
| **Word (`.docx`)** | `PDF`, `HTML`, `Markdown`, `Word (.docx)` | Preserves A4 page flow, custom fonts, embedded tables, and images |
| **HTML (`.html`)** | `PDF`, `Word (.docx)`, `Markdown`, `HTML` | Clean styling inlining, responsive layout preservation |
| **Excel (`.xlsx`, `.csv`)**| `Excel (.xlsx)`, `CSV`, `HTML`, `PDF` | Accurate table borders, cell alignments, multi-sheet views |
| **PDF (`.pdf`)** | `Annotated PDF`, `Word (.docx)`, `HTML` | High-res vector markup retention, text and table extraction |

---

### 🎨 Modernized Toolbar & Polished IDE Experience

* **Two-Row Anti-Avalanche Toolbar**: Say goodbye to crowded toolbars wrapping into 4–5 chaotic lines. ViewAny utilizes an organized dual-row flex rail (Row 1: Formatting & VIP; Row 2: Layout, Viewports, Themes, Export) with smooth horizontal scrolling.
* **Responsive Compact Mode**: On narrower split panes (`<=1250px` / `<=900px`), verbose button labels automatically condense into clean icon buttons while preserving full hover tooltips.
* **Unified Find & Replace Widget (`Ctrl+F` / `Ctrl+H`)**: Native VS Code look-and-feel with smooth transition between find and replace rows, automated focus management, and zero duplicate instances.
* **CSS Variable Theme Tokens**: Blockquotes, code surfaces, scrollbars, and diagrams dynamically harmonize across **Classic**, **Eye-Care Sepia**, and **Dark** paper themes.

---

## 📋 Format Support Matrix

| Document Category | Extensions | Viewing | WYSIWYG Edit | Core Highlights | Output & Export |
| :--- | :--- | :---: | :---: | :--- | :--- |
| **Markdown** | `.md`, `.markdown` | ✅ | ✅ | Typora-like, 8-dir image/Mermaid resize, KaTeX, GFM tasks, split-sync | PDF, DOCX, HTML, MD |
| **Word Document** | `.docx`, `.doc` | ✅ | ✅ | A4 pagination, binary DOCX save, table stitching, line-box accuracy | PDF, DOCX, HTML, MD |
| **HTML Page** | `.html`, `.htm`, `.xhtml`| ✅ | ✅ | 5 Viewports (Mobile/Tablet/PC), Outline TOC, bi-directional sync | PDF, DOCX, MD, HTML |
| **Spreadsheets** | `.xlsx`, `.xls`, `.csv` | ✅ | ✅ | Formulas (=SUM/AVERAGE), multi-sheet tabs, grid resizing | XLSX, CSV, HTML, PDF |
| **PDF Documents** | `.pdf` | ✅ | ✅ | Offline CJK fonts, pen drawing, highlighters, sticky notes | Annotated PDF, DOCX, HTML |

---

## ⚡ Quick Start & Installation

### Option 1: Install from GitHub Releases (Recommended)

1. Head over to [ViewAny Releases](https://github.com/netproxy/ViewAny/releases).
2. Download the latest `viewany-3.0.11.vsix`.
3. Open VS Code, press `Ctrl+Shift+X` (`Cmd+Shift+X` on Mac) to open Extensions.
4. Click the **`⋯`** menu in the top-right corner $\rightarrow$ select **Install from VSIX...**.
5. Select the downloaded `.vsix` file.

Alternatively, install directly from your command line:
```bash
code --install-extension viewany-3.0.11.vsix
```

### Option 2: Install from VS Code Marketplace

Search for `ViewAny` in the Extensions view inside VS Code and click **Install**.

---

## 🎯 How to Enable ViewAny

ViewAny supports **Markdown (`.md`, `.markdown`)**, **Word (`.docx`, `.doc`)**, **Excel (`.xlsx`, `.xls`, `.csv`)**, **PDF (`.pdf`)**, and **HTML (`.html`, `.htm`, `.xhtml`)**. Once installed, you can easily activate and use ViewAny through any of the following methods:

### 1. Automatic Activation (Default Editor)
ViewAny registers itself as the default custom editor for all supported document types upon installation:
- In the Explorer sidebar, simply **click or double-click** any supported file (e.g. `README.md`, `spec.docx`, `budget.xlsx`, or `paper.pdf`). VS Code will automatically open it with ViewAny's dedicated WYSIWYG editor.

### 2. Method 1: Editor Title Bar Quick Toggle (Most Convenient)
If a file is currently open in the default plain-text / code editor:
- Look at the top-right corner of the editor title tab bar; you will see an eye icon **`👁️`** (Tooltip: `ViewAny: Switch to WYSIWYG Editor`);
- **Click the eye icon** to instantly switch into the ViewAny rich-text WYSIWYG editor.

### 3. Method 2: Explorer Context Menu
- In the VS Code file Explorer sidebar, **right-click** any supported document;
- Select **`ViewAny: Switch to WYSIWYG Editor`** from the context menu.

### 4. Method 3: Command Palette
- Open any supported file and press `Ctrl+Shift+P` (`Cmd+Shift+P` on macOS);
- Search for and run **`ViewAny: Switch to WYSIWYG Editor`**.

### 5. Method 4: Set as Default via "Open With..." (Fix Conflicts)
If another extension or the default text editor currently takes priority over your files:
1. In the file Explorer, **right-click** the file;
2. Select **`Open With...`**;
3. Choose the appropriate ViewAny editor:
   - `ViewAny: Markdown WYSIWYG Editor`
   - `ViewAny: Word (DOCX) Visual Editor`
   - `ViewAny: Excel Spreadsheet Visual Editor`
   - `ViewAny: PDF HD Viewer & Annotator`
   - `ViewAny: HTML Visual Web & Doc Viewer`
4. **Set as Permanent Default**: Select **`Configure default editor for '...'`** at the bottom of the list and choose ViewAny. VS Code will now remember and always use ViewAny for that extension.

> 💡 **Pro Tip: Bind Defaults Permanently in `settings.json`**  
> Press `Ctrl+,`, open your `settings.json`, and insert:
> ```json
> "workbench.editorAssociations": {
>   "*.md": "viewany.markdownEditor",
>   "*.markdown": "viewany.markdownEditor",
>   "*.docx": "viewany.docxEditor",
>   "*.doc": "viewany.docxEditor",
>   "*.xlsx": "viewany.sheetEditor",
>   "*.xls": "viewany.sheetEditor",
>   "*.csv": "viewany.sheetEditor",
>   "*.pdf": "viewany.pdfEditor",
>   "*.html": "viewany.htmlEditor",
>   "*.htm": "viewany.htmlEditor"
> }
> ```

---

## ⌨ Shortcuts & Workflows

| Action | Shortcut / Trigger | Description |
| :--- | :--- | :--- |
| **Open with ViewAny** | Single click in Explorer | Files with supported extensions open in ViewAny by default |
| **Switch Editor** | Right-click file $\rightarrow$ `ViewAny: Switch to WYSIWYG Editor` | Toggles from text editor to ViewAny |
| **Quick Toggle** | Click `👁️` in the Editor Tab bar | Instant toggle between raw code and WYSIWYG |
| **Find in Document** | `Ctrl + F` (`Cmd + F`) | Opens the compact search bar |
| **Find & Replace** | `Ctrl + H` (`Cmd + H`) | Expands search bar with replace controls |
| **Cut Image / Selection** | `Ctrl + X` (`Cmd + X`) | Cuts selected image with size metadata |
| **Undo / Redo** | `Ctrl + Z` / `Ctrl + Y` | Undo/redo with caret location restoration |
| **Export Document** | Click `📤 Export...` on toolbar | Opens multi-format conversion dialogue |
| **Table Navigation & Auto-Row** | `Tab` / `Shift + Tab` | Navigate cells; press `Tab` on the final cell to append a new row |
| **Table Floating Bar & Menu** | Focus cell / Right-click | Insert/delete rows & columns, align text, delete table |

---

## 🔒 Privacy & Security Guarantee

* 🛡️ **100% Local Processing**: All document parsing, rendering, formula evaluation, and multi-format conversions execute directly in your local VS Code process.
* 🚫 **Zero Cloud Dependencies**: No documents, keystrokes, formulas, or images are ever uploaded to any third-party or cloud server.
* 🏢 **Enterprise Ready**: Fully compliant with strict corporate air-gapped security policies and sensitive NDA projects.

---

## ❓ Frequently Asked Questions (FAQ)

#### Q1: Can ViewAny truly replace Typora inside VS Code?
**A:** Yes! ViewAny brings the fluid, distraction-free Typora experience straight into VS Code. It features live KaTeX math formula rendering, Mermaid diagrams with interactive drag-handles, interactive tables, task lists, code block syntax highlighting, and smooth split-view sync.

#### Q2: Does editing and saving a Word (`.docx`) file corrupt its layout?
**A:** No. ViewAny strictly utilizes the standard OpenXML specification. It preserves paragraph hierarchies, font formatting, table styles, and margins. When you save, it serializes directly back into binary `.docx` format, ensuring 100% compatibility with MS Office and WPS.

#### Q3: Why is the HTML Visual Editor useful for developers?
**A:** It acts as an integrated responsive design previewer. You can test email templates, static pages, or generated reports across Mobile (`375px`), Tablet (`768px`), and Desktop (`1024px`) viewports without leaving your code or opening an external browser.

#### Q4: Does the PDF viewer require an active internet connection?
**A:** Not at all. ViewAny bundles Mozilla's PDF.js Web Worker and comprehensive East Asian CJK CMaps locally. Formulas, Chinese/Japanese/Korean characters, and custom fonts render crisply in completely offline environments.

#### Q5: What are the differences between the Free and Pro VIP Editions?
**A:** The Free Edition provides complete viewing and WYSIWYG editing capabilities for Markdown, Word, HTML, Excel, and PDF files. Document export is free for single-page files ($\le 1$ page). Activating the Pro VIP Edition unlocks unlimited multi-page high-definition export across all formats, native Word OMML formula support, and priority updates.

---

# 🇨🇳 中文文档 (Chinese Documentation)

## 💡 为什么选择 ViewAny？

在软件开发、技术写作与日常办公中，我们经常被割裂的工具链困扰：

* ❌ **查看 Office 文档频繁跳出**：想看一眼需求文档 `.docx` 或测试用例 `.xlsx`，不得不离开 VS Code，等待启动沉重庞大的桌面 Office 或 WPS。
* ❌ **Markdown 纯源码编辑费力**：纯源码缺少富文本直观排版反馈；而 VS Code 默认的分屏预览又强行占用近一半屏幕。你无比怀念 **Typora 般丝滑沉浸的所见即所得体验**。
* ❌ **HTML 网页调试流程繁琐**：修改 HTML 模版或邮件样式时，需要在外置浏览器和编辑器之间反复横跳，无法快速切换手机、平板等不同视口做响应式测试。
* ❌ **PDF 阅读与标注功能简陋**：内置或普通 PDF 插件大多只支持简单阅读，缺少平滑涂鸦画笔、荧光笔高亮、便签批注以及离线 CJK 中日韩字库支持。
* ❌ **跨格式转换充斥隐私风险**：想把 Markdown 转成 Word/PDF，或把 Word 转为 Markdown，到处找在线转换网站，既有页数限制，又有源码与商业机密泄漏的风险。

✨ **ViewAny 为彻底终结这些痛点而生！**  
ViewAny 将 Visual Studio Code 全面升级为**轻量级、全能型的一站式本地办公与文档工作台**。一个插件，即可在本地流畅打开、可视化编辑、画笔批注与互转导出 **Markdown (`.md`)、Word (`.docx`, `.doc`)、Excel (`.xlsx`, `.xls`, `.csv`)、HTML (`.html`, `.htm`) 与 PDF (`.pdf`)**！

---

## 🚀 核心功能深度解析

### 1. 📝 Markdown 所见即所得编辑器 (`.md`, `.markdown`)
*在 VS Code 中畅享原汁原味的 Typora 级沉浸式富文本排版。*

* **媲美 Typora 的所见即所得**：敲击键盘即完成精美排版，彻底告别传统源码与预览窗口割裂的糟糕体验。完整支持多级标题、粗斜体、下划线、删除线、文字高亮及引用块。
* **三重视图随心切换**：支持「所见即所得 (WYSIWYG)」、「左右实时分屏 (Split)」与「纯源码 (Source)」一键快捷切换。
* **双分栏高精度选区穿透与滚动平滑联动**：独创 AST 双向区间映射算法，点击富文本即刻准确定位源码，源码修改即时平滑联动；能智能穿透复杂的 Markdown 符号标记、LaTeX 公式块与 Mermaid 图表定义。
* **图片 8 向自由无级缩放与微调工具栏**：选中图片立即显示 8 处边界吸附控制手柄，解除强制等比例约束，并实时显示宽高悬浮徽标（`W × H px`）。悬浮工具栏提供 `W:` 与 `H:` 数值精准输入框、对齐切换与超链接编辑，支持无损写回 Markdown/HTML 属性。
* **图片高保真剪切/复制/粘贴与边框自动清理**：支持 `Ctrl+X` / `Ctrl+C` / `Ctrl+V`，剪贴板完整记录自定义宽高并像素级还原；内嵌 DOM 生命周期监听机制，图片删除瞬间自动销毁手柄与工具栏，绝不残留虚线边框。
* **Mermaid 流程图交互式拖拽缩放**：所见即所得渲染流程图、时序图、甘特图、类图与脑图。点击图表唤起 8 向调整手柄与浮动工具栏（预设 25%、50%、75%、100% 快捷比例，支持精准宽度数值输入）。采用标准 HTML 注释元数据（`<!-- mermaid: width="520px" align="center" -->`）纯净存储，**100% 兼容 GitHub、Obsidian 与 VS Code 原生预览**。
* **KaTeX 高清数学公式**：行内与独立块级公式矢量呈现，在导出 PDF 时保持白底高对比度与矢量无损，公式绝不溢出或被边缘裁剪：
  $$\int_{0}^{+\infty} e^{-x^2} dx = \frac{\sqrt{\pi}}{2}$$
* **交互式表格增删与 GFM 待办任务**：一键插入、追加或删除行列；直接在可视化界面勾选完成任务清单。
* **智能文末光标与跳出段落**：点击页面底部空白瞬间聚焦文末；在引用块、代码块、表格中双击回车自动跳出至下方标准段落，完整保留主动键入的空行。

---

### 2. 📄 Word (DOCX / DOC) 可视化文档编辑器
*真正的 A4 拟真分页视图，支持二进制 DOCX 本地直接保存。*

* **真实 A4 拟真分页排版**：严格基于 OpenXML 标准规范，精准还原页边距、字号行距、段落缩进、表格样式与页眉页脚。
* **直接保存为标准二进制 `.docx`**：可视化编辑后按 `Ctrl+S` 直接回写为二进制 `.docx` 文件，与 Microsoft Office、WPS 完美互通。
* **精准空行与行框计算**：彻底解决多次保存后空行滚雪球膨胀或行高塌陷的行业难题，还原原文档段落层次。
* **跨页表格逆向自动缝合**：A4 视图中被分页算法切分的跨页大表格，在保存或导出时自动缝合回原生单一表格结构，保留完整排版。
* **图片与字体样式精准保护**：修复二次保存图片尺寸回退问题；字体解析严格继承文档主题字体，防止中文字体被误覆盖为西文字体。
* **支持经典 `.doc` 二进制提取预览**。

---

### 3. 📊 Excel & CSV 电子表格编辑器 (`.xlsx`, `.xls`, `.csv`)
*集成式表格数据处理网格，支持常用公式与多工作表。*

* **完整表格交互**：单元格拖拽填充、矩形区域框选、列宽与行高自由拉伸、行列动态增删。
* **多工作表 (Multi-Sheet) 标签管理**：自由切换不同工作表、新建 Sheet 或重命名工作表标签。
* **内置公式自动计算与便捷编制**：完整支持 `=SUM(A1:A20)`、`=AVERAGE(...)`、`=COUNT(...)`、`=MAX(...)`、`=MIN(...)` 等运算；提供工具栏函数库下拉、求和下拉、点选单元格与拖拽选区自动注入引用，保存真实保留写真公式。
* **双向无损保存与导出**：修改后直接保存回标准 `.xlsx` 或纯文本 `.csv` 文件，自动维护文本编码与分隔符。

---

### 4. 🌐 HTML 网页多视口可视化预览与编辑 (`.html`, `.htm`, `.xhtml`)
*专为前端模版、富文本邮件、报表设计的响应式可视化工作台。*

* **5 种模拟视口自由切换**：
  - 📱 **手机端 (Mobile 375px)**
  - 📟 **平板端 (Tablet 768px)**
  - 💻 **笔记本 (Laptop 1024px)**
  - 🖥️ **自适应 (Responsive 自由画布拉伸)**
  - 🖨️ **A4 打印拟真 (Print 纸张排版)**
* **智能大纲树 (TOC) 导航**：自动抽取全部 H1~H6 标题，支持实时关键字过滤筛选与点击极速跳转。
* **双向源码实时同步**：所见即所得模式下修改排版、增删表格或插入图片，底层 HTML 源码即刻同步更新。
* **纸张主题与无级缩放**：经典白纸、护眼浅黄、沉浸深色三种模式，支持 75%~150% 连续缩放。

---

### 5. 📑 PDF 高清阅读与专业批注套件 (`.pdf`)
*高性能离线 PDF 阅读与编辑平台，配备底层矢量烧录、页面编排与加密文档全套能力。*

* **Mozilla PDF.js 与 @cantoo/pdf-lib 双引擎驱动**：平滑滚动、适应页宽、双页并排与任意比例缩放；底层直接操作 PDF 二进制流。
* **原文件真实保存与批注矢量烧录**：涂鸦画笔、荧光笔、便签批注全面支持通过快捷键 `Ctrl+S` 或保存按钮直接写回本地 PDF 原文件；支持 VS Code 标签页未保存脏状态小圆点与动态提示，重新打开文件时批注图层无损呈现。
* **完备的撤销/重做 (Undo / Redo) 历史栈**：内置 20 步深度快照历史栈，全面覆盖画笔绘制、荧光笔标注、便签新增/编辑/拖动、橡皮擦除以及全量清空等完整生命周期。
* **全功能 PDF 页面编排与管理**：
  - 🗑️ **页面删除**：支持多选页面一键删除（自动保留最后一页安全兜底），配合 `Delete` 快捷键。
  - 🔄 **页面旋转**：支持单页或批量向左/向右 90° 旋转，视口与坐标系实时同步换算。
  - 🔀 **缩略图拖拽重排**：在侧边栏缩略图列表中支持直观的拖拽手势重排页面顺序，并在保存时重组页面树结构。
  - 📤 **页面提取**：支持将选中的单页或连续多页一键提取并另存为独立的 PDF 文件。
  - ➕ **合并追加**：支持从本地选择外部 PDF 文件，直接合并并追加到当前文档的指定位置。
* **加密 PDF 安全防护与口令解锁编辑体系**：
  - 字节级 `/Encrypt` 字典主动扫描探测，精准识别加密状态与各级权限位。
  - 支持在打开或操作时弹出密码输入框解锁受保护的 PDF。
  - 保存时自动继承原加密规格重新加密写盘；附带电子签名失效预警保护。
  - 对无编辑权限的文档提供完备的只读保护横幅与操作禁用提示。
* **全离线 Worker 与 CJK 中日韩字库内置**：本地内置渲染 Worker 与字库 CMaps，彻底杜绝包含复杂数学公式或东亚字符的 PDF 渲染乱码、缺字或白屏，毫秒级极速打开。
* **侧边栏缩略图与边缘滚轮翻页**：快速预览章节页面，滚轮触底/触顶顺畅翻页，侧边栏缩略图自动同步居中。
* **全功能批注工具箱**：
  - 🖌️ **涂鸦画笔 (Pen)**：自定义笔触粗细与颜色，自由圈画。
  - 🖍️ **荧光高亮笔 (Highlighter)**：半透明高亮标注关键段落。
  - 💬 **富文本便签 (Text Note)**：在任意位置放置文本批注。
  - 🧹 **矢量橡皮擦 (Eraser)**：一键轻松擦除笔迹。
* **含批注高清无损导出**：完整将批注图层压制并导出为高清 PDF。

---

### 6. 🔄 跨格式自由转换与多功能导出
*告别充斥广告与限制的在线转换网站，在本地安全完成文档格式互转。*

| 源文件类型 | 目标格式 | 转换特色与质量保证 |
| :--- | :--- | :--- |
| **Markdown (`.md`)** | `PDF`, `Word (.docx)`, `HTML`, `Markdown` | KaTeX 公式矢量排版、代码语法高亮、Mermaid 矢量图表 |
| **Word (`.docx`)** | `PDF`, `HTML`, `Markdown`, `Word (.docx)` | 保留 A4 版面流式、样式字体、图片与表格结构 |
| **HTML (`.html`)** | `PDF`, `Word (.docx)`, `Markdown`, `HTML` | 样式精准内联，保留响应式布局排版 |
| **Excel (`.xlsx`, `.csv`)**| `Excel (.xlsx)`, `CSV`, `HTML`, `PDF` | 单元格对齐保真、表格线清晰、多 Sheet 支持 |
| **PDF (`.pdf`)** | `含批注 PDF`, `Word (.docx)`, `HTML` | 保留矢量批注，文字与表格高保真提取 |

---

### 🎨 匠心打造的工具栏与 IDE 级使用体验

* **两行防雪崩固定轨道工具栏**：彻底告别窗口变窄时工具栏折成 4~5 行并严重侵占编辑高度的尴尬。主格式行与辅助功能行双轨排布，支持平滑横向滑动。
* **窄屏响应式紧凑模式**：在窄分屏或侧边栏拉伸时（`<=1250px` / `<=900px`），冗长文本按钮自动收敛为精致图标按钮，同时保留完整悬浮 Tooltip 提示。
* **平滑查找替换浮窗 (`Ctrl+F` / `Ctrl+H`)**：贴合 VS Code 原生设计，单行搜索与替换行平滑展开收起，焦点自动跳转，杜绝多浮窗重复创建缺陷。
* **纸张主题令牌化**：引用块、代码块、滚动条与图表全面接入 CSS 变量主题，经典白、护眼浅黄与深色模式皆可呈现最佳对比度。

---

## 📋 格式支持与导出全览

| 文档类型 | 支持后缀 | 查看模式 | 所见即所得编辑 | 核心特色 | 支持导出格式 |
| :--- | :--- | :---: | :---: | :--- | :--- |
| **Markdown** | `.md`, `.markdown` | ✅ | ✅ | Typora 级体验、8向图片与图表缩放、KaTeX、GFM 清单、双分栏联动 | PDF, Word, HTML, Markdown |
| **Word 文档** | `.docx`, `.doc` | ✅ | ✅ | A4 拟真分页、二进制 DOCX 保存、跨页表格缝合、行框精准还原 | PDF, Word, HTML, Markdown |
| **HTML 网页** | `.html`, `.htm`, `.xhtml`| ✅ | ✅ | 5 种视口模拟、智能大纲树 (TOC)、源码实时双向同步 | PDF, Word, Markdown, HTML |
| **电子表格** | `.xlsx`, `.xls`, `.csv` | ✅ | ✅ | 常用公式计算、多工作表 Sheet 标签、网格自由增删拖拽 | Excel, CSV, HTML, PDF |
| **PDF 文档** | `.pdf` | ✅ | ✅ | 本地离线 Worker 与中文字库、画笔涂鸦、荧光高亮、便签笔记 | 含批注 PDF, Word, HTML |

---

## ⚡ 快速开始与安装

### 方式 1：通过 GitHub Releases 安装（推荐）

1. 访问 [ViewAny Releases](https://github.com/netproxy/ViewAny/releases)。
2. 下载最新版 `viewany-3.0.11.vsix` 安装包。
3. 打开 VS Code，按下快捷键 `Ctrl+Shift+X` 打开扩展面板。
4. 点击扩展面板右上角 **`⋯`**（更多操作）菜单 $\rightarrow$ 选择 **「从 VSIX 安装...」**。
5. 选择下载好的 `.vsix` 文件即可完成安装。

或在终端中执行一键安装指令：
```bash
code --install-extension viewany-3.0.11.vsix
```

### 方式 2：从 VS Code 官方市场安装

在 VS Code 扩展市场中搜索 `ViewAny` 并点击 **安装** 即可。

---

## 🎯 如何启用 ViewAny 功能

ViewAny 支持 **Markdown (`.md`, `.markdown`)**、**Word (`.docx`, `.doc`)**、**Excel (`.xlsx`, `.xls`, `.csv`)**、**PDF (`.pdf`)** 和 **HTML (`.html`, `.htm`, `.xhtml`)**。安装完成后，您可以通过以下几种方式轻松启用 ViewAny：

### 1. 自动启用（开箱即用）
插件安装成功后，已在 VS Code 中注册为对应格式的默认编辑器：
- 在左侧资源管理器中，**直接单击或双击**任意支持的文件（例如 `README.md`、`doc.docx`、`table.xlsx` 或 `file.pdf`），VS Code 将自动调用 ViewAny 专属可视化编辑器打开。

### 2. 方式一：编辑器顶栏一键切换按钮（最常用）
若文件当前正在以普通纯文本或代码方式浏览：
- 查看编辑器右上角的标签工具栏，会看到一个眼睛图标 **`👁️`**（悬停提示：`ViewAny: 切换为所见即所得编辑器`）；
- **点击该图标**，即可瞬间无缝切入 ViewAny 所见即所得编辑/预览界面。

### 3. 方式二：资源管理器右键菜单
- 在左侧资源管理器（Explorer）文件树中，**右键点击**任意支持的文件；
- 在弹出菜单中选择 **「ViewAny: 切换为所见即所得编辑器」** 即可。

### 4. 方式三：通过命令面板 (Command Palette)
- 在当前打开的文件窗口中按下快捷键 `Ctrl+Shift+P`（macOS 为 `Cmd+Shift+P`）；
- 输入并执行 **`ViewAny: 切换为所见即所得编辑器`**（英文系统为 `ViewAny: Switch to WYSIWYG Editor`）。

### 5. 方式四：手动配置默认打开方式（解决被其他插件占用问题）
若您此前安装过其他 Markdown/Office/PDF 插件，或者文件默认以纯文本代码方式打开，可快速将其指定为 ViewAny：
1. 在左侧资源管理器中 **右键点击** 该文件；
2. 选择 **「打开方式...」(Open With...)**；
3. 在弹出的列表中选择对应的 ViewAny 编辑器：
   - `ViewAny: Markdown 所见即所得编辑器`
   - `ViewAny: Word (DOCX) 可视化编辑器`
   - `ViewAny: Excel 表格可视化编辑器`
   - `ViewAny: PDF 高清阅读与批注器`
   - `ViewAny: HTML 可视化网页与文档查看器`
4. **永久设为默认**：在弹出的打开方式列表最底部，点击 **「配置 "*.<后缀>" 的默认编辑器...」(Configure default editor for '...' )**，并选中对应的 ViewAny 编辑器。以后再次打开该类型文件时，将一律默认使用 ViewAny。

> 💡 **进阶技巧：在 VS Code 全局设置中永久绑定**  
> 打开设置（快捷键 `Ctrl+,`），点击右上角的「打开设置 (JSON)」图标，在 `settings.json` 中加入以下配置：
> ```json
> "workbench.editorAssociations": {
>   "*.md": "viewany.markdownEditor",
>   "*.markdown": "viewany.markdownEditor",
>   "*.docx": "viewany.docxEditor",
>   "*.doc": "viewany.docxEditor",
>   "*.xlsx": "viewany.sheetEditor",
>   "*.xls": "viewany.sheetEditor",
>   "*.csv": "viewany.sheetEditor",
>   "*.pdf": "viewany.pdfEditor",
>   "*.html": "viewany.htmlEditor",
>   "*.htm": "viewany.htmlEditor"
> }
> ```

---

## ⌨ 使用技巧与快捷键

| 操作场景 | 快捷方式 / 触发动作 | 功能说明 |
| :--- | :--- | :--- |
| **默认打开** | 在资源管理器中单击支持的文件 | 自动调用 ViewAny 对应专属编辑器打开 |
| **右键切换** | 右键文件 $\rightarrow$ `ViewAny: 切换为所见即所得编辑器` | 在纯文本源码与 ViewAny 编辑器之间自由切换 |
| **顶栏快捷切换** | 点击右上角标签栏的 `👁️` 按钮 | 源码编辑与所见即所得视图无缝互切 |
| **查找内容** | `Ctrl + F` (`Cmd + F`) | 呼出轻量查找浮窗 |
| **查找与替换** | `Ctrl + H` (`Cmd + H`) | 展开包含替换行的增强浮窗 |
| **剪切选区/图片** | `Ctrl + X` (`Cmd + X`) | 携带尺寸元数据剪切图片，自动销毁边框手柄 |
| **撤销与重做** | `Ctrl + Z` / `Ctrl + Y` | 撤销与恢复操作，精准还原光标落点 |
| **导出文档** | 点击工具栏 `📤 导出...` 按钮 | 呼出多格式转换与高质量导出面板 |
| **表格快速导航与末尾增行** | `Tab` / `Shift + Tab` | 单元格间平滑跳格；在末尾单元格按 `Tab` 自动新增下一行 |
| **表格悬浮工具栏与右键菜单** | 点击单元格或右键表格 | 快速在上方/下方增行、左侧/右侧增列、删除行/列/表、居中对齐 |

---

## 🔒 100% 离线与隐私保护

* 🛡️ **纯本地环境运行**：所有文件的语法解析、富文本渲染、公式运算及格式转换均在本地 VS Code 进程内完成。
* 🚫 **绝无数据外传**：插件不向任何外部服务器发送你的文档正文、图片或统计信息。
* 🏢 **契合企业合规**：完美支持纯局域网与物理隔离（Air-gapped）高密开发环境，无泄密风险。

---

## ❓ 常见问题解答 (FAQ)

#### Q1: ViewAny 可以完全替代 Typora 吗？
**答：** 完全可以！ViewAny 在 VS Code 内部重塑了与 Typora 高度一致的无缝沉浸式富文本编辑体验。不仅支持实时 KaTeX 数学公式渲染、Mermaid 交互式图表拖拽、表格与代码高亮，更原生依托 VS Code 的文件树与版本控制系统，无需在多个软件间频繁切换。

#### Q2: 编辑保存 Word (.docx) 会破坏原本样式吗？
**答：** 不会。ViewAny 严格遵循微软 OpenXML 标准协议，对标题层级、字体字号、色彩、表格及段落缩进进行解析与保真重构，保存时直接序列化为二进制 `.docx` 文件，确保与 Microsoft Office 及 WPS 100% 互通。

#### Q3: HTML 可视化编辑有什么实用价值？
**答：** 非常适合前端研发、全栈工程师与运营人员直接在编辑器中预览调试 HTML 模版、富文本邮件及自动化测试报表。提供手机 (375px)、平板 (768px)、电脑 (1024px) 视口无缝切换，并支持大纲定位与源码双向实时同步。

#### Q4: PDF 阅读器在无网或内网环境下能否稳定工作？
**答：** 可以。ViewAny 完整内嵌本地 Mozilla PDF.js 核心 Worker 与全套 CJK（中日韩）CMaps 标准字库，完全不依赖外网 CDN，公式、中文及专业文献在内网离线环境下毫秒级极速打开且永不乱码。

#### Q5: 免费版与 Pro 尊享专业版有什么区别？
**答：** ViewAny 免费版已向所有用户开放对 Markdown、Word (.docx/.doc)、HTML、Excel 电子表格与 PDF 的全套查看与所见即所得编辑功能；导出功能对单页（$\le 1$ 页）文件永久免费开放。激活尊享专业版后，可解锁全格式无限制多页超清导出、Word 原生 OMML 公式编辑以及终身 VIP 升级支持。

---

## 💖 支持与社区

如果 ViewAny 帮助你提升了文档与办公效率，欢迎给予支持或反馈建议：

* 🌟 **给项目点个 Star**：[GitHub - netproxy/ViewAny](https://github.com/netproxy/ViewAny)
* 🐛 **提交 Bug 或建议**：[GitHub Issue Tracker](https://github.com/netproxy/ViewAny/issues)
* ☕ **赞助开发者持续维护**：[Sponsor ViewAny on Creem](https://www.creem.io/payment/prod_Bhr8PSD0C8p30IbMxcvy8)
* 🏠 **官方网站**：[https://www.eycloud.net/](https://www.eycloud.net/)

---

# 🇭🇰 繁體中文文檔 (Traditional Chinese Documentation)

## 💡 為什麼選擇 ViewAny？

在軟體開發、技術寫作與日常辦公中，我們經常被割裂的工具鏈困擾：

* ❌ **檢視 Office 文件頻繁跳出**：想看一眼規格文件 `.docx` 或測試用例 `.xlsx`，不得不離開 VS Code，等待啟動沉重龐大的桌面 Office 或 WPS。
* ❌ **Markdown 純原始碼編輯費力**：純原始碼缺少富文本直觀排版回饋；而 VS Code 預設的分屏預覽又強行佔用近一半螢幕。你無比懷念 **Typora 般絲滑沉浸的所見即所得體驗**。
* ❌ **HTML 網頁除錯流程繁瑣**：修改 HTML 樣板或郵件樣式時，需要在外置瀏覽器和編輯器之間反覆橫跳，無法快速切換手機、平板等不同視口做響應式測試。
* ❌ **PDF 閱讀與標註功能簡陋**：內建或普通 PDF 外掛大多只支援簡單閱讀，缺少平滑塗鴉畫筆、螢光筆高亮、便簽註解以及離線 CJK 中日韓字庫支援。
* ❌ **跨格式轉換充斥隱私風險**：想把 Markdown 轉成 Word/PDF，或把 Word 轉為 Markdown，到處找線上轉換網站，既有頁數限制，又有原始碼與商業機密洩漏的風險。

✨ **ViewAny 為徹底終結這些痛點而生！**  
ViewAny 將 Visual Studio Code 全面升級為**輕量級、全能型的一站式本機辦公與文件工作台**。一個外掛，即可在本機流暢開啟、視覺化編輯、畫筆標註與互轉匯出 **Markdown (`.md`)、Word (`.docx`, `.doc`)、Excel (`.xlsx`, `.xls`, `.csv`)、HTML (`.html`, `.htm`) 與 PDF (`.pdf`)**！

---

## 🚀 核心功能深度解析

### 1. 📝 Markdown 所見即所得編輯器 (`.md`, `.markdown`)
*在 VS Code 中暢享原汁原味的 Typora 級沉浸式富文本排版。*

* **媲美 Typora 的所見即所得**：敲擊鍵盤即完成精美排版，徹底告別傳統原始碼與預覽視窗割裂的糟糕體驗。完整支援多級標題、粗斜體、底線、刪除線、文字高亮及引用區塊。
* **三重檢視隨心切換**：支援「所見即所得 (WYSIWYG)」、「左右即時分屏 (Split)」與「純原始碼 (Source)」一鍵快捷切換。
* **雙分欄高精度選區穿透與滾動平滑連動**：獨創 AST 雙向區間映射演算法，點擊富文本即刻準確定位原始碼，原始碼修改即時平滑連動；能智慧穿透複雜的 Markdown 符號標記、LaTeX 公式區塊與 Mermaid 圖表定義。
* **圖片 8 向自由無級縮放與微調工具列**：選中圖片立即顯示 8 處邊界吸附控制手柄，解除強制等比例約束，並即時顯示寬高懸浮徽標（`W × H px`）。懸浮工具列提供 `W:` 與 `H:` 數值精準輸入框、對齊切換與超連結編輯，支援無損寫回 Markdown/HTML 屬性。
* **圖片高保真剪下/複製/貼上與邊框自動清理**：支援 `Ctrl+X` / `Ctrl+C` / `Ctrl+V`，剪貼簿完整記錄自訂寬高並像素級還原；內嵌 DOM 生命週期監聽機制，圖片刪除瞬間自動銷毀手柄與工具列，絕不殘留虛線邊框。
* **Mermaid 流程圖互動式拖曳縮放**：所見即所得渲染流程圖、循序圖、甘特圖、類別圖與心智圖。點擊圖表喚起 8 向調整手柄與浮動工具列（預設 25%、50%、75%、100% 快捷比例，支援精準寬度數值輸入）。採用標準 HTML 註釋元數據（`<!-- mermaid: width="520px" align="center" -->`）純淨儲存，**100% 相容 GitHub、Obsidian 與 VS Code 原生預覽**。
* **KaTeX 高畫質數學公式**：行內與獨立區塊級公式向量呈現，在匯出 PDF 時保持白底高對比度與向量無損，公式絕不溢出或被邊緣裁剪：
  $$\int_{0}^{+\infty} e^{-x^2} dx = \frac{\sqrt{\pi}}{2}$$
* **互動式表格增刪與 GFM 待辦任務**：一鍵插入、追加或刪除行列；直接在視覺化介面勾選完成任務清單。
* **智慧文末游標與跳出段落**：點擊頁面底部空白瞬間聚焦文末；在引用區塊、程式碼區塊、表格中連按兩次回車自動跳出至下方標準段落，完整保留主動鍵入的空白行。

---

### 2. 📄 Word (DOCX / DOC) 視覺化文件編輯器
*真正的 A4 擬真分頁檢視，支援二進位 DOCX 本機直接儲存。*

* **真實 A4 擬真分頁排版**：嚴格基於 OpenXML 標準規範，精準還原頁邊距、字級行距、段落縮排、表格樣式與頁首頁尾。
* **直接儲存為標準二進位 `.docx`**：視覺化編輯後按 `Ctrl+S` 直接回寫為二進位 `.docx` 檔案，與 Microsoft Office、WPS 完美互通。
* **精準空白行與行框計算**：徹底解決多次儲存後空白行滾雪球膨脹或行高塌陷的行業難題，還原原文件段落層次。
* **跨頁表格逆向自動縫合**：A4 檢視中被分頁演算法切分的跨頁大表格，在儲存或匯出時自動縫合回原生單一表格結構，保留完整排版。
* **圖片與字型樣式精準保護**：修復二次儲存圖片尺寸回退問題；字型解析嚴格繼承文件主題字型，防止中文字型被誤覆蓋為西文字型。
* **支援經典 `.doc` 二進位提取預覽**。

---

### 3. 📊 Excel & CSV 試算表編輯器 (`.xlsx`, `.xls`, `.csv`)
*整合式表格資料處理網格，支援常用公式與多工作表。*

* **完整表格互動**：儲存格拖曳填滿、矩形區域框選、欄寬與列高自由拉伸、行列動態增刪。
* **多工作表 (Multi-Sheet) 標籤管理**：自由切換不同工作表、新建 Sheet 或重新命名工作表標籤。
* **內建公式自動計算與便捷編制**：完整支援 `=SUM(A1:A20)`、`=AVERAGE(...)`、`=COUNT(...)`、`=MAX(...)`、`=MIN(...)` 等運算；提供工具列函數庫下拉、求和下拉、點選儲存格與拖曳選區自動注入引用，儲存真實保留寫真公式。
* **雙向無損儲存與匯出**：修改後直接儲存回標準 `.xlsx` 或純文字 `.csv` 檔案，自動維護文字編碼與分隔符號。

---

### 4. 🌐 HTML 網頁多視口視覺化預覽與編輯 (`.html`, `.htm`, `.xhtml`)
*專為前端樣板、富文本郵件、報表設計的響應式視覺化工作台。*

* **5 種模擬視口自由切換**：
  - 📱 **手機端 (Mobile 375px)**
  - 📟 **平板端 (Tablet 768px)**
  - 💻 **筆記型電腦 (Laptop 1024px)**
  - 🖥️ **自適應 (Responsive 自由畫布拉伸)**
  - 🖨️ **A4 列印擬真 (Print 紙張排版)**
* **智慧大綱樹 (TOC) 導覽**：自動抽取全部 H1~H6 標題，支援即時關鍵字過濾篩選與點擊極速跳轉。
* **雙向原始碼即時同步**：所見即所得模式下修改排版、增刪表格或插入圖片，底層 HTML 原始碼即刻同步更新。
* **紙張主題與無級縮放**：經典白紙、護眼淺黃、沉浸深色三種模式，支援 75%~150% 連續縮放。

---

### 5. 📑 PDF 高畫質閱讀與專業註解套件 (`.pdf`)
*高效能離線 PDF 閱讀器，配備完備的向量畫筆與標記工具。*

* **Mozilla PDF.js 核心驅動**：平滑滾動、適應頁寬、雙頁並排與任意比例縮放。
* **全離線 Worker 與 CJK 中日韓字庫內建**：本機內建渲染 Worker 與字庫 CMaps，徹底杜絕包含複雜數學公式或東亞字元的 PDF 渲染亂碼、缺字或白屏，毫秒級極速開啟。
* **側邊欄縮圖與邊緣滾輪翻頁**：快速預覽章節頁面，滾輪觸底/觸頂順暢翻頁，側邊欄縮圖自動同步居中。
* **全功能註解工具箱**：
  - 🖌️ **塗鴉畫筆 (Pen)**：自訂筆觸粗細與顏色，自由圈畫。
  - 🖍️ **螢光高亮筆 (Highlighter)**：半透明高亮標註關鍵段落。
  - 💬 **富文本便簽 (Text Note)**：在任意位置放置文字註解。
  - 🧹 **向量橡皮擦 (Eraser)**：一鍵輕鬆擦除筆跡。
* **含註解高畫質無損匯出**：完整將註解圖層壓制並匯出為高畫質 PDF。

---

### 6. 🔄 跨格式自由轉換與多功能匯出
*告別充斥廣告與限制的線上轉換網站，在本機安全完成文件格式互轉。*

| 來源檔案類型 | 目標格式 | 轉換特色與品質保證 |
| :--- | :--- | :--- |
| **Markdown (`.md`)** | `PDF`, `Word (.docx)`, `HTML`, `Markdown` | KaTeX 公式向量排版、程式碼語法高亮、Mermaid 向量圖表 |
| **Word (`.docx`)** | `PDF`, `HTML`, `Markdown`, `Word (.docx)` | 保留 A4 版面流式、樣式字型、圖片與表格結構 |
| **HTML (`.html`)** | `PDF`, `Word (.docx)`, `Markdown`, `HTML` | 樣式精準內嵌，保留響應式版面排版 |
| **Excel (`.xlsx`, `.csv`)**| `Excel (.xlsx)`, `CSV`, `HTML`, `PDF` | 儲存格對齊保真、表格線清晰、多 Sheet 支援 |
| **PDF (`.pdf`)** | `含註解 PDF`, `Word (.docx)`, `HTML` | 保留向量註解，文字與表格高保真擷取 |

---

### 🎨 匠心打造的工具列與 IDE 級使用體驗

* **兩行防雪崩固定軌道工具列**：徹底告別視窗變窄時工具列折成 4~5 行並嚴重侵占編輯高度的尷尬。主格式行與輔助功能行雙軌排布，支援平滑橫向滑動。
* **窄螢幕響應式緊湊模式**：在窄分屏或側邊欄拉伸時（`<=1250px` / `<=900px`），冗長文字按鈕自動收斂為精緻圖示按鈕，同時保留完整懸浮 Tooltip 提示。
* **平滑尋找取代浮動視窗 (`Ctrl+F` / `Ctrl+H`)**：貼合 VS Code 原生設計，單行搜尋與取代行平滑展開收起，焦點自動跳轉，杜絕多浮動視窗重複建立缺陷。
* **紙張主題令牌化**：引用區塊、程式碼區塊、捲軸與圖表全面接入 CSS 變數主題，經典白、護眼淺黃與深色模式皆可呈現最佳對比度。

---

## 📋 格式支援與匯出全覽

| 文件類型 | 支援後綴 | 檢視模式 | 所見即所得編輯 | 核心特色 | 支援匯出格式 |
| :--- | :--- | :---: | :---: | :--- | :--- |
| **Markdown** | `.md`, `.markdown` | ✅ | ✅ | Typora 級體驗、8向圖片與圖表縮放、KaTeX、GFM 清單、雙分欄連動 | PDF, Word, HTML, Markdown |
| **Word 文件** | `.docx`, `.doc` | ✅ | ✅ | A4 擬真分頁、二進位 DOCX 儲存、跨頁表格縫合、行框精準還原 | PDF, Word, HTML, Markdown |
| **HTML 網頁** | `.html`, `.htm`, `.xhtml`| ✅ | ✅ | 5 種視口模擬、智慧大綱樹 (TOC)、原始碼即時雙向同步 | PDF, Word, Markdown, HTML |
| **試算表** | `.xlsx`, `.xls`, `.csv` | ✅ | ✅ | 常用公式計算、多工作表 Sheet 標籤、網格自由增刪拖曳 | Excel, CSV, HTML, PDF |
| **PDF 文件** | `.pdf` | ✅ | ✅ | 本機離線 Worker 與中文字庫、畫筆塗鴉、螢光高亮、便簽筆記 | 含註解 PDF, Word, HTML |

---

## ⚡ 快速開始與安裝

### 方式 1：透過 GitHub Releases 安裝（推薦）

1. 造訪 [ViewAny Releases](https://github.com/netproxy/ViewAny/releases)。
2. 下載最新版 `viewany-3.0.11.vsix` 安裝包。
3. 開啟 VS Code，按下快捷鍵 `Ctrl+Shift+X` 開啟擴充套件面板。
4. 點擊擴充套件面板右上角 **`⋯`**（更多動作）選單 $\rightarrow$ 選擇 **「從 VSIX 安裝...」**。
5. 選擇下載好的 `.vsix` 檔案即可完成安裝。

或在終端機中執行一鍵安裝指令：
```bash
code --install-extension viewany-3.0.11.vsix
```

### 方式 2：從 VS Code 官方市集安裝

在 VS Code 擴充功能市集中搜尋 `ViewAny` 並點擊 **安裝** 即可。

---

## 🎯 如何啟用 ViewAny 功能

ViewAny 支援 **Markdown (`.md`, `.markdown`)**、**Word (`.docx`, `.doc`)**、**Excel (`.xlsx`, `.xls`, `.csv`)**、**PDF (`.pdf`)** 和 **HTML (`.html`, `.htm`, `.xhtml`)**。安裝完成後，您可以透過以下幾種方式輕鬆啟用 ViewAny：

### 1. 自動啟用（開箱即用）
外掛安裝成功後，已在 VS Code 中註冊為對應格式的預設編輯器：
- 在左側檔案總管中，**直接單擊或按兩下**任意支援的檔案（例如 `README.md`、`doc.docx`、`table.xlsx` 或 `file.pdf`），VS Code 將自動調用 ViewAny 專屬視覺化編輯器開啟。

### 2. 方式一：編輯器頂欄一鍵切換按鈕（最常用）
若檔案目前正在以普通純文字或原始碼方式瀏覽：
- 查看編輯器右上角的分頁工具列，會看到一個眼睛圖示 **`👁️`**（懸停提示：`ViewAny: 切換為所見即所得編輯器`）；
- **點擊該圖示**，即可瞬間無縫切入 ViewAny 所見即所得編輯/預覽介面。

### 3. 方式二：檔案總管右鍵選單
- 在左側檔案總管（Explorer）檔案樹中，**右鍵點擊**任意支援的檔案；
- 在彈出選單中選擇 **「ViewAny: 切換為所見即所得編輯器」** 即可。

### 4. 方式三：透過命令面板 (Command Palette)
- 在目前開啟的檔案視窗中按下快捷鍵 `Ctrl+Shift+P`（macOS 為 `Cmd+Shift+P`）；
- 輸入並執行 **`ViewAny: 切換為所見即所得編輯器`**（英文系統為 `ViewAny: Switch to WYSIWYG Editor`）。

### 5. 方式四：手動設定預設開啟方式（解決被其他外掛佔用問題）
若您此前安裝過其他 Markdown/Office/PDF 外掛，或者檔案預設以純文字程式碼方式開啟，可快速將其指定為 ViewAny：
1. 在左側檔案總管中 **右鍵點擊** 該檔案；
2. 選擇 **「開啟方式...」(Open With...)**；
3. 在彈出的清單中選擇對應的 ViewAny 編輯器：
   - `ViewAny: Markdown 所見即所得編輯器`
   - `ViewAny: Word (DOCX) 視覺化編輯器`
   - `ViewAny: Excel 表格視覺化編輯器`
   - `ViewAny: PDF 高畫質閱讀與註解器`
   - `ViewAny: HTML 視覺化網頁與文件檢視器`
4. **永久設為預設**：在彈出的開啟方式清單最底部，點擊 **「設定 "*.<副檔名>" 的預設編輯器...」(Configure default editor for '...' )**，並選中對應的 ViewAny 編輯器。以後再次開啟該類型檔案時，將一律預設使用 ViewAny。

> 💡 **進階技巧：在 VS Code 全域設定中永久綁定**  
> 開啟設定（快捷鍵 `Ctrl+,`），點擊右上角的「開啟設定 (JSON)」圖示，在 `settings.json` 中加入以下設定：
> ```json
> "workbench.editorAssociations": {
>   "*.md": "viewany.markdownEditor",
>   "*.markdown": "viewany.markdownEditor",
>   "*.docx": "viewany.docxEditor",
>   "*.doc": "viewany.docxEditor",
>   "*.xlsx": "viewany.sheetEditor",
>   "*.xls": "viewany.sheetEditor",
>   "*.csv": "viewany.sheetEditor",
>   "*.pdf": "viewany.pdfEditor",
>   "*.html": "viewany.htmlEditor",
>   "*.htm": "viewany.htmlEditor"
> }
> ```

---

## ⌨ 使用技巧與快捷鍵

| 操作場景 | 快捷方式 / 觸發動作 | 功能說明 |
| :--- | :--- | :--- |
| **預設開啟** | 在檔案總管中按一下支援的檔案 | 自動調用 ViewAny 對應專屬編輯器開啟 |
| **右鍵切換** | 右鍵檔案 $\rightarrow$ `ViewAny: 切換為所見即所得編輯器` | 在純文字原始碼與 ViewAny 編輯器之間自由切換 |
| **頂欄快捷切換** | 點擊右上角分頁列的 `👁️` 按鈕 | 原始碼編輯與所見即所得檢視無縫互切 |
| **尋找內容** | `Ctrl + F` (`Cmd + F`) | 呼出輕量尋找浮動視窗 |
| **尋找與取代** | `Ctrl + H` (`Cmd + H`) | 展開包含取代行的增強浮動視窗 |
| **剪下選區/圖片** | `Ctrl + X` (`Cmd + X`) | 攜帶尺寸元數據剪下圖片，自動銷毀邊框手柄 |
| **復原與重做** | `Ctrl + Z` / `Ctrl + Y` | 復原與重做操作，精準還原游標落點 |
| **匯出文件** | 點擊工具列 `📤 匯出...` 按鈕 | 呼出多格式轉換與高品質匯出面板 |
| **表格快速導覽與末尾增行** | `Tab` / `Shift + Tab` | 儲存格間平滑跳格；在末尾儲存格按 `Tab` 自動新增下一行 |
| **表格懸浮工具列與右鍵選單** | 點擊儲存格或右鍵表格 | 快速在上方/下方增行、左側/右側增欄、刪除行/欄/表、置中對齊 |

---

## 🔒 100% 離線與隱私保護

* 🛡️ **純本機環境運作**：所有檔案的語法解析、富文本渲染、公式運算及格式轉換均在本機 VS Code 行程內完成。
* 🚫 **絕無資料外傳**：外掛不向任何外部伺服器發送你的文件內文、圖片或統計資訊。
* 🏢 **契合企業合規**：完美支援純區域網路與實體隔離（Air-gapped）高密開發環境，無洩密風險。

---

## ❓ 常見問題解答 (FAQ)

#### Q1: ViewAny 可以完全替代 Typora 嗎？
**答：** 完全可以！ViewAny 在 VS Code 內部重塑了與 Typora 高度一致的無縫沉浸式富文本編輯體驗。不僅支援即時 KaTeX 數學公式渲染、Mermaid 互動式圖表拖曳、表格與程式碼高亮，更原生依託 VS Code 的檔案樹與版本控制系統，無需在多個軟體間頻繁切換。

#### Q2: 編輯儲存 Word (.docx) 會破壞原本樣式嗎？
**答：** 不會。ViewAny 嚴格遵循微軟 OpenXML 標準協議，對標題層級、字型字級、色彩、表格及段落縮排進行解析與保真重構，儲存時直接序列化為二進位 `.docx` 檔案，確保與 Microsoft Office 及 WPS 100% 互通。

#### Q3: HTML 視覺化編輯有什麼實用價值？
**答：** 非常適合前端研發、全端工程師與營運人員直接在編輯器中預覽除錯 HTML 樣板、富文本郵件及自動化測試報表。提供手機 (375px)、平板 (768px)、電腦 (1024px) 視口無縫切換，並支援大綱定位與原始碼雙向即時同步。

#### Q4: PDF 閱讀器在無網路或內部網路環境下能否穩定運作？
**答：** 可以。ViewAny 完整內嵌本機 Mozilla PDF.js 核心 Worker 與全套 CJK（中日韓）CMaps 標準字庫，完全不依賴外網 CDN，公式、中文及專業文獻在內網離線環境下毫秒級極速開啟且永不亂碼。

#### Q5: 免費版與 Pro 尊享專業版有什麼區別？
**答：** ViewAny 免費版已向所有使用者開放對 Markdown、Word (.docx/.doc)、HTML、Excel 試算表與 PDF 的全套檢視與所見即所得編輯功能；匯出功能對單頁（$\le 1$ 頁）檔案永久免費開放。啟用尊享專業版後，可解鎖全格式無限制多頁超高畫質匯出、Word 原生 OMML 公式編輯以及終身 VIP 升級支援。

---

## 💖 支援與社群

如果 ViewAny 幫助你提升了文件與辦公效率，歡迎給予支援或回饋建議：

* 🌟 **給專案點個 Star**：[GitHub - netproxy/ViewAny](https://github.com/netproxy/ViewAny)
* 🐛 **提交 Bug 或建議**：[GitHub Issue Tracker](https://github.com/netproxy/ViewAny/issues)
* ☕ **贊助開發者持續維護**：[Sponsor ViewAny on Creem](https://www.creem.io/payment/prod_Bhr8PSD0C8p30IbMxcvy8)
* 🏠 **官方網站**：[https://www.eycloud.net/](https://www.eycloud.net/)

---

# 🇯🇵 日本語ドキュメント (Japanese Documentation)

## 💡 なぜ ViewAny を選ぶのか？

日々のソフトウェア開発、技術文書の執筆、研究、オフィス業務において、ツールの頻繁な切り替えによるコンテキストスイッチは大きな課題です：

* ❌ **Office ファイル閲覧による VS Code 離脱**：仕様書 `.docx` やテストデータ `.xlsx` を確認するたびに VS Code を離れ、起動の重いデスクトップ Office や WPS の起動を待つ必要があります。
* ❌ **Markdown 生ソースコード編集のストレス**：テキストエディタのままでは直感的なタイポグラフィ確認ができず、VS Code 標準の分割プレビューは画面の約半分を無駄に専有します。**Typora のような自然で没入感のあるインライン WYSIWYG 環境**が切望されていました。
* ❌ **煩雑な HTML レスポンシブ検証**：HTML テンプレートやメールマガジンの調整時に外部ブラウザを立ち上げ、手動でウィンドウサイズを変更しながら確認する手間が発生します。
* ❌ **貧弱な PDF 閲覧・注釈機能**：従来の PDF 拡張機能は閲覧機能に留まるものが多く、手書きペン、蛍光ペンハイライト、付箋メモ、そしてオフラインでの CJK（日中韓）フォントの完全表示に対応していません。
* ❌ **オンライン変換サイトの情報漏洩リスク**：Markdown を Word/PDF に変換するためにサードパーティのオンライン変換サービスを利用すると、社外秘コードや機密情報の流出リスクが生じます。

✨ **ViewAny は、これらすべての課題を完全に解決するために誕生しました！**  
ViewAny は、Visual Studio Code を**軽量かつ万能な 100% 完全ローカルのオフィス＆ドキュメント統合ワークステーション**へと進化させます。拡張機能 1 つで、**Markdown (`.md`)、Word (`.docx`, `.doc`)、Excel (`.xlsx`, `.xls`, `.csv`)、HTML (`.html`, `.htm`)、PDF (`.pdf`)** の高速閲覧、ビジュアル編集、高精度注釈、マルチフォーマット相互エクスポートを IDE 内で完結できます！

---

## 🚀 コア機能の詳細解説

### 1. 📝 Markdown WYSIWYG エディター (`.md`, `.markdown`)
*VS Code 内で本物の Typora レベルのシームレスなインラインリッチテキスト編集を実現。*

* **Typora 級のインラインリッチテキスト**：キーボード入力と同時に美しいスタイルがレンダリングされます。見出し、インラインコード、太字、斜体、取り消し線、テキスト蛍光マーカー、引用ブロックに完全対応。
* **3 つの表示モードを瞬時に切り替え**：「WYSIWYG（所見即所得）」、「Split（左右双方向リアルタイム分割）」、「Source（純粋ソースコード）」を 1 クリックまたはショートカットで切り替え可能。
* **高精度な双方向 AST 選択範囲マッピング＆スムーズスクロール同期**：独自の AST 双方向レンジマッピングエンジンにより、リッチテキストのクリック箇所からソースコードの該当位置を即座に特定。LaTeX 数式ブロックや Mermaid ダイアグラムもずれなく滑らかに同期します。
* **8 方向の無段階画像リサイズ＆精密ツールバー**：画像をクリックすると 8 箇所のバウンディングハンドルが表示され、リアルタイムの解像度バッジ（`W × H px`）を確認しながら自由に変形できます。フローティングツールバーで `W:` と `H:` の数値を直接入力して微調整することも可能です。
* **高精度な画像切り取り・コピー・貼り付け（`Ctrl+X / C / V`）**：クリップボード操作時にもピクセル単位のサイズ情報を保持。画像削除時にはリサイズ枠やツールバーが自動破棄され、不要な残骸を残しません。
* **インタラクティブ Mermaid ダイアグラム**：フローチャート、シーケンス図、ガントチャート、クラス図、マインドマップを WYSIWYG 描画。クリックして 8 方向ハンドルやツールバー（25%、50%、75%、100% プリセット）で直感的にサイズ変更可能。標準の HTML コメント形式（`<!-- mermaid: width="520px" align="center" -->`）で保存されるため、**GitHub、Obsidian、VS Code 標準プレビューと 100% 互換**です。
* **KaTeX 高精細数式レンダリング**：インライン数式および独立したブロック数式をベクタークオリティで描画。PDF エクスポート時にも高コントラストを維持し、はみ出しや欠落を防ぎます：
  $$\int_{0}^{+\infty} e^{-x^2} dx = \frac{\sqrt{\pi}}{2}$$
* **インタラクティブな表編集＆ GFM タスクリスト**：表の行や列をワンクリックで追加・削除・並べ替え。チェックボックスリストも画面上で直接トグル可能です。
* **スマートキャレット移動＆ブロック脱出**：余白をクリックするだけで文末にジャンプ。引用ブロックやコードブロック、表の内部で `Enter` キーを 2 回押すと、スムーズに直下の通常段落へと脱出できます。

---

### 2. 📄 Word (DOCX / DOC) ビジュアルエディター
*本物の A4 印刷レイアウト・ページネーションに対応し、バイナリ DOCX を直接保存可能。*

* **忠実な A4 ページネーション**：OpenXML 標準規格に厳格に基づき、余白、文字サイズ、行間、段落インデント、表スタイル、ヘッダー・フッターを印刷イメージ通りに再現。
* **バイナリ `.docx` への直接保存**：ビジュアル編集後に `Ctrl+S` を押すだけで、直接バイナリ `.docx` として保存。Microsoft Office や WPS と 100% 完全な互換性を保証します。
* **正確な空行・行ボックス計算**：保存を繰り返しても空行が膨張したり行高が潰れたりする不具合を根本解決し、ドキュメント本来の段落レイアウトを維持します。
* **改ページをまたぐ表の自動再結合（Reverse-Stitching）**：A4 印刷ビューで複数ページに分割された表も、保存・エクスポート時にネイティブな単一テーブル構造へと自動結合されます。
* **画像サイズとフォントの確実な保護**：再保存時の画像解像度リセットを防止。ドキュメントテーマに基づきフォントファミリを正確に継承し、日本語フォントが欧文フォントに誤変換されるのを防ぎます。
* **レガシー `.doc` バイナリファイルの抽出プレビューに対応**。

---

### 3. 📊 Excel & CSV スプレッドシートエディター (`.xlsx`, `.xls`, `.csv`)
*数式計算と複数シート管理に対応した、フル機能のスプレッドシートグリッド。*

* **本格的なスプレッドシート操作**：セルのドラッグフィル、矩形範囲選択、列幅・行高の自在なドラッグ調整、行・列の動的追加・削除。
* **複数シート（Multi-Sheet）タブ管理**：シート間のスムーズな切り替え、新規シートの追加、タブ名変更をサポート。
* **組み込み計算エンジン**：`=SUM(A1:A20)`、`=AVERAGE(...)`、`=COUNT(...)`、`=MAX(...)`、`=MIN(...)` などの標準的な集計計算や四則演算に完全対応。
* **ロスレスなバイナリ `.xlsx` / `.csv` 保存・エクスポート**：編集内容をそのまま標準の `.xlsx` またはプレーンな `.csv` として保存可能。文字エンコードや区切り文字を確実に維持します。

---

### 4. 🌐 HTML マルチビューポート WYSIWYG エディター (`.html`, `.htm`, `.xhtml`)
*Web テンプレート、HTML メール、各種レポートのためのレスポンシブ・ビジュアルスタジオ。*

* **5 種類のシミュレーションビューポート**：
  - 📱 **モバイル (Mobile 375px)**
  - 📟 **タブレット (Tablet 768px)**
  - 💻 **ノート PC (Laptop 1024px)**
  - 🖥️ **レスポンシブ (Responsive 自由キャンバスドラッグ)**
  - 🖨️ **A4 印刷シミュレーション (Print ページレイアウト)**
* **インテリジェント目次ツリー (TOC)**：すべての `H1`〜`H6` 見出しを自動抽出。キーワードによる絞り込み検索と瞬時のジャンプ移動が可能。
* **双方向リアルタイム同期**：リッチテキスト上でレイアウト変更、表の追加、画像挿入を行うと、背後の HTML ソースコードがリアルタイムに更新されます。
* **ペーパーテーマと無段階ズーム**：クラシックホワイト、目に優しいセピア、ダークテーマの 3 種を搭載。75%〜150% の連続ズームに対応。

---

### 5. 📑 PDF HDリーダー＆プロフェッショナル注釈ツール (`.pdf`)
*高度なベクターペンと注釈マーカーを備えた、高パフォーマンスな完全オフライン PDF リーダー。*

* **Mozilla PDF.js コアエンジン採用**：滑らかなスクロール、ページ幅へのフィット、見開き 2 ページ表示、無段階ズームに対応。
* **完全オフライン Worker ＆ CJK（日中韓）CMaps 内蔵**：ローカルに Worker スクリプトと CJK キャラクタマップを完全バンドル。複雑な学術数式や東アジア文字を含む PDF も、外部通信なしで文字化け・欠落なく高速表示。
* **サイドバーサムネイル＆境界スムーズホイールスクロール**：ページ境界でのスムーズなホイールめくりと、サムネイル自動追従センタリングに対応。
* **充実の注釈ツールキット**：
  - 🖌️ **手書きペン (Pen)**：線の太さと色を自由に調整して描画。
  - 🖍️ **蛍光マーカー (Highlighter)**：半透明ハイライトで重要箇所をマーク。
  - 💬 **付箋テキストノート (Text Note)**：任意の位置にテキストコメントを配置。
  - 🧹 **ベクター消しゴム (Eraser)**：不要な筆跡や注釈をワンクリックで削除。
* **注釈付き高解像度 PDF エクスポート**：描画した注釈レイヤーを統合し、クリアなベクター画質のまま PDF として書き出し可能。

---

### 6. 🔄 マルチフォーマット相互変換＆自在なエクスポート
*怪しいオンライン変換ツールに頼る必要はありません。機密情報を守りながらローカルで安全に相互変換。*

| 変換元フォーマット | 変換先フォーマット | 特徴と品質保証 |
| :--- | :--- | :--- |
| **Markdown (`.md`)** | `PDF`, `Word (.docx)`, `HTML`, `Markdown` | KaTeX 数式ベクター出力、シンタックスハイライト、Mermaid ダイアグラム |
| **Word (`.docx`)** | `PDF`, `HTML`, `Markdown`, `Word (.docx)` | A4 ページレイアウト、カスタムフォント、埋め込み表・画像の完全維持 |
| **HTML (`.html`)** | `PDF`, `Word (.docx)`, `Markdown`, `HTML` | CSS インライン化、レスポンシブレイアウトの忠実な再現 |
| **Excel (`.xlsx`, `.csv`)**| `Excel (.xlsx)`, `CSV`, `HTML`, `PDF` | セル配置の正確性、罫線描画、複数シート対応 |
| **PDF (`.pdf`)** | `注釈付き PDF`, `Word (.docx)`, `HTML` | ベクター注釈の保持、高精度テキスト・テーブル抽出 |

---

### 🎨 洗練されたツールバーと IDE クオリティの操作感

* **2 段構成の崩れない固定レールツールバー**：ウィンドウ幅が狭くなった際にツールバーが 4〜5 行に折り返されてエディタ領域を圧迫する問題を防止。滑らかな横スクロールに対応。
* **狭画面レスポンシブ・コンパクトモード**：分割ペインの幅が狭い場合（`<=1250px` / `<=900px`）、ボタンがアイコン形式に自動集約され、ツールチップを維持したまま省スペース化。
* **スムーズな検索・置換ウィジェット (`Ctrl+F` / `Ctrl+H`)**：VS Code ネイティブのデザインを踏襲し、検索行と置換行のスムーズな展開・フォーカス移動を実現。
* **CSS 変数によるペーパーテーマ**：クラシック、セピア、ダークの各テーマにおいて、引用枠、コードブロック、スクロールバー、図表のコントラストを最適化。

---

## 📋 対応フォーマット＆エクスポート一覧

| ドキュメント種類 | 対応拡張子 | 閲覧 | WYSIWYG 編集 | 主な特徴 | 出力・エクスポート |
| :--- | :--- | :---: | :---: | :--- | :--- |
| **Markdown** | `.md`, `.markdown` | ✅ | ✅ | Typora 級、8方向画像/図表リサイズ、KaTeX、GFM タスク、双方向同期 | PDF, Word, HTML, Markdown |
| **Word ドキュメント** | `.docx`, `.doc` | ✅ | ✅ | A4 印刷レイアウト、バイナリ DOCX 保存、表の再結合、行ボックス維持 | PDF, Word, HTML, Markdown |
| **HTML ページ** | `.html`, `.htm`, `.xhtml`| ✅ | ✅ | 5 視口プレビュー、インテリジェント目次 (TOC)、双方向ソース同期 | PDF, Word, Markdown, HTML |
| **スプレッドシート** | `.xlsx`, `.xls`, `.csv` | ✅ | ✅ | 数式計算、複数シートタブ、グリッドの動的調整 | Excel, CSV, HTML, PDF |
| **PDF ドキュメント** | `.pdf` | ✅ | ✅ | オフライン CJK フォント、手書きペン、蛍光ペン、付箋メモ | 注釈付き PDF, Word, HTML |

---

## ⚡ クイックスタート＆インストール

### 方法 1: GitHub Releases からインストール（推奨）

1. [ViewAny Releases](https://github.com/netproxy/ViewAny/releases) にアクセスします。
2. 最新の `viewany-3.0.11.vsix` パッケージをダウンロードします。
3. VS Code を開き、`Ctrl+Shift+X` (`Cmd+Shift+X`) を押して拡張機能ビューを開きます。
4. 右上の **`⋯`**（その他の操作）メニュー $\rightarrow$ **「VSIX からのインストール...」** を選択します。
5. ダウンロードした `.vsix` ファイルを選択するとインストールが完了します。

または、ターミナルから直接コマンドを実行してインストールすることも可能です：
```bash
code --install-extension viewany-3.0.11.vsix
```

### 方法 2: VS Code マーケットプレイスからインストール

VS Code 内の拡張機能ビューで `ViewAny` を検索し、**「インストール」** をクリックします。

---

## 🎯 ViewAny 機能を有効化・起動する方法

ViewAny は **Markdown (`.md`, `.markdown`)**、**Word (`.docx`, `.doc`)**、**Excel (`.xlsx`, `.xls`, `.csv`)**、**PDF (`.pdf`)**、**HTML (`.html`, `.htm`, `.xhtml`)** に対応しています。インストール後、以下のいずれかの方法ですぐに有効化して利用できます：

### 1. 自動起動（デフォルトエディタとして利用）
インストール完了後、ViewAny は対応拡張子のカスタムエディタとして自動登録されます：
- サイドバーのエクスプローラーで対象ファイル（`README.md`、`doc.docx`、`table.xlsx`、`file.pdf` など）を**クリックまたはダブルクリック**するだけで、ViewAny のビジュアルエディタが自動で起動します。

### 2. 方法 1: エディタ右上の一発切り替えボタン（最も便利）
ファイルが通常のソースコードエディタで開かれている場合：
- エディタ右上タブのツールバーにある目のアイコン **`👁️`**（ツールチップ: `ViewAny: WYSIWYGエディターに切り替え`）を確認します。
- **アイコンをクリック**するだけで、瞬時に ViewAny の WYSIWYG ビジュアル編集画面へと切り替わります。

### 3. 方法 2: エクスプローラーの右クリックメニュー
- エクスプローラーのファイルツリーで対象ファイルを**右クリック**します。
- メニューから **「ViewAny: WYSIWYGエディターに切り替え」**（または `ViewAny: Switch to WYSIWYG Editor`）を選択します。

### 4. 方法 3: コマンドパレットから実行
- ファイルを開いた状態で `Ctrl+Shift+P`（macOS は `Cmd+Shift+P`）を押します。
- **`ViewAny: WYSIWYGエディターに切り替え`** と入力して実行します。

### 5. 方法 4: 「プログラムから開く...」で既定エディタに指定（競合解消）
他プラグインやデフォルトのテキストエディタが優先されてしまう場合：
1. 対象ファイルを**右クリック** $\rightarrow$ **「プログラムから開く...」(Open With...)** を選択します。
2. 表示される候補から対応する ViewAny エディタを選択します：
   - `ViewAny: Markdown WYSIWYG エディター`
   - `ViewAny: Word (DOCX) ビジュアルエディター`
   - `ViewAny: Excel 表計算ビジュアルエディター`
   - `ViewAny: PDF HDリーダー＆注釈ツール`
   - `ViewAny: HTML ビジュアル Web ＆ ドキュメントビューア`
3. **常にデフォルトにする場合**：リスト最下部の **「'*.<拡張子>' の既定のエディターを構成する...」** を選択し、ViewAny を指定してください。

> 💡 **上級Tips: VS Code の `settings.json` で完全に固定する**  
> 設定画面を開き、`settings.json` に以下を追記します：
> ```json
> "workbench.editorAssociations": {
>   "*.md": "viewany.markdownEditor",
>   "*.markdown": "viewany.markdownEditor",
>   "*.docx": "viewany.docxEditor",
>   "*.doc": "viewany.docxEditor",
>   "*.xlsx": "viewany.sheetEditor",
>   "*.xls": "viewany.sheetEditor",
>   "*.csv": "viewany.sheetEditor",
>   "*.pdf": "viewany.pdfEditor",
>   "*.html": "viewany.htmlEditor",
>   "*.htm": "viewany.htmlEditor"
> }
> ```

---

## ⌨ ショートカット＆ワークフロー

| 操作内容 | ショートカット / トリガー | 説明 |
| :--- | :--- | :--- |
| **既定のエディターで開く** | エクスプローラーで対象ファイルをシングルクリック | 対応拡張子のファイルが ViewAny で自動的に開きます |
| **エディターの切り替え** | ファイルを右クリック $\rightarrow$ `ViewAny: WYSIWYGエディターに切り替え` | 通常のテキストエディタと ViewAny を自由に切り替え |
| **ワンクリック切り替え** | エディタタブ右上の `👁️` アイコンをクリック | ソースコードと WYSIWYG プレビューを即座にトグル |
| **文書内検索** | `Ctrl + F` (`Cmd + F`) | 軽量な検索バーを表示 |
| **検索と置換** | `Ctrl + H` (`Cmd + H`) | 置換行を含む拡張検索バーを表示 |
| **画像の切り取り** | `Ctrl + X` (`Cmd + X`) | サイズ情報を保持したまま画像を切り取り、ハンドル枠を自動消去 |
| **元に戻す / やり直し** | `Ctrl + Z` / `Ctrl + Y` | キャレット位置を正確に復元しながらアンドゥ・リドゥ |
| **ドキュメントのエクスポート** | ツールバーの `📤 エクスポート...` をクリック | マルチフォーマット変換＆高品質エクスポートパネルを表示 |
| **表の高速移動＆末尾行追加** | `Tab` / `Shift + Tab` | セル間を移動。最終セルで `Tab` を押すと新しい行を自動追加 |
| **表のツールバー＆右クリックメニュー** | セルをクリックまたは右クリック | 上下への行追加、左右への列追加、削除、中央揃えなどを素早く実行 |

---

## 🔒 100% オフライン＆プライバシー保護

* 🛡️ **完全ローカル処理**：すべてのファイルのパース、描画、数式計算、フォーマット変換はお使いの PC の VS Code プロセス内のみで完結します。
* 🚫 **外部通信ゼロ**：ユーザーの文書内容、画像、統計情報が外部サーバーへ送信されることは一切ありません。
* 🏢 **エンタープライズ対応**：物理的に隔離された環境（Air-gapped）や社内セキュリティポリシーが厳しい開発現場でも安心してご利用いただけます。

---

## ❓ よくある質問 (FAQ)

#### Q1: ViewAny は VS Code 内で Typora の代わりになりますか？
**A:** はい、十分に代用可能です！ViewAny は、VS Code の内部で Typora と同等のストレスのないインラインリッチテキスト編集を提供します。KaTeX 数式のリアルタイム描画、Mermaid 図のドラッグ調整、インタラクティブな表操作、コードシンタックスハイライト、そして滑らかな分割同期をサポートしています。

#### Q2: Word (.docx) ファイルを編集・保存してもレイアウトは崩れませんか？
**A:** 崩れません。ViewAny は Microsoft の標準 OpenXML 仕様に厳格に準拠しています。段落階層、文字フォント、スタイル、余白、表の構造を忠実に再現し、バイナリ `.docx` として保存するため、Microsoft Office や WPS と 100% の相互運用性を備えています。

#### Q3: HTML ビジュアルエディターはどのような場面で役立ちますか？
**A:** フロントエンド開発、テンプレート設計、HTML メールの作成に最適です。外部ブラウザを開くことなく、VS Code 内で Mobile (375px)、Tablet (768px)、Laptop (1024px) などの各画面サイズでの見栄えを瞬時に確認でき、アウトライン目次やソースコードとのリアルタイム同期も利用できます。

#### Q4: PDF リーダーはインターネット接続がないオフライン環境でも動作しますか？
**A:** 問題なく動作します。ViewAny には Mozilla の PDF.js コア Worker と CJK（日中韓）CMaps 文字セットがローカルに完全内包されています。複雑な数式や日本語の学術論文も、オフラインで文字化けすることなく高速に表示されます。

#### Q5: 無料版と Pro VIP 版の違いは何ですか？
**A:** 無料版でも Markdown、Word、HTML、Excel、PDF の全フォーマットにおける閲覧およびビジュアル編集がすべて利用可能です。また、単一ページ（$\le 1$ ページ）のドキュメントエクスポートは永久に無料です。Pro VIP 版を有効化すると、すべての形式でページ数無制限の高解像度エクスポート、Word ネイティブの OMML 数式編集、生涯 VIP アップデートがアンロックされます。

---

## 💖 コミュニティ＆サポート

ViewAny がお役に立ちましたら、ぜひプロジェクトへのサポートやフィードバックをお願いいたします：

* 🌟 **GitHub で Star を送る**：[GitHub - netproxy/ViewAny](https://github.com/netproxy/ViewAny)
* 🐛 **バグ報告・機能リクエスト**：[GitHub Issue Tracker](https://github.com/netproxy/ViewAny/issues)
* ☕ **開発者を支援する**：[Sponsor ViewAny on Creem](https://www.creem.io/payment/prod_Bhr8PSD0C8p30IbMxcvy8)
* 🏠 **公式サイト**：[https://www.eycloud.net/](https://www.eycloud.net/)

---

# 🇰🇷 한국어 문서 (Korean Documentation)

## 💡 왜 ViewAny인가?

소프트웨어 개발, 기술 문서 작성, 연구 및 일상적인 오피스 업무 환경에서 우리는 분절된 도구들로 인해 끊임없는 컨텍스트 스위칭을 겪습니다:

* ❌ **Office 문서를 열기 위해 VS Code를 벗어남**: 간단한 기획서 `.docx`나 테스트 데이터 `.xlsx`를 확인하기 위해 무거운 데스크톱 MS Office나 한컴오피스 실행을 기다려야 합니다.
* ❌ **원시 Markdown 소스 코드 편집의 피로감**: 원시 소스 코드는 직관적인 서식 피드백이 부족하고, VS Code의 기본 분할 미리보기는 화면의 절반을 무의미하게 차지합니다. **Typora처럼 자연스러운 인라인 위지윅(WYSIWYG)** 환경이 절실합니다.
* ❌ **번거로운 HTML 반응형 웹 디버깅**: 이메일 템플릿이나 HTML 마크업을 수정할 때 외부 브라우저를 띄우고 창 크기를 수동으로 조절해야 하는 불편함이 있습니다.
* ❌ **미흡한 PDF 뷰어 및 주석 도구**: 기존 PDF 확장 도구는 단순 조회만 지원하며, 벡터 펜, 형광펜 하이라이트, 텍스트 메모 및 CJK(한중일) 폰트 오프라인 렌더링을 제대로 지원하지 못합니다.
* ❌ **보안 위험이 도사리는 온라인 변환 사이트**: Markdown, Word, PDF 상호 변환을 위해 광고성 온라인 변환기에 기밀 문서나 소스 코드를 업로드하는 보안 위험을 감수해야 합니다.

✨ **ViewAny가 이 모든 문제를 완벽하게 해결합니다!**  
ViewAny는 Visual Studio Code를 **가볍고 강력한 100% 로컬 올인원 오피스 & 문서 워크스테이션**으로 완전히 탈바꿈합니다. 단 하나의 확장으로 **Markdown (`.md`), Word (`.docx`, `.doc`), Excel (`.xlsx`, `.xls`, `.csv`), HTML (`.html`, `.htm`), PDF (`.pdf`)**의 원활한 열람, 시각화 편집, 벡터 주석 및 상호 변환 내보내기를 IDE 내부에서 끝마칠 수 있습니다!

---

## 🚀 핵심 기능 심층 분석

### 1. 📝 Markdown WYSIWYG 에디터 (`.md`, `.markdown`)
*VS Code 안에서 Typora 수준의 부드럽고 몰입감 넘치는 인라인 리치 텍스트 편집을 경험하세요.*

* **Typora급 인라인 리치 텍스트**: 키보드 입력과 동시에 정교한 서식이 렌더링됩니다. 제목(Header), 인라인 코드, 굵게, 기울임, 취소선, 텍스트 하이라이트, 인용구 블록을 완벽하게 지원합니다.
* **3가지 뷰 모드 자유 전환**: 「WYSIWYG (위지윅)」, 「Split (실시간 양방향 2분할)」, 「Source (원시 소스 코드)」를 클릭 한 번이나 단축키로 손쉽게 전환할 수 있습니다.
* **고정밀 양방향 AST 매핑 & 부드러운 스크롤 동기화**: 독자적인 AST 양방향 구간 매핑 엔진으로 비주얼 텍스트 클릭 시 소스 코드의 정확한 위치를 찾아가며, 복잡한 LaTeX 수식 블록이나 Mermaid 다이어그램도 어긋남 없이 부드럽게 동기화됩니다.
* **8방향 무단 이미지 리사이즈 & 정밀 플로팅 툴바**: 이미지를 클릭하면 8개의 경계 핸들이 나타나며, 실시간 해상도 배지(`W × H px`)를 확인하면서 자유롭게 크기를 조정할 수 있습니다. 플로팅 툴바에서 `W:` 및 `H:` 수치를 직접 입력해 픽셀 단위로 정밀 제어할 수도 있습니다.
* **고품질 이미지 잘라내기/복사/붙여넣기 (`Ctrl+X / C / V`)**: 클립보드 작업 시에도 픽셀 단위의 크기 메타데이터를 유지합니다. 이미지 삭제 시 크기 조절 테두리와 툴바가 자동으로 즉시 정리됩니다.
* **대화형 드래그 지원 Mermaid 다이어그램**: 플로우차트, 시퀀스 다이어그램, 간트 차트, 클래스 다이어그램, 마인드맵을 위지윅으로 시각화합니다. 다이어그램을 클릭하여 8방향 핸들이나 툴바(25%, 50%, 75%, 100% 프리셋)로 간편하게 크기를 조정할 수 있습니다. 표준 HTML 주석 형식(`<!-- mermaid: width="520px" align="center" -->`)으로 저장되어 **GitHub, Obsidian, VS Code 기본 미리보기와 100% 완벽 호환**됩니다.
* **고해상도 KaTeX 수식 렌더링**: 인라인 수식 및 독립 블록 수식을 벡터 품질로 선명하게 표시합니다. PDF 내보내기 시에도 배경 대비를 선명하게 유지하며 잘림 현상이 없습니다:
  $$\int_{0}^{+\infty} e^{-x^2} dx = \frac{\sqrt{\pi}}{2}$$
* **대화형 표 편집 & GFM 체크리스트**: 표의 행과 열을 클릭 한 번으로 추가, 삭제 및 재정렬할 수 있으며 체크리스트를 화면에서 직접 토글할 수 있습니다.
* **스마트 커서 이동 & 단락 탈출**: 하단 여백을 클릭하면 문서 끝으로 즉시 이동합니다. 인용구나 코드 블록, 표 안에서 `Enter` 키를 두 번 누르면 하단의 새 단락으로 깔끔하게 빠져나옵니다.

---

### 2. 📄 Word (DOCX / DOC) 비주얼 문서 에디터
*실제 A4 인쇄 규격 페이지네이션을 지원하며 바이너리 DOCX를 로컬에 직접 저장합니다.*

* **충실한 A4 페이지네이션 조판**: OpenXML 표준 규격을 엄격히 준수하여 여백, 글꼴 크기, 줄 간격, 들여쓰기, 표 서식, 머리글/바닥글을 인쇄된 용지처럼 정확히 재현합니다.
* **바이너리 `.docx` 직접 로컬 저장**: 비주얼 편집 후 `Ctrl+S`를 누르면 즉시 표준 바이너리 `.docx` 파일로 저장됩니다. Microsoft Word, 한글(오피스), WPS와 100% 완벽 호환됩니다.
* **정밀한 빈 줄 및 행 높이 계산**: 여러 번 저장해도 빈 줄이 눈덩이처럼 불어나거나 행 높이가 무너지는 문제를 근본적으로 해결하여 원본 문서의 단락 구조를 보존합니다.
* **다중 페이지 표 자동 역결합 (Reverse-Stitching)**: A4 뷰에서 페이지 경계로 인해 분할된 표를 저장 및 내보내기 시 네이티브 단일 표 구조로 자동 봉합합니다.
* **이미지 규격 및 폰트 서식 보호**: 재저장 시 이미지 크기가 초기화되는 현상을 방지합니다. 문서 테마 글꼴을 정확히 계승하여 한글/아시아 폰트가 영문 폰트로 오버라이드되는 현상을 차단합니다.
* **클래식 바이너리 `.doc` 파일 내용 추출 및 미리보기 지원**.

---

### 3. 📊 Excel & CSV 스프레드시트 에디터 (`.xlsx`, `.xls`, `.csv`)
*수식 자동 계산과 다중 시트 관리를 지원하는 풀 기능 스프레드시트 그리드.*

* **완벽한 스프레드시트 인터랙션**: 셀 드래그 채우기, 직사각형 범위 선택, 열 너비 및 행 높이 자유 조절, 행/열 동적 추가 및 삭제.
* **다중 시트 (Multi-Sheet) 탭 관리**: 워크시트 간 원활한 전환, 새 시트 추가 및 시트 이름 변경 지원.
* **내장 수식 자동 계산 엔진**: `=SUM(A1:A20)`, `=AVERAGE(...)`, `=COUNT(...)`, `=MAX(...)`, `=MIN(...)` 등의 통계 함수와 사칙연산 수식을 완벽하게 지원합니다.
* **무손실 바이너리 `.xlsx` / `.csv` 저장 및 내보내기**: 편집된 데이터를 표준 `.xlsx` 또는 순수 텍스트 `.csv`로 직접 저장하며, 문자 인코딩과 구분자를 안전하게 유지합니다.

---

### 4. 🌐 HTML 반응형 다중 뷰포트 시각화 & 에디터 (`.html`, `.htm`, `.xhtml`)
*웹 템플릿, HTML 이메일, 정적 보고서를 위한 통합 반응형 비주얼 스튜디오.*

* **5가지 시뮬레이션 뷰포트 전환**:
  - 📱 **모바일 (Mobile 375px)**
  - 📟 **태블릿 (Tablet 768px)**
  - 💻 **노트북 (Laptop 1024px)**
  - 🖥️ **반응형 (Responsive 자유 캔버스 조절)**
  - 🖨️ **A4 인쇄 시뮬레이션 (Print 용지 레이아웃)**
* **스마트 목차 트리 (TOC) 빠른 탐색**: 모든 `H1`~`H6` 제목을 자동 추출하며, 실시간 키워드 필터링 및 원클릭 이동을 지원합니다.
* **양방향 소스 코드 실시간 동기화**: 리치 텍스트 환경에서 서식을 변경하거나 표, 이미지를 삽입하면 기본 HTML 소스 코드가 실시간으로 업데이트됩니다.
* **용지 테마 및 무단계 줌**: 클래식 화이트, 눈 보호 세피아, 다크 테마를 제공하며 75%~150% 연속 확대/축소를 지원합니다.

---

### 5. 📑 PDF HD 뷰어 & 프로페셔널 주석 도구 (`.pdf`)
*고성능 벡터 펜과 주석 마커를 탑재한 완전 오프라인 고해상도 PDF 리더.*

* **Mozilla PDF.js 강력한 엔진 구동**: 부드러운 스크롤, 페이지 너비 맞춤, 2페이지 나란히 보기, 자유 배율 확대를 지원합니다.
* **100% 오프라인 Worker & CJK (한중일) CMaps 폰트 내장**: 로컬 환경에 렌더링 Worker와 CJK 문자 맵을 완벽하게 내장하여, 복잡한 수식이나 한글 문서도 외부 네트워크 통신 없이 깨짐이나 누락 없이 즉시 렌더링합니다.
* **사이드바 썸네일 & 부드러운 마우스 휠 페이지 넘김**: 페이지 경계에 도달 시 부드러운 휠 페이지 전환과 썸네일 자동 중앙 정렬 동기화를 지원합니다.
* **완벽한 주석 도구 상자**:
  - 🖌️ **자유 드로잉 펜 (Pen)**: 선 굵기와 색상을 자유롭게 조절하여 필기.
  - 🖍️ **형광펜 (Highlighter)**: 반투명 하이라이트로 핵심 문장 강조.
  - 💬 **텍스트 메모 (Text Note)**: 원하는 위치에 텍스트 주석 배치.
  - 🧹 **벡터 지우개 (Eraser)**: 불필요한 필기나 주석을 한 번에 삭제.
* **주석 포함 고해상도 PDF 내보내기**: 작업한 주석 레이어를 병합하여 선명한 벡터 화질의 PDF로 저장합니다.

---

### 6. 🔄 크로스 포맷 자유 변환 & 내보내기
*신뢰할 수 없는 온라인 변환기에 기밀 문서를 올리지 마세요. 로컬에서 데이터 유출 없이 안전하게 변환합니다.*

| 원본 문서 유형 | 변환 목표 포맷 | 변환 특징 및 품질 보증 |
| :--- | :--- | :--- |
| **Markdown (`.md`)** | `PDF`, `Word (.docx)`, `HTML`, `Markdown` | KaTeX 수식 벡터 렌더링, 코드 신택스 하이라이팅, Mermaid 다이어그램 |
| **Word (`.docx`)** | `PDF`, `HTML`, `Markdown`, `Word (.docx)` | A4 페이지 흐름, 사용자 글꼴, 포함된 표 및 이미지 레이아웃 완벽 보존 |
| **HTML (`.html`)** | `PDF`, `Word (.docx)`, `Markdown`, `HTML` | 스타일 인라인화, 반응형 레이아웃 정밀 유지 |
| **Excel (`.xlsx`, `.csv`)**| `Excel (.xlsx)`, `CSV`, `HTML`, `PDF` | 셀 정렬 유지, 선명한 테두리선, 다중 Sheet 지원 |
| **PDF (`.pdf`)** | `주석 포함 PDF`, `Word (.docx)`, `HTML` | 벡터 주석 보존, 텍스트 및 표 고품질 추출 |

---

### 🎨 현대적인 툴바와 정제된 IDE 조작 경험

* **2행 고정 레일 툴바**: 창 너비가 좁아질 때 툴바가 4~5줄로 무너져 에디터 공간을 침범하는 현상을 원천 방지합니다. 부드러운 가로 스크롤을 지원합니다.
* **좁은 화면 반응형 콤팩트 모드**: 분할 창이 좁아지면(`<=1250px` / `<=900px`) 긴 텍스트 버튼이 세련된 아이콘 버튼으로 자동 전환되며 풍부한 툴팁 설명을 유지합니다.
* **부드러운 찾기 & 바꾸기 위젯 (`Ctrl+F` / `Ctrl+H`)**: VS Code 기본 디자인 감각을 계승하여 찾기 행과 바꾸기 행 간의 부드러운 전환과 자동 포커스 이동을 구현했습니다.
* **CSS 변수 기반 용지 테마**: 클래식 화이트, 세피아, 다크 테마 전반에서 인용 블록, 코드 박스, 스크롤바, 다이어그램의 시인성을 극대화합니다.

---

## 📋 지원 포맷 및 내보내기 매트릭스

| 문서 카테고리 | 지원 확장자 | 열람 모드 | 위지윅 편집 | 핵심 기능 하이라이트 | 지원 내보내기 포맷 |
| :--- | :--- | :---: | :---: | :--- | :--- |
| **Markdown** | `.md`, `.markdown` | ✅ | ✅ | Typora급 경험, 8방향 이미지/다이어그램 조절, KaTeX, GFM 체크리스트, 양방향 동기화 | PDF, Word, HTML, Markdown |
| **Word 문서** | `.docx`, `.doc` | ✅ | ✅ | A4 용지 조판, 바이너리 DOCX 저장, 표 역결합, 행 높이 정확성 | PDF, Word, HTML, Markdown |
| **HTML 웹문서** | `.html`, `.htm`, `.xhtml`| ✅ | ✅ | 5가지 뷰포트 시뮬레이션, 스마트 목차 (TOC), 실시간 양방향 동기화 | PDF, Word, Markdown, HTML |
| **스프레드시트** | `.xlsx`, `.xls`, `.csv` | ✅ | ✅ | 수식 자동 계산, 다중 Sheet 탭 관리, 그리드 동적 조절 | Excel, CSV, HTML, PDF |
| **PDF 문서** | `.pdf` | ✅ | ✅ | 오프라인 CJK 폰트, 드로잉 펜, 형광펜, 텍스트 메모 주석 | 주석 포함 PDF, Word, HTML |

---

## ⚡ 빠른 시작 및 설치 안내

### 방법 1: GitHub Releases에서 설치 (권장)

1. [ViewAny Releases](https://github.com/netproxy/ViewAny/releases) 페이지에 접속합니다.
2. 최신 버전의 `viewany-3.0.11.vsix` 파일을 다운로드합니다.
3. VS Code를 열고 `Ctrl+Shift+X` (`Cmd+Shift+X`)를 눌러 확장 패널을 엽니다.
4. 확장 패널 우측 상단의 **`⋯`** 메뉴 $\rightarrow$ **「VSIX에서 설치...」**를 선택합니다.
5. 다운로드한 `.vsix` 파일을 선택하면 설치가 완료됩니다.

또는 터미널에서 다음 명령어를 직접 실행할 수도 있습니다:
```bash
code --install-extension viewany-3.0.11.vsix
```

### 방법 2: VS Code 마켓플레이스에서 설치

VS Code 확장 마켓플레이스에서 `ViewAny`를 검색한 후 **「설치」** 버튼을 클릭합니다.

---

## 🎯 ViewAny 기능 활성화 및 실행 방법

ViewAny는 **Markdown (`.md`, `.markdown`)**, **Word (`.docx`, `.doc`)**, **Excel (`.xlsx`, `.xls`, `.csv`)**, **PDF (`.pdf`)**, **HTML (`.html`, `.htm`, `.xhtml`)** 문서를 지원합니다. 설치 후 아래의 간편한 방법들을 통해 즉시 활성화하여 사용할 수 있습니다:

### 1. 자동 실행 (기본 에디터)
확장 프로그램 설치가 완료되면 지원 파일의 기본 커스텀 에디터로 자동 등록됩니다:
- 좌측 파일 탐색기에서 대상 파일(`README.md`, `doc.docx`, `data.xlsx`, `paper.pdf` 등)을 **클릭하거나 더블클릭**하면 ViewAny 전용 위지윅 에디터로 자동 열립니다.

### 2. 방법 1: 에디터 우측 상단 빠른 전환 버튼 (가장 편리)
파일이 일반 텍스트/코드 에디터로 열려 있는 경우:
- 에디터 상단 탭 툴바 우측의 눈 아이콘 **`👁️`** (툴팁: `ViewAny: WYSIWYG 에디터로 전환`)을 확인합니다.
- **아이콘을 클릭**하면 즉시 ViewAny 리치 텍스트 위지윅 화면으로 매끄럽게 전환됩니다.

### 3. 방법 2: 파일 탐색기 우클릭 메뉴
- 좌측 파일 탐색기(Explorer) 트리에서 대상 파일을 **마우스 우클릭**합니다.
- 메뉴에서 **「ViewAny: WYSIWYG 에디터로 전환」** (또는 `ViewAny: Switch to WYSIWYG Editor`)을 선택합니다.

### 4. 방법 3: 명령 팔레트(Command Palette) 실행
- 문서를 연 상태에서 단축키 `Ctrl+Shift+P` (macOS는 `Cmd+Shift+P`)를 누릅니다.
- **`ViewAny: WYSIWYG 에디터로 전환`**을 입력하고 실행합니다.

### 5. 방법 4: 「연결 프로그램...」을 통해 기본 에디터로 재지정 (충돌 해결)
다른 마크다운/PDF 확장이 우선 적용되거나 일반 텍스트로 열리는 경우:
1. 대상 파일을 **마우스 우클릭** $\rightarrow$ **「연결 프로그램...」(Open With...)**을 선택합니다.
2. 목록에서 해당 포맷의 ViewAny 에디터를 선택합니다:
   - `ViewAny: Markdown WYSIWYG Editor`
   - `ViewAny: Word (DOCX) 비주얼 문서 에디터`
   - `ViewAny: Excel 스프레드시트 비주얼 에디터`
   - `ViewAny: PDF HD 뷰어 & 프로페셔널 주석 도구`
   - `ViewAny: HTML 반응형 웹 & 문서 뷰어`
3. **항상 기본값으로 지정**: 목록 맨 아래의 **「'*.<확장자>'에 대한 기본 편집기 구성...」**을 선택한 뒤 ViewAny를 지정해 주세요.

> 💡 **고급 팁: VS Code `settings.json`에서 영구 바인딩**  
> 설정 창을 열고 `settings.json`에 아래 구성을 추가합니다:
> ```json
> "workbench.editorAssociations": {
>   "*.md": "viewany.markdownEditor",
>   "*.markdown": "viewany.markdownEditor",
>   "*.docx": "viewany.docxEditor",
>   "*.doc": "viewany.docxEditor",
>   "*.xlsx": "viewany.sheetEditor",
>   "*.xls": "viewany.sheetEditor",
>   "*.csv": "viewany.sheetEditor",
>   "*.pdf": "viewany.pdfEditor",
>   "*.html": "viewany.htmlEditor",
>   "*.htm": "viewany.htmlEditor"
> }
> ```

---

## ⌨ 단축키 및 유용한 팁

| 동작 | 단축키 / 실행 방법 | 상세 설명 |
| :--- | :--- | :--- |
| **기본 에디터로 열기** | 파일 탐색기에서 지원 파일 클릭 | 확장자에 맞춰 ViewAny 전용 에디터로 자동 열기 |
| **에디터 전환** | 파일 우클릭 $\rightarrow$ `ViewAny: WYSIWYG 에디터로 전환` | 일반 텍스트 편집기와 ViewAny 에디터 간 자유로운 전환 |
| **빠른 토글** | 에디터 탭 우측 상단의 `👁️` 아이콘 클릭 | 소스 코드와 WYSIWYG 뷰를 즉시 상호 전환 |
| **문서 내 찾기** | `Ctrl + F` (`Cmd + F`) | 간결한 검색 바 호출 |
| **찾기 및 바꾸기** | `Ctrl + H` (`Cmd + H`) | 바꾸기 입력 행이 포함된 확장 검색 바 표시 |
| **이미지/선택 영역 잘라내기** | `Ctrl + X` (`Cmd + X`) | 크기 정보를 유지한 채 이미지를 잘라내며 테두리 핸들 자동 정리 |
| **실행 취소 / 다시 실행** | `Ctrl + Z` / `Ctrl + Y` | 커서 위치를 정확히 복원하며 Undo / Redo 수행 |
| **문서 내보내기** | 툴바의 `📤 내보내기...` 클릭 | 다중 포맷 변환 및 고품질 내보내기 대화창 표시 |
| **표 내 빠른 이동 & 행 추가** | `Tab` / `Shift + Tab` | 셀 간 부드러운 이동; 마지막 셀에서 `Tab`을 누르면 다음 행 자동 생성 |
| **표 툴바 & 컨텍스트 메뉴** | 셀 클릭 또는 표 우클릭 | 상/하 행 추가, 좌/우 열 추가, 삭제, 가운데 정렬 등을 신속하게 조작 |

---

## 🔒 100% 오프라인 동작 및 완벽한 프라이버시 보호

* 🛡️ **완전한 로컬 처리 환경**: 모든 파일의 구문 분석, 렌더링, 수식 계산 및 포맷 변환이 로컬 PC의 VS Code 프로세스 내부에서만 수행됩니다.
* 🚫 **외부 데이터 전송 차단**: 사용자의 문서 내용, 이미지, 통계 데이터가 외부 서버로 전송되지 않습니다.
* 🏢 **엔터프라이즈 보안 준수**: 물리적 망분리(Air-gapped) 환경 및 기업 보안 규정이 엄격한 개발 환경에서도 안심하고 사용할 수 있습니다.

---

## ❓ 자주 묻는 질문 (FAQ)

#### Q1: ViewAny가 VS Code 내에서 Typora를 완전히 대체할 수 있나요?
**A:** 네, 완벽히 대체할 수 있습니다! ViewAny는 VS Code 내부에서 Typora와 동일한 부드러운 인라인 위지윅 편집 경험을 선사합니다. 실시간 KaTeX 수식 렌더링, 드래그 지원 Mermaid 다이어그램, 대화형 표, 코드 구문 강조 및 2분할 실시간 동기화를 지원합니다.

#### Q2: Word (.docx) 문서를 편집하고 저장하면 레이아웃이 깨지나요?
**A:** 깨지지 않습니다. ViewAny는 마이크로소프트의 표준 OpenXML 규격을 엄격히 준수합니다. 단락 계층, 글꼴 서식, 여백, 표 스타일을 정밀하게 보존하며 표준 바이너리 `.docx` 형식으로 직접 저장하므로 MS Office 및 한글(오피스), WPS와 100% 상호 호환됩니다.

#### Q3: HTML 비주얼 에디터는 어떤 작업에 유용한가요?
**A:** 프론트엔드 개발, HTML 템플릿 제작, 마케팅 이메일 작성 시 매우 유용합니다. 외부 브라우저를 열지 않고도 모바일(375px), 태블릿(768px), 데스크톱(1024px) 뷰포트에서 즉시 레이아웃을 확인하고, 스마트 목차 및 소스 코드와의 실시간 양방향 동기화를 활용할 수 있습니다.

#### Q4: PDF 뷰어는 인터넷 연결이 없는 오프라인 환경에서도 잘 작동하나요?
**A:** 완벽하게 작동합니다. ViewAny는 Mozilla PDF.js 렌더링 Worker와 CJK (한중일) CMaps 폰트 라이브러리를 로컬 패키지에 완전히 포함하고 있습니다. 수식이나 한글이 포함된 복잡한 문서도 오프라인에서 글꼴 깨짐 없이 매우 빠르게 열립니다.

#### Q5: 무료 버전과 Pro VIP 버전의 차이점은 무엇인가요?
**A:** 무료 버전에서도 Markdown, Word, HTML, Excel, PDF 전 포맷에 대한 열람 및 위지윅 편집 기능을 모두 제한 없이 이용할 수 있습니다. 또한 1페이지 이하($\le 1$페이지) 문서 내보내기는 영구 무료입니다. Pro VIP 버전을 활성화하면 전 포맷 무제한 다중 페이지 초고해상도 내보내기, Word 네이티브 OMML 수식 편집, 평생 VIP 업데이트 혜택이 제공됩니다.

---

## 💖 지원 및 커뮤니티

ViewAny가 문서 작업과 업무 효율 향상에 도움이 되었다면 많은 관심과 응원을 부탁드립니다:

* 🌟 **GitHub Star 누르기**: [GitHub - netproxy/ViewAny](https://github.com/netproxy/ViewAny)
* 🐛 **버그 제보 및 기능 제안**: [GitHub Issue Tracker](https://github.com/netproxy/ViewAny/issues)
* ☕ **개발자 후원하기**: [Sponsor ViewAny on Creem](https://www.creem.io/payment/prod_Bhr8PSD0C8p30IbMxcvy8)
* 🏠 **공식 웹사이트**: [https://www.eycloud.net/](https://www.eycloud.net/)

---

<div align="center">
  <sub>Built with ❤️ for developers, writers, and researchers worldwide. Powered by Open Source.</sub>
</div>
