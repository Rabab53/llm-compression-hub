# llm-compression-hub
# 🚀 Compression Methods for LLMs & VLMs  
*A curated research repository on ultra-efficient AI training and inference*

---

## 📌 Overview
This repository curates **state-of-the-art research, methods, and benchmarks** on **different compression methods for Large Language Models (LLMs) and Vision-Language Models (VLMs)**.

The goal is to:
- Reduce **memory footprint (KV cache, weights, activations)**
- Enable **long-context inference**
- Improve **throughput on modern accelerators (GPUs, AI chips)**
- Maintain **accuracy under extreme compression (≤4-bit, 1-bit)**

---

## 🔥 Featured Papers

### ⚡ KV (Key-Value) Cache Quantization

- **TurboQuant: Finally, Fast and Widely Available Low-Bit KV Cache Quantization?**  
  - Blog: https://kaitchup.substack.com/p/turboquant-finally-fast-and-widely  
  - Google Blog: https://research.google/blog/turboquant-redefining-ai-efficiency-with-extreme-compression/  
  - Paper: https://arxiv.org/pdf/2504.19874  
  - Code: https://github.com/0xSero/turboquant  
  - News: https://arstechnica.com/ai/2026/03/google-says-new-turboquant-compression-can-lower-ai-memory-usage-without-sacrificing-quality/  

- **QJL: 1-Bit Quantized JL Transform for KV Cache Quantization with Zero Overhead**  
  https://arxiv.org/abs/2406.03482  

- **PolarQuant: Quantizing KV Caches with Polar Transformation**  
  https://arxiv.org/pdf/2502.02617

- **KIVI: A Tuning-Free Asymmetric 2bit Quantization for KV Cache**
  https://arxiv.org/pdf/2402.02750

---

### 🎯 Advanced Quantization Techniques

- **Channel-Aware Mixed-Precision Quantization for Long-Context Inference**  
  https://openreview.net/pdf?id=yjr2jX41qO  

- **littleBit: Ultra Low-Bit Quantization via Latent Factorization**  
  https://openreview.net/pdf?id=zJzu9evD5K  

- **ParetoQ: Improving Scaling Laws in Extremely Low-bit LLM Quantization**  
  https://arxiv.org/pdf/2502.02631  

- **Cherry on Top: Parameter Heterogeneity and Quantization in LLMs**  
  https://proceedings.neurips.cc/paper_files/paper/2024/file/6fcc2190f456464160921e98393bf50e-Paper-Conference.pdf

- **The Era of 1-bit LLMs: All Large Language Models are in 1.58 Bits**
  https://arxiv.org/pdf/2402.17764

---

### 🤖 Multimodal & VLM Quantization

- **Q-VLM: Post-training Quantization for Large Vision-Language Models**  
  - Paper: https://proceedings.neurips.cc/paper_files/paper/2024/file/cffbaf4f47546ece96bb42c0edda40ee-Paper-Conference.pdf  
  - Code: https://github.com/changyuanwang17/qvlm  

- **LUQ: Layerwise Ultra-Low Bit Quantization for Multimodal LLMs**  
  https://arxiv.org/html/2509.23729v2  

---

### 🧮 Foundational PTQ Methods

- **GPTQ: Accurate Post-Training Quantization for Generative Pre-trained Transformers**  
  https://arxiv.org/pdf/2210.17323  

---

### ⚙️ Systems & Deployment

- **Efficient Multi-task LLM Quantization and Serving for Multiple LoRA Adapters**  
  https://proceedings.neurips.cc/paper_files/paper/2024/file/747dc7c6566c74eb9a663bcd8d057c78-Paper-Conference.pdf  

---

## 📊 Benchmarks & Leaderboards

- Hugging Face Low-Bit Leaderboard  
  https://huggingface.co/spaces/Intel/low_bit_open_llm_leaderboard  

- Intel Low-Bit Open LLM Leaderboard  
  https://www.intel.com/content/www/us/en/developer/articles/technical/low-bit-quantized-open-llm-leaderboard.html  

---

## 📚 Surveys & Comprehensive Studies

- **Low-bit Large Language Models: Basics, Systems, and Algorithms**  
  https://arxiv.org/pdf/2409.16694  

- **A Comprehensive Study on Quantization Techniques for LLMs**  
  https://arxiv.org/pdf/2411.02530  

- **Efficient Large Language Models: A Survey**  
  https://arxiv.org/pdf/2312.03863  

- **A Survey on Post-Training of Large Language Models**  
  https://arxiv.org/pdf/2503.06072  

---

## 🧪 Benchmarks & Evaluation

- **LLMCBench: Benchmarking Large Language Model Compression for Efficient Deployment**  
  https://arxiv.org/pdf/2410.21352

- **Quantization Hurts Reasoning? An Empirical Study on Quan-
tized Reasoning Models**
https://arxiv.org/pdf/2504.04823

- **Towards Understanding Best Practices for
Quantization of Vision-Language Models**
https://arxiv.org/pdf/2601.15287

---

## 🧾 Posters & Emerging Ideas

- **The Geometry of LLM Quantization: GPTQ as Babai's Nearest Plane Algorithm**  
  https://neurips.cc/virtual/2025/loc/san-diego/136811  

- **Post Training Quantization of Large Language Models with Microscaling Formats**  
  https://neurips.cc/virtual/2024/106487  

- **AdaQuantLM: LLM Quantization with Adaptive Bit-Widths**  
  https://neurips.cc/virtual/2024/98201  

- **LLM-MQ: Mixed-precision Quantization for Efficient LLM Deployment**  
  https://nips.cc/virtual/2023/81141  
 
---

## Articles
- **About Quantization**
  https://huggingface.co/docs/optimum/en/concept_guides/quantization

---

## 🤝 Contributions

Contributions are welcome:
- Add papers  
- Add benchmarks  
- Add implementations (especially GPU / HPC optimized)  

---

## ⭐ Star This Repo

If you are working on:
- Quantization  
- Efficient LLMs  
- AI systems for production  

This repo will keep you up-to-date.
