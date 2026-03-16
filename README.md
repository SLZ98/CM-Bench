# CM-Bench: A Comprehensive Cross-Modal Feature Matching Benchmark Bridging Visible and Infrared Images

[cite_start]Official GitHub repository for the paper: **CM-Bench**. [cite: 3]
[cite_start][Liangzheng Sun*](https://github.com/SLZ98), [Mengfan He*], Xingyu Shao, Binbin Li, Zhiqiang Yan, Chunyu Li, Ziyang Meng, and Fei Xing. [cite: 4]

[![arXiv](https://img.shields.io/badge/arXiv-2603.12690-b31b1b.svg)](https://arxiv.org/abs/2603.12690) 
![Status](https://img.shields.io/badge/Status-Code%20After%20Acceptance-orange)

---

## 🚀 News & Status
* [cite_start]**[2026/03/13]:** Our paper is available on arXiv! [cite: 1]
* **[Status]:** 🏗️ **The complete codebase and the ThermoSat dataset will be released upon the official acceptance of the paper.** We are currently cleaning up the implementation and preparing documentation. [cite_start]Stay tuned! [cite: 14]

## 📝 Abstract
[cite_start]Infrared-visible (IR-VIS) feature matching is essential for cross-modality visual localization and navigation. [cite: 5] [cite_start]However, a significant gap exists due to the absence of standardized benchmarks. [cite: 8] [cite_start]We introduce **CM-Bench**, which evaluates **30 feature matching algorithms** across **10 diverse datasets**. [cite: 9, 50]

### Key Contributions:
* [cite_start]**Comprehensive Benchmark:** Systematic evaluation of 30 algorithms (spanning sparse, semi-dense, and dense methods) across 4 tasks: Homography, Relative Pose, Geo-localization, and Hard Geo-localization. [cite: 11, 44, 49, 53]
* [cite_start]**ThermoSat Dataset:** A new infrared-satellite dataset featuring **832 manually annotated pairs** captured by a DJI Matrice 4T platform, covering approximately $35.86 km^2$. [cite: 55, 57, 95]
* [cite_start]**Adaptive Preprocessing:** A classification-network-based front-end that automatically selects suitable enhancement strategies (e.g., Scharr-LCN, Morph-grad) for different image pairs before matching. [cite: 12, 54, 112]

---

## 📊 Benchmark Overview
| Category | Representative Methods Evaluated |
| :--- | :--- |
| **Sparse** | [cite_start]SuperPoint, ALIKED, SIFT, RIFT, DeDoDe, etc. [cite: 168, 169] |
| **Semi-Dense** | [cite_start]LoFTR, ELoFTR, XoFTR, ASpanFormer, etc. [cite: 170, 171] |
| **Dense** | [cite_start]RoMa, DKM, GIM, MASt3R, etc. [cite: 171] |

---

## 📝 Citation
If you find our benchmark or dataset useful, please consider citing:

```bibtex
@article{sun2026cmbench,
  title={CM-Bench: A Comprehensive Cross-Modal Feature Matching Benchmark Bridging Visible and Infrared Images},
  author={Sun, Liangzheng and He, Mengfan and Shao, Xingyu and Li, Binbin and Yan, Zhiqiang and Li, Chunyu and Meng, Ziyang and Xing, Fei},
  journal={arXiv preprint arXiv:2603.12690},
  year={2026}
}
