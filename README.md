# Shenghan Gao | Engineering Portfolio

**Mechanical design, materials, and hands-on engineering.**  
**机械设计、材料与工程实践。**

[Website / 网站](https://shenghan.cc/) · [LinkedIn](https://www.linkedin.com/in/shenghan-gao-254157432/) · [Email / 邮箱](mailto:23RL30@queensu.ca)

## About / 关于网站

This is my personal engineering portfolio. I study Mechanical & Materials Engineering at Queen’s University, in the Materials Option. The website brings together my projects, academic background, internships, laboratory work, and practical experience in one place.

这是我的个人工程作品集网站。我在加拿大女王大学就读机械与材料工程专业，选择材料方向。网站集中展示我的工程项目、教育背景、实习经历、材料实验和动手实践。

The portfolio shows both the work and my contribution: mechanical design, control code, simulation, experimental analysis, and technical documentation. Project photographs, CAD models, plots, and laboratory images provide examples alongside the descriptions.

作品集展示项目内容及我承担的工作，包括机械设计、控制编程、仿真、实验分析和技术文档。项目照片、CAD 模型、数据图表和实验图片与文字说明配合，呈现具体的工作过程。

The site is built with HTML, CSS, and vanilla JavaScript. It uses separate pages, shared styling, and a shared bilingual content dictionary. It can be served directly as a static website, with no package installation or build step.

网站使用 HTML、CSS 和原生 JavaScript 开发，由独立页面、共用样式和中英文内容字典组成。可以直接作为静态网站部署，无需安装项目依赖或执行构建。

## Pages / 页面内容

| Page / 页面 | File / 文件 | Content / 内容 |
| --- | --- | --- |
| Home / 首页 | `index.html` | Personal introduction, academic profile, and portfolio overview. / 个人介绍、学业概况与作品集入口。 |
| Education / 教育背景 | `education.html` | Degree information, academic highlights, scholarships, and a transcript overview. / 学位信息、学业表现、奖学金与课程成绩概览。 |
| Timeline / 经历时间线 | `timeline.html` | Internships, projects, awards, certificates, and mentoring experience, with category filters. / 实习、项目、奖项、证书和导师经历，可按类别筛选。 |
| Projects / 项目 | `projects.html` | Engineering prototypes, simulations, laboratory studies, documentation, and website projects. Featured projects include expandable details. / 工程原型、仿真、材料实验、文档及网站项目，重点项目可展开查看详情。 |
| Tools / 工具与方法 | `tools.html` | Engineering methods, software, programming, workshop experience, and examples of their use. / 工程方法、软件、编程、现场实践及对应的应用实例。 |
| Contact / 联系方式 | `contacts.html` | Email, phone, location, GitHub, LinkedIn, and professional interests. / 邮箱、电话、所在地、GitHub、LinkedIn 与职业交流方向。 |

## Site Features / 网站功能

- **English and Chinese / 中英双语:** Switch the main page content without navigating to another URL. The language preference is saved in the browser’s `localStorage`. / 在当前页面切换主要内容的语言，语言偏好保存在浏览器的 `localStorage` 中。
- **Responsive layouts / 响应式布局:** CSS Grid, Flexbox, and media queries adapt navigation, cards, and content columns to different screen widths. / 使用 CSS Grid、Flexbox 和媒体查询，按屏幕宽度调整导航、卡片和内容分栏。
- **Filterable timeline / 可筛选时间线:** Show experience by category using the timeline controls. / 通过时间线筛选按钮按类别查看经历。
- **Expandable case studies / 可展开项目详情:** Selected projects open dialogs with photographs, technical descriptions, and workflow details. Triggers support Enter and Space; Escape closes the dialog. / 部分项目可展开照片、技术说明和流程详情；支持 Enter 或空格打开、Escape 关闭。
- **Tool image galleries / 工具图片展示:** Continuously scrolling image strips connect tools with examples of their use and pause on hover. / 连续滚动的图片展示工具应用实例，鼠标悬停时暂停。
- **Search and sharing metadata / 搜索与分享信息:** Page titles, descriptions, canonical URLs, Open Graph metadata, `robots.txt`, and `sitemap.xml` are included. / 配置页面标题、描述、规范链接、Open Graph 信息、`robots.txt` 和 `sitemap.xml`。

## Implementation / 技术实现

| Component / 组成 | Implementation / 实现 |
| --- | --- |
| Page structure / 页面结构 | Six HTML pages with shared navigation and footer patterns. / 六个 HTML 页面，共用导航和页脚结构。 |
| Styling / 样式 | `style.css`: layout, typography, colors, image fitting, transitions, and responsive rules. / 布局、字体、配色、图片适配、过渡效果与响应式规则。 |
| Interaction / 交互 | `script.js`: language switching, navigation, timeline filters, project dialogs, scroll reveals, and image galleries. / 语言切换、导航、时间线筛选、项目弹窗、滚动显示与图片展示。 |
| Translation / 翻译 | `translations.en` and `translations.zh`, connected to HTML through `data-i18n` and `data-i18n-alt`. / 中英文内容字典，通过对应属性关联正文与已配置的图片替代文本。 |
| Fonts / 字体 | Space Grotesk and Noto Sans SC, loaded through Google Fonts. / 通过 Google Fonts 加载。 |
| Icons / 图标 | Font Awesome, loaded through a CDN stylesheet. / 通过 CDN 样式表加载。 |
| Assets / 素材 | Local photographs, diagrams, plots, micrographs, certificates, and patent PDFs. / 本地照片、示意图、数据图、显微照片、证书和专利 PDF。 |
| Hosting model / 部署方式 | Static files, with no backend service or database required. / 静态文件，无需后端服务或数据库。 |

JavaScript enables the interactive sections and language switching. Google Fonts and the icon stylesheet require network access; the HTML, CSS, JavaScript, and portfolio assets are stored with the site.

交互部分和语言切换依赖 JavaScript。Google Fonts 和图标样式表需要网络连接，网页文件、样式、脚本及作品集素材保存在网站目录中。

## File Structure / 文件结构

Place this README beside `index.html` in the website source directory.

将本 README 放在网站源码目录中，与 `index.html` 同级。

| Path / 路径 | Purpose / 用途 |
| --- | --- |
| `index.html` | Homepage / 首页 |
| `education.html` | Education and academic information / 教育与学业信息 |
| `timeline.html` | Experience timeline / 经历时间线 |
| `projects.html` | Project cards and case studies / 项目卡片与详情 |
| `tools.html` | Engineering methods and tools / 工程方法与工具 |
| `contacts.html` | Contact information and social profiles / 联系方式与个人账号 |
| `style.css` | Shared stylesheet / 共用样式表 |
| `script.js` | Shared interactions and translations / 共用交互与翻译 |
| `img/profile/` | Portrait and affiliation imagery / 肖像与学校相关图片 |
| `img/projects/` | Project photographs and figures / 项目照片与图表 |
| `img/timeline/` | Experience, award, and certificate images / 经历、奖项与证书配图 |
| `img/tools/` | Software screenshots and practical-work images / 软件截图与实践图片 |
| `docs/certificates/` | Certificate PDFs / 证书 PDF |
| `docs/patents/` | Patent PDFs / 专利 PDF |
| `favicon.svg`, `favicon-32x32.png`, `apple-touch-icon.png` | Browser and device icons / 浏览器与设备图标 |
| `robots.txt`, `sitemap.xml` | Crawler instructions and page index / 爬虫访问说明与页面索引 |

## Local Preview / 本地预览

With Python 3 installed, open a terminal in the directory containing `index.html` and run:

安装 Python 3 后，在包含 `index.html` 的目录中打开终端并运行：

```bash
python3 -m http.server 8000 --bind 127.0.0.1
```

On Windows, the equivalent command using the Python launcher is:

Windows 上可以通过 Python 启动器运行：

```powershell
py -m http.server 8000 --bind 127.0.0.1
```

Open [http://127.0.0.1:8000](http://127.0.0.1:8000) in a browser. Stop the server with `Ctrl+C`.

在浏览器中打开 [http://127.0.0.1:8000](http://127.0.0.1:8000)，使用 `Ctrl+C` 停止服务器。

## Deployment / 部署

Upload the contents of the website source directory to the static host’s document root, keeping `index.html` at the entry point. Preserve the relative paths of `img/`, `docs/`, `style.css`, and `script.js`.

将网站源码目录内的文件上传到静态托管服务的网站根目录，以 `index.html` 作为入口。保持 `img/`、`docs/`、`style.css` 和 `script.js` 的相对路径不变。

For an archive containing a `shenghan` folder, deploy the contents of that folder. If moving the site to another domain, update the canonical and sharing URLs in the HTML files, as well as the domain references in `sitemap.xml` and `robots.txt`.

如果压缩包中包含 `shenghan` 文件夹，上传该文件夹内的内容。更换域名时，需要同步修改 HTML 中的规范链接和分享链接，以及 `sitemap.xml`、`robots.txt` 中的域名。

## Maintaining the Site / 内容维护

1. **Update both languages / 同步维护双语。** Add or edit matching keys in `translations.en` and `translations.zh`. Keep the English fallback text in HTML consistent with the English dictionary. / 在中英文内容字典中维护对应键，并让 HTML 默认英文与英文词条一致。
2. **Keep image context / 保留图片含义。** Use descriptive alt text and captions. When cropping technical figures, retain the measurements or features needed to understand the image and preserve attribution. / 编写清楚的替代文本和图注；裁切技术图片时保留理解图片所需的测量标记或关键特征，并注明来源。
3. **Reuse page components / 沿用现有组件。** Follow the existing project-card, timeline-item, and tool-gallery structures. Keep dialog IDs and their triggers paired. / 沿用项目卡片、时间线条目和工具图集结构，确保弹窗 ID 与触发元素对应。
4. **Refresh shared assets / 刷新共用资源。** When changing shared CSS or JavaScript, update their version query strings consistently across all six HTML pages. / 修改共用 CSS 或 JavaScript 后，在六个 HTML 页面中同步更新引用的版本参数。
5. **Review before publishing / 发布前复核。** Check both languages, links, images, navigation, project dialogs, and desktop/mobile layouts. / 检查中英文、链接、图片、导航、项目弹窗及电脑和手机布局。

## Credits / 作者与素材来源

Website design and development: **Shenghan Gao**. The project descriptions identify my own work and contributions made by teammates. The orbital simulation builds on a provided course framework. Laboratory micrographs credited on the site were supplied by the MECH 396 teaching team; the associated analysis is described in my project reports.

网站设计与开发：**高胜寒（Shenghan Gao）**。项目介绍区分本人工作和组员贡献。其中轨道仿真基于课程提供的框架；网站中注明来源的材料实验显微照片由 MECH 396 教学团队提供，相关分析记录在我的项目报告中。

The site uses Google Fonts and Font Awesome for typography and icons. University and company names and logos identify the relevant institutions and projects.

网站使用 Google Fonts 和 Font Awesome 提供字体与图标。页面中的学校、公司名称及标志用于说明相关机构和项目背景。

## Contact / 联系方式

| Channel / 渠道 | Link / 链接 |
| --- | --- |
| Website / 网站 | [shenghan.cc](https://shenghan.cc/) |
| LinkedIn | [Shenghan Gao](https://www.linkedin.com/in/shenghan-gao-254157432/) |
| Email / 邮箱 | [23RL30@queensu.ca](mailto:23RL30@queensu.ca) |
