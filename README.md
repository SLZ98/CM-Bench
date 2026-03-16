# CM-Bench: A Comprehensive Cross-Modal Feature Matching Benchmark Bridging Visible and Infrared Images

Official GitHub repository for the paper: **CM-Bench**. 
[Liangzheng Sun*](https://github.com/SLZ98), [Mengfan He*], Xingyu Shao, et al.

[![arXiv](https://img.shields.io/badge/arXiv-2603.12690-b31b1b.svg)](https://arxiv.org/abs/2603.12690) 
![Status](https://img.shields.io/badge/Status-Coming%20Soon-orange)

---

## 🚀 News
* **[2026/03/13]:** Paper available on arXiv! [Check it out here](https://arxiv.org/abs/2603.12690).
* **[Coming Soon]:** We are cleaning up the code and preparing the **ThermoSat** dataset for public release. Stay tuned!

## 📝 Abstract
Infrared-visible (IR-VIS) feature matching is essential for cross-modality visual localization and navigation. However, a significant gap exists due to the absence of standardized benchmarks. In this paper, we introduce **CM-Bench**, which evaluates **30 feature matching algorithms** (sparse, semi-dense, and dense) across **10 diverse datasets**.

### Key Contributions:
1. **Comprehensive Benchmark:** Systematic evaluation of 30 algorithms on four tasks: Homography, Relative Pose, Geo-localization, and Hard Geo-localization.
2. **ThermoSat Dataset:** A new infrared-satellite dataset with 832 manually annotated pairs captured by a DJI Matrice 4T platform.
3. **Adaptive Preprocessing:** A classification-network-based front-end that automatically selects the best enhancement strategy for each image pair.

---

## 📊 Benchmark Overview
| Category | Representative Methods Evaluated |
| :--- | :--- |
| **Sparse** | SuperPoint, ALIKED, SIFT, RIFT, DeDoDe, etc. |
| **Semi-Dense** | LoFTR, ELoFTR, XoFTR, ASpanFormer, etc. |
| **Dense** | RoMa, DKM, GIM, MASt3R, etc. |

*Detailed results for all 30 algorithms can be found in the paper.*

---

## 📅 TODO List
- [ ] Release ArXiv technical report.
- [ ] Upload **ThermoSat** dataset (Infrared-Satellite pairs).
- [ ] Release evaluation scripts and adaptive preprocessing front-end.
- [ ] Release pre-trained models for cross-modal matching.

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
