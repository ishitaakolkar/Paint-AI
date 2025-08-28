# Cartoonizer AI

Create vibrant, high-quality cartoon versions of your photos using cutting-edge AI powered by Hugging Face’s Stable Diffusion Instruct Pix2Pix model.

## Overview

Cartoonizer AI transforms images into artistic, cartoon-style renditions with ease. This project leverages a state-of-the-art instruct-tuned diffusion model for superior, painterly cartoon effects.

Features:
- Uses Hugging Face’s `instruction-tuning-sd/cartoonizer` pretrained model
- Fast and high-quality image-to-image style transfer
- Easily runnable in Google Colab with GPU support
- Dockerized API server for local or cloud deployment
- Simple upload and generate workflow with visual output

## Demo

<img width="950" height="326" alt="image" src="https://github.com/user-attachments/assets/78b89c4c-afeb-4ed7-93ba-076397a4b1e6" />

## Getting Started

### Google Colab

Run the provided Colab notebook to interactively upload images and generate cartoonized versions.

1. Set your Hugging Face API token as a secret in Colab (`HUGGINGFACE_API_TOKEN`).
2. Run all cells to install dependencies, load the model, and upload images.
3. View and download your cartoonized images instantly.

### Docker Deployment

Use the included Dockerfile and FastAPI backend to deploy a REST API for cartoonization.

