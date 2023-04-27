## YOLO Air 3 : Makes improvements easy again

<div align="center">
  <p>
    <a align="center" href="https://github.com/iscyy/yoloair" target="_blank">
      <img width="850" src="https://img-blog.csdnimg.cn/11d5f1f403f74cff9c2f70a0c3b92de4.png"></a>
    <br><br>
  </p>
  <p>YOLOAir3是一个基于PyTorch的YOLO算法库的第三个版本。统一模型代码框架、统一应用、统一改进、易于模块组合、构建更强大的网络模型。</p>

  简体中文 | [English](./README_EN.md)

  ![](https://img.shields.io/badge/News-2022-red)  ![](https://img.shields.io/badge/Update-YOLOAir-orange) ![](https://visitor-badge.glitch.me/badge?page_id=iscyy.yoloair)  

  #### **支持**

![https://github.com/iscyy/yoloair](https://img.shields.io/badge/Support-YOLOv5-red) ![https://github.com/iscyy/yoloair](https://img.shields.io/badge/Support-YOLOv7-brightgreen) ![https://github.com/iscyy/yoloair](https://img.shields.io/badge/Support-YOLOv6-blueviolet) ![https://github.com/iscyy/yoloair](https://img.shields.io/badge/Support-YOLOX-yellow) ![https://github.com/iscyy/yoloair](https://img.shields.io/badge/Support-PPYOLOE-007d65) ![https://github.com/iscyy/yoloair](https://img.shields.io/badge/Support-YOLOv4-green) ![https://github.com/iscyy/yoloair](https://img.shields.io/badge/Support-TOOD-6a6da9) 
![https://github.com/iscyy/yoloair](https://img.shields.io/badge/Support-YOLOv3-yellowgreen) ![https://github.com/iscyy/yoloair](https://img.shields.io/badge/Support-YOLOR-lightgrey) ![https://github.com/iscyy/yoloair](https://img.shields.io/badge/Support-Scaled_YOLOv4-ff96b4) ![](https://img.shields.io/badge/Support-Transformer-9cf) ![https://github.com/iscyy/yoloair](https://img.shields.io/badge/Support-PPYOLO-lightgrey) ![https://github.com/iscyy/yoloair](https://img.shields.io/badge/Support-PPYOLOv2-yellowgreen) ![https://github.com/iscyy/yoloair](https://img.shields.io/badge/Support-PPYOLOEPlus-d5c59f) ![https://github.com/iscyy/yoloair](https://img.shields.io/badge/Support-MLP-ff69b4) ![https://github.com/iscyy/yoloair](https://img.shields.io/badge/Support-Attention-green)

[特性🚀](#主要特性) • [使用🍉](#使用) • [文档📒](https://github.com/iscyy/yoloair) • [报告问题🌟](https://github.com/iscyy/yoloair/issues/new) • [更新💪](#-to-do) • [讨论✌️](https://github.com/iscyy/yoloair/discussions)  


![https://github.com/iscyy/yoloair](https://img-blog.csdnimg.cn/f7045ecc4f90430cafc276540dddd702.gif#pic_center)

</div>

## Introduction

**模型多样化**: 基于不同网络模块构建不同检测网络模型。

**模块组件化**: 帮助用户自定义快速组合Backbone、Neck、Head，使得网络模型多样化，助力科研改进检测算法、模型改进，网络排列组合🏆。构建强大的网络模型。

**统一模型代码框架、统一应用方式、统一调参、统一改进、集成多任务、易于模块组合、构建更强大的网络模型**。

内置集成YOLOv8、YOLOv5、YOLOv7、YOLOv6、YOLOX、YOLOR、Transformer、PP-YOLO、PP-YOLOv2、PP-YOLOE、PP-YOLOEPlus、Scaled_YOLOv4、YOLOv3、YOLOv4、YOLO-Face、TPH-YOLO、YOLOv5Lite、SPD-YOLO、SlimNeck-YOLO、PicoDet等模型网络结构... 
集成多种检测算法 和 相关多任务模型 使用统一模型代码框架，**集成在 YOLOAir 库中，统一应用方式**。便于科研者用于论文算法模型改进，模型对比，实现网络组合多样化。包含轻量化模型和精度更高的模型，根据场景合理选择，在精度和速度俩个方面取得平衡。同时该库支持解耦不同的结构和模块组件，让模块组件化，通过组合不同的模块组件，用户可以根据不同数据集或不同业务场景自行定制化构建不同检测模型。

支持集成多任务，包括目标检测、实例分割、图像分类、姿态估计、人脸检测、目标跟踪等任务

<img src='https://img-blog.csdnimg.cn/1589c7f744004401b9d88132de35abe8.jpeg#pic_center' alt='ingishvcn'>
______________________________________________________________________

### 🌟 To Do

- 支持多任务, 包括 目标检测、分类、分割、姿态估计、人脸检测、目标跟踪 等任务
______________________________________________________________________

### 主要特性🚀

🚀支持更多的YOLO系列算法模型改进(持续更新...)

YOLOAir 算法库汇总了多种主流YOLO系列检测模型


🚀支持更多的网络模型组件
- 如表

<details open>
<div align="center">
  <b>YOLOAir Structural Module Components</b>
</div>
<table align="center">
  <tbody>
    <tr align="center" valign="bottom">
      <td>
        <b>Backbones</b>
      </td>
      <td>
        <b>Necks</b>
      </td>
      <td>
        <b>Head</b>
      </td>
    </tr>
    <tr valign="top">
      <td>
      <ul>
        <li>CSPDarkNet系列</li>
        <li>HorNet系列</li>
        <li>ResNet系列</li>
        <li>RegNet系列</li>
        <li>ShuffleNet系列</li>
        <li>RepLKNet系列</li>
        <li>MobileNet系列</li>
        <li>EfficientNet系列</li>
        <li>ConvNext系列</li>
        <li>Ghost系列</li>
        <li>RepVGG系列</li>
        <li>transformer系列</li>
      </ul>
      </td>
      <td>
      <ul>
        <li>PANet</li>
        <li>RepPAN</li>
        <li>BiFPN</li>
        <li>CSPPAN</li>
        <li>SlimNeck</li>
        <li>ELANPAN</li>
        <li>GSNeck</li>
      </ul>
      </td>
      <td>
        <ul>
          <li>YOLOv4Head</li>
          <li>YOLOv5Head</li>
          <li>YOLOv6 Efficient decoupled head </li>
          <li>YOLOv7 IDetect Head</li>
          <li>YOLOv7 IAuxDetect Head</li>
          <li>YOLOX DetectX Head</li>
          <li>自适应空间特征融合 检测头ASFF Head</li>
          <li>YOLOR 隐式学习 Head</li>
          <li>EH-Head</li>
          <li>Dual Weighting Head</li>
          <li>FCOS Head</li>
          <li>Dynamic Head</li>
          ...
        </ul>
      </td>
    </tr>
</td>
    </tr>
  </tbody>
</table>

</details>


<details open>
<div align="center">
  <b>YOLOAir Module Components</b>
</div>
<table align="center">
  <tbody>
    <tr align="center" valign="bottom">
      <td>
        <b>Attention注意力机制</b>
      </td>
      <td>
        <b>标签分配策略</b>
      </td>
      <td>
        <b>IoU损失函数</b>
      </td>
    </tr>
    <tr valign="top">
      <td>
      <ul>
        <li>Self Attention</li>
        <li>Contextual Transformer</li>
        <li>Bottleneck Transformer</li>
        <li>S2-MLP Attention</li>
        <li>AxialAttention</li>
        <li>DANet</li>
        <li>DoubleAttention</li>
        <li>GlobalContextBlock</li>
        <li>ParNetAttention</li>
        <li>PolarizedSelfAttention</li>
        <li>SpatialGroupEnhance copy</li>
        <li>TripletAttention</li>
        <li>SK Attention</li>
        <li>CBAM Attention</li>
        <li>SE Attention</li>
        <li>Coordinate attention</li>
        <li>NAM Attention</li>
        <li>GAM Attention</li>
        <li>ECA Attention</li>
        <li>Shuffle Attention</li>
        <li>CrissCrossAttention</li>
        <li>SOCAttention</li>
        <li>SimAM Attention</li>
        <li>CrissCrossAttention</li>
      </ul>
      </td>
      <td>
      <ul>
          <li>Multi Anchor策略</li>
          <li>YOLOv5 标签分配策略</li>
          <li>SimOTA 标签分配策略</li>
          <li>YOLOv7 标签分配策略</li>
          <li>FreeAnchor 标签分配策略</li>
          <li>AutoAssign 标签分配策略</li>
          <li>Dual Weighting 标签分配策略</li>
          <li>Probabilistic Anchor Assignment 锚分配策略</li>
          <li>其他改进的标签分配策略</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>CIoU</li>
          <li>DIoU</li>
          <li>GIoU</li>
          <li>EIoU</li>
          <li>SIoU</li>
          <li>alpha IOU</li>      
          ...
        </ul>
      </td>
    </tr>
</td>
    </tr>
  </tbody>
</table>

</details>


<details open>
<div align="center">
  <b>Module Components</b>
</div>
<table align="center">
  <tbody>
    <tr align="center" valign="bottom">
      <td>
        <b>Loss</b>
      </td>
      <td>
        <b>NMS</b>
      </td>
      <td>
        <b>数据增强</b>
      </td>
    </tr>
    <tr valign="top">
      <td>
      <ul>
        <li>ComputeLoss(v3)</li>
        <li>ComputeLoss(v4)</li>
        <li>ComputeLoss(v5)</li>
        <li>ComputeLoss(v6)</li>
        <li>ComputeLoss(X)</li>
        <li>ComputeLossAuxOTA(v7)</li>
        <li>ComputeLossOTA(v7)</li>
      </ul>
      </td>
      <td>
      <ul>
        <li>NMS</li>
        <li>Merge-NMS</li>
        <li>Soft-NMS</li>
        <li>CIoU_NMS</li>
        <li>DIoU_NMS</li>
        <li>GIoU_NMS</li>
        <li>EIoU_NMS</li>
        <li>SIoU_NMS</li>
        <li>Soft-SIoUNMS</li>
        <li>Soft-CIoUNMS</li>
        <li>Soft-DIoUNMS</li>
        <li>Soft-EIoUNMS</li>
        <li>Soft-GIoUNMS</li>
        <li>SimSPPF</li>
        <li>SimSPPF</li>
        <li>SimSPPF</li>  
      </ul>
      </td>
      <td>
        <ul>
          <li>Mosaic</li>
          <li>Copy paste</li>
          <li>Random affine(Rotation, Scale, Translation and Shear)</li>
          <li>MixUp</li>
          <li>HSV</li>
          <li>Random horizontal flip</li> 
          ...
        </ul>
      </td>
    </tr>
</td>
    </tr>
  </tbody>
</table>

</details>


<details open>
<div align="center">
  <b>YOLOAir Module Components</b>
</div>
<table align="center">
  <tbody>
    <tr align="center" valign="bottom">
      <td>
        <b>空间金字塔池化结构</b>
      </td>
      <td>
        <b>模块化组件</b>
      </td>
      <td>
        <b>AnchorBased / AnchorFree</b>
      </td>
    </tr>
    <tr valign="top">
      <td>
        <ul>
        <li>SPP</li>
        <li>SPPF</li>
        <li>ASPP</li>
        <li>RFB</li>
        <li>SPPCSPC</li>
        <li>SPPFCSPC</li>
        <li>SimSPPF</li>
      </ul>
      </td>
      <td>
        <ul>
          <li>Conv, GhostConv, Bottleneck, GhostBottleneck, SPP, SPPF, DWConv, MixConv2d, Focus, CrossConv,BottleneckCSP, C3, C3TR, C3SPP, C3Ghost, C3HB, C3RFEM, MultiSEAM, SEAM, C3STR, SPPCSPC, RepConv, BoT3, Air, CA, CBAM, Involution, Stem, ResCSPC, ResCSPB, ResXCSPB, ResXCSPC, BottleneckCSPB, BottleneckCSPC, ASPP, BasicRFB, SPPCSPC_group, HorBlock, CNeB,C3GC ,C3C2, nn.ConvTranspose2d, DWConvblock, RepVGGBlock, CoT3, ConvNextBlock, SPPCSP, BottleneckCSP2, DownC, BottleneckCSPF, RepVGGBlock, ReOrg, DWT, MobileOne,HorNet...</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>YOLOv5、YOLOv7、YOLOv3、YOLOv4、YOLOR、ScaledYOLOv4、PPYOLO、PPYOLOv2、Improved-YOLOv5、Improved-YOLOv7</li> 
          <li>YOLOX、YOLOv6 (Paper)、PPYOLOE、PPYOLOE+</li>
          ...
        </ul>
      </td>
    </tr>
</td>
    </tr>
  </tbody>
</table>
</details>


<details>

🚀支持更多Backbone

-  CSPDarkNet系列   
-  HorNet系列  
-  ResNet系列  
-  RegNet 系列  
-  ShuffleNet系列  
-  Ghost系列  
-  MobileNet系列  
-  EfficientNet系列  
-  ConvNext系列  
-  RepLKNet系列  
-  重参数化系列  
-  RepVGG系列  
-  RepMLP系列  
-  ACNet系列
-  RepConv系列  
-  OREPA系列
-  Mobileone系列  
-  自注意力Transformer系列  
-  MobileViT系列
-  BoTNet-Transfomrer  
-  CoTNet-Transfomrer  
-  Swin-Transfomrer  
-  Swin-Transfomrer(v2)  
-  以及其他trans系列
持续更新中🎈🚀🚀🚀
注: (YOLOAir(Beta)🔥 已经完成更新 20+ 种Transformer系列主干网络、多种MLP网络 以及 绝大部分重参数化结构模型网络)

🚀支持更多Neck
- FPN  
- PANet  
- RepPAN
- BiFPN
- CSPPAN
- SlimNeck
- ELANPAN  
 持续更新中🎈

🚀支持更多检测头Head  
-  YOLOv4、YOLOv5 Head检测头;
-  YOLOR 隐式学习Head检测头;
-  YOLOX的解耦合检测头Decoupled Head、DetectX Head;
-  自适应空间特征融合 检测头ASFF Head;
-  YOLOv6-v2.0 Efficient decoupled head;
-  YOLOv7检测头IAuxDetect Head, IDetect Head等;

-  其他不同检测头

🚀支持更多即插即用的注意力机制Attention
- 在网络任何部分即插即用式使用注意力机制
- Self Attention  
- Contextual Transformer  
- Bottleneck Transformer  
- S2-MLP Attention  
- SK Attention  
- CBAM Attention  
- SE Attention  
- Coordinate attention  
- NAM Attention  
- GAM Attention  
- ECA Attention  
- Shuffle Attention  
- CrissCrossAttention  
- Coordinate attention  
- SOCAttention  
- SimAM Attention 
持续更新中🎈  

- 🔥🔥🔥 重磅！！！作为开源项目补充，推荐一个注意力算法代码库[External-Attention](https://github.com/xmu-xiaoma666/External-Attention-pytorch)，里面汇总整理很全面，包含各种Attention等代码，代码简洁易读，一行代码实现Attention机制。

🚀更多空间金字塔池化结构  
- SPP
- SPPF
- ASPP
- RFB
- SPPCSPC  
- SPPFCSPC  
- SimSPPF
持续更新中🎈    

🚀支持更多Loss   
- ComputeLoss  
- ComputeLoss(v5)  
- ComputeLoss(v6)  
- ComputeLoss(X)  
- ComputeLossAuxOTA(v7)  
- ComputeLossOTA(v7)  
- ComputeNWDLoss  
- 其他Loss

🚀支持 Anchor-base 和 Anchor-Free  

- 🌟 YOLOv5、YOLOv7、YOLOv3、YOLOv4、YOLOR、ScaledYOLOv4、PPYOLO、PPYOLOv2、Improved-YOLOv5、Improved-YOLOv7

- 🌟 YOLOX、YOLOv6 (Paper)、PPYOLOE、PPYOLOE+

🚀支持多种标签分配策略  
- Multi Anchor策略
- YOLOv5 标签分配策略
- SimOTA 标签分配策略
- YOLOv7 标签分配策略
- AutoAssign 标签分配策略🌟
- Dual Weighting 标签分配策略🌟
- FreeAnchor 标签分配策略🌟
- 其他改进的标签分配策略
持续更新中🎈  

🚀支持加权框融合(WBF)  

🚀 内置多种网络模型模块化组件  
Conv, GhostConv, Bottleneck, GhostBottleneck, SPP, SPPF, DWConv, MixConv2d, Focus, CrossConv,BottleneckCSP, C3, C3TR, C3SPP, C3Ghost, C3HB, C3RFEM, MultiSEAM, SEAM, C3STR, SPPCSPC, RepConv, BoT3, Air, CA, CBAM, Involution, Stem, ResCSPC, ResCSPB, ResXCSPB, ResXCSPC, BottleneckCSPB, BottleneckCSPC, ASPP, BasicRFB, SPPCSPC_group, HorBlock, CNeB,C3GC ,C3C2, nn.ConvTranspose2d, DWConvblock, RepVGGBlock, CoT3, ConvNextBlock, SPPCSP, BottleneckCSP2, DownC, BottleneckCSPF, RepVGGBlock, ReOrg, DWT, MobileOne,HorNet...等详细代码 **./models/common.py文件** 内  

🚀支持更多IoU损失函数  
- CIoU  
- DIoU  
- GIoU  
- EIoU  
- SIoU  
- alpha IOU  
持续更新中🎈    

🚀支持更多NMS  
- NMS  
- Merge-NMS  
- Soft-NMS  
- CIoU_NMS  
- DIoU_NMS  
- GIoU_NMS  
- EIoU_NMS  
- SIoU_NMS  
- Soft-SIoUNMS、Soft-CIoUNMS、Soft-DIoUNMS、Soft-EIoUNMS、Soft-GIoUNMS等;    
持续更新中🎈    

🚀支持更多数据增强  
- Mosaic、Copy paste、Random affine(Rotation, Scale, Translation and Shear)、MixUp、Augment HSV(Hue, Saturation, Value、Random horizontal flip  

</details>

🚀支持加载YOLOv3、YOLOv4、YOLOv5、YOLOv7、YOLOR、Scaled_YOLO等网络的官方预训练权重进行迁移学习

🚀 YOLO系列网络模型热力图可视化(GardCAM、GardCAM++等)
支持YOLOv3、、YOLOv3-SPP、YOLOv4、YOLOv5、YOLOR、YOLOv7Scaled_YOLOv4、TPH-YOLO、SPD-YOLO以及自定义网络模型等模型 (YOLOAir(Beta版本内测)🔥已支持) 

以上组件模块使用统一模型代码框架、统一任务形式、统一应用方式，**模块组件化**🚀 可以帮助用户自定义快速组合Backbone、Neck、Head，使得网络模型多样化，助力科研改进检测算法，构建更强大的网络模型。

说明: 以上主要特性支持 包括 Main版本 和 Beta版本，部分特性暂时只完成更新在 Beta 中，不是所有更新都直接在 Main 中，后续 Beta 版本内测之后逐渐加入到 Main版本中。

______________________________________________________________________

### 内置网络模型配置支持✨

______________________________________________________________________

### 效果预览🚀

|目标检测|目标分割|
:-------------------------:|:-------------------------:
<img src='https://img-blog.csdnimg.cn/0b04579f80d145d7bd2e854753e9f367.jpeg' width='300px' height='180px'  alt='ingishvcn'>  |  <img src='https://img-blog.csdnimg.cn/adb10e3c47e440f9acf4a183df9acf05.jpeg#pic_center' width='300px' height='180px'  alt='ingishvcn'>

|图像分类|实例分割|
:-------------------------:|:-------------------------:
<img src='https://img-blog.csdnimg.cn/b1ca7795b70c4b6086b5e6b43b687c1b.jpeg#pic_center' width='300px' height='180px'  alt='ingishvcn'>  |  <img src='https://img-blog.csdnimg.cn/d29f6d6fa0624c5cacf107bd5d1a5fa2.jpeg#pic_center' width='300px' height='180px'  alt='ingishvcn'>

|目标分割|目标跟踪|
:-------------------------:|:-------------------------:
<img src='https://img-blog.csdnimg.cn/0ce7c7584f2149c980d7e292fc1fcd24.jpeg#pic_center' width='300px' height='180px'  alt='ingishvcn'>  |  <img src='https://img-blog.csdnimg.cn/d9ae8953fb394a74a6b1096a401fc315.jpeg#pic_center' width='300px' height='180px'  alt='ingishvcn'>

|姿态估计|人脸检测|
:-------------------------:|:-------------------------:
<img src='https://img-blog.csdnimg.cn/01f41103dc6c416aaeeb4577b87bb363.gif#pic_center' width='300px' height='260px' alt='ingishvcn'>  |  <img src='https://img-blog.csdnimg.cn/d18a095621b64da69d2a712fa5613976.gif#pic_center' width='300px' height='260px'   alt='ingishvcn'>

|热力图01|热力图02|
:-------------------------:|:-------------------------:
<img src='https://img-blog.csdnimg.cn/eef8f911702242a5bb3e10a2e3188ca6.jpeg#pic_center' width='300px' height='180px' alt='ingishvcn'>  |  <img src='https://img-blog.csdnimg.cn/a22986632c25462cbe6abddc75a01ca5.jpeg#pic_center' width='300px' height='180px'   alt='ingishvcn'>


![yolo](https://img-blog.csdnimg.cn/b962fcd1bfa841399226ca564f22a385.gif#pic_center)
### 预训练权重🚀

- YOLOv5
https://github.com/ultralytics/yolov5/releases/tag/v6.1

- YOLOv4
https://github.com/iscyy/yoloair/releases/tag/v1.0

- YOLOv3
https://github.com/iscyy/yoloair/releases/tag/v1.0

- YOLOR
https://github.com/iscyy/yoloair/releases/tag/v1.0

- Scaled_YOLO
https://github.com/iscyy/yoloair/releases/tag/v1.0

- YOLOv7
https://github.com/iscyy/yoloair/releases/tag/v1.0

______________________________________________________________________

## 使用🍉

**About the code.** Follow the design principle of [YOLOv5](https://github.com/ultralytics/yolov5).  
The original version was created based on YOLOv5(v6.1)

### 安装

在**Python>=3.7.0** 的环境中克隆版本仓并安装 requirements.txt，包括**PyTorch>=1.7**。

```bash
$ git clone https://github.com/iscyy/yoloair.git  # 克隆
$ cd YOLOAir
$ pip install -r requirements.txt  # 安装
```

### 训练

```bash
$ python train.py --data coco128.yaml --cfg configs/yolov5/yolov5s.yaml #默认为yolo
```

### 推理

`detect.py` 在各种数据源上运行推理, 并将检测结果保存到 `runs/detect` 目录。

```bash
$ python detect.py --source 0  # 网络摄像头
                          img.jpg  # 图像
                          vid.mp4  # 视频
                          path/  # 文件夹
                          path/*.jpg  # glob
```

### 融合
如果您使用不同模型来推理数据集，则可以使用 wbf.py文件 通过加权框融合来集成结果。
您只需要在 wbf.py文件 中设置 img 路径和 txt 路径。
```bash
$ python wbf.py
```
______________________________________________________________________


### 未来增强✨
后续会持续建设和完善 YOLOAir 生态  
完善集成更多 YOLO 系列模型，持续结合不同模块，构建更多不同网络模型  
横向拓展和引入关联技术等等   

______________________________________________________________________

## Citation✨

```python
@article{2023yoloair3,
  title={{YOLOAir3}: Makes improvements easy again},
  author={iscyy},
  repo={github https://github.com/iscyy/yoloair3},
  year={2023}
}
```

## Statement
<details><summary> <b>Expand</b> </summary>

* The content of this site is only for sharing notes. If some content is infringing, please sending email.

* If you have any question, please discuss with me by sending email.
</details>

## Acknowledgements

<details><summary> <b>Expand</b> </summary>

[https://github.com/ultralytics/ultralytics](https://github.com/ultralytics/ultralytics)  
[https://github.com/iscyy/yoloair](https://github.com/iscyy/yoloair)

</details>
