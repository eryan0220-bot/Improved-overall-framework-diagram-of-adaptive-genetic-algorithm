# Improved-overall-framework-diagram-of-adaptive-genetic-algorithm
```mermaid
flowchart TD
    A[算法开始] --> B[参数初始化]
    B --> C[种群初始化]
    C --> D[适应度计算]
    D --> E[精英保留策略]
    E --> F[种群状态评估]
    F --> G[自适应交叉/变异概率计算]
    G --> H[选择操作]
    H --> I[自适应交叉操作]
    I --> J[自适应变异操作]
    J --> K[种群更新]
    K --> L{终止条件是否满足？}
    L -->|否| D
    L -->|是| M[输出全局最优解]
    M --> N[算法结束]
