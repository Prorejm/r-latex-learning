# R语言与LaTeX交互式学习站

一个集成了 **浏览器内运行R代码**、**实时LaTeX公式预览** 和 **论文写作方法指南** 的交互式学习网站。

## 在线访问

**GitHub Pages**: [https://prorejm.github.io/r-latex-learning](https://prorejm.github.io/r-latex-learning)

## 网站功能

### R 语言交互学习
- **浏览器内运行R代码**：基于 [webR](https://docs.r-wasm.org/webr/latest/) (R WebAssembly)，无需安装R环境
- 基础语法（变量、向量、基础运算）
- 数据操作（筛选、汇总、分组）
- 统计建模（线性回归、t检验、方差分析）
- 数据可视化（基础R绘图）

### LaTeX 交互式排版
- **实时公式渲染**：基于 [KaTeX](https://katex.org/)，即时预览数学公式
- 行内与独立公式
- 矩阵与多行对齐公式
- 统计与概率公式
- 学术论文模板速查

### 综合实例
- R 生成 LaTeX 表格代码
- 统计检验报告（含LaTeX格式输出）
- 描述性统计表
- R Markdown 输出思想

### 论文写作方法与规范
- **IMRaD 论文结构**：引言、方法、结果、讨论的标准框架
- **引言写作技巧**：漏斗式结构与常见错误
- **方法部分写作**：可重复性原则
- **结果与讨论**：分工明确的原则
- **文献引用与管理**：Zotero、Mendeley、EndNote、JabRef 工具推荐
- **图表制作规范**：分辨率、配色、三线表等
- **写作工具链**：Overleaf、Grammarly、Connected Papers 等
- **论文检查清单**：投稿前逐项核对（含可交互复选框）

## 技术栈

| 技术 | 用途 |
|------|------|
| [webR](https://docs.r-wasm.org/webr/latest/) | 浏览器内运行R代码 |
| [KaTeX](https://katex.org/) | LaTeX数学公式渲染 |
| 纯 HTML/CSS/JS | 前端展示，无需构建工具 |
| GitHub Pages | 静态网站托管 |

## 本地使用

由于网站使用纯静态文件，可以直接在本地浏览器中打开 `index.html` 文件使用。

```bash
git clone https://github.com/Prorejm/r-latex-learning.git
cd r-latex-learning
# 直接用浏览器打开 index.html
```

## 项目结构

```
r-latex-learning/
├── index.html      # 主页面（包含所有内容和交互逻辑）
└── README.md       # 项目说明
```

## 更新日志

- **2025-06-26**: 初始版本上线，包含R语言交互学习、LaTeX实时预览和论文写作方法板块

## License

MIT
