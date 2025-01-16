# Wildfire-detection
제6회 2024 연구개발특구 AI SPARK 챌린지

#### Final result 89.15 : 열린moon 19등

1. Transformer + Unet
2. Transformer + Attention + Unet
3. swin transformer : 구현 X

-----------

## Reference papers

1. **3D TransUNet: Advancing Medical Image Segmentation through Vision Transformers**

[3D TransUNet: Advancing Medical Image Segmentation through Vision...](https://arxiv.org/abs/2310.07781)



2. **Attention U-Net: Learning Where to Look for the Pancreas" by Ozan Oktay et al. (2018)**

[Attention U-Net: Learning Where to Look for the Pancreas](https://arxiv.org/abs/1804.03999)

-----------

## Preprocessing
Analyze the dataset and find anomalies in the most characteristic channel = 6 and 7 out of 10 channel image

![10channel](https://github.com/hytric/Wildfire-detection/blob/main/10channel.png)

분석 코드


-----------

## learning point

1. Control all randomness (np, tf, os 등등)
2. Versioning
3. Ensembles are good for performance
