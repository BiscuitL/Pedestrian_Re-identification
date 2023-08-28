# Pedestrian_Re-identification

## Overview

This repository contains a person re-identification (ReID) model that utilizes fusion techniques in both spatial and channel dimensions to enhance the attention mechanism. The goal of this project is to improve the performance of person re-identification by effectively combining spatial and channel information.

## Features

- Fusion of spatial and channel dimensions for enhanced attention in ReID.
- Utilizes the DukeMTMC, Market-1501-v15.09.15, and MSMT17_V2 datasets for evaluation.

## Datasets

The model is evaluated on the following datasets:
- [DukeMTMC](https://drive.google.com/file/d/1qdzSGvtd7ZRAb_MqSieFQoxFpUnIzzNI/view?usp=drive_link)
- [Market-1501-v15.09.15](https://drive.google.com/file/d/17QAMNMaLJl20XkdQ_FgSxlz0Dmb9HdnE/view?usp=drive_link)
- [MSMT17_V2](https://drive.google.com/file/d/17QAMNMaLJl20XkdQ_FgSxlz0Dmb9HdnE/view?usp=drive_link)

## Results

Our fusion-based attention model achieves competitive results on the DukeMTMC, Market-1501-v15.09.15, and MSMT17_V2 datasets. The fusion of spatial and channel dimensions enhances the attention mechanism, leading to improved person re-identification accuracy.

### Performance Comparison on Market Dataset

| Method    | Rank-1 | mAP  |
|-----------|--------|------|
| Baseline  | 92.4   | 81.3 |
| OSNet     | 94.8   | 84.9 |
| IANet     | 94.4   | 83.1 |
| PCB       | 92.3   | 77.4 |
| Ours      | 94.2   | 85.7 |

### Performance Comparison on Duke Dataset

| Method    | Rank-1 | mAP  |
|-----------|--------|------|
| Baseline  | 83.8   | 71.9 |
| OSNet     | 88.6   | 73.5 |
| IANet     | 87.1   | 73.4 |
| PCB       | 81.9   | 65.3 |
| Ours      | 87.1   | 75.9 |

### Performance Comparison on MSMT17 Dataset

| Method    | Rank-1 | mAP  |
|-----------|--------|------|
| Baseline  | 68.1   | 42.7 |
| OSNet     | 78.7   | 52.9 |
| IANet     | 75.5   | 45.8 |
| PCB       | 68.2   | 40.4 |
| Ours      | 73.8   | 48.7 |

Our proposed method demonstrates competitive performance across different datasets, with notable improvements in both Rank-1 accuracy and mean Average Precision (mAP) compared to the baseline methods. This indicates the effectiveness of our spatial and channel dimension fusion approach for enhancing attention mechanisms in person re-identification.
