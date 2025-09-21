<h1>Weed Detection using Deep Learning</h1>

This repository contains Jupyter notebooks for <b>weed detection in agricultural videos</b>. The workflow is designed to:

1. <t><b>Preprocess agricultural</b> video data into frames.</t>

2. <b>Train and evaluate a deep learning model</b> (CNN/transfer learning) for weed classification.

<h2>Repository Contents</h2>

<h4>Model.ipynb</h4>

<ul>-Defines and trains a PyTorch-based deep learning model for weed detection.

-Uses transfer learning (torchvision.models) along with preprocessing pipelines (transforms).

-Handles dataset loading with DataLoader and optimizes training with torch.optim.</ul>

<h4>WeedDetectionVideoConverter.ipynb</h4>

<ol>-Converts input agricultural videos into frames for training/testing.

-Uses OpenCV (cv2) for frame extraction and image handling.

-Provides utilities for saving frames and optionally comparing frames using SSIM (structural similarity).</ol>

Supports Google Colab integration for file handling.
