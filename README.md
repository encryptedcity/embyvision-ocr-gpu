<p align="center">
  <img src="images/banner.png" alt="EmbyVision OCR Banner">
</p>

# EmbyVision OCR (GPU Edition)

AI-powered **NVIDIA GPU-accelerated OCR microservice for Emby Credits Detector** using PaddleOCR and Docker.

EmbyVision OCR is a self-hosted OCR backend designed to enhance credit detection for Emby media servers. It provides a modern AI-based OCR engine that works alongside the Emby Credits Detector plugin to improve text recognition from video frames.

This project is the **GPU Edition** of EmbyVision OCR. It is designed for users who want maximum OCR performance using an NVIDIA GPU with CUDA acceleration.

> EmbyVision OCR provides a supercharged OCR experience by enhancing traditional OCR workflows with PaddleOCR's deep-learning computer vision technology.

---

# Features

* NVIDIA GPU-accelerated OCR processing
* High-performance inference using CUDA + cuDNN
* AI-powered OCR using PaddleOCR
* Designed for Emby Credits Detector integration
* Docker-based deployment
* Persistent model storage (models are downloaded only once)
* No database required
* Optimized for self-hosted media servers with NVIDIA GPUs

---

# Important Notice – NVIDIA Only

**This edition requires an NVIDIA GPU.**

It will **not** work with:

* AMD GPUs
* Intel GPUs / Arc
* CPU-only systems

You must have:

* An NVIDIA GPU
* NVIDIA Driver installed on the host
* NVIDIA Container Toolkit (`nvidia-container-toolkit`)

If you do not have an NVIDIA GPU, please use the official **CPU Edition** instead:  
https://github.com/encryptedcity/embyvision-ocr

---

# Docker Image

You can use the image from your private registry or build it yourself.

Example private registry image:

```text
myregistry.serverteck.xyz/embyvision-ocr-gpu:latest
