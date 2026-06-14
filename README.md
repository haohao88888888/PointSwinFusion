# PointSwinFusion

This repository provides the core implementation of PointSwinFusion, a serialized 3D-to-2D feature-bridging framework for point-cloud recognition and semantic segmentation.

## Main Components

- Point-cloud serialization with Z-Order, Hilbert, and coordinate-transposed traversal orders
- Adaptive 1D-to-2D feature folding for Swin Transformer
- Inverse bridging for point-wise segmentation
- Multi-view voting for S3DIS whole-room inference
- Reproduction scripts for ModelNet40, ScanObjectNN, and S3DIS experiments

## Datasets

The repository does not redistribute ModelNet40, ScanObjectNN, or S3DIS. Please download them from their official sources and set the dataset paths using the command-line arguments.

## Example Commands

See `autodl_multi_order_experiments.md` for the training and evaluation commands used in the paper.

## Code Availability

The code is released to support reproducibility of the manuscript.
