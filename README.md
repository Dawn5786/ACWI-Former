# ACWI-Former
# Adaptive Complex Wavelet Informed Transformer Operator

This repository contains PyTorch implementation of the Adaptive Complex Wavelet Informed Transformer Operator. 
Classification code is provided in 'classification' .

## Usage

### Requirements

- torch>=1.8.0
- torchvision
- timm
- PyWavelets
- PyYAML

*Note*: To use the ```rfft2``` and ```irfft2``` functions in PyTorch, you need to install PyTorch>=1.8.0. Complex numbers are supported after PyTorch 1.6.0, but the ```fft``` API is slightly different from the current version. 


### Installation
```
pip install -e .
```
