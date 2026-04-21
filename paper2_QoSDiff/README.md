<div align="center">

# 🌊 QoSDiff

### Graph-Free Embedding Learning via Denoising Diffusion<br>and Adversarial Attention for Robust QoS Prediction

<p>
  <a href="https://arxiv.org/abs/2512.04596"><img src="https://img.shields.io/badge/📄_Paper-EAAI_2026-red?style=flat-square" alt="Paper"></a>
  <a href="https://arxiv.org/abs/2512.04596"><img src="https://img.shields.io/badge/arXiv-2512.04596-b31b1b?style=flat-square&logo=arxiv&logoColor=white" alt="arXiv"></a>
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3.9+-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"></a>
  <a href="https://pytorch.org/"><img src="https://img.shields.io/badge/PyTorch-2.0+-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"></a>
  <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-yellow?style=flat-square" alt="License"></a>
  <a href="https://github.com/guanchendu/Paper_Code_STU"><img src="https://img.shields.io/github/stars/guanchendu/Paper_Code_STU?style=flat-square&logo=github&color=gold" alt="Stars"></a>
</p>

<p><em>A single-step diffusion framework that recovers robust user–service embeddings<br>without ever constructing an explicit interaction graph.</em></p>

<p>
  <a href="#-highlights"><b>✨ Highlights</b></a> ·
  <a href="https://arxiv.org/abs/2512.04596"><b>📖 Paper</b></a> ·
  <a href="#-method"><b>🧩 Method</b></a> ·
  <a href="#-results"><b>📊 Results</b></a> ·
  <a href="#-quick-start"><b>⚡ Quick Start</b></a> ·
  <a href="#-contact"><b>📬 Contact</b></a>
</p>

</div>

---

## ✨ Highlights

<table>
<tr>
<td width="50%" valign="top">

### 🚀 Graph-Free by Design
No explicit user–service interaction graph required — scales naturally to **hyper-large service ecosystems** where reliable graphs are intractable to build.

</td>
<td width="50%" valign="top">

### ⚡ Single-Step Diffusion
One-shot denoising in the **continuous latent space**, avoiding the costly multi-step Markov chain of standard DDPMs while retaining their generative power.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎯 Bidirectional Hybrid Attention
Captures high-order `user → service` **and** `service → user` dependencies within a unified attention block — a true dual-perspective view of interactions.

</td>
<td width="50%" valign="top">

### 🛡️ Adversarially Robust
A generator–discriminator interplay filters out observational noise, yielding predictions that **stay stable even under severe data corruption**.

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### 📈 Proven at Scale
Validated on **WS-DREAM** and the large-scale **EEL dataset** (5,174 edge nodes, ~900M PING measurements) — outperforming twelve state-of-the-art baselines with consistent gains of up to **17.7%** in MAE and strong cross-dataset generalization.

</td>
</tr>
</table>

---
