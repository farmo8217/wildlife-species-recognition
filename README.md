# Wildlife Species Recognition from Camera Traps

A computer vision project focused on wildlife species recognition using camera-trap images from the Snapshot Serengeti dataset.

## Project Objective

Build and evaluate a deep learning pipeline for recognizing wildlife species from camera-trap images, with an emphasis on reliable data handling, reproducible experiments, and meaningful evaluation.

## Dataset

- **Name:** Snapshot Serengeti
- **Source:** [LILA BC — Snapshot Serengeti](https://lila.science/datasets/snapshot-serengeti)
- **Data access strategy:** Retrieve selected images from remote storage when needed, rather than downloading the entire image collection.
- **Dataset preparation:** In progress.

## Planned Workflow

1. Inspect dataset metadata and annotations.
2. Explore species labels and image distributions.
3. Build a remote image-loading pipeline with bounded caching.
4. Prepare leakage-aware training, validation, and test splits.
5. Train a baseline classification model.
6. Evaluate performance and analyze errors.
7. Improve the model and document the experiments.

## Current Status

**Stage 1 — Project Setup and Remote Image Access**

- [x] Initialize the project repository.
- [x] Set up the Python virtual environment.
- [x] Verify remote image access with a small test.
- [ ] Inspect official dataset metadata.
- [ ] Implement the PyTorch dataset and data-loading pipeline.
- [ ] Train and evaluate the first baseline model.

## Project Structure

```text
wildlife-species-recognition/
├── data/
│   ├── raw/
│   ├── processed/
│   └── splits/
├── notebooks/
├── src/
├── models/
├── reports/
├── tests/
├── .gitignore
├── requirements.txt
└── README.md
```

## Technologies

- Python
- PyTorch
- Pillow
- Requests
- Git and GitHub

Additional dependencies will be documented as the project develops.