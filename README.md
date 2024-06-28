# Wildfire-detection
제6회 2024 연구개발특구 AI SPARK 챌린지

최종 결과 89.15

Transformer + Unet

Transformer + Attention + Unet

swin transformer : 구현 X

-----------

## 참고 논문

1. **3D TransUNet: Advancing Medical Image Segmentation through Vision Transformers**

[3D TransUNet: Advancing Medical Image Segmentation through Vision...](https://arxiv.org/abs/2310.07781)



2. **Attention U-Net: Learning Where to Look for the Pancreas" by Ozan Oktay et al. (2018)**

[Attention U-Net: Learning Where to Look for the Pancreas](https://arxiv.org/abs/1804.03999)

-----------

## 전처리
데이터 셋 분석 10 channel image 중에 가장 특징적인 channel = 6, 7번 에서 특이점 발견

![10channel](https://github.com/hytric/Wildfire-detection/blob/main/10channel.png)

분석 코드


-----------

## 깨달은 점

1. 모든 랜덤성 제어 (np, tf, os 등등)
2. 버전 관리
