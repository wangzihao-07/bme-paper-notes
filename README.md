# 生物医学工程（BME）论文精读笔记

> 个人整理的 BME 论文精读笔记库。目标读者是**基础较弱的学习者**（大一新生，具备基础微积分与线性代数），采用**刨根问底**的方式讲解：不满足于"是什么"，一路追问到"为什么"。

- **对象与深度**：为大一新生写。每个公式只说明"表达什么关系"，**不推导**；所有符号、单位、数量级都解释到位。
- **结构**：一句话看懂 → 背景动机 → 核心概念 → 逐节精读 → 数学建模 → 风险 / 局限 / 未来方向 → 对比 → Q&A → 自测清单 → 词汇表。

## 目录结构

```
bme-paper-notes/
├── README.md                 ← 你正在看这个
└── papers/                   ← 每篇论文一个子目录
    └── <论文slug>/
        ├── <论文slug>.md     ← 精读笔记
        └── images/           ← 插图
            └── paper-figures/  ← （可选）论文原图等非原创图片，附 NOTICE 说明出处
```

> 说明：**自绘示意图**直接放在 `images/`；**论文原图等非原创图片**统一放在 `images/paper-figures/`，并在该目录的 `NOTICE.md` 中列明出处与版权归属，以区分原创与非原创内容。

## 已收录

| 论文 | 方向 | 笔记 |
| --- | --- | --- |
| Photoacoustic Triaxial Force Sensing via Integrated Polymer Waveguides for Ultra-Compact Robotic Surgical Instruments（IEEE/ASME TMech 2025, DOI 10.1109/TMECH.2025.3628300） | 光声三轴力传感 / 微创手术器械 | [查看](papers/photoacoustic-triaxial-force-sensing/photoacoustic-triaxial-force-sensing.md) |
| Iontronic tip-sensing guidewires（Nature Biomedical Engineering 2025, DOI 10.1038/s41551-025-01548-9） | 离子电子压力传感 / FFR 导丝 | [查看](papers/iontronic-tip-sensing-guidewires/iontronic-tip-sensing-guidewires.md) |

## 声明

- 笔记中的**论文事实**（作者、DOI、数据、结论）均摘自论文原文。
- **个人分析 / 补充**部分（风险、局限性、推导动机等）版权归整理者，转载请注明来源。
- 论文版权归原作者及其出版机构所有，本仓库仅作学习交流。
- 各篇笔记 `images/paper-figures/` 目录下的**论文原图**版权归原作者及出版机构所有，仅作学习评述之用，详见各目录内的 `NOTICE.md`；如需他用请自行取得授权。

> 说明：本仓库由 **Claude Code**协助整理。
