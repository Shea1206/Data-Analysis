# 孙诗晴 · 数据分析与量化研究作品集

> Shea · Data / Product / Finance
> 围绕期货套利与多因子研究、大宗供应链 AI 转型的数据作品集合。

## 作品集主页
完整的交互式作品集（暗色 · 雨帘动效 · 逐章翻页）：[index.html](./index.html)
- 在线预览：https://cdn.jsdelivr.net/gh/Shea1206/Data-Analysis@main/index.html
- GitHub Pages（启用后）：https://shea1206.github.io/data-analysis/

---

## 项目

### 一、白银期货研究台 Suite
围绕沪银的套利测算、多因子可视化与一站式研究工作台，三件工具自成体系：

- **套利分析计算器** — TD-期货 / 期现 / 跨期 / 交割 / 递延费多策略实时测算价差、持仓成本与年化
- **多维数据看板** — 跨市场价差、金银比、库存与持仓、宏观与资金情绪等多因子联动（暗色主题）
- **期货研究台** — 行情、因子、回测与笔记的一站式研究终端

| 工具 | 在线预览 | 源码 |
|------|----------|------|
| 项目介绍页 | [预览](https://cdn.jsdelivr.net/gh/Shea1206/Data-Analysis@main/期货研究/index.html) | [期货研究/index.html](./期货研究/index.html) |
| 套利分析计算器 | [预览](https://cdn.jsdelivr.net/gh/Shea1206/Data-Analysis@main/期货研究/白银套利分析计算器.html) | [白银套利分析计算器.html](./期货研究/白银套利分析计算器.html) |
| 多维数据看板 | [预览](https://cdn.jsdelivr.net/gh/Shea1206/Data-Analysis@main/期货研究/dashboard.html) | [dashboard.html](./期货研究/dashboard.html) |
| 期货研究台 | [预览](https://cdn.jsdelivr.net/gh/Shea1206/Data-Analysis@main/期货研究/output.html) | [output.html](./期货研究/output.html) |

目录：[`期货研究/`](./期货研究)

### 二、大宗供应链企业 AI 转型试点研究
对标建发股份、物产中大、厦门象屿、厦门国贸、浙商中拓五家龙头企业的 AI 转型方案，含三维加权评分模型与 ROI 三情景测算。

- 在线查看 PDF：[大宗供应链AI转型试点研究方案.pdf](https://github.com/Shea1206/Data-Analysis/raw/main/行研案例/大宗供应链AI转型试点研究方案.pdf)
- 目录：[`行研案例/`](./行研案例)

---

## 关于链接
- 上表「在线预览」走 **jsDelivr CDN**，无需部署即可直接在浏览器渲染查看（HTML 工具）。
- PDF 走 GitHub **raw**，点击在浏览器在线打开（文件较大，加载稍慢）。
- 若希望使用自有地址：开启 **GitHub Pages**（Settings → Pages → Source: `main` / root），即可通过
  `https://shea1206.github.io/data-analysis/` 访问，例如
  `https://shea1206.github.io/data-analysis/期货研究/dashboard.html`。

## 目录结构
```
.
├── index.html                      # 作品集主页（暗色 · 雨帘 · 翻页）
├── README.md
├── 期货研究/
│   ├── index.html                  # 项目介绍页（三件工具总览）
│   ├── 白银套利分析计算器.html        # 计算器
│   ├── dashboard.html              # 多维数据看板
│   └── output.html                 # 期货研究台
└── 行研案例/
    └── 大宗供应链AI转型试点研究方案.pdf
```

---
© 孙诗晴 (Shea) · 2026
