# ObjectReconstruction_ViewSynthesis_NeRF

## Introduction
This repository contains the code for object reconstruction and novel view synthesis using NeRF.

## Requirements
- Install the required dependencies:
  ```bash
  pip install torch torchvision opencv-python tensorboard
  apt-get install colmap

### Train

1. Prepare the dataset and camera parameters.
2. Run the training script:

   python train.py --data_path /content/extracted_frames/ --params_path /content/sparse/0/

### Test

Use the trained model to render new views:

   python train.py --data_path /content/extracted_frames/ --params_path /content/sparse/0/

