# Diffusion-based Conditional Facial Image Completion

This repository contains code and resources for a diffusion-based conditional face completion project.

## Overview

The project demonstrates facial image inpainting using a conditional diffusion model. The repository includes a Jupyter notebook for training models, running inference to generate new samples, a pretrained model checkpoint, generated sample images, and a project report.

## Repository Structure

- `main.ipynb` — Jupyter notebook with code for model training and inference.
- `model.pth` — Pretrained model checkpoint for inference.
- `report.pdf` — Project report with methodology, experiments, and results.
- `requirements.txt` — Python dependencies.
- `generated samples/` — Folder with generated outputs:
  - `samples.png` — Model outputs (3 different samples) for example images.
  - `training_faces.png` — Model outputs on training set faces.
  - `unseen_faces.png` — Model outputs on held-out faces.
- `images/` — Example input images for inference.

## Requirements

Install dependencies from `requirements.txt` (recommended in a virtual environment):

```bash
pip install -r requirements.txt
```

## Usage

1. Install dependencies as above.
2. Launch Jupyter and open the notebook:
3. Run the cells in `main.ipynb` to perform inference using the pretrained `model.pth` and visualize new samples. The notebook will generate a grid of inpainted faces and save it as `generated samples/samples.png`.

**Note:**
- Ensure your working directory is the repository root so that relative paths (e.g., `model.pth`, `images/`, `generated samples/`) resolve correctly.

## Reproducing Training

Training scripts are included in the notebook. See `report.pdf` for details about the training setup, hyperparameters, and evaluation metrics.

## Results

- Generated samples of the example images are saved in `generated samples/samples.png`.
- Additional outputs on training and unseen faces are in `training_faces.png` and `unseen_faces.png`.

## Further Information

See `main.ipynb` and `report.pdf` for implementation details, experimental results, and discussion.

