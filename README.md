
## satellite-image-processing

# Satellite Image Processing

![Pipeline](https://img.shields.io/badge/pipeline-active-brightgreen)
![Framework](https://img.shields.io/badge/framework-PyTorch%20%7C%20OpenCV-ee4c2c)

## Overview
This repository features an end-to-end computer vision pipeline optimized for remote sensing and satellite imagery. It includes tools for image preprocessing, multispectral band alignment, orthorectification, and deep learning-based feature extraction (such as cloud masking, land cover classification, and object detection).

## Features
* **Preprocessing:** Radiometric calibration, atmospheric correction, and histogram equalization.
* **Band Manipulation:** Tools for computing NDVI (Normalized Difference Vegetation Index), NDWI, and false-color composites.
* **AI Models:** Pre-trained U-Net and ResNet architectures for automated segmentation of buildings, roads, and water bodies.
* **Scalability:** Built with Dask and Rasterio to handle massive GeoTIFF datasets efficiently.

## Directory Layout
```text
├── src/
│   ├── preprocessing/  # Tiling, orthorectification, and geo-referencing
│   ├── models/         # PyTorch segmentation architectures
│   └── utils/          # GeoTIFF and shapefile helpers
├── notebooks/          # Exploratory Jupyter notebooks
└── config/             # Model hyperparameters and pipeline configurations
