# CM-Bench: A Comprehensive Cross-Modal Feature Matching Benchmark Bridging Visible and Infrared Images

Official GitHub repository for the paper: **CM-Bench**.  
[Liangzheng Sun*](https://github.com/SLZ98), [Mengfan He*], Xingyu Shao, Binbin Li, Zhiqiang Yan, Chunyu Li, Ziyang Meng, and Fei Xing.

[![arXiv](https://img.shields.io/badge/arXiv-2603.12690-b31b1b.svg)](https://arxiv.org/abs/2603.12690) 
![Status](https://img.shields.io/badge/Status-Code%20After%20Acceptance-orange)

---

## 🚀 News & Status
* **[2026/03/13]:** Our paper is available on arXiv!
* **[Status]:** 🏗️ **The complete codebase and the ThermoSat dataset will be released upon the official acceptance of the paper.** We are currently cleaning up the implementation and preparing documentation. Stay tuned!

## 📝 Abstract
Infrared-visible (IR-VIS) feature matching is essential for cross-modality visual localization and navigation. However, a significant gap exists due to the absence of standardized benchmarks. We introduce **CM-Bench**, which evaluates **30 feature matching algorithms** across **10 diverse datasets**.

### Key Contributions:
* **Comprehensive Benchmark:** Systematic evaluation of 30 algorithms (spanning sparse, semi-dense, and dense methods) across 4 tasks: Homography, Relative Pose, Geo-localization, and Hard Geo-localization.
* **ThermoSat Dataset:** A new infrared-satellite dataset featuring **832 manually annotated pairs** captured by a DJI Matrice 4T, covering approximately $35.86 km^2$.

---

## 📊 Benchmark Overview
| Category | Representative Methods Evaluated |
| :--- | :--- |
| **Sparse** | SuperPoint, ALIKED, SIFT, RIFT, DeDoDe, etc. |
| **Semi-Dense** | LoFTR, ELoFTR, XoFTR, ASpanFormer, etc. |
| **Dense** | RoMa, DKM, GIM, MASt3R, etc. |

---

## 📅 TODO List
- [x] Release ArXiv technical report.
- [ ] Release **ThermoSat** dataset (Infrared-Satellite pairs with GT correspondences).
- [ ] Release evaluation scripts and benchmarking tools for all 30 matchers.

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
