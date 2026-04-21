<div align="center">

# 🌊 QoSDiff

### Graph-Free Embedding Learning via Denoising Diffusion and Adversarial Attention for Robust QoS Prediction

[![Paper](https://img.shields.io/badge/Paper-EAAI_2026-red)](https://arxiv.org/abs/2512.04596)
[![arXiv](https://img.shields.io/badge/arXiv-2512.04596-b31b1b.svg)](https://arxiv.org/abs/2512.04596)
[![Python 3.9+](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-ee4c2c.svg)](https://pytorch.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Stars](https://img.shields.io/github/stars/guanchendu/Paper_Code_STU?style=social)](https://github.com/guanchendu/Paper_Code_STU)

*A single-step diffusion framework that learns robust user–service embeddings without explicit graph construction.*

[**📖 Paper**](https://arxiv.org/abs/2512.04596) · [**⚡ Quick Start**](#-quick-start) · [**📊 Results**](#-results) · [**🧩 Method**](#-method) · [**📬 Contact**](#-contact)

</div>

---

## ✨ Highlights

- 🚀 **Graph-free**: No explicit user–service interaction graph required — scales to large service ecosystems.
- ⚡ **Single-step diffusion**: One-shot denoising in continuous latent space, avoiding the costly multi-step Markov chain of standard DDPMs.
- 🎯 **Bidirectional hybrid attention**: Captures high-order user–service dependencies from both directions.
- 🛡️ **Adversarial robustness**: Filters observational noise through generator–discriminator interplay.
- 📈 **Proven at scale**: Validated on WS-DREAM and the large-scale EEL dataset (5,174 edge nodes, ~900M PING measurements).

---
