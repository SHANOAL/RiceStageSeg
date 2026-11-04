<p align="center">
  <img src="assets/banner.svg" alt="RiceStageSeg" width="100%">
</p>

<p align="center">
  <a href="https://doi.org/10.3390/rs17162858"><img src="https://img.shields.io/badge/Paper-Remote%20Sensing%202025-1f6f4a?style=flat-square" alt="Paper"></a>
  <a href="https://doi.org/10.3390/rs17162858"><img src="https://img.shields.io/badge/DOI-10.3390%2Frs17162858-2f9e6b?style=flat-square" alt="DOI"></a>
  <a href="https://pan.baidu.com/s/14aJjnKKZ8gxUKInJa39zEA?pwd=ydek"><img src="https://img.shields.io/badge/Dataset-Baidu%20NetDisk-c9963c?style=flat-square" alt="Dataset"></a>
  <img src="https://img.shields.io/badge/Modalities-RGB%20%2B%2010--band%20MS-5fbf6b?style=flat-square" alt="Modalities">
  <img src="https://img.shields.io/badge/Task-Semantic%20Segmentation-0f3d2e?style=flat-square" alt="Task">
</p>

<p align="center">
  <b>Jianping Zhang, Tailai Chen, Yizhe Li, Qi Meng, Yanying Chen, Jie Deng, Enhong Sun</b><br>
  <i>Remote Sensing</i>, 2025, 17(16), 2858
</p>

<p align="center">
  <a href="#-overview">Overview</a> ·
  <a href="#-dataset-at-a-glance">Dataset</a> ·
  <a href="#-download">Download</a> ·
  <a href="#-benchmark-settings">Benchmark</a> ·
  <a href="#-citation">Citation</a>
</p>

---

## 🌾 Overview

Accurate identification of rice growth stages is critical for precision agriculture, crop management, and yield
estimation. Multimodal remote sensing provides complementary spectral and spatial information for this task, but
publicly available multimodal datasets designed for rice growth-stage identification have been lacking.

**RiceStageSeg** is a multimodal benchmark dataset captured by unmanned aerial vehicles (UAVs). It contains paired
centimeter-level **RGB** and **10-band multispectral (MS)** images acquired during several critical rice growth
stages, including jointing and heading. Every image comes with fine-grained, pixel-level annotations that
distinguish the growth stages.

We provide baselines with several state-of-the-art semantic segmentation models under unimodal (RGB-only, MS-only)
and multimodal (RGB + MS fusion) settings. Multimodal feature-level fusion outperforms the unimodal settings in
segmentation accuracy.

## 📊 Dataset at a Glance

| | |
| :-- | :-- |
| **Platform** | UAV |
| **Modalities** | Centimeter-level RGB, 10-band multispectral, paired |
| **Growth stages** | Several critical stages of rice, including jointing and heading |
| **Annotations** | Pixel-level semantic labels of growth stages |
| **Task** | Semantic segmentation of rice growth stages |

## 📥 Download

| Source | Link |
| :-- | :-- |
| Baidu NetDisk | [pan.baidu.com](https://pan.baidu.com/s/14aJjnKKZ8gxUKInJa39zEA?pwd=ydek) &nbsp; password: `ydek` |

This repository re-hosts the dataset to make it easier to access for researchers outside China.

## 🧪 Benchmark Settings

| Setting | Input |
| :-- | :-- |
| RGB-only | RGB image |
| MS-only | 10-band multispectral image |
| RGB + MS | Feature-level fusion of both modalities |

Detailed results of every baseline are reported in the [paper](https://doi.org/10.3390/rs17162858).

## 📝 Citation

If you find RiceStageSeg useful, please cite:

```bibtex
@article{zhang2025ricestageseg,
  title   = {RiceStageSeg: A Multimodal Benchmark Dataset for Semantic Segmentation of Rice Growth Stages},
  author  = {Zhang, Jianping and Chen, Tailai and Li, Yizhe and Meng, Qi and Chen, Yanying and Deng, Jie and Sun, Enhong},
  journal = {Remote Sensing},
  volume  = {17},
  number  = {16},
  pages   = {2858},
  year    = {2025},
  doi     = {10.3390/rs17162858}
}
```

## 📬 Contact

Questions and suggestions are welcome through [GitHub Issues](https://github.com/SHANOAL/RiceStageSeg/issues).
