# Frontier AI Technical Handbook (2025-2026)

The math, architectures, and open problems behind frontier AI.

A technical reference covering what's actually inside the systems being built today.

**[Download the PDF](frontier-ai-handbook-2025-2026.pdf)** | **[Author](https://qig.github.io)**

---

## What's Inside

| Module | Topic | Key Concepts |
|--------|-------|-------------|
| 1 | **Generative Engine** | ELBO, Diffusion (DDPM/DDIM), Score Matching, EDM, Flow Matching, DiT, Tokenization (VQ-VAE/FSQ), Samplers, CFG, Million-Token Context |
| 2 | **Physical World** | World Models (Genie 1/2/3, V-JEPA, Cosmos), Sim-to-Real, Domain Randomization, Differentiable Physics, Contact, PINNs, FNO, 3DGS |
| 3 | **Systems Engineering** | DDP/FSDP/DeepSpeed, FlashAttention, Fault Tolerance, FP8, Distillation, LoRA/QLoRA, Speculative Decoding, Continuous Batching |
| 4 | **Mixture of Experts** | Routing, Load Balancing, DeepSeek-V3 (MLA, Auxiliary-Loss-Free), Expert Parallelism, 5D Parallelism |
| 5 | **Native Multimodal** | Early vs Late Fusion, Chameleon, Transfusion, CLIP/SigLIP, Audio Tokenization (RVQ), Any-to-Any Generation |
| 6 | **Reasoning & Beyond** | RLHF/DPO, Test-Time Compute, GRPO/RLVR, DeepSeek-R1, Reasoning Distillation, TTT Layers, Mamba/SSMs, Hybrid Architectures |

Includes 34 "Think Deeper" questions, a build roadmap, and 80+ references.

## Prerequisites

Assumes familiarity with linear algebra, probability, calculus, and basic deep learning (transformers, backpropagation, attention). It's a reference for practitioners working at the frontier.

## Suggested Reading Paths

- **Generative AI:** Modules 1 (Sections 1.0–1.5)
- **World Simulation:** Module 2
- **Systems Engineering:** Module 3
- **Architecture:** Modules 4 → 5
- **Reasoning:** Module 6

## Author

[Qi Guo](https://qig.github.io) and Claude.

Contributions and corrections welcome.
