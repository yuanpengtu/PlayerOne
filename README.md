
<p align="center">

  <h2 align="center">PlayerOne: Egocentric World Simulator</h2>
  <p align="center">
    <a href=""><strong>Yuanpeng Tu</strong></a>
    ·
    <a href="https://scholar.google.com/citations?user=7QvWnzMAAAAJ&hl=zh-CN"><strong>Hao Luo</strong></a>
    ·
    <a href="https://xavierchen34.github.io/"><strong>Xi Chen</strong></a>
    ·
    <a href="https://scholar.google.com/citations?user=UeltiQ4AAAAJ&hl=en"><strong>Xiang Bai</strong></a>
    <br>
    <a href="https://scholar.google.com/citations?user=WCRGTHsAAAAJ&hl=en"><strong>Fan Wang</strong></a>
    ·
    <a href="https://hszhao.github.io/"><strong>Hengshuang Zhao</strong></a><sup>†</sup>
    <br>
    <br>
        <a href="https://arxiv.org/abs/2410.10306"><img src='https://img.shields.io/badge/arXiv-PlayerOne-red' alt='Paper PDF'></a>
        <a href='https://playerone-hku.github.io/'><img src='https://img.shields.io/badge/Project_Page-PlayerOne-blue' alt='Project Page'></a>
        <!-- <a href='https://mp.weixin.qq.com/s/vDR4kPLqnCUwfPiBNKKV9A'><img src='https://badges.aleen42.com/src/wechat.svg'></a> -->
        <!-- <a href='https://huggingface.co/Shuaishuai0219/Animate-X'><img src='https://img.shields.io/badge/%F0%9F%A4%97%20HuggingFace-Model-yellow'></a> -->
    <br>
    <b></a>HKU &nbsp; | &nbsp; </a> Alibaba DAMO Academy</b>
    <br>
  </p>
</p>

This repository is the official implementation of paper "PlayerOne: Egocentric World Simulator". PlayerOne is the first egocentric realistic world simulator, facilitating immersive and unrestricted exploration within vividly dynamic environments. Given an egocentric scene image from the user, PlayerOne can accurately construct the corresponding world and generate egocentric videos that are strictly aligned with the real-scene human motion of the user captured by an exocentric camera. 
  <table align="center">
    <tr>
    <td>
      <img src="/assets/teaser.png">
    </td>
    </tr>
  </table>


## &#x1F4CC; Updates
* [2025.6.10] 🔥 Our [paper](https://arxiv.org/abs/2410.10306) is in public on arxiv.






## &#x1F304; Gallery
### Demonstration of Motion Video Alignment 
<table class="center">
<tr>
    <td width=98% style="border: none">
        <video controls loop src="/assets/MotionVideoAlign.mp4" muted="false"></video>
    </td>
</tr>
</table>


### More simulated videos produced by PlayerOne
<table class="center">
<tr>
    <td width=50% style="border: none">
        <video controls loop src="/assets/example1.mp4" muted="false"></video>
    </td>
        <td width=50% style="border: none">
        <video controls loop src="/assets/Moreexample.mp4" muted="false"></video>
    </td>
</tr>
</table>




### Comparisons with previous works


<table class="center">
<tr>
    <td width=50% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/73d53b31-ac48-4b97-b2bf-a3d8c1d4f3ff" muted="false"></video>
    </td>
        <td width=50% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/3488092a-f918-4c7d-86ee-b0de46668ccd" muted="false"></video>
    </td>
</tr>
</table>

<table class="center">
<tr>
    <td width=50% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/f3a23204-69b9-45f3-8f70-ba0d7aba1bff" muted="false"></video>
    </td>
        <td width=50% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/a361bba9-a406-461c-aa78-099ef9b0206f" muted="false"></video>
    </td>
</tr>
</table>

<table class="center">
<tr>
    <td width=50% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/349b69c2-5333-42f2-88ac-742de6bd5a0f" muted="false"></video>
    </td>
        <td width=50% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/fdc118ff-aa9e-4c20-a444-e6873a1bad2f" muted="false"></video>
    </td>
</tr>
</table>

<table class="center">
<tr>
    <td width=50% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/cfd1228b-ee4e-4d95-b378-b79c41aa247d" muted="false"></video>
    </td>
        <td width=50% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/5fef5527-f938-4484-bf89-51361ff7ee17" muted="false"></video>
    </td>
</tr>
</table>


## &#x1F4E7; Acknowledgement
Our implementation is based on [Wanx](https://github.com/modelscope/DiffSynth-Studio), [CUT3R](https://github.com/CUT3R/CUT3R), and [CausVid](https://github.com/tianweiy/CausVid). Thanks for their remarkable contribution and released code! If we missed any open-source projects or related articles, we would like to complement the acknowledgement of this specific work immediately.

## &#x2696; License
This repository is released under the Apache-2.0 license as found in the [LICENSE](LICENSE) file.

## &#x1F4DA; Citation
If you find this codebase useful for your research, please use the following entry.
```BibTeX
@article{tu2025PlayerOne,
title={PlayerOne: Egocentric World Simulator},
author={Tu, Yuanpeng and Luo, Hao and Chen, Xi and Bai, Xiang and Wang, Fan and Zhao, Hengshuang},
journal={arXiv preprint},
year={2025}}
        

```
