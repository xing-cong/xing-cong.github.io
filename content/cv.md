## Education

**Beihang University**, Ph.D. in Computer Science and Technology, *2024.06 - Present*  
Direct master-doctor track.
- Lab: Sino-German Joint Software Institute
- GPA: 3.82/4.0, ranked 4/146
- Research: high-performance computing, GPU optimization, AI infrastructure, Transformer inference acceleration
- Honors and roles: Outstanding Graduate Student, University Merit Student, First-Class Scholarship, No.9 Scholarship, TACO reviewer, Party Branch Secretary

**Beihang University**, M.S. in Computer Science and Technology, *2023.09 - 2024.06*

**Northeastern University**, B.S. in Computer Science and Technology, *2019.09 - 2023.06*

## Publications

**DB-SpMSpV: Dual-View Blocked Sparse Matrix-Sparse Vector Multiplication for Dynamic GPU Workloads**  
First author, ICPP 2026 (CCF-B), accepted in July 2026.
- Proposed a dual-view blocked SpMSpV framework that reuses a single low-level block payload for adaptive row-driven pull and column-driven push, with runtime selection of global traversal paths and local block microkernels.
- Achieved average speedups of 5.48x-64.34x over cuSPARSE and 2.36x-14.01x over TileSpMSpV on NVIDIA A100; DB-BFS achieved average speedups of 2.66x on A100 and 3.60x on RTX 4090 over TileBFS, while DB-Decoding accelerated single-token linear layers by up to 4.50x.

**RT-Lynx: Putting the GEMM Sparsity In a Right Way for Diffusion Models**  
First author, ICML 2026 (CCF-A), [Paper](https://arxiv.org/abs/2605.26632)
- Designed a semi-structured activation sparsity framework for DiT models, with norm compensation, lightweight LoRA error recovery, and online fused sparse inference.
- Achieved up to 1.88x Sparse GEMM speedup, 1.55x average linear-layer speedup, and about 1.2x end-to-end speedup on models such as Qwen-Image.

**CB-SpMV: A Data Aggregating and Balance Algorithm for Cache-Friendly Block-Based SpMV on GPUs**  
First author, ICS 2025 (CCF-B), [Paper](https://arxiv.org/abs/2605.18515)
- Proposed a cache-friendly block sparse framework for GPU SpMV to address irregular memory access, thread idling, and load imbalance.
- Evaluated on thousands of matrices on NVIDIA A100 and RTX 4090, outperforming cuSPARSE, TileSpMV, and DASP; achieved up to 3.95x average speedup over TileSpMV and improved L1/L2 cache hit rates by 82%/19%.

**TC-SpGEMM: High Performance Sparse General Matrix Multiplication with Tensor Core-Accelerated**  
Second author, IPDPS 2026 (CCF-B), accepted.

## Internships

**Alibaba Holding Group**, Technical Platform, AI Research Intern, *2025.09 - Present*
- Built profiling, sparse robustness analysis, and image-quality evaluation tools for DiT image-generation models such as Qwen-Image using Nsight Systems and Diffusion-Studio.
- Built an online sparse inference acceleration system based on Diffusion-Studio and CUTLASS, supporting sparse operators and end-to-end experiments on activation sparsity, quantization, caching, distillation, and sparse attention.

**Huawei Technologies**, Computing and Network Innovation Lab, AI R&D Intern, *2025.04 - 2025.08*
- Studied NPU architecture mechanisms and built compute, memory, communication, and cache simulation models for the ALLtoALL operator.
- Ported and adapted FA/FD operators from GPU implementations to NPU platforms based on Triton.

**Douyin Vision Co., Ltd.**, AML, R&D Intern, *2024.06 - 2024.09*
- Used Nsight Compute to locate Kokkos parallel execution bottlenecks in LAMMPS for molecular dynamics model prediction, and designed specialized GPU kernels to improve simulation performance.

**Baidu Online Network Technology (Beijing) Co., Ltd.**, ACG Public Cloud, Cloud Native R&D Intern, *2024.03 - 2024.06*
- Built cluster-management tooling for cloud-native supercomputing platforms by abstracting scheduler features such as PBS job submission into Python interfaces.

## Projects

**Domestic DCU Ten-Million-Core Parallel Algorithms and Deep Optimization Technology**, National Key R&D Program subproject lead, *2023.10 - Present*
- Designed efficient matrix storage structures for domestic DCU heterogeneous computing, improved intra-node computation efficiency, and implemented adaptive task distribution and inter-node load balancing for distributed acceleration.
- Related outputs include one published paper and one authorized patent.

## Honors and Service

- Outstanding Graduate Student, University Merit Student, First-Class Scholarship, No.9 Scholarship.
- Reviewer for ACM Transactions on Architecture and Code Optimization (TACO).
- Party Branch Secretary.
