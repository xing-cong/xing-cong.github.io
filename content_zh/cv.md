## 教育背景

**北京航空航天大学**，计算机科学与技术博士（硕博连读），*2024.06 - 至今*  
- 实验室：中德软件联合研究所
- GPA：3.82/4.0，排名 4/146
- 研究方向：高性能计算、GPU 计算优化、AI Infra、Transformer 推理加速
- 荣誉与职务：优秀研究生、校级三好学生、一等奖学金、九号奖学金、TACO 审稿人、党支部书记

**北京航空航天大学**，计算机科学与技术硕士，*2023.09 - 2024.06*

**东北大学**，计算机科学与技术本科，*2019.09 - 2023.06*

## 学术成果

**RT-Lynx: Putting the GEMM Sparsity In a Right Way for Diffusion Models**  
第一作者，ICML 2026 (CCF-A)，[Paper](https://arxiv.org/abs/2605.26632)
- 主导设计面向 DiT 的半结构化激活稀疏框架 RT-Lynx，首次系统验证激活侧相比权重侧更适合 2:4 N:M 稀疏；提出范数补偿、轻量级 LoRA 误差恢复等策略，在保持生成质量的同时释放 Sparse Tensor Core 加速潜力。
- 开发在线融合稀疏推理流水线，将激活筛选、格式压缩与 GEMM 融合到 CUDA 执行路径中；在 Qwen-Image 等模型上实现最高 1.88x Sparse GEMM 加速、1.55x 线性层平均加速和约 1.2x 端到端加速。

**CB-SpMV: A Data Aggregating and Balance Algorithm for Cache-Friendly Block-Based SpMV on GPUs**  
第一作者，ICS 2025 (CCF-B)，[Paper](https://arxiv.org/abs/2605.18515)
- 针对 GPU SpMV 中访存跳跃、线程空转与负载不均问题，提出缓存友好的块稀疏框架 CB-SpMV；通过块内数据聚合、虚拟指针、列聚合与自适应子块格式选择统一优化数据局部性和硬件利用率。
- 在数千个矩阵上完成大规模评测，在 NVIDIA A100 与 RTX 4090 上优于 cuSPARSE、TileSpMV 和 DASP；相较 TileSpMV 最高取得 3.95x 平均加速，并提升 L1/L2 Cache 命中率 82%/19%。

**TC-SpGEMM: High Performance Sparse General Matrix Multiplication with Tensor Core-Accelerated**  
第二作者，IPDPS 2026 (CCF-B)，已中。

## 实习经历

**阿里控股集团**，技术平台，AI 研究型实习生，*2025.09 - 至今*
- 面向 DiT 图像生成模型推理场景，利用 Nsight Systems 和 Diffusion-Studio 实现 Qwen-Image 等模型的性能 profiling、稀疏鲁棒性分析与图像质量评估工具，形成可复用的稀疏效果评测实验流程。
- 基于 Diffusion-Studio 框架和 CUTLASS 工具构建在线稀疏推理加速系统，实现核心稀疏算子与端到端评测链路，支撑激活稀疏、量化、缓存、蒸馏和稀疏注意力等组合加速实验。

**华为技术有限公司**，计算与网络创新 Lab，AI 研发实习生，*2025.04 - 2025.08*
- 深入 NPU 体系结构机制，对 ALLtoALL 算子构建计算、访存与通信仿真模型，并完成 Cache 建模。
- 面向 FA/FD 算子，基于 Triton 完成 GPU 实现向 NPU 平台的迁移与适配，打通执行流程。

**抖音视界有限公司**，AML，研发实习生，*2024.06 - 2024.09*
- 面向分子动力学模型预测场景，基于 Nsight Compute 定位 LAMMPS 中 Kokkos 并行执行瓶颈，并设计特化 GPU 计算内核，提升整体模拟性能。

**百度在线网络技术（北京）有限公司**，ACG 公有云，云原生研发实习生，*2024.03 - 2024.06*
- 围绕云原生平台对超算集群的管理需求，抽象 PBS 等调度器的作业提交等功能，提供 Python 调用接口。

## 项目经历

**国产 DCU 千万核级并行算法以及深度优化技术**，十四五科技部重点研发项目，子课题负责人，*2023.10 - 至今*
- 设计面向国产 DCU 异构计算的高效矩阵存储结构，提升节点内计算效率；实现任务自适应分配与节点间负载均衡，支撑分布式计算加速。
- 相关成果发表论文一篇、授权专利一项。

## 荣誉与服务

- 优秀研究生、校级三好学生、一等奖学金、九号奖学金。
- TACO 审稿人。
- 党支部书记。
