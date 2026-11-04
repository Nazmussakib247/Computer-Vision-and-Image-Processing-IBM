# Computer Vision and Image Processing with Python

IBM computer vision learning materials focused on practical image loading,
visualization, color channels, quantization, and NumPy array manipulation.

## Repository layout

```text
Module 2/
├── 2-1.ipynb
├── LAB_01_Image_Processing_With_Pillow.ipynb
├── baboon.png
├── barbara.png
└── lenna.png
```

## Quick start

1. Create and activate a virtual environment:

   ```bash
   python -m venv .venv
   # Windows PowerShell
   .\.venv\Scripts\Activate.ps1
   # macOS/Linux
   source .venv/bin/activate
   ```

2. Install the pinned project dependencies:

   ```bash
   python -m pip install --upgrade pip
   python -m pip install -r requirements.txt
   ```

3. Start Jupyter from the repository root:

   ```bash
   jupyter notebook
   ```

   Open `Module 2/2-1.ipynb` and run the cells from top to bottom. The
   included images are already available locally, so the notebook can be
   followed without downloading additional assets.

## Learning objectives

- Load and inspect images with Pillow.
- Display images with Matplotlib.
- Convert RGB images to grayscale and reduce intensity levels.
- Convert Pillow images to NumPy arrays.
- Slice image regions and inspect individual color channels.

## Reproducibility

- Use Python 3.9 or newer.
- Install dependencies from `requirements.txt` rather than installing
  packages inside a notebook.
- Run notebook cells in order because later examples reuse earlier variables.
- Every push and pull request runs an automated check for valid notebooks and
  required image assets.

## Notes

The PNG files are provided as learning assets for the accompanying IBM
course material. The notebooks are intended for interactive study rather
than production image-processing pipelines.
