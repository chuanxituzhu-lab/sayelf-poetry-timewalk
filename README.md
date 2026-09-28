# SayElf Poetry Timewalk

### 古诗词沉浸探访系统 · SayElf Poetry Immersion Engine

**v1.3.2 Public Starter Download｜v1.3.2 免费公开入门包**

把诗词带回它发生的现场：以可复核的文本与证据为基础，组织历史语境、人物处境、诗词意境和连续视觉叙事。本仓库只提供公开 Demo / Starter，不包含完整商业交付包。

[下载最新版公开包 v1.3.2（ZIP）](https://github.com/chuanxituzhu-lab/sayelf-poetry-timewalk/releases/latest/download/sayelf-poetry-timewalk-public-starter-v1.3.2.zip) · [查看 v1.3.0 公开介绍](01-core-product/webui/poetry-immersion-engine-v1.3-public-intro.html) · [v1.3.2 发布记录](https://github.com/chuanxituzhu-lab/sayelf-poetry-timewalk/releases/tag/v1.3.2) · [商业咨询](https://github.com/chuanxituzhu-lab/sayelf-poetry-timewalk/issues/new?template=commercial-inquiry.md)

v1.3.2 扩充公开版证据链来源规范，并更新分发包；包内介绍页仍为 v1.3.0，单文件离线 Demo 仍为 v1.2 历史版，工作台画面和演示数据未改。每次公开更新均使用不可变的 `vMAJOR.MINOR.PATCH` 版本标签；此处“最新版下载”会跟随 GitHub 最新稳定 Release。

---

## 中文

### 这是什么

SayElf Poetry Timewalk（诗词沉浸探访系统）帮助创作者、教育者和研究者，把一首诗词整理为可审阅的内容与视觉创作方案。它强调“先有文本和证据，再做解读与创作”，不是诗词事实数据库，也不把 AI 生成的解释自动当作史实。

### 公开版能做什么

- **C/E/S 证据分层**：区分诗词文本（Content）、历史与文本依据（Evidence）、解读与创作综合（Synthesis）。
- **回到写作现场**：围绕人物、器物、空间、光线与情绪组织场景。
- **图像与分镜配对**：为关键画面生成可复制的图像提示词，并与视频分镜逐项对应。
- **连续性与发布检查**：用稳定编号和连续性约束减少画面漂移；发布前由人复核史实、版权和平台要求。

公开版输出的是创作方案、提示词和分镜，不承诺在本仓库中直接渲染成品视频；历史与创作内容应由使用者核验后再发布。

### 快速开始

1. 下载 [最新版公开包 v1.3.2（ZIP）](https://github.com/chuanxituzhu-lab/sayelf-poetry-timewalk/releases/latest/download/sayelf-poetry-timewalk-public-starter-v1.3.2.zip) 并解压。
2. 打开包内 v1.3.0 介绍页了解工作流，或在现代浏览器中打开 v1.2 单文件离线 Demo。无需构建步骤。
3. 按仓库中的 [Public Starter Skill](SKILL.md)、[C/E/S 证据链说明](docs/C-E-S-evidence-chain.md) 与[证据来源索引](docs/evidence-source-index.md) 试用流程。

Demo 是用于了解方法的公开样例，不是完整诗词库或完整商业系统。公开 HTML 可本地打开；特定浏览器功能和设备能力可能有所不同。

### 免费公开内容与商业边界

| 免费公开仓库 | 商业交付边界 |
| --- | --- |
| v1.3.2 公开分发 ZIP（含 v1.3.0 介绍页、v1.2 历史 Demo、精简 Starter Skill 与证据来源索引） | 完整工作台 H5、全量诗词库、完整导入 Skill、Creator / Pro 内容及权属未核素材不放在公共仓库 |
| 用于体验 C/E/S、场景拆解、提示词与分镜工作流 | 具体可提供内容、授权范围、交付格式、排期与费用须逐项确认；本仓库不公布价格，也不构成购买或交付承诺 |

`02-commercial-packages/` 中的文件仅说明边界，是占位说明，不是可下载的付费包。商业需求可通过 [GitHub Issues 商业咨询模板](https://github.com/chuanxituzhu-lab/sayelf-poetry-timewalk/issues/new?template=commercial-inquiry.md) 提交。请只写非敏感的需求摘要，不要公开发布个人联系方式、付款信息、客户材料、密钥或私有链接；经受理后再通过获准的私下渠道确认商务信息。

### 目录

- `01-core-product/` — 公开 WebUI 与方法说明。
- `02-commercial-packages/` — 商业包边界占位说明，不含商业包本体。
- `03-sales-materials/` — 公开产品介绍与 FAQ。
- `04-ops-extension-archive/` — 暂不纳入 Starter 的扩展范围说明。
- `docs/` — C/E/S 证据链说明与证据来源索引。
- `examples/` — Demo 使用说明。
- `assets/` — 公开素材来源与边界说明。

### 版权与使用

本仓库中适用的代码和文档许可见 [`LICENSE`](LICENSE)。诗词版本、引用材料、字体、图片及其他第三方内容可能适用各自的授权或版权规则；公开仓库的许可不自动覆盖第三方素材，使用者应在再发布前逐项核验。

---

## English

**Latest public package: v1.3.2** · [Download the versioned ZIP](https://github.com/chuanxituzhu-lab/sayelf-poetry-timewalk/releases/latest/download/sayelf-poetry-timewalk-public-starter-v1.3.2.zip) · [Release notes](https://github.com/chuanxituzhu-lab/sayelf-poetry-timewalk/releases/tag/v1.3.2)

v1.3.2 adds a public evidence-source index for primary texts, scholarly editions, modern research, attributed contemporary interpretation, and library catalogs. It distinguishes discovery metadata from inspected evidence. The package still contains the v1.3.0 introduction and v1.2 legacy single-file demo; it is not a new full-catalog or UI build. Public releases use immutable `vMAJOR.MINOR.PATCH` tags; the “latest” URL follows the newest stable GitHub Release.

### What this project is

SayElf Poetry Timewalk (the Poetry Immersion Engine) helps creators, educators, and researchers turn a poem into a reviewable content and visual-storytelling plan. It starts with the text and its evidence, then separates interpretation from creative synthesis. It is not a comprehensive poetry fact database, and AI-generated interpretation must not be treated as historical fact by default.

### What the public edition offers

- **C/E/S evidence layers** — distinguish poem content, historical or textual evidence, and synthesis or creative interpretation.
- **A return to the poem’s scene** — organize people, objects, space, light, and emotional movement.
- **Matched image and storyboard prompts** — create copyable image prompts for keyframes and corresponding video-storyboard prompts.
- **Continuity and release checks** — use stable IDs and continuity constraints to reduce visual drift; have a person review facts, rights, and platform requirements before publication.

The public edition provides creative plans, prompts, and storyboards. It does not promise to render finished videos in this repository. Historical and creative material should be reviewed before publication.

### Get started

1. Download and unzip the [latest v1.3.2 public package](https://github.com/chuanxituzhu-lab/sayelf-poetry-timewalk/releases/latest/download/sayelf-poetry-timewalk-public-starter-v1.3.2.zip).
2. Open the included v1.3.0 introduction or the v1.2 legacy single-file demo in a modern browser. No build step is required.
3. Follow the [Public Starter Skill](SKILL.md), [C/E/S evidence-chain guide](docs/C-E-S-evidence-chain.md), and [evidence-source index](docs/evidence-source-index.md).

The demo is a public example of the method, not a complete poetry library or commercial system. The public HTML can be opened locally; browser features and device capabilities may vary.

### Free public edition and commercial boundary

| Free public repository | Commercial delivery boundary |
| --- | --- |
| v1.3.2 public ZIP (v1.3.0 introduction, v1.2 legacy demo, abbreviated Starter Skill, and evidence-source index) | The complete workbench H5, full poetry catalog, complete import Skill, Creator / Pro materials, and uncleared assets are not included |
| Explore the C/E/S method, scene breakdown, prompt writing, and storyboard workflow | Scope, licensing, format, schedule, and fees must be confirmed individually. No prices are published here, and this README is not a purchase or delivery commitment. |

Files under `02-commercial-packages/` are boundary placeholders only; they are not downloadable paid packages. For a commercial inquiry, use the [GitHub Issues inquiry template](https://github.com/chuanxituzhu-lab/sayelf-poetry-timewalk/issues/new?template=commercial-inquiry.md). Share only a non-sensitive summary. Do not post personal contact details, payment information, customer materials, credentials, or private URLs publicly. If an inquiry is accepted, commercial details should be confirmed through an authorized private channel.

### Repository map

- `01-core-product/` — public WebUI and method notes.
- `02-commercial-packages/` — commercial-boundary placeholders; no package contents.
- `03-sales-materials/` — public product description and FAQ.
- `04-ops-extension-archive/` — notes on extensions outside the Starter scope.
- `docs/` — C/E/S evidence-chain guide and evidence-source index.
- `examples/` — public demo usage notes.
- `assets/` — public asset provenance and boundary notes.

### Copyright and use

See [`LICENSE`](LICENSE) for the license applicable to files in this repository. Poem editions, quoted sources, fonts, images, and other third-party materials may have separate rights or license terms. The repository license does not automatically cover third-party materials; review them before redistribution.

---

**Repository:** [chuanxituzhu-lab/sayelf-poetry-timewalk](https://github.com/chuanxituzhu-lab/sayelf-poetry-timewalk) · **Latest public package:** [v1.3.2](https://github.com/chuanxituzhu-lab/sayelf-poetry-timewalk/releases/tag/v1.3.2)
