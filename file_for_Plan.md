[原始官方数据表]
├── Table 310-31001 (excl symbols)_en.xlsx  ──> 提取名义与实质 GDP (1961-2025)
├── Table 310-31002 (excl symbols)_en.xlsx  ──> 提取支出法分项 (2022-2023)
└── Table 310-34101 (excl symbols)_en.xlsx  ──> 提取五大部门增加值占比 (2021-2024)
                           │
                           ▼
[Python 自动化管线: generate_pset1_assets.py]
├── 1. 数值清洗与对齐 (剔除修订标记/转格式)
├── 2. 计算实证指标: 历年实质增长率、平减指数、两套通胀率时序、开放度
└── 3. 渲染输出论文级矢量图表:
       ├── fig1_nominal_real_gdp.pdf / .png     (用于 Q1)
       └── fig2_inflation_comparison.pdf / .png (用于 Q3)
                           │
                           ▼
[LaTeX 报告渲染: ECON2123_PSet1_Norman.tex]
├── Preamble & 学术元信息 (Norman Lin, Student ID: 20861656)
├── Section 1: Real GDP and the GDP Deflator (Q1-Q3, 20 pts)
├── Section 2: The Composition of HK GDP, 2023 (Q4-Q7, 25 pts)
├── Section 3: The Employment Rate (Q8, 10 pts)
└── Section 4: Goods Market Equilibrium & Multipliers (Q9-Q17, 55 pts)
                           │
                           ▼
[最终交付物: Canvas 提交用 PDF 报告 (110/110 Check-Plus)]