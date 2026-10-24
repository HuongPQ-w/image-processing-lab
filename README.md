# Basic Image Processing with OpenCV

> 📚 **Course lab** – Computer Vision (FPT University Can Tho)

A Jupyter notebook implementing five classic image-processing operations with OpenCV and NumPy. Outputs of every step are saved in the notebook, so you can view the results directly on GitHub.

## Functions

| # | Operation | Notes |
|---|---|---|
| 1 | **Color balance** | Per-channel (R/G/B) scaling with interactive sliders (`ipywidgets`) |
| 2 | **Histogram equalization** | Histogram before/after equalization using `cv2.equalizeHist` |
| 3 | **Median filter** | Removes salt-and-pepper noise (noise generated at 5% ratio) |
| 4 | **Mean filter** | Manual implementation with sliding window (3×3) |
| 5 | **Gaussian smoothing** | 3×3 Gaussian kernel with `cv2.GaussianBlur` |

## Getting started

```bash
git clone https://github.com/HuongPQ-w/image-processing-lab.git
cd image-processing-lab
pip install -r requirements.txt
jupyter notebook image_processing_lab.ipynb
```

The notebook reads three input images from the same folder, which are not included in this repository:

- `woman.png` – a color image (functions 1, 3, 4)
- `blur.png` – a low-contrast image (function 2)
- `noise.png` – an image with salt-and-pepper noise (function 5)

Place your own images with these names next to the notebook, then run the cells in order.

## Tech stack

Python · OpenCV · NumPy · Matplotlib · ipywidgets · Jupyter
