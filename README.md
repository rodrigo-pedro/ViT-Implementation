# ViT-Implementation

Basic ViT implementation in PyTorch. Based on the paper ["An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale"](https://arxiv.org/abs/2010.11929) by Dosovitskiy et al. (2021) and [Better plain ViT baselines for ImageNet-1k](https://arxiv.org/abs/2205.01580) by Beyer et al. (2022).

All code is contained in the `vit-implementation.ipynb` file.

Achieves 80.74% accuracy in CIFAR-10 with 100 epochs, 8 layers, 8 heads, and 256 embedding dimensions. _Disclaimer: Not much hyperparameter tuning was done._
