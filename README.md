# AHEAD: Aerial Hazard Evaluation and Detection Benchmark

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

## Repository Structure

```
configs/
datasets/
models/
training/
utils/
figures/
results/
```

---

## Features

- RT-DETR-based detection framework
- Difficulty-Guided Expert Routing (DGER)
- Multi-weather degradation benchmark
- Difficulty-aware training
- Extensive evaluation protocol

---

## Dataset

The AHEAD dataset contains:

- 37,572 annotated images
- 150 real-world videos
- Bird and drone hazards
- Four viewpoints
  - Aerial
  - Ground-sky
  - Multi-view
  - Bird's-eye view (BEV)
- Four difficulty levels (L1–L4)

---

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

## License

This project is released under the MIT License.

---

## Contact

**Shehzad Ali**

Department of Applied Artificial Intelligence

Sungkyunkwan University

Email: *your-email*

---

## Acknowledgements

This work is based on the AHEAD benchmark and AHEAD-Net developed for robust aerial hazard detection under adverse environmental conditions.
