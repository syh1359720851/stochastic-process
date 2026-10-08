# 项目说明：随机过程课程学习

> **本文件是项目唯一规范文档（CLAUDE.md）。任何 agent 进来工作前，必须先读完本文件。**

---

## 1. 项目用途

本目录用于存放两门"随机过程"相关课程的课件，并作为使用 Claude Code（或其他 agent）辅助学习的入口。

学习者最终要达到的目标：**系统掌握两门课的全部知识点，达到能解题、能应试、能应用的水平**。可视化与交互只是手段之一，不是目的本身。

---

## 2. 课程资料（原始课件，禁止改动）

- `随机过程/` ——《随机过程》课程（彭江燕·UESTC）
  - `sjgc0.0.pdf`：总论/导论
  - `sjgc0-1概率空间-1.pdf`：概率空间（讲次 1）
  - `第二次课9.7.zip`、`第3次课件9.9.zip`、`第5次课9.16.zip`、`第6次课课件9.21.zip`：按上课日期归档
  - `第7次课9.23.zip`（内含 `sjgc1.1-2.pdf` 随机过程的定义及分类、`sjgc1.2-1.pdf` 随机过程的数字特征）、`第8次课件9.30.zip`（内含 `sjgc1.2-2.pdf` 随机过程的数字特征、`sjgc1.3-1.pdf` 随机过程的基本类型）：**第一章全章**，第 06 讲主要来源
- `随机过程与排队论/` ——《随机过程与排队论》课程（王庆先·UESTC）
  - `排队论-唐应辉等.pdf`：唐应辉等《排队论》教材
  - `随机过程及应用-陈良均.pdf`：陈良均《随机过程及应用》教材
  - `第1讲.pptx` ~ `第6讲.pptx`：按讲次归档（第 6 讲 = 马尔可夫链，属第 08 / 09 讲范围）

> ⚠️ **不要删除或重命名课件。** 新增学习产物只能放在新建子目录中。

---

## 3. 当前状态（持续维护）

- ✅ **第 01 讲 · 概率空间（公理化基础）** — 已完成 10 个页面
  - 目录：`01-概率空间/`
  - 文件：index.html + 6 个概念页（01~06，含 "集合的并与交：有限/可列/不可列"澄清页）+ 2 个动画页 + 自测.html
- ✅ **第 02 讲 · 条件概率与 Bayes** — 已完成 9 个页面
  - 目录：`02-条件概率与Bayes/`
  - 文件：index.html + 6 个概念页（01~06：定义 / 乘法公式 / 全概率 / Bayes / 独立性 / 独立重复试验）+ 1 个动画页（Monte Carlo 验证）+ 自测.html（含 1 道挑战题）
  - 来源：sjgc0-1概率空间-2.pdf（含三门问题 + Monty Fall + $n$ 扇门推广 + GPT/LLM 视角）
- ✅ **第 03 讲 · 随机变量与分布函数** — 已完成 10 个页面
  - 目录：`03-随机变量与分布函数/`
  - 文件：index.html + 8 个概念页（01~08：随机变量定义 / 分布函数 / 离散型 / 连续型 / **混合型 / 二维联合 / 边缘条件 / 函数分布）+ 1 个动画页（9 种分布的 $F$/$f$ 实时可视化）+ 自测.html（10 题，含单调公式法、卷积等）
  - 来源：sjgc0-2随机变量-2.pdf + sjgc0-3随机变量的函数.pdf（彭江燕）+ 第2讲.pptx（王庆先）
- ✅ **第 04 讲 · 常见分布族** — 已完成 8 个页面（精简纯理论版）
  - 目录：`04-常见分布族/`
  - 文件：index.html + 6 个概念页（01~06：Bernoulli / 二项 / 几何 / 负二项 / **Poisson / 均匀 / 指数 / Gamma / 正态**）+ 自测.html（10 题，含 3σ 原则、Gamma-Poisson 对偶）
  - 来源：陈良均《随机过程及应用》第 1 章 + 唐应辉《排队论》第 1 章 + 王庆先第 1 讲（两点/二项）+ 彭江燕第 3 讲（随机变量-2 离散族例）
- ✅ **第 05 讲 · 数字特征与特征函数** — 已完成 13 个页面
  - 目录：`05-数字特征与特征函数/`
  - 文件：index.html + 10 个概念页（01 R-S 积分 / 02 期望 / 03 函数期望 / 04 方差 / 05 协方差 / 06 矩 / 07 条件期望 / 08 Wald 方程 / 09 特征函数 / 10 常见分布特征函数对照）+ 1 个动画页（分布参数与 E/D/|φ(t)| 三联画联动）+ 自测.html（10 题，含全期望、Wald、特征函数唯一性、独立 Poisson 之和、投资组合）
  - 来源：彭江燕第 3/5 次课件（数值特征 + 特征函数）+ 王庆先第 2 讲（数字特征）+ Wald 方程 → LLM Perplexity 延伸
- ✅ **第 06 讲 · 随机过程的基本概念** — 已完成 20 个页面（2026-10-08 扩充）
  - 目录：`06-随机过程的基本概念/`
  - 文件：index.html + 前置页 `00-n维随机变量与协方差阵.html` + 16 个概念页（01~16）+ **2 个动画页**（`动画-过程样本轨道族.html` 轨道族 ↔ 均值 ↔ 均方差带、`动画-有限维分布搭积木.html` 相容性交互演示）+ 自测.html（15 题）
  - 来源：**彭江燕第 7 次课（9.23）** `sjgc1.1-2.pdf` + `sjgc1.2-1.pdf` · **第 8 次课（9.30）** `sjgc1.2-2.pdf` + `sjgc1.3-1.pdf` · 王庆先第 3 讲.pptx · 陈良均《随机过程及应用》第 2 章
  - **2026-10-08 扩充内容**：按彭江燕课件第一章补齐"二阶矩 → 判据"整条链
    - 新增 4 页：`09-二阶矩过程与协方差非负定性`（定义 1.3.1、许瓦茨不等式、非负确定性理 1.3.1 完整证明、埃密特性、实平稳 $R(\tau)$ 偶函数）、`10-宽平稳过程`（课件思考题"方差函数呢"、随机振幅电信号、随机正弦波、**四种随机正弦波对比表**、$Y(t)=U\cos t^2+V\sin t^2$ 反例）、`11-严平稳过程`（定义、三个经典例子、严/宽对比表、柯西无矩反例、高斯等价）、`12-正交增量与白噪声`（正交增量 vs 独立增量、离散/连续白噪声、谱平坦性、半二元传输信号）
    - **讲次重编号**：原 09~12 顺延为 13~16（`13-独立过程与独立增量过程` / `14-平稳独立增量过程` / `15-正态过程` / `16-维纳过程`），全部 pager / 目录 / 节号引用同步修正
    - 现有页补课件原例：04 页九宫格二维分布函数（$X_t=\pm2\cos t$，$p=2/3,1/3$）、06 页随机开关系统 + $X_t=U+Vt$ 一二维密度、07 页随机开关系统 $R$/$C$ 完整推导、08 页含噪系统 $Y_t=X_t+N_t$ 正交分解与"互不相关 vs 正交"定义
    - **2026-10-08 追加 · 04 节重做**：用户反馈"有限维分布仍不理解"。新增 `动画-有限维分布搭积木.html`——演示 A 手填 $3\times3$ 联合分布表 + 两份一维分布，点"检查相容性"看是 ✅ 自洽还是 ❌ 自相矛盾（预设：独立 / 完全相关 / 完全反相关 / 行和≠一维 / 总和≠1）；演示 B 从真实轨道反推分布，验证"一维 ≡ 二维的行和列和"。04 页同步补课件 §1.1.4 四步逻辑链、相容性的"压扁成边缘"画面、六应用对照表（含 LLM 自回归分解）、分布函数取 $+\infty$ vs 特征函数取 $0$ 的对照。
  - 课件勘误（已在页面中标注）：
    1. 王庆先第 3 讲 slide 45 写 $D[Y(n)]=pq$，正确应为 $npq$（$B(n,p)$ 的方差）
    2. 彭江燕第 7 次课随机正弦波页写 $D(t)=C(t,t)=1$，按其自身给出的 $C(s,t)=\frac12\cos\beta(s-t)$ 应为 $\boxed{\frac12}$
    3. 彭江燕第 7 次课随机开关系统页的 $C(s,t)$ 化简漏系数，应为 $\frac14\cos\pi s\cos\pi t-\frac t2\cos\pi s-\frac s2\cos\pi t+st$（用 $C(t,t)=D(t)$ 一验即发现）
- ⏳ 第 07 讲 ~ 第 14 讲 — 待开始（见下表）

> 📌 **2026-10-08 课件更新**：新增 `随机过程/第7次课9.23.zip`、`随机过程/第8次课件9.30.zip`、`随机过程与排队论/第6讲.pptx`。前两者即彭江燕教材第一章全章（§1.1 定义及分类 / §1.2 数字特征 / §1.3 基本类型），已全部并入第 06 讲；王庆先第 6 讲是**马尔可夫链**（状态分类、首达与常返、状态空间分解、周期性、连续参数马氏链与 $Q$ 矩阵），归属第 08 / 09 讲，暂未制作。

> 📌 **2026-09-22 讲次编号校准**：原第 06 讲「多维随机变量」（标注"教材补"）已并入第 06 讲的**前置页 00**——因其核心内容（二维联合、边缘、条件、协方差）与第 03 / 05 讲重叠较多，且无现成课件；原第 07 讲「随机过程的基本概念」升为第 06 讲；原第 10 讲「Poisson 过程」前移补位为第 07 讲（与王庆先第 3 讲末尾的"下一讲内容预告"顺序一致）。**总讲次由 16 讲调整为 14 讲。** 若需恢复原编号，只需改回 `index.html` 与本表的讲次数字段。

### 3.1 融合讲次路线图（统一 14 讲）

| # | 标题 | 主要来源 | 备注 |
|---|---|---|---|
| 01 | 概率空间（公理化基础） | 两门课 + 教材 | ✅ **已交付** |
| 02 | 条件概率与 Bayes | 两门课 + 教材 | ✅ **已交付** |
| 03 | 随机变量与分布函数 | 两门课 + 教材 | 离散 / 连续 / 混合 | ✅ **已交付** |
| 04 | 常见分布族 | 两门课 + 教材 | Bernoulli/Poisson/正态/指数/Gamma… | ✅ **已交付** |
| 05 | 数字特征与特征函数 | 两门课 + 教材 | 期望 / 方差 / 矩 / 协方差 / 特征函数 | ✅ **已交付**（13 页） |
| 06 | 随机过程的基本概念 | 彭江燕第 7/8 次课 + 王庆先第 3 讲 + 教材 | 定义 / 分类 / 有限维分布 / 四个数字特征 / 二阶矩与平稳性 / 独立与正态 / 维纳 | ✅ **已交付**（20 页） |
| 07 | Poisson 过程 | 王庆先第 4 讲 + 两门课 + 教材 | 两定义等价性、分布、数字特征、非齐次、复合、更新计数 | 王庆先第 3 讲预告的下一讲 |
| 08 | Markov 链（离散时间） | **王庆先第 6 讲** + 两门课 + 教材 | 转移矩阵、状态分类（互通/首达/常返/正常返）、状态空间分解、不可约、周期性、遍历性与平稳分布 | 课件已到位 |
| 09 | Markov 链（连续时间） | **王庆先第 6 讲后半** + 两门课 + 教材 | 转移概率函数、连续参数齐次链、$Q$ 矩阵、后退/前进方程、福克-普朗克方程 | 课件已到位 |
| 10 | 更新过程 | 教材补 | 更新定理、Blackwell、关键更新定理 | |
| 11 | Brown 运动与鞅 | 两门课 + 教材 | 维纳过程深入、鞅、Doob 分解、可选停时、二次变差 | 第 06 讲已打底 |
| 12 | 排队论基础 | 仅 排队论 | Kendall 记号、Little 律、PASTA、M/M/1、M/M/c | |
| 13 | 排队论高级 | 仅 排队论 | M/G/1、G/M/1、嵌入 Markov、优先级、队列网络 | |
| 14 | 综合自测与考研题 | 综合 | 综合卷 + 考研真题 + 应用案例 | |

> 讲次编号已按 2026-09-22 的校准结果固定；后续若新增课件（如彭江燕的"n 维随机变量"专章），可再考虑把前置页 00 拆成独立一讲。

### 3.2 课程入口

- 根目录 `index.html`：融合版课程地图（第 01 ~ 06 讲绿色高亮可点，均已链接到对应讲次首页）

---

## 4. 核心目标（按优先级）

任何 agent 制作新讲次时，按以下层级判断如何呈现：

1. **概念完整覆盖**（必须）——本讲涉及的**所有**定义、定理、性质、公式、典型例题、常见考点都要呈现。**不允许**为了"好做动画"而省略纯证明、纯推导、纯抽象定义的内容。
2. **可读讲解**（必须）——每个知识点给：① 直观含义 ② 严格陈述（KaTeX 渲染）③ 课件/教材原例 ④ 一句话记忆要点。
3. **现实例子**（必须）——每个抽象概念至少配一个贴近生活的类比（排队、客服电话、网页访问、股价、粒子扩散、抛硬币、摸彩球……）。
4. **可视化 / 交互**（按需）——仅当可视化能显著降低理解成本时才做：
   - 样本轨道 / 时间演化（Markov 链、Poisson、Brown 运动、排队演化）
   - 分布形状随参数变化（滑块控制 λ, μ, p, n）
   - σ-代数的集合关系（维恩图）
   - Bayes 先验→后验更新
   - 大数定律、CLT 收敛
   - 纯定理证明 / 长公式推导 / 抽象代数结构 → **不做动画**，用结构化排版 + 折叠"展开证明"。
6. **自测巩固**（建议）——每讲末尾附 6–10 题自测，原页面直接给答案与解析。

---

## 5. 学习产物组织约定

### 5.1 目录结构

```
StochasticProcess/
├── CLAUDE.md                      ← 本文件
├── index.html                     ← 融合版课程地图
│
├── 01-概率空间/                   ← 每个讲次一个目录
│   ├── index.html                 ← 讲次首页：学习目标、知识图谱、目录卡片
│   ├── 01-XXX.html                ← 单个概念页
│   ├── 02-XXX.html
│   ├── ...
│   ├── 动画-XXX.html              ← 独立可交互演示
│   └── 自测.html
│
├── 02-条件概率与Bayes/
├── 03-随机变量与分布函数/
├── ...
│
├── shared/                        ← （待建立）跨讲次共享资源
│   ├── styles.css
│   ├── katex-config.html
│   └── prng.js
│
└── （原课件目录不动）
    ├── 随机过程/
    └── 随机过程与排队论/
```

### 5.2 单文件 HTML 模板要求

- **HTML 头部**固定包含：
  - KaTeX CSS：`<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.16.9/dist/katex.min.css">`
  - KaTeX 核心 + auto-render 脚本（用 `defer`，见 §6.2）
  - 自动调用 `renderMathInElement(document.body, {...})`（分隔符见 §6.4）
- **CSS 变量**统一在 `:root` 定义（浅色 + 暗色 via `prefers-color-scheme: dark`），调色板见 §6.4。
- 同一讲次内的所有页面**共享一套 `<style>` 块**——从已完成的 `01-概率空间/` 中任意一个页面复制即可。

### 5.3 单个概念页的标准结构（七段式）

```
1. 直观含义（蓝色 callout）
2. 严格定义（KaTeX 公式）
3. 现实例子（绿色 callout）——课件/教材原例优先
4. 关键性质 / 推导（紫色 callout + 折叠证明）
5. 易错点（黄色 callout）
6. 自检问题（折叠的 details/summary）
7. 一句话记忆要点（顶部带 📌 标记的灰色 callout）
```

每页**底部必须**有 pager：`< 上一节 | 下一节 >`。每页**顶部必须**有 breadcrumb：`课程地图 / 第0X讲 / 页号`。

### 5.4 讲次首页（`index.html`）必含元素

- 讲次标题（h1）
- 课程元信息（来源课件、参考教材、难度）
- 本讲学习目标（ol）
- 知识图谱 / 一句话定位
- 讲次目录（卡片网格，每个链接到对应页面）
- 与后续章节的关系（callout 警示）

---

## 6. ⚠️ 技术经验与陷阱（必读）

### 6.1 KaTeX auto-render **会忽略**以下标签

`KaTeX` 的 `renderMathInElement` 默认 `ignoredTags = ["script", "noscript", "style", "textarea", "pre", "code", "option"]`。**`$...$` 放在 `<code>` 里不会被渲染**，浏览器只会显示原始文本。

> ❌ 错误写法（页面看起来像"代码"，但 KaTeX 不会处理）：
> ```html
> 概率空间 <code>$(\Omega,\mathcal{F},P)$</code> 是……
> ```
>
> ✅ 正确写法：去掉 `<code>` 外层，让 `$...$` 直接出现在文本节点中。
> ```html
> 概率空间 $(\Omega,\mathcal{F},P)$ 是……
> ```

**类似坑**：`<pre>$...$</pre>`、`<textarea>$...$</textarea>` 都不会渲染。新建页面时用 `grep -lE '<code>\\$[^<]*\\$</code>' *.html` 自我扫描。

### 6.2 KaTeX 脚本加载顺序

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.16.9/dist/katex.min.css">
<script defer src="https://cdn.jsdelivr.net/npm/katex@0.16.9/dist/katex.min.js"></script>
<script defer src="https://cdn.jsdelivr.net/npm/katex@0.16.9/dist/contrib/auto-render.min.js"
  onload="renderMathInElement(document.body,{delimiters:[...],throwOnError:false});"></script>
```

- `defer` + `onload` 的组合可以让 `renderMathInElement` 在 KaTeX 加载完成后被调用。
- 必须设 `throwOnError:false`——这样公式错误不会阻断后续渲染。

### 6.3 分隔符配置

每页都用这套四种分隔符（兼容多份课件混排）：

```js
{
  delimiters: [
    {left:'$$', right:'$$', display:true},
    {left:'$',  right:'$',  display:false},
    {left:'\\[', right:'\\]', display:true},
    {left:'\\(', right:'\\)', display:false}
  ],
  throwOnError:false
}
```

### 6.4 调色板（统一规范）

所有页面共用：

```css
:root {
  --c-bg:#ffffff; --c-fg:#1f2328; --c-muted:#57606a; --c-line:#d0d7de; --c-card:#f6f8fa;
  --c-primary:#0969da; --c-primary-bg:#ddf4ff;
  --c-accent:#1a7f37;  --c-accent-bg:#dafbe1;
  --c-warn:#9a6700;    --c-warn-bg:#fff8c5;
  --c-danger:#cf222e;  --c-danger-bg:#ffebe9;
  --c-theorem:#8250df; --c-theorem-bg:#fbefff;
}
@media (prefers-color-scheme: dark) {
  :root {
    --c-bg:#0d1117; --c-fg:#e6edf3; --c-muted:#8b949e; --c-line:#30363d; --c-card:#161b22;
    --c-primary:#58a6ff; --c-primary-bg:#051d4d;
    --c-accent:#3fb950;  --c-accent-bg:#0f2419;
    --c-warn:#d29922;    --c-warn-bg:#341a00;
    --c-danger:#f85149;  --c-danger-bg:#2d0a0a;
    --c-theorem:#d2a8ff; --c-theorem-bg:#1f1530;
  }
}
```

callout 颜色含义：蓝色=直观含义 / 紫色=定理性质 / 绿色=例子 / 黄色=易错 / 红色=警告。

### 6.5 SVG `<text>` 是纯文本节点（**不能放 HTML 子元素**）

> 2026-09-20 bug：第 03 讲"三角形区域均匀分布"配图里写了 `<text>S<sub>D</sub> = 1/4</text>`，导致**整个 SVG 解析失败**——所有 `<text>` 都 fallback 成 HTML 文字堆在 SVG 下面。

**规则**：SVG `<text>` 是 XML 元素，**内容只能是纯字符**，不能放 `<sub>`/`<sup>`/`<strong>` 等 HTML 标签。`text-anchor`/`font-size`/`font-style` 等属性可以，HTML 内联元素不行。

替代写法：
```svg
<!-- ❌ 错：HTML 子元素会让 SVG 解析失败 -->
<text>S<sub>D</sub> = 1/4</text>

<!-- ✅ 对：Unicode 数学符号 / 下划线表示 / 分行 -->
<text>S_D = 1/4</text>
<text>Sₙ = 1/4</text>  <!-- ₔ Unicode 下标，可直接用 -->
```

另外：KaTeX 的 `renderMathInElement(document.body)` **会扫描 SVG 内的文字**（默认 `ignoredTags` 不含 SVG），所以 SVG 内的 `$...$` 会被强行按数学模式处理。建议 SVG 内全部用普通文本 + Unicode 数学符号（`∫ √ π μ σ → ≤ ≥`），不在 SVG 里写 `$...$`。
相关经验：[[feedback-headless-screenshot]]。

### 6.5b SVG `viewBox` 必须正好 **4 个值** `min-x min-y width height`（5 个值 Chrome 会 fallback 到默认 300×150 把内容压扁）

> 2026-09-20 第 03 讲"三角形区域均匀分布"3 个图，**连续踩了 3 个 SVG 渲染坑**：
>
> **坑 1 · `aspect-ratio` 在 SVG 上失效**：用 `style="aspect-ratio:820/180"` 撑开 wrapper → headless Chrome 不支持，wrapper 高度撑不开。
>
> **坑 2 · `padding-top` hack wrapper 高度被撑大**：换成 `position:relative; padding-top:22%` + `position:absolute; height:100%` SVG → wrapper 高度被 SVG 内容撑到 411px（预期 317px），内容只填顶部 30%。
>
> **坑 3 · `viewBox` 多打一个 0**（最隐蔽）：原本想写 `viewBox="0 -150 820 320"`（4 个值：min-x min-y width height），手滑写成 `viewBox="0 0 -150 820 320"`（**5 个值**）。Chrome 把这种语法错误的 viewBox 当无效，fallback 到默认 300×150 viewport，**曲线斜率被压扁**（f_X=2x 看起来像 f_X=1x），y 轴上半部分标签全部被裁掉。用户连续反馈"纵向被压缩"才找到原因。

**规则 ①**：`viewBox` 必须**正好 4 个值** `min-x min-y width height`：

```svg
<!-- ❌ 错：多一个 0，5 个值 → Chrome fallback 默认 300×150 -->
<svg viewBox="0 0 -150 820 320" ...>

<!-- ✅ 对：4 个值 -->
<svg viewBox="0 -150 820 320" ...>
```

**规则 ②**：`viewBox` 高度匹配实际绘制 y 范围（上下各留 5-15px 余量）：

```svg
<svg viewBox="0 0 820 180" ...>           <!-- 实际 y ∈ [15, 145]，viewBox 给 180 -->
<svg viewBox="0 -150 820 320" ...>        <!-- 实际 y ∈ [-140, 140]，从 y=-150 起 -->
```

**规则 ③**：让 SVG 自己按 viewBox 算高度，**不要**用 `aspect-ratio` 或 `padding-top` hack：

```html
<!-- ✅ 唯一正确模板 -->
<div style="margin:18px 0;background:var(--c-card);border:1px solid var(--c-line);border-radius:8px;padding:8px">
  <svg viewBox="0 0 820 180"
       style="width:100%;height:auto;display:block">
    ...
  </svg>
</div>
```

**Why `height:auto` works**：SVG 元素有 `viewBox` 时，`width:100%` 会触发 intrinsic aspect ratio 解析，浏览器自动用 `viewBox.width / viewBox.height` 比例算 height。Chrome / Safari / Firefox 都支持。

**自检**：Chrome headless 截图（[[feedback-headless-screenshot]]）后**目视检查**——曲线斜率是否正确（f_X=2x 看起来应该明显比 45° 陡），y 轴标签是否完整。如果看起来"扁了"或"被压缩"，99% 是 viewBox 写错。

相关：[[feedback-svg-text-no-html]]（SVG `<text>` 不能放 HTML 子元素的另一个常见坑）。

### 6.6 一次性截图验证用 Chrome headless 单次命令（首选）

> 2026-09-20 经验：之前 §6.6/§6.7 写的 "browser-use 截图" 是反模式——它要起常驻 daemon、还要接管你电脑上的 Chrome（要求 `chrome://inspect/#remote-debugging` 已开），否则会自己拉一个独立 Chrome 实例，进程很难清理。**一次性"打开 HTML → 截图 → 走人"用 Chrome headless 单次命令就够了**：

```bash
# KaTeX 需要 JS 渲染，给 5 秒预算；长视口截全页（页面很长时调高 height）
"/c/Program Files/Google/Chrome/Application/chrome.exe" \
  --headless=new --no-sandbox --disable-gpu --hide-scrollbars \
  --window-size=1280,3000 \
  --virtual-time-budget=5000 \
  --screenshot="E:/.../out.png" \
  "file:///E:/.../page.html"
# 进程结束即清理，**不留任何 Chrome 进程或端口**
```

> 真要做交互式浏览（点击、填表单、跨页跳转）才用 `uv tool install browser-use`，那种场景才需要 daemon。

### 6.7 Windows + 中文路径坑

- 任何含中文路径的 Python/Shell 命令前要设：
  ```bash
  export PYTHONIOENCODING=utf-8
  export PYTHONUTF8=1
  ```
- 系统 `python` / `python3` 是 Microsoft Store 占位符（会提示安装），写脚本时**直接调用 `python3`**，若失败改用 `node` / `sed` / `awk` 等替代。
- `pdftotext` 提取中文 PDF 经常乱码（字体问题），可用 `unzip -p` 解 PPTX 后用 XML grep 取文本。

### 6.8 `<table>` 多列表头的列数陷阱（最容易出的 bug）

写二维表头（`rowspan` + `colspan` 混合）时，**必须保证每行的 `<th>/<td>` 总数 = 表头列数**。否则浏览器会自动补格，表头与数据错位串行。

> 2026-09-20 bug：第 03 讲"摸两次球"两个表格都中招——
> - 表头 4 列：`X\Y`(rspan=2) + `Y`(cspan=2) + `边缘 P(X)`(rspan=2) = 1+2+1
> - 数据第 1 行写了 5 个 cell：多了一个 `<th rowspan="2">$X$</th>`（表头里 `X\Y` 已经标识了行变量）
> - 最后一行写了 5 个 cell：多了一个 `<td>—</td>`
> - 结果：浏览器自动补格，表头"串行"（用户最早截图里的现象）

**衍生 bug · 底部行 `<th colspan="2">` 会吃掉 Y=0 那一列**：

> 同一个摸球表，最后一行原本写成 `<tr><th colspan="2">边缘 P(Y)</th><td>6/10</td><td>4/10</td></tr>`。4 列（X\Y | Y=0 | Y=1 | 边缘P(X)）。`colspan=2` 让"边缘 P(Y)"标签吃掉 X\Y 和 Y=0 两列，把 6/10 挤到 Y=1 下方、4/10 挤到边缘 P(X) 下方——数据值错位但**表头没有串行**，更难发现！

**正确写法**：底部行用 4 个 cell（标签窄 + 两个边缘值 + 角上的 1）：

```html
<!-- ❌ 错：colspan=2 把标签吃进 Y=0 列，数据被挤到错位置 -->
<tr><th colspan="2">边缘 P(Y)</th><td>6/10</td><td>4/10</td></tr>

<!-- ✅ 对：标签窄放在 X\Y 列，边缘值各占一列，角上放 "1" 验证归一 -->
<tr><th>边缘 P(Y)</th><td>6/10</td><td>4/10</td><td>1</td></tr>
```

**自检方法**：写完表后立即在浏览器里看一遍；或写一段最小验证：

```js
// 临时塞到页面底部
[...document.querySelectorAll('table')].forEach((t,i)=>{
  const hdr = t.rows[0].cells.length;
  t.querySelectorAll('tr').forEach((r,j)=>{
    if (r.cells.length !== hdr) console.warn(`table ${i} row ${j}: ${r.cells.length} cells vs header ${hdr}`);
  });
});
```

### 6.9 新讲次落地的最小检查流程

> 2026-09-22 更新：把原来"人工数表格列数""人工目视 viewBox"替换成**一次跑完的 Python 校验脚本**。第 06 讲 16 个页面就是靠这段脚本一次性过掉的（0 报错）。**建议把下面第 3~5 步合并执行**，比人工检查快且不会漏。

```bash
# 1. 创建目录
mkdir "0X-主题名"

# 2. 生成页面（参考 01-概率空间/ 中已有文件）

# 3. 静态自检（一次跑完四类检查）——把 LEC 换成你的讲次目录名
LEC="0X-主题名"
# 3a. 不能有 <code>$...$</code>（§6.1）
grep -lE '<code>\$[^<]*\$</code>' "$LEC"/*.html          # 期望：无输出
# 3b. viewBox 必须正好 4 个值（§6.5b）
#     注意：`viewBox="0 0 680 190"` 按空白切分正好 4 段（不要写成 NF-1）
grep -ohE 'viewBox="[^"]*"' "$LEC"/*.html | awk '{n=NF; if(n!=4) print "❌ "n" 个值: "$0}'   # 期望：无输出
# 3c+d. SVG 内不能有 HTML 子元素 / 不能出现 $ 公式；表格列数必须折算 colspan（§6.5 / §6.8）
python -c "
import re,glob,sys
lec=sys.argv[1]; bad=False
for f in sorted(glob.glob(lec+'/*.html')):
    s=open(f,encoding='utf-8').read()
    for svg in re.findall(r'<svg.*?</svg>', s, re.S):
        if re.search(r'<text[^>]*>[^<]*<(sub|sup|strong|em|b|i|code)', svg):
            print('❌ SVG text 含 HTML 子元素:',f); bad=True
        if '\$' in svg:
            print('❌ SVG 内含 \$ 公式:',f); bad=True
    for ti,t in enumerate(re.findall(r'<table.*?</table>', s, re.S)):
        rows=re.findall(r'<tr>(.*?)</tr>', t, re.S)
        if not rows: continue
        def cnt(r):
            n=0
            for m in re.finditer(r'<t[hd]([^>]*)>', r):
                cs=re.search(r'colspan=\"(\d+)\"', m.group(1)); n += int(cs.group(1)) if cs else 1
            return n
        h=cnt(rows[0])
        for ri,r in enumerate(rows):
            if cnt(r)!=h: print('❌ %s table%d row%d: %d 列 vs 表头 %d'%(f,ti,ri,cnt(r),h)); bad=True
print('✅ 静态自检全部通过' if not bad else '⚠️ 有报错，需修复')
" "$LEC"

# 4. Chrome headless 截图（§6.6）——建议对「讲次首页 + 每个含 SVG 的页 + 动画页」逐一截图
"/c/Program Files/Google/Chrome/Application/chrome.exe" --headless=new --no-sandbox \
  --disable-gpu --hide-scrollbars --window-size=1280,3200 --virtual-time-budget=6000 \
  --screenshot="/tmp/verify.png" "file:///.../index.html"

# 4b. 页面很长时截图会截断 → 用 Pillow 裁剪目标区域放大目视（比整页缩略图可靠得多）
python -c "
from PIL import Image
im=Image.open('/tmp/verify.png'); im.crop((100,2650,1180,3250)).save('/tmp/crop.png')
"
# 目视检查：KaTeX 是否渲染成数学符号 / 曲线斜率与标注是否被压扁（§6.5b）/ 表格是否串行

# 5. 动画页（带 canvas）必须单独截图 + 看 stderr 有无 JS 报错
"/c/Program Files/Google/Chrome/Application/chrome.exe" --headless=new --no-sandbox \
  --disable-gpu --window-size=1280,2400 --virtual-time-budget=8000 \
  --enable-logging=stderr --screenshot="/tmp/anim.png" "file:///.../动画-XXX.html" 2>&1 \
  | grep -iE "error|exception|uncaught"      # 期望：无输出
```

---

### 6.10 批量重编号 / 改 nav：写一次性 node 脚本，**不要**手改 20 个文件

> 2026-10-08 经验：第 06 讲插入 4 个新页后要把原 09~12 顺延为 13~16，涉及<strong>20 个页面</strong>的 nav 块、pager、`<title>`、面包屑、正文里 40 多处"第 NN 节"交叉引用。手改必然漏。

**统一用脚本做三件事**：

1. **文件重命名**：`git mv "09-xxx.html" "13-xxx.html"`（逆序重命名避免撞名）。
2. **链接与节号批量替换**：先把旧 href 全部映射到新名（`./09-xxx.html` → `./13-xxx.html`），再改正文节号。
   ⚠️ **陷阱**：节号引用里 **`第 10 讲`（全局讲次）与 `第 10 节`（本讲小节）是两回事**，正则<strong>必须带上"节"字</strong>：`/第\s*10\s*节/g`。同理 `第 09 / 10 节` 这种"节号区间"要<strong>先处理区间、再处理单值</strong>，否则 `第 09 ~ 12 节` 会被拆坏。
3. **重建 nav 块**：正则匹配 `<nav class="lecture-nav">[\s\S]*?</nav>` 整块替换，比逐行替换安全得多；<strong>替换前先解析出 `class="current"` 挂在哪个 href 上</strong>（重命名后要把 current 映射到新文件名，否则当前页高亮会丢）。

**PowerShell 里的坑**：
- 正则里的 `\d`、`$`、反引号会被 PowerShell 二次解析。**直接把脚本写成 `.js` 文件用 `node xxx.js` 跑**，不要 `node -e "..."` 内联。
- `[ordered]@{...}` 哈希表<strong>不允许重复键</strong>，同一文件要改多处时用<strong>数组的数组</strong>而不是哈希表。
- `.NET` 的 `[IO.File]::ReadAllText` <strong>不吃相对路径</strong>，必须先 `Join-Path (Get-Location).Path`。

### 6.11 表格首列被挤成竖排：给 `th:first-child` 加 `min-width`

> 2026-10-08 bug：第 06 讲 11 页的"严平稳 vs 宽平稳"对比表，第一列只有"特性/要求/强度/关系/例子"四个字，被浏览器压成<strong>每行一个字的竖排</strong>，极难阅读。

```css
table th:first-child{min-width:5.5em}   /* 加在 th{background:var(--c-card)} 之后 */
```

- 同一讲次的所有页面共享 `<style>` 块，用 node 脚本批量插入即可。
- 用 `min-width` <strong>而不是</strong> `white-space:nowrap`：后者遇到"$(X_0)\backslash X_{\pi/4}$"这种超长表头会把表格撑破，移动端尤其明显。
- 凡是首列是**短中文标签**的表（对比表、清单表）都要加；首列是长公式的表加了也无害。

### 6.12 Windows 下没有 Python：Pillow 裁图改用 System.Drawing

> CLAUDE.md §6.7 说过 `python3` 是 Microsoft Store 占位符。**连 `python` 也没有**（"Python was not found"）。

**截图后放大目视某一段区域**（§6.9 第 4b 步）改用 PowerShell 内置的 `System.Drawing`：

```powershell
Add-Type -AssemblyName System.Drawing
$img=[System.Drawing.Image]::FromFile("$out\p.png"); $y1=5250; $h=900
$bmp=New-Object System.Drawing.Bitmap(1100,$h); $g=[System.Drawing.Graphics]::FromImage($bmp)
$g.DrawImage($img,(New-Object System.Drawing.Rectangle(0,0,1100,$h)),(New-Object System.Drawing.Rectangle(100,$y1,1100,$h)),[System.Drawing.GraphicsUnit]::Pixel)
$bmp.Save("$out\crop.png",[System.Drawing.Imaging.ImageFormat]::Png); $g.Dispose();$bmp.Dispose();$img.Dispose()
```

页面很长时 `chrome --headless --window-size=1280,6200` <strong>可以一次截全</strong>（实测 6200px 没问题），比反复截更省事。

### 6.13 带内联 JS 的页面：预算是"验证脚本本身"，不是"截图"

> 2026-10-08 经验：给第 06 讲做交互动画页时，截图**看不出** JS 逻辑对不对，且踩了三个只有真跑才会暴露的 bug。

**三个 bug 与对应教训**：

1. **四位小数陷阱**：`setv()` 写入时做了 `Math.round(v*100)/100`，于是 $1/9$ 变成 $0.11$，九个格子加起来 $=0.99\ne1$，**"合法"预设被误判成矛盾**。→<strong>概率数值一律写原值，不做展示用的四舍五入</strong>；要好看就把 `<input step>` 调小，而不是截断数值。
2. **`let` 的 TDZ**：`goTab()` 定义在脚本最前，但它内部用到后面才 `let` 声明的 `curProc`；把 `if(location.hash==='#B') goTab('B')` 写在 `goTab` 旁边 → 页面加载即抛 `Cannot access 'curProc' before initialization`，<strong>整个面板空白，而截图只是"看起来没内容"</strong>。→<strong>任何"自动触发"（hash、自动播放、初始化）必须放在脚本最末尾</strong>，并用 IIFE 圈起来。
3. **坐标映射算错**：`py=v=>Y0-(Y1-Y0)*v` 展开是 $140+80v$（向下递增），与"值大画得高"相反。→<strong>SVG 映射函数写完先代两个端点验一次</strong>（$v=0$ 落在轴上、$v=1$ 落在顶部）。

**验证姿势（Chrome headless 抓真异常）**：

```powershell
& $chrome --headless=new --no-sandbox --disable-gpu --window-size=1280,2000 `
  --virtual-time-budget=7000 --enable-logging=stderr --screenshot="$out\x.png" "$url#B" 2>&1 |
  Select-String -Pattern 'Uncaught|ReferenceError|TypeError|SyntaxError'
# 期望：无输出；有输出会形如 INFO:CONSOLE:375] "Uncaught ReferenceError: ..."，直接给出出错行号
```

<strong>注意</strong>：Chrome 自己也会刷屏 `mojo ... Message rejected`、`externally_managed_app_manager` 之类基础设施日志，<strong>只 grep `Uncaught|ReferenceError|TypeError|SyntaxError` 这几类</strong>，不要看到 ERROR 就以为页面坏了。

**再加一层"无头算法验证"**：把页面 `<script>` 里最后一段取出来，在 Node 里配一个极简 DOM shim（`getElementById` 返回带 `value/textContent/innerHTML/className` 的对象）直接 `eval`，然后调用预设函数断言输出。这样<strong>不依赖浏览器就能把"判定逻辑对不对"钉死</strong>：

```js
const scripts=[...html.matchAll(/<script(?![^>]*src=)[^>]*>([\s\S]*?)<\/script>/g)];
eval(scripts[scripts.length-1][1]);        // 最后一段 = 页面主脚本
preset('bad1');
console.log(store['verdict'].innerHTML);    // 应当以 ❌ 开头
```

这个 shim 的好处：<strong>它对不存在的 id 也返回对象，所以能测出"拼错的 id"（浏览器里会抛 null 异常）</strong>——与 §6.9 静态扫描 `getElementById` 引用是互补的。

---

### 7.1 事件 1 · 你添加新课件

把你新加的 PDF / PPTX / ZIP 按命名约定放在：
- 《随机过程》 → `随机过程/`
- 《随机过程与排队论》 → `随机过程与排队论/`

agent 不需要立即做什么——新课件等着下一讲制作时被引用即可。

### 7.2 事件 2 · 让 agent 生成下一讲 HTML

#### 触发方式（任选其一）

| 方式 | 说明 |
|---|---|
| **`/下一讲`** | 推荐。Claude Code 原生斜杠命令，等价于下面这条 prompt |
| **`/next-lecture`** | 英文别名，同 `/下一讲` |
| **"生成下一章"** / "做第 0X 讲" | 自然语言触发，agent 应识别并走相同流程 |

两个斜杠命令的源文件：
- `.claude/commands/下一讲.md`（中文版，权威）
- `.claude/commands/next-lecture.md`（英文版，引用中文版）

#### agent 必须执行

1. 先读 `CLAUDE.md`（即本文件）；
2. 参考 `01-概率空间/` 作为风格样板（CSS、调色板、callout 写法）；
3. **先列出本讲要覆盖的所有知识点**（不能漏）→ 向用户确认 → 再开始写文件；
4. 按 §5.3 的七段式产出每个概念页；
5. 自检 §6.9 的最小检查流程（含 grep + 表格列数自检 + Chrome headless 截图）；
6. 完成后同步更新根目录 `index.html` 与 `CLAUDE.md` §3.1 / §3 顶部状态。

### 7.3 事件 3 · 你给新建议，agent 改文档

直接说"改 CLAUDE.md：……"。agent 应：
- **只改文档**（CLAUDE.md / 共享资源），不擅自改已完成页面，除非你也明确要求改页面。
- 在 §3、§4、§5、§6 中找到合适小节插入或更新内容。
- 如果是新的技术经验，优先放在 §6。

---

## 8. 详细参考

如需了解更多：
- 风格样板：见 `01-概率空间/` 中任一已完成的 `.html` 文件
- 课程地图：根目录 `index.html`
- 排版/调色细节：§5.2 + §6.4

---

## 9. 待办（未来 agent 接手时可以考虑）

- [ ] 建立 `shared/` 子目录，抽取通用 CSS / PRNG / 绘图工具
- [ ] 升级根目录 `index.html` 为完整课程地图（点击跳转已完成讲次）
- [ ] 为每一讲加一份"讲次大纲速查.md"（一句话知识点清单 + 跳转链接）
- [ ] 引入 KaTeX 渲染失败检测：在每个页面末尾加 JS 检查 `document.querySelectorAll('.katex').length`，若为 0 则提示刷新或检查 CDN
- [ ] 接入 CSP / SRI 保证 CDN 安全（可选）
- [ ] 给动画页加"导出数据"按钮（用户能拿到 CSV/JSON 做后续分析）

---

**最后更新**：2026-10-08 · 第 01 ~ 06 讲均已完成（共 84 个页面） · **第 06 讲依据彭江燕第 7 / 8 次课扩充至 20 页**：新增 `09-二阶矩过程与协方差非负定性` / `10-宽平稳过程` / `11-严平稳过程` / `12-正交增量与白噪声` 四页（原 09~12 顺延重编号为 13~16），并在 04 / 06 / 07 / 08 页补入课件原例（随机开关系统全套数字特征、九宫格二维分布函数、含噪系统正交分解、半二元传输信号）· 自测扩至 15 题 · 新增 2 处课件勘误（随机正弦波 $D(t)=\frac12$ 而非 $1$；随机开关系统 $C(s,t)$ 化简漏系数）· 王庆先第 6 讲 PPTX（马尔可夫链）已入库，归属第 08 / 09 讲 · 自检通过：20 个页面 0 处 `<code>` 公式陷阱、全部 `viewBox` 均为 4 值、SVG 内无 HTML 子元素与 `$` 公式、全部表格列数一致、全部内部链接无死链。