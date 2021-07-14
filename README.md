# Virtual Try-On
This is a non-commercial educational project that uses [FrankMocap](https://github.com/facebookresearch/frankmocap) for pose estimation, [MultiGarmentNetwork](https://github.com/bharat-b7/MultiGarmentNetwork) for garment re-targeting. FrankMocap's [PyTorch3D](https://pytorch3d.org/) renderer was modified to support textures from MultiGarmentNetwork's garments.

Original videos was taken from [shutterstock.com](https://www.shutterstock.com/)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1q3RXEZAFAx6rdy6lynf735Pm4CLi2XLK/view?usp=sharing)

## Sample videos:

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/z5ka8HIwTH0/0.jpg)](https://youtu.be/Vlhmpd2RY4w)

## List of changes:

### FrankMocap

[Virtual Try-on Demo](https://github.com/igorlaryush/frankmocap/commit/fae10fd8afebfff66e8d424eacbbefe28ecb3bec)

[Add textures to FrankMocap's p3d_renderer](https://github.com/igorlaryush/frankmocap/commit/7f8173a5b896ecc3d345cb9541fcd4ca8cef225f)

### MultiGarmentNetwork

[Delete absolute paths](https://github.com/igorlaryush/MultiGarmentNetwork/commit/02407a2c5d47b3e82827964617b089bcdb73ccaa)

[Update to Python 3](https://github.com/igorlaryush/MultiGarmentNetwork/commit/ea82dcf6f2e8d4a304de7edddc4fffbbd986b6e2)

## License

This non-commercial educational demo MIT licensed. See the license file [here](https://github.com/pbelevich/virtual-try-on/blob/main/LICENSE). It's based on [FrankMocap](https://github.com/facebookresearch/frankmocap) (Copyright (c) Facebook, Inc. and its affiliates) and [MultiGarmentNetwork](https://github.com/bharat-b7/MultiGarmentNetwork) (Copyright (c) 2019 Bharat Lal Bhatnagar, Max-Planck-Gesellschaft). It uses [PyTorch3d](https://github.com/facebookresearch/pytorch3d) (Copyright (c) Facebook, Inc. and its affiliates. All rights reserved.) renderer and [MPI-IS Mesh Processing Library](https://github.com/MPI-IS/mesh) to support [SMPL](https://smpl.is.tue.mpg.de/). Original low-resolution videos was taken from [shutterstock.com](https://www.shutterstock.com/)
