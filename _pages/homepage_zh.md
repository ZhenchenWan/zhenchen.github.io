---
permalink: /zh-cn/
title: ""
excerpt: "Zhenchen Wan 是悉尼大学博士候选人，主要研究高保真虚拟试穿与生成式视觉。"
lang: zh-CN
layout: default_zh
author_profile: true
redirect_from:
  - /zh/
---

<span class='anchor' id='about-me'></span>

我目前是[悉尼大学](https://www.sydney.edu.au/)博士候选人，导师为 [Prof. Tongliang Liu](https://tongliang-liu.github.io/index.html) 和 [Dr. Yu Yao](https://a5507203.github.io/)，并由 [Prof. Mingming Gong](https://mingming-gong.github.io/) 联合指导。

在攻读博士学位之前，我于[墨尔本大学](https://www.unimelb.edu.au/)获得计算机科学硕士学位，以及计算机与软件系统专业理学学士学位。我的研究方向为计算机视觉与生成式人工智能，尤其关注**高保真虚拟试穿**、基于 Transformer 与扩散模型的图像生成、三维视觉，以及高效端侧生成。

欢迎通过 [flashwzc@gmail.com](mailto:flashwzc@gmail.com) 或 [zwan0681@uni.sydney.edu.au](mailto:zwan0681@uni.sydney.edu.au) 与我联系，探讨学术合作。


<span class='anchor' id='-新闻'></span>
# 🔥 新闻

- *2026*: &nbsp;🎉 **Mobile-VTON** 被 CVPR 2026 接收。
- *2025*: &nbsp;🎉 **MFT-VITON** 被 ICCV 2025 HiGen Workshop 接收。


<span class='anchor' id='-论文发表'></span>
# 📝 论文发表

> \* 表示同等贡献。

## 同行评审论文

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src="{{ '/images/teaser/2026Mobile-VTON.png' | relative_url }}" alt="Mobile-VTON 方法概览" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Mobile-VTON: High-Fidelity On-Device Virtual Try-On](https://arxiv.org/abs/2603.00947) \\
**_<u>Zhenchen Wan</u>_**\*, Ce Chen\*, Runqi Lin, Jiaxin Huang, Tianxi Chen, Yanwu Xu, Tongliang Liu, Mingming Gong

[**项目主页**](https://zhenchenwan.github.io/Mobile-VTON/) \| [**论文**](https://arxiv.org/abs/2603.00947) \| [**GitHub**](https://github.com/tmllab/2026_CVPR_Mobile-VTON) \| [**Hugging Face**](https://huggingface.co/FlashStight/Mobile-VTON) \| [**Scholar**](https://scholar.google.com.au/citations?view_op=view_citation&hl=en&user=zKh-MAEAAAAJ&citation_for_view=zKh-MAEAAAAJ:UeHWp8X0CEIC)

- 一个保护隐私的虚拟试穿框架，可在普通移动设备上完全离线运行。
- 提出模块化 TeacherNet–GarmentNet–TryonNet 架构和特征引导对抗蒸馏，实现高保真的 1024×768 图像生成。
</div>
</div>


<div class='paper-box' style='border-bottom: none;'><div class='paper-box-image'><div><div class="badge">ICCVW 2025</div><img src="{{ '/images/teaser/2025MFT-VITON.png' | relative_url }}" alt="MFT-VITON 无掩码虚拟试穿结果" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MFT-VITON: High-Fidelity Virtual Try-On with Minimal Input via a Mask-Free Transformer-Diffusion Model](https://openaccess.thecvf.com/content/ICCV2025W/HiGen/html/Wan_MFT-VITON_High-Fidelity_Virtual_Try-On_with_Minimal_Input_via_a_Mask-Free_ICCVW_2025_paper.html) \\
**_<u>Zhenchen Wan</u>_**, Yanwu Xu, Dongting Hu, Weilun Cheng, Tianxi Chen, Zhaoqing Wang, Feng Liu, Tongliang Liu, Mingming Gong

[**项目主页**](https://zhenchenwan.github.io/MF-VITON/) \| [**论文**](https://openaccess.thecvf.com/content/ICCV2025W/HiGen/html/Wan_MFT-VITON_High-Fidelity_Virtual_Try-On_with_Minimal_Input_via_a_Mask-Free_ICCVW_2025_paper.html) \| [**GitHub**](https://github.com/ZhenchenWan/MF-VITON-High-Fidelity-Mask-Free-Virtual-Try-On-with-Minimal-Input) \| [**Scholar**](https://scholar.google.com.au/citations?view_op=view_citation&hl=en&user=zKh-MAEAAAAJ&citation_for_view=zKh-MAEAAAAJ:qjMakFHDy7sC)

- 一个仅需人物图像和目标服装的无掩码 Transformer–Diffusion 虚拟试穿框架。
- 在避免不准确掩码所引发伪影的同时，提升服装语义表达和文字细节保真度。
</div>
</div>


## 预印本与技术报告

<div class='paper-box paper-box--text-only'>
<div class='paper-box-text' markdown="1">

<span class="paper-venue">技术报告 2026</span>

[JuZhou 1.0 Technical Report: The First Edge-Native Text-to-Image Foundation Model Trained Entirely on China-Developed AI Accelerators](https://arxiv.org/abs/2606.28421) \\
Ce Chen, Congrui Wang, Yonglin Li, **_<u>Zhenchen Wan</u>_**, et al.

[**arXiv**](https://arxiv.org/abs/2606.28421) \| [**Scholar**](https://scholar.google.com.au/citations?view_op=view_citation&hl=en&user=zKh-MAEAAAAJ&citation_for_view=zKh-MAEAAAAJ:zYLM7Y9cAGgC)

- 首个完全使用中国自主 AI 加速器训练、面向端侧全离线生成的轻量级文生图基础模型。
- **我的主要贡献：** 512×512 到 1024×1024 分辨率训练、多尺寸分辨率推理，以及将采样步数从 28 步减少到 4 步的 DMD2 加速。
</div>
</div>


<div class='paper-box paper-box--text-only'>
<div class='paper-box-text' markdown="1">

<span class="paper-venue">arXiv 2026</span>

[LightHarmony3D: Harmonizing Illumination and Shadows for Object Insertion in 3D Gaussian Splatting](https://arxiv.org/abs/2603.29209) \\
Tianyu Huang, Zhenyang Ren, **_<u>Zhenchen Wan</u>_**, Jiyang Zheng, Wenjie Wang, Runnan Chen, Mingming Gong, Tongliang Liu

[**arXiv**](https://arxiv.org/abs/2603.29209) \| [**GitHub**](https://github.com/TianyuHuang-000/LightHarmony3D) \| [**Scholar**](https://scholar.google.com.au/citations?view_op=view_citation&hl=en&user=zKh-MAEAAAAJ&citation_for_view=zKh-MAEAAAAJ:IjCSPb-OGe4C)

- 预测完整的 360° HDR 环境光照图，实现 3D Gaussian Splatting 场景中具有物理一致光照与阴影的网格物体插入。
</div>
</div>


<div class='paper-box paper-box--text-only'>
<div class='paper-box-text' markdown="1">

<span class="paper-venue">arXiv 2025</span>

[MF-VITON: High-Fidelity Mask-Free Virtual Try-On with Minimal Input](https://arxiv.org/abs/2503.08650) \\
**_<u>Zhenchen Wan</u>_**, Yanwu Xu, Dongting Hu, Weilun Cheng, Tianxi Chen, Zhaoqing Wang, Feng Liu, Tongliang Liu, Mingming Gong

[**项目主页**](https://zhenchenwan.github.io/MF-VITON/) \| [**arXiv**](https://arxiv.org/abs/2503.08650) \| [**GitHub**](https://github.com/ZhenchenWan/MF-VITON-High-Fidelity-Mask-Free-Virtual-Try-On-with-Minimal-Input) \| [**Scholar**](https://scholar.google.com.au/citations?view_op=view_citation&hl=en&user=zKh-MAEAAAAJ&citation_for_view=zKh-MAEAAAAJ:2osOgNQ5qMEC)

- 利用合成训练数据，将基于掩码的虚拟试穿模型适配为无掩码服装迁移模型的两阶段框架。
</div>
</div>


<div class='paper-box paper-box--text-only' style='border-bottom: none;'>
<div class='paper-box-text' markdown="1">

<span class="paper-venue">arXiv 2024</span>

[TED-VITON: Transformer-Empowered Diffusion Models for Virtual Try-On](https://arxiv.org/abs/2411.17017) \\
**_<u>Zhenchen Wan</u>_**, Yanwu Xu, Zhaoqing Wang, Feng Liu, Tongliang Liu, Mingming Gong

[**项目主页**](https://zhenchenwan.github.io/TED-VITON/) \| [**arXiv**](https://arxiv.org/abs/2411.17017) \| [**Scholar**](https://scholar.google.com.au/citations?view_op=view_citation&hl=en&user=zKh-MAEAAAAJ&citation_for_view=zKh-MAEAAAAJ:u5HHmVD_uO8C)

- 提出基于 Diffusion Transformer 的虚拟试穿框架，结合服装语义适配器、文字保真损失和 LLM 引导的语义提示。
</div>
</div>


<span class='anchor' id='-教育背景'></span>
# 🎓 教育背景

<div class='education-item'>
<div class='edu-logo'><img src="{{ '/images/usyd-logo.jpg' | relative_url }}" alt='悉尼大学'></div>
<div class='edu-text' markdown="1">
**博士候选人** \\
[悉尼大学](https://www.sydney.edu.au/)，澳大利亚悉尼 \\
导师：[Prof. Tongliang Liu](https://tongliang-liu.github.io/index.html) 和 [Dr. Yu Yao](https://a5507203.github.io/) \\
联合导师：[Prof. Mingming Gong](https://mingming-gong.github.io/)
</div>
</div>

<div class='education-item'>
<div class='edu-logo'><img src="{{ '/images/unimelb-logo.png' | relative_url }}" alt='墨尔本大学'></div>
<div class='edu-text' markdown="1">
**计算机科学硕士** \\
[墨尔本大学](https://www.unimelb.edu.au/)，澳大利亚墨尔本 \\
导师：[Prof. Mingming Gong](https://mingming-gong.github.io/)
</div>
</div>

<div class='education-item'>
<div class='edu-logo'><img src="{{ '/images/unimelb-logo.png' | relative_url }}" alt='墨尔本大学'></div>
<div class='edu-text' markdown="1">
**理学学士** \\
计算机与软件系统专业 \\
[墨尔本大学](https://www.unimelb.edu.au/)，澳大利亚墨尔本
</div>
</div>


<span class='anchor' id='-实习经历'></span>
# 💻 实习经历

<div class='internship-item'>
<div class='intern-logo'><img src="{{ '/images/alibaba-logo.png' | relative_url }}" alt='阿里巴巴'></div>
<div class='intern-text' markdown="1">
**研究实习生** \\
[阿里巴巴虎鲸文娱集团](https://www.alibabagroup.com/)（优酷） \\
2025年12月 – 2026年5月 \\
导师：[Dr. Huan Fu](https://huan-fu.github.io/)
</div>
</div>

<div class='internship-item'>
<div class='intern-logo'><img src="{{ '/images/mbzuai-logo.png' | relative_url }}" alt='MBZUAI'></div>
<div class='intern-text' markdown="1">
**研究工程师** \\
[穆罕默德·本·扎耶德人工智能大学 (MBZUAI)](https://mbzuai.ac.ae/)，阿联酋阿布扎比 \\
2025年3月 – 2025年12月 \\
导师：[Prof. Mingming Gong](https://mingming-gong.github.io/)
</div>
</div>
