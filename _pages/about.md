---
permalink: /
title: ""
excerpt: "Zhenchen Wan is a Ph.D. candidate at the University of Sydney working on high-fidelity virtual try-on and generative vision."
lang: en
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

I am a Ph.D. candidate at the [University of Sydney](https://www.sydney.edu.au/), supervised by [Prof. Tongliang Liu](https://tongliang-liu.github.io/index.html) and [Dr. Yu Yao](https://a5507203.github.io/), with [Prof. Mingming Gong](https://mingming-gong.github.io/) as my co-supervisor.

Before starting my Ph.D., I received a Master of Computer Science and a Bachelor of Science with a major in Computing and Software Systems from the [University of Melbourne](https://www.unimelb.edu.au/). My research focuses on computer vision and generative AI, particularly **high-fidelity virtual try-on**, transformer- and diffusion-based generative models, 3D vision, and efficient on-device generation.

I am open to academic collaboration. Please feel free to contact me at [flashwzc@gmail.com](mailto:flashwzc@gmail.com) or [zwan0681@uni.sydney.edu.au](mailto:zwan0681@uni.sydney.edu.au).


# 🔥 News

- *2026*: &nbsp;🎉 **Mobile-VTON** was accepted to CVPR 2026.
- *2025*: &nbsp;🎉 **MFT-VITON** was accepted to the ICCV 2025 HiGen Workshop.

# 📝 Publications

> \* indicates equal contribution.

## Peer-reviewed Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src="{{ '/images/teaser/2026Mobile-VTON.png' | relative_url }}" alt="Mobile-VTON method overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Mobile-VTON: High-Fidelity On-Device Virtual Try-On](https://arxiv.org/abs/2603.00947) \\
**_<u>Zhenchen Wan</u>_**\*, Ce Chen\*, Runqi Lin, Jiaxin Huang, Tianxi Chen, Yanwu Xu, Tongliang Liu, Mingming Gong

[**Project**](https://zhenchenwan.github.io/Mobile-VTON/) \| [**Paper**](https://arxiv.org/abs/2603.00947) \| [**GitHub**](https://github.com/tmllab/2026_CVPR_Mobile-VTON) \| [**Hugging Face**](https://huggingface.co/FlashStight/Mobile-VTON) \| [**Scholar**](https://scholar.google.com.au/citations?view_op=view_citation&hl=en&user=zKh-MAEAAAAJ&citation_for_view=zKh-MAEAAAAJ:UeHWp8X0CEIC)

- A privacy-preserving virtual try-on framework that runs fully offline on commodity mobile devices.
- Introduces a modular TeacherNet–GarmentNet–TryonNet architecture and feature-guided adversarial distillation for high-fidelity 1024×768 generation.
</div>
</div>


<div class='paper-box' style='border-bottom: none;'><div class='paper-box-image'><div><div class="badge">ICCVW 2025</div><img src="{{ '/images/teaser/2025MFT-VITON.png' | relative_url }}" alt="MFT-VITON mask-free virtual try-on results" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MFT-VITON: High-Fidelity Virtual Try-On with Minimal Input via a Mask-Free Transformer-Diffusion Model](https://openaccess.thecvf.com/content/ICCV2025W/HiGen/html/Wan_MFT-VITON_High-Fidelity_Virtual_Try-On_with_Minimal_Input_via_a_Mask-Free_ICCVW_2025_paper.html) \\
**_<u>Zhenchen Wan</u>_**, Yanwu Xu, Dongting Hu, Weilun Cheng, Tianxi Chen, Zhaoqing Wang, Feng Liu, Tongliang Liu, Mingming Gong

[**Project**](https://zhenchenwan.github.io/MF-VITON/) \| [**Paper**](https://openaccess.thecvf.com/content/ICCV2025W/HiGen/html/Wan_MFT-VITON_High-Fidelity_Virtual_Try-On_with_Minimal_Input_via_a_Mask-Free_ICCVW_2025_paper.html) \| [**GitHub**](https://github.com/ZhenchenWan/MF-VITON-High-Fidelity-Mask-Free-Virtual-Try-On-with-Minimal-Input) \| [**Scholar**](https://scholar.google.com.au/citations?view_op=view_citation&hl=en&user=zKh-MAEAAAAJ&citation_for_view=zKh-MAEAAAAJ:qjMakFHDy7sC)

- A mask-free transformer–diffusion framework that needs only a person image and a target garment.
- Improves garment semantics and text fidelity while avoiding artifacts caused by inaccurate user-provided masks.
</div>
</div>


## Preprints & Technical Reports

<div class='paper-box paper-box--text-only'>
<div class='paper-box-text' markdown="1">

<span class="paper-venue">Technical Report 2026</span>

[JuZhou 1.0 Technical Report: The First Edge-Native Text-to-Image Foundation Model Trained Entirely on China-Developed AI Accelerators](https://arxiv.org/abs/2606.28421) \\
Ce Chen, Congrui Wang, Yonglin Li, **_<u>Zhenchen Wan</u>_**, et al.

[**arXiv**](https://arxiv.org/abs/2606.28421) \| [**Scholar**](https://scholar.google.com.au/citations?view_op=view_citation&hl=en&user=zKh-MAEAAAAJ&citation_for_view=zKh-MAEAAAAJ:zYLM7Y9cAGgC)

- An edge-native text-to-image foundation model trained entirely on China-developed AI accelerators for fully offline generation.
- **My contributions:** 512×512-to-1024×1024 training, multi-resolution inference, and DMD2 acceleration that reduces sampling from 28 steps to 4.
</div>
</div>


<div class='paper-box paper-box--text-only'>
<div class='paper-box-text' markdown="1">

<span class="paper-venue">arXiv 2026</span>

[LightHarmony3D: Harmonizing Illumination and Shadows for Object Insertion in 3D Gaussian Splatting](https://arxiv.org/abs/2603.29209) \\
Tianyu Huang, Zhenyang Ren, **_<u>Zhenchen Wan</u>_**, Jiyang Zheng, Wenjie Wang, Runnan Chen, Mingming Gong, Tongliang Liu

[**arXiv**](https://arxiv.org/abs/2603.29209) \| [**GitHub**](https://github.com/TianyuHuang-000/LightHarmony3D) \| [**Scholar**](https://scholar.google.com.au/citations?view_op=view_citation&hl=en&user=zKh-MAEAAAAJ&citation_for_view=zKh-MAEAAAAJ:IjCSPb-OGe4C)

- Predicts a full 360° HDR environment map for illumination-consistent mesh insertion into 3D Gaussian Splatting scenes, with physically grounded shading and shadows.
</div>
</div>


<div class='paper-box paper-box--text-only'>
<div class='paper-box-text' markdown="1">

<span class="paper-venue">arXiv 2025</span>

[MF-VITON: High-Fidelity Mask-Free Virtual Try-On with Minimal Input](https://arxiv.org/abs/2503.08650) \\
**_<u>Zhenchen Wan</u>_**, Yanwu Xu, Dongting Hu, Weilun Cheng, Tianxi Chen, Zhaoqing Wang, Feng Liu, Tongliang Liu, Mingming Gong

[**Project**](https://zhenchenwan.github.io/MF-VITON/) \| [**arXiv**](https://arxiv.org/abs/2503.08650) \| [**GitHub**](https://github.com/ZhenchenWan/MF-VITON-High-Fidelity-Mask-Free-Virtual-Try-On-with-Minimal-Input) \| [**Scholar**](https://scholar.google.com.au/citations?view_op=view_citation&hl=en&user=zKh-MAEAAAAJ&citation_for_view=zKh-MAEAAAAJ:2osOgNQ5qMEC)

- A two-stage framework that adapts mask-based virtual try-on models to mask-free garment transfer using synthesized training data.
</div>
</div>


<div class='paper-box paper-box--text-only' style='border-bottom: none;'>
<div class='paper-box-text' markdown="1">

<span class="paper-venue">arXiv 2024</span>

[TED-VITON: Transformer-Empowered Diffusion Models for Virtual Try-On](https://arxiv.org/abs/2411.17017) \\
**_<u>Zhenchen Wan</u>_**, Yanwu Xu, Zhaoqing Wang, Feng Liu, Tongliang Liu, Mingming Gong

[**Project**](https://zhenchenwan.github.io/TED-VITON/) \| [**arXiv**](https://arxiv.org/abs/2411.17017) \| [**Scholar**](https://scholar.google.com.au/citations?view_op=view_citation&hl=en&user=zKh-MAEAAAAJ&citation_for_view=zKh-MAEAAAAJ:u5HHmVD_uO8C)

- Introduces a diffusion-transformer virtual try-on framework with a Garment Semantic Adapter, text-preservation loss, and LLM-guided semantic prompts.
</div>
</div>


# 🎓 Education

<div class='education-item'>
<div class='edu-logo'><img src="{{ '/images/usyd-logo.jpg' | relative_url }}" alt='University of Sydney'></div>
<div class='edu-text' markdown="1">
**Ph.D. Candidate** \\
[University of Sydney](https://www.sydney.edu.au/), Sydney, Australia \\
Supervisors: [Prof. Tongliang Liu](https://tongliang-liu.github.io/index.html) and [Dr. Yu Yao](https://a5507203.github.io/) \\
Co-supervisor: [Prof. Mingming Gong](https://mingming-gong.github.io/)
</div>
</div>

<div class='education-item'>
<div class='edu-logo'><img src="{{ '/images/unimelb-logo.png' | relative_url }}" alt='University of Melbourne'></div>
<div class='edu-text' markdown="1">
**Master of Computer Science** \\
[University of Melbourne](https://www.unimelb.edu.au/), Melbourne, Australia \\
Supervisor: [Prof. Mingming Gong](https://mingming-gong.github.io/)
</div>
</div>

<div class='education-item'>
<div class='edu-logo'><img src="{{ '/images/unimelb-logo.png' | relative_url }}" alt='University of Melbourne'></div>
<div class='edu-text' markdown="1">
**Bachelor of Science** \\
Major in Computing and Software Systems \\
[University of Melbourne](https://www.unimelb.edu.au/), Melbourne, Australia
</div>
</div>


# 💻 Experience

<div class='internship-item'>
<div class='intern-logo'><img src="{{ '/images/alibaba-logo.png' | relative_url }}" alt='Alibaba'></div>
<div class='intern-text' markdown="1">
**Research Intern** \\
[Alibaba Hujing Digital Media and Entertainment Group](https://www.alibabagroup.com/) (Youku) \\
Dec. 2025 – May 2026 \\
Supervisor: [Dr. Huan Fu](https://huan-fu.github.io/)
</div>
</div>

<div class='internship-item'>
<div class='intern-logo'><img src="{{ '/images/mbzuai-logo.png' | relative_url }}" alt='MBZUAI'></div>
<div class='intern-text' markdown="1">
**Research Engineer** \\
[Mohamed bin Zayed University of Artificial Intelligence (MBZUAI)](https://mbzuai.ac.ae/), Abu Dhabi, UAE \\
Mar. 2025 – Dec. 2025 \\
Supervisor: [Prof. Mingming Gong](https://mingming-gong.github.io/)
</div>
</div>
