# PlayerOne: Egocentric World Simulator

<p align="center">
  <img src="./assets/attn-mask.png" width=100%>
</p>

**Authors:** [Yuanpeng Tu](https://github.com/LeoXing1996), [Hao Luo](https://people.mpi-inf.mpg.de/~gfox/), [Xi Chen](https://zengyh1900.github.io/), [Xiang Bai](https://xingangpan.github.io/), [Fan Wang](https://people.mpi-inf.mpg.de/~elgharib/), [Hengshuang Zhao †](https://people.mpi-inf.mpg.de/~theobalt/) (†: corresponding author)


[![arXiv](https://img.shields.io/badge/arXiv-2407.08701-b31b1b.svg)](https://arxiv.org/abs/2407.08701)
[![Project Page](https://img.shields.io/badge/Project-Page-blue)](https://playerone-hku.github.io/)
<a target="_blank" href="https://huggingface.co/spaces/Leoxing/Live2Diff">
  <img src="https://huggingface.co/datasets/huggingface/badges/raw/main/open-in-hf-spaces-sm.svg" alt="HugginFace"/>
</a>

## Introduction Video

[![Youtube Introduction Video](https://github.com/user-attachments/assets/548e200e-90c3-4d51-a1d2-3f5ba78cb151)](https://youtu.be/4w2cLRW3RX0)


## TODO List

- [x] Support Colab

## Key Features

<p align="center">
  <img src="./assets/framework.jpg" width=100%>
</p>

* **Uni-directional** Temporal Attention with **Warmup** Mechanism
* **Multitimestep KV-Cache** for Temporal Attention during Inference
* **Depth Prior** for Better Structure Consistency
* Compatible with **DreamBooth and LoRA** for Various Styles
* **TensorRT** Supported

The speed evaluation is conducted on **Ubuntu 20.04.6 LTS** and **Pytorch 2.2.2** with **RTX 4090 GPU** and **Intel(R) Xeon(R) Platinum 8352V CPU**. Denoising steps are set as 2.

| Resolution | TensorRT |    FPS    |
| :--------: | :------: | :-------: |
| 512 x 512  |  **On**  | **16.43** |
| 512 x 512  |   Off    |   6.91    |
| 768 x 512  |  **On**  | **12.15** |
| 768 x 512  |   Off    |   6.29    |




## Acknowledgements

The design of Video Diffusion Model is built with [Wanx](https://github.com/modelscope/DiffSynth-Studio) and [CUT3R](https://github.com/CUT3R/CUT3R). We use [CausVid]([https://github.com/lewiji/MiDaS](https://github.com/tianweiy/CausVid)) implementation to support real-time generation. 

## BibTex

If you find it helpful, please consider citing our work:

```bibtex
@article{tu2025PlayerOne,
title={PlayerOne: Egocentric World Simulator},
author={Tu, Yuanpeng and Luo, Hao and Chen, Xi and Bai, Xiang and Wang, Fan and Zhao, Hengshuang},
journal={arXiv preprint},
year={2025}}
```
