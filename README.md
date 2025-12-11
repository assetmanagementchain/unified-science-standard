# unified-science-standard

unified-science-standard/
│
├── 0_foundations/                     ← 所有学科共享的基础结构
│   ├── mathematics/
│   │   ├── static_math_principles.md
│   │   ├── dynamic_math_principles.md
│   │   └── structural_axioms.md
│   ├── rule_dynamic_geometry_framework.md
│   ├── glossary.md
│   └── notation_conventions.md
│
├── 1_static_math/                     ← 仅需静态数学即可完全数学化的学科
│   ├── algebra/
│   │   ├── Algebra_Standard_v1.0.md
│   │   ├── field_theory.md
│   │   └── group_structure_axioms.md
│   ├── geometry/
│   ├── topology/
│   ├── classical_analysis/
│   ├── logic_and_set_theory/
│   └── static_models/                 ← 静态物理/工程模型
│       ├── classical_mechanics.md
│       ├── electromagnetism.md
│       ├── static_structures.md
│       └── linear_systems.md
│
├── 2_dynamic_math/                    ← 必须使用动态数学才能数学化的学科（重点区）
│   │
│   ├── dynamics/                      ← 已完成：动力系统 DGSM
│   │   ├── DGSM/
│   │   │   └── DGSM_v1.0.md
│   │   └── DGSM_appendices/
│   │
│   ├── complex_networks/              ← 已完成：复杂网络科学 CNSM
│   │   ├── CNSM_v1.0.md
│   │   └── DEST_foundations.md
│   │
│   ├── computation_theory/            ← 即将完成：程序理论 CTS
│   │   ├── CTS_v1.0.md
│   │   ├── CTS_FormalAxioms.md
│   │   └── CTS_ImplementationGuide.md
│   │
│   ├── information_theory/            ← 动态信息论（SIT）：下一优先级
│   │   ├── SIT_Standard_v1.0.md
│   │   ├── structural_entropy.md
│   │   └── info_dynamics_axioms.md
│   │
│   ├── chemical_reaction_networks/    ← CRN-MSM：准备度 60%（可排下一个）
│   │   ├── CRN_Standard_v1.0.md
│   │   └── reaction_geometry.md
│   │
│   ├── system_science/                ← 生态/经济/控制理论等
│   │   ├── DynamicSystems_Applications.md
│   │   └── Stability_Control_Framework.md
│   │
│   └── machine_learning_theory/       ← 动态版 ML 的未来标准（能量/吸引盆视角）
│       ├── ML_DynamicGeometry.md
│       └── LearningAsStability.md
│
├── 3_not_ready/                       ← **暂不纳入标准化（演化数学领域）**
│   ├── evolutionary_math/             ← 暂缓（未来数年最重点突破）
│   ├── biological_dynamics/           ← 生物进化/发育/基因网络
│   ├── cognition_and_intelligence/
│   └── socio_cultural_evolution/
│
├── models/                            ← 通用模型库（对应 Static/Dynamic）
│   ├── dgsm/
│   ├── computation/
│   ├── complexnet/
│   ├── crn/
│   └── sit/
│
├── formalization/                     ← Lean + mathOS 文件
│   ├── lean/
│   └── mathos/
│
├── tools/
│   ├── simulators/
│   ├── analyzers/
│   └── visualizers/
│
└── README.md

