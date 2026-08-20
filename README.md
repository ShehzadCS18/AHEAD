# AHEAD

## Overview
> The source code, benchmark dataset, pretrained models, and detailed documentation will
> be publicly released upon completion of the editorial/review process of
> the associated manuscript.


AHEAD is a comprehensive benchmark for aerial hazard detection designed to evaluate robust perception under real-world aviation scenarios. The benchmark introduces:

- A large-scale aerial hazard dataset
- Multi-view image collection
- Four difficulty levels (L1–L4)
- Physically inspired multi-weather degradation protocols
- AHEAD-Net with Difficulty-Guided Expert Routing (DGER)

The benchmark aims to facilitate research on robust aerial hazard detection for low-altitude aviation and autonomous aerial systems.

---


## Features

- RT-DETR-based detection framework
- Difficulty-Guided Expert Routing (DGER)
- Multi-weather degradation benchmark
- Difficulty-aware training
- Extensive evaluation protocol

---

## Dataset

The AHEAD dataset is designed to support research on robust aerial
hazard detection under diverse real-world environmental conditions. It
includes carefully annotated aerial hazard samples collected from
multiple viewpoints, a wide range of operational scenarios, and
comprehensive metadata for performance evaluation.

The complete dataset, annotation protocol, and benchmark statistics
will be released upon completion of the editorial process of the
associated manuscript.

## Installation

```bash
git clone https://github.com/ShehzadCS18/AHEAD.git
cd AHEAD

pip install -r requirements.txt
```

---

## Training

```bash
python training/train.py
```

---

## Evaluation

```bash
python training/evaluate.py
```

---

## Citation

If you use this repository, please cite our paper.

```bibtex
Citation will be added after publication.
```

---


## Contact

**Shehzad Ali**

Department of Applied Artificial Intelligence

Sungkyunkwan University

Email: *shehzadali@g.skku.edu*

---
