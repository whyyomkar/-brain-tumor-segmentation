# 🧠 Attention-Gated 3D U-Net for Brain Tumor Segmentation

[![Python](https://img.shields.io/badge/Python-3.14-blue)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0-orange)](https://pytorch.org)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

&gt; **MRI-based glioma segmentation with attention mechanisms and explainable AI**

## 🎯 Problem

Brain tumors affect **250,000 people annually**. Manual MRI segmentation takes **7+ days**. Our system segments tumors in **30 seconds** with attention-guided focus.

## 🏗️ Architecture
vbrats_project/
├── dataset_fixed.py          # Patient-level split + augmentation
├── model_attention.py        # Attention U-Net architecture
├── train_attention.py        # Training script
├── visualize_attention.py    # Attention heatmaps
├── plot_training_curves.py   # Training curves
├── test_eval.py              # Test evaluation
└── results/                  # Generated figures
