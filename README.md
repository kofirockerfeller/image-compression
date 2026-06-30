# SVD Image Compression

A short notebook demonstrating image compression using Singular Value Decomposition (SVD).

## Contents
- SVD theorem overview and key relationships
- Rank-k approximation for grayscale images
- Compression applied to color images (per-channel RGB)
- Visual comparisons across different k values with data reduction stats

## Requirements
```
numpy
matplotlib
scikit-image
pillow
```

Install with `uv`:
```
uv pip install numpy matplotlib scikit-image pillow
```

## Usage
Open `svd_image_compression.ipynb` in Jupyter and run all cells. A color image (`greg.jpeg`) is required in the working directory for the color compression section.
