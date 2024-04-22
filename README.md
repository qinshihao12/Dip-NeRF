# Dip-NeRF

Dip-NeRF: Depth-Based Anti-Aliased Neural Radiance Fields

Shihao Qin,Jiangjian Xiao and Jianfei Ge

Faculty of Electrical Engineering and Computer Science, Ningbo University, Ningbo 315201, China

Ningbo Institute of Industrial Technology, Chinese Academy of Sciences, Ningbo 315201, China

Electronics 2024, 13(8), 1527

https://www.mdpi.com/2079-9292/13/8/1527

## Table Of Contents
- [Keywords](#keywords)
- [Abstract](#abstract)
- [Results](#results)
  - [Comparison](#comparison)
  - [Ablation Study](#ablation-study)

## Keywords

NeRF; scene representation; novel view synthesis; depth priors; point cloud generation; rendering accelerations

## Abstract

Neural radiation field (NeRF)-based novel view synthesis methods are gaining popularity for their ability to generate detailed and realistic images. However, most NeRF-based methods only use images to learn scene representations, ignoring the importance of depth information. The Zip-NeRF method has achieved impressive results in unbounded scenes by combining anti-aliasing techniques and mesh representations. However, the method requires a large number of input images and may perform poorly in complex scenes. Our method incorporates the advantages of Zip-NeRF and incorporates depth information to reduce the number of required images and solve the scale-free problem in borderless scenes. Experimental results show that our method effectively reduces the training time.And we can generate high-quality images and fine point cloud models using few images, even in complex scenes with numerous occlusions.

![Overall Framework](https://github.com/qinshihao12/Dip-NeRF/assets/96531673/e974813b-1f07-4075-ab90-9b8d9e56bb18)

## Results

### Comparison

![对比图bar](https://github.com/qinshihao12/Dip-NeRF/assets/96531673/b9dbfe63-4ec1-4a32-9554-2822dd2b0170)

![对比图class](https://github.com/qinshihao12/Dip-NeRF/assets/96531673/a5fdb5e0-86f7-496f-9fbf-fffd13a9ae59)

![对比图tool](https://github.com/qinshihao12/Dip-NeRF/assets/96531673/18af6cb6-d427-4815-9130-3c43bb08e92d)

![Comparative Experimental Table](https://github.com/qinshihao12/Dip-NeRF/assets/96531673/c524ef98-9116-42a2-ba65-a55e8b0ad2a5)

### Ablation Study

![Ablation Experiments](https://github.com/qinshihao12/Dip-NeRF/assets/96531673/60d4bf54-2889-4d9a-8738-d3d95c58ea73)

![Ablation Experiments Table](https://github.com/qinshihao12/Dip-NeRF/assets/96531673/13d54d59-790b-4c19-8ca6-14301cc90949)
