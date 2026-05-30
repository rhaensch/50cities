# 50 Cities to Visit Before You Classify

### A World-Wide Benchmark Dataset for Remote Sensing Semantic Segmentation

[![Paper](https://img.shields.io/badge/Paper-CVPRW%202026-blue)]([PAPER_LINK](https://openaccess.thecvf.com/content/CVPR2026W/EarthVision/html/Weitzel_50_Cities_to_visit_before_you_classify_-_A_world-wide_CVPRW_2026_paper.html))
[![Dataset](https://img.shields.io/badge/Dataset-Available-green)](DATASET_LINK)
[![License](https://img.shields.io/badge/License-LICENSE-lightgrey)](https://creativecommons.org/licenses/by/4.0/)

Official repository for the CVPR EarthVision 2026 Workshop paper:

> **50 Cities to Visit Before You Classify: A World-Wide Benchmark Dataset for Remote Sensing Semantic Segmentation**
> Kenneth Weitzel, Bruno Zabielski, Johannes Heinrich, Ronny Hänsch
> CVPR EarthVision Workshop 2026

---
![Geographic distribution of 50 cities](figures/teaser.png)

## Overview

Earth observation imagery is vital for land use monitoring, urban planning, and environmental management. Semantic segmentation of satellite data enables global Land Use and Land Cover (LULC) mapping, yet progress is limited by the scarcity of accurate benchmarks as existing datasets often rely on semi-automatically generated labels, patch based sampling, and local geographic regions. 

**50 Cities to Visit Before You Classify** for multi-modal LULC segmentation and cross-continental generalization. It offers multimodal satellite imagery across 50 urban regions worldwide, including 33 cities with manual pixel-level annotations and 17 unlabeled cities for semi- and self-supervised learning. Each city is provided as a large, continuous scene capturing diverse urban morphologies and surrounding landscapes.

The dataset includes **50 cities distributed worldwide**, covering a broad range of:

* Geographic regions
* Climate zones
* Urban structures
* Population densities
* Land-cover characteristics
* Socio-economic environments

The benchmark is intended for:

* Semantic segmentation
* Domain generalization
* Cross-city transfer learning
* Foundation model evaluation
* Remote sensing representation learning
* Robustness and out-of-distribution analysis

---

## Key Features

* 🌍 Global geographic coverage
* 🏙️ 50 cities across multiple continents
* 🛰️ Medium-resolution remote sensing imagery
* 🎯 Pixel-wise semantic annotations
<!-- * 📊 Standardized evaluation protocol
* 🔄 Cross-city generalization benchmark
* 🏆 Reproducible train/validation/test splits -->

---

## Download

* Dataset: 

---

## Citation

If you use this dataset in your research, please cite:

```bibtex
@InProceedings{Haensch_2026_CVPR,
    author    = {Weitzel, Kenneth and Zabielski, Bruno and Heinrich, Johannes and H\"ansch, Ronny},
    title     = {50 Cities to visit before you classify - A world-wide multi-modal dataset for semantic segmentation of remote sensing imagery},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops},
    month     = {June},
    year      = {2026},
    pages     = {8085-8094}
}
```

---

## License

* [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

---

## Contact

For questions, bug reports, or dataset issues:

* Open a GitHub Issue
* Contact: `rww.haensch@gmail.com`

---

## Links

* [Paper](https://openaccess.thecvf.com/content/CVPR2026W/EarthVision/html/Weitzel_50_Cities_to_visit_before_you_classify_-_A_world-wide_CVPRW_2026_paper.html)
* [Project Page](https://github.com/rhaensch/50cities)
* Dataset: DATASET_LINK
