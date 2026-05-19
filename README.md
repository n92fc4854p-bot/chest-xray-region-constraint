# chest-xray-region-constraint
Weakly supervised chest X-ray explainability

基于弱监督学习的胸部X光区域约束可解释辅助诊断方法研究。

## 项目简介

本项目基于 NIH ChestX-ray14 数据集，构建胸部X光多标签分类模型，并结合 Grad-CAM 可解释性方法，对模型热力图进行分析与增强。

本文提出胸腔区域软约束方法，通过构建近似胸腔区域分布的软掩膜，对原始热力图进行区域约束，以提升热力图与胸部解剖结构之间的一致性。

## 主要内容

- DenseNet121 多标签分类模型
- Weighted BCE 损失函数
- 类别特异性阈值优化
- Grad-CAM 热力图生成
- 胸腔区域软约束方法
- 定性与定量实验分析

## 数据集

NIH ChestX-ray14

## 运行环境

- Python 3.10
- PyTorch
- NumPy
- OpenCV
- Matplotlib

## 文件说明

- `main.ipynb`：完整实验代码
- `figures/`：论文实验结果图片
