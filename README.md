
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



<!-- <video controls loop src="https://cloud.video.taobao.com/vod/vs4L24EAm6IQ5zM3SbN5AyHCSqZIXwmuobrzqNztMRM.mp4" muted="false"></video> -->

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
    <td width=47% style="border: none">
        <video controls loop src="/assets/AblationStudy.mp4" muted="false"></video>
    </td>
    <td width=53% style="border: none">
        <video controls loop src="/assets/AblationStudy.mp4" muted="false"></video>
    </td>
</tr>
</table>



### Comparisons with previous works
<table class="center">
<tr>
    <td width=50% style="border: none">
        <video controls loop src="/assets/example1.mp4" muted="false"></video>
    </td>
        <td width=50% style="border: none">
        <video controls loop src="/assets/example2.mp4" muted="false"></video>
    </td>
</tr>
</table>

<table class="center">
<tr>
    <td width=50% style="border: none">
        <video controls loop src="/assets/example3.mp4" muted="false"></video>
    </td>
        <td width=50% style="border: none">
        <video controls loop src="/assets/example4.mp4" muted="false"></video>
    </td>
</tr>
</table>

<table class="center">
<tr>
    <td width=50% style="border: none">
        <video controls loop src="/assets/example5.mp4" muted="false"></video>
    </td>
        <td width=50% style="border: none">
        <video controls loop src="/assets/example6.mp4" muted="false"></video>
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
