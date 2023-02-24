# Fast voxel grid interpolation

CUDA implementation (via Python Numba) of GPU-powered grid interpolation, aligning two regular 3D voxel grids. \
Given an offset in location and voxel scaling, one voxel grid is aligned with the other through linear interpolation.


## Background
This implementation was created in 2020 to resample voxel data of medical scans in two published paper implementations ([1](https://github.com/tarolangner/ukb_segmentation), [2](https://github.com/tarolangner/ukb_mimir)).
