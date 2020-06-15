# Free-form Image Inpainting with Gated Convolution

## Introduction

```
@inproceedings{yu2019free,
  title={Free-form image inpainting with gated convolution},
  author={Yu, Jiahui and Lin, Zhe and Yang, Jimei and Shen, Xiaohui and Lu, Xin and Huang, Thomas S},
  booktitle={Proceedings of the IEEE International Conference on Computer Vision},
  pages={4471--4480},
  year={2019}
}
```

## Results and models
### Places365-Challenge
|   Method   | Mask Type | Resolution | Train Iters |   Test Set    | l1 error |  PSNR  | SSIM  |            Download            |
| :--------: | :-------: | :--------: | :---------: | :-----------: | :------: | :----: | :---: | :----------------------------: |
| DeepFillv2 | free-form |  256x256   |    500k     | Places365-val |  8.635   | 22.398 | 0.815 | [model](xxx) &#124; [log](xxx) |


### CelebA-HQ
|   Method   | Mask Type | Resolution | Train Iters |  Test Set  | l1 error |  PSNR  | SSIM  |            Download            |
| :--------: | :-------: | :--------: | :---------: | :--------: | :------: | :----: | :---: | :----------------------------: |
| DeepFillv2 | free-form |  256x256   |    500k     | CelebA-val |  5.411   | 25.721 | 0.871 | [model](xxx) &#124; [log](xxx) |