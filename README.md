# Nerflets: Local Radiance Fields for Efficient Structure-Aware 3D Scene Representation from 2D Inputs
fork address: https://github.com/google-research/google-research/tree/6351ed2aef6a9ded7cb6138decfd1a96eb78320e/nerflets


This is work in progress and under active development.

## Installation

Please use [anaconda](https://www.anaconda.com/) to install all dependencies:

```bash
conda env create -f environment.yaml
```

## To Test
We conduct experiments on ToyBox-5, Kitti-360, ScanNet. You can train as following:

```bash
python train.py -c CONFIG.yaml --exp_name EXP_NAME --img_wh W H
```

For inference, you can run as:

```bash
python eval.py -c CONFIG.yaml --ckpt_path CKPT_PATH  --img_wh W H
```

For more arguments, please refer to `opt.py`.
