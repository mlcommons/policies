# Table of Contents

## Training

| Model            | 0.5 | 0.6 | 0.7 | 1.0 | 1.1 | 2.0 | 2.1 |
|------------------|-----|-----|-----|-----|-----|-----|-----|
| ResNet-50 v1.5   | X 6+| X   |     |     |     |     |     |
| SSD-ResNet34     | X 4+| X 2+| N/A |     |     |     |     |
| RetinaNet-ResNeXt50 5+| N/A 2+| X   |     |     |     |     |
| MaskRCNN         | X 6+| X   |     |     |     |     |     |
| NCF              | X 6+| N/A |     |     |     |     |     |
| NMT              | X 2+| X 4+| N/A |     |     |     |     |
| Transformer      | X 2+| X 4+| N/A |     |     |     |     |
| MiniGo           | X   | X 5+| X   |     |     |     |     |
| DLRM 2+          | N/A 5+| X   |     |     |     |     |     |
| BERT 3+          | N/A 4+| X   |     |     |     |     |     |
| RNN-T 3+         | N/A   | X 3+| X   |     |     |     |     |
| 3D U-Net 3+      | N/A 4+| X   |     |     |     |     |     |

Metric: Time-to-train (measured in minutes)

Note: v0.6 ResNet-50 v1.5, SSD-ResNet34, NMT increased accuracy targets, all v0.6 benchmarks changed initialization timing, and v0.7 MiniGo moved to 19x19 board

## HPC

| Model         | 0.7 | 1.0 | 2.0 |
|---------------|-----|-----|-----|
| CosmoFlow     | X   | X   | X   |
| DeepCAM 2+    | X   | X   |     |
| Open Catalyst | N/A | X   | X   |

Metrics: Time-to-train (measured in minutes) and throughput (weak scaling - measured in models/minute)

## Inference

| Model         | 0.5 | 0.7 | 1.0 | 1.1 | 2.0 |
|---------------|-----|-----|-----|-----|-----|
| MobileNet-v1  | X 4+| N/A |     |     |     |
| ResNet-50 v1.5 5+| X   |     |     |     |     |
| SSD-MobileNets 5+| X   |     |     |     |     |
| SSD-ResNet34 5+| X   |     |     |     |     |
| NMT           | X 4+| N/A |     |     |     |
| DLRM          | N/A 4+| X   |     |     |     |
| BERT          | N/A 4+| X   |     |     |     |
| RNN-T         | N
