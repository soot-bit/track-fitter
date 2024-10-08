# TrackFormer: Particle Trackfitting with Transformer 

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Python](https://img.shields.io/badge/Python-3.7%2B-green.svg)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-1.10%2B-orange.svg)](https://pytorch.org/)
[![PyTorch Lightning](https://img.shields.io/badge/PyTorch%20Lightning-1.6%2B-purple.svg)](https://www.pytorchlightning.ai/)

## Overview

TrackFormer is a unique solution to particle trajectory reconstruction that uses transformer-inspired design. Using Transformers' powerful self-attention mechanism, this model successfully performs track fitting, resulting in better accuracy and efficiency.

## Features

- **Transformer-based Architecture**: For fast efficient and accurate particle track reconstruction.
- **Built with Lightning Integration**:
- **Modular Design**: 
- **Logging and CLI integration**:

## Getting Started

1. **Clone the repository**:
2. download datasets to specific directory in Data
3. train, test split dataset  with `Data/Acts/datamaker.sh /path/to/dataset 80 10 10`
4. example usage `python main.py fit --config configs/tformer.yaml  --data ActsDataModule  --config configs/trainer.yaml`
