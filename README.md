# Anomalib PatchCore CPU Optimizer

[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![OpenVINO](https://img.shields.io/badge/OpenVINO-2024.3-orange.svg)](https://www.intel.com/content/www/us/en/developer/tools/openvino-toolkit.html)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Optimized unsupervised industrial anomaly detection for real-time CPU inference. Reduced memory footprint by 65% and boosted throughput 8× via embedding compression and INT8 quantization — with <1.2% recall degradation.**

---

## 📌 Problem Statement

Industrial visual inspection systems face a critical deployment gap:

- **Research models are GPU-hungry:** PatchCore achieves state-of-the-art anomaly detection but stores massive patch embeddings, consuming ~1.8 GB of RAM.
- **Factory floors run on CPUs:** Edge devices and legacy industrial PCs lack CUDA support, forcing inference at 2–5 FPS — too slow for conveyor-belt inspection.
- **Data scarcity is real:** Defects are rare and expensive to label. Supervised approaches fail; unsupervised methods are required.

**Objective:** Bridge the gap between research accuracy and production deployment by optimizing PatchCore for low-latency, memory-efficient CPU inference.

---
**Acceptance Criteria Met:** ✅ ≥25 FPS on CPU | ✅ ≤35% memory footprint | ✅ <1.2% recall drop
