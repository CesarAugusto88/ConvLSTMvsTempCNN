# Flood Classification using ConvLSTM and TempCNN

[![License: CC0 1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
[![Python 3.10+](https://img.shields.io/badge/Python-3.10%2B-blue)](https://www.python.org/downloads/)
[![Framework: Keras](https://img.shields.io/badge/Framework-Keras-red)](https://keras.io)

This repository contains the code and datasets for the paper **"Comparing ConvLSTM and TempCNN for Flood Classification in Satellite Image Time Series"**. The study evaluates deep learning models for flood mapping using Sentinel-2 satellite imagery during the 2024 Rio Grande do Sul floods (Brazil).

## Key Features
- **Two state-of-the-art models**:
  - **ConvLSTM**: Combines CNNs with LSTMs for spatio-temporal analysis
  - **TempCNN**: Uses 3D convolutions for time-series processing
- **resolution data**: Sentinel-2 imagery (10m resolution)

## Repositore clone
```bash
git clone https://github.com/CesarAugusto88/ConvLSTMvsTempCNN.git
cd ConvLSTMvsTempCNN
```

## Repository Structure
 - scripts - Python 
 - data - Training/test datasets in notebook
 - models - Training and test the models
 - notebooks - Visualization notebooks

## Results
Model     mIoU    F1-score  Accuracy
ConvLSTM  0.7085  0.9027    0.9022
TempCNN   0.6624  0.8838    0.8830

@article{costa2024flood,
  title={Comparing ConvLSTM and TempCNN for Flood Classification},
  author={Costa, Cesar A. M. et al.},
  journal={INPE},
  year={2024}
}
