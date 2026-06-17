---
permalink: /
author_profile: true
title: "Hi there, I'am Muyi Bao(包沐亦)"
redirect_from: 
  - /about/
  - /about.html
---


I am currently an M.S. student in Electrical and Computer Engineering at Carnegie Mellon University. My research interests lie in Embodied AI and multimodal foundation models for robotics. I am particularly interested in building vision-language agents that can perceive, reason, and act in embodied environments. At CMU, I am working with Dr. [Ji Zhang](https://frc.ri.cmu.edu/~zhangji/) and Dr. [Wenshan Wang](http://www.wangwenshan.com/) on Embodied AI, with a focus on Vision-and-Language Navigation using vision-language models. Before joining CMU, I received my B.Eng. degree in Computer Science and Technology from Xi'an Jiaotong-Liverpool University in 2025. During my undergraduate studies, I focused on computer vision and was fortunate to work with Prof. [Guangliang Cheng](https://sites.google.com/view/guangliangcheng/homepage), Prof. [Wei Wang](https://scholar.xjtlu.edu.cn/en/persons/WeiWang03), and Prof. [Ming Xu](https://scholar.xjtlu.edu.cn/en/persons/MingXu).

My resume can be found [here](https://github.com/BaoBao0926/BaoBao0926.github.io/blob/master/assets/Muyi%20Bao%20CV.pdf) (updated in 2025.08.10) and My email is [muyib@andrew.cmu.edu](mailto:muyib@andrew.cmu.edu).


<p style="color:red;">
I am actively looking for Ph.D. opportunities starting in Fall 2027, with research interests in Embodied AI and multimodal foundation models for robotics.
</p>



## News

<ul style="font-size: 0.9em; line-height: 1.45; margin-top: 0;">
  <li><strong>[Jun. 2026]</strong> One paper, <a href="https://baobao0926.github.io/Goal2Pixel/">Goal2Pixel</a>, was submitted into CoRL2026.</li>
  <li><strong>[Feb. 2026]</strong> Our survey paper, <a href="https://github.com/BaoBao0926/Awesome-Mamba-in-Remote-Sensing/tree/main">Vision Mamba in Remote Sensing</a>, was accepted by <em>Remote Sensing</em>.</li>
  <li><strong>[Aug. 2025]</strong> I joined Carnegie Mellon University as an M.S. student in Electrical and Computer Engineering.</li>
  <li><strong>[Jul. 2025]</strong> <a href="https://github.com/BaoBao0926/FTCFormer/tree/main">FTCFormer</a> was accepted by ECAI 2025, the European Conference on Artificial Intelligence.</li>
  <li><strong>[Jun. 2025]</strong> I received my B.Eng. degree in Computer Science and Technology from Xi'an Jiaotong-Liverpool University.</li>
  <li><strong>[Feb. 2025]</strong> My first paper, <a href="https://github.com/BaoBao0926/AlexCapsNet">AlexCapsNet</a>, was accepted by <em>IEEE Access</em>.</li>
  <li><strong>[Dec. 2024]</strong> One paper on <a href="https://github.com/BaoBao0926/Comparative-Performance-Analysis-of-Rendering-Optimization-Method">Performance Analysis of Rendering optimization on Game Engine</a> was accepted by UIC 2024, IEEE International Conference on Ubiquitous Intelligence and Computing.</li>
</ul>

<style>
  .research-table {
    width: 100%;
    border: 0 !important;
    border-spacing: 0;
    border-collapse: separate !important;
    margin: 0 auto 1em;
    font-size: 0.95em;
  }

  .research-table tr,
  .research-table td {
    border: 0 !important;
    background: transparent !important;
  }

  .research-image-cell {
    width: 44%;
    padding: 16px 20px 24px 0;
    vertical-align: middle;
  }

  .research-text-cell {
    width: 56%;
    padding: 16px 0 24px 8px;
    vertical-align: middle;
  }

  .research-image {
    display: block;
    width: 100%;
    height: auto;
    max-height: 260px;
    object-fit: contain;
    border-radius: 4px;
  }

  .research-title {
    font-size: 1.05em;
    line-height: 1.25;
    font-weight: 700;
  }

  .research-authors {
    margin-top: 5px;
    line-height: 1.4;
  }

  .research-venue {
    margin-top: 5px;
    line-height: 1.4;
  }

  .research-description {
    margin-top: 12px;
    margin-bottom: 8px;
    line-height: 1.45;
  }

  .research-links {
    margin-top: 6px;
  }

  @media screen and (max-width: 768px) {
    .research-table,
    .research-table tbody,
    .research-table tr,
    .research-table td {
      display: block;
      width: 100%;
    }

    .research-image-cell {
      padding: 18px 0 8px 0;
    }

    .research-text-cell {
      padding: 6px 0 24px 0;
    }

    .research-image {
      max-height: none;
    }
  }
</style>

<h2>Research Projects</h2>

<table class="research-table">
  <tbody>

    <!-- Goal2Pixel -->
    <tr>
      <td class="research-image-cell">
        <img
          class="research-image"
          src="https://github.com/BaoBao0926/Goal2Pixel/raw/website/resources/images/pipeline.jpg"
          alt="Goal2Pixel framework"
        />
      </td>

      <td class="research-text-cell">
        <a href="https://baobao0926.github.io/Goal2Pixel/">
          <span class="research-title">
            Goal2Pixel: Grounding Goals to Pixels for Vision-Language Navigation
          </span>
        </a>

        <div class="research-authors">
          <strong>Muyi Bao</strong><sup>*</sup>,
          Yuxin Cai<sup>*</sup>,
          Hang Xu,
          Zongtai Li,
          Jinxi He,
          Jingfan Tang,
          Chen Lv,
          Ji Zhang,
          Yaqi Xie,
          Wenshan Wang
        </div>

        <div>
          <small><sup>*</sup> Equal contribution</small>
        </div>

        <div class="research-venue">
          <em>arXiv, 2026</em>
        </div>

        <p class="research-description">
          Goal2Pixel first reformulates Vision-and-Language Navigation in Continuous Environments (VLN-CE) as pure navigable pixel grounding. The model predicts a visible pixel in the current observation and back-projects it into a 3D waypoint for low-level navigation, providing a unified spatial interface between
          vision-language reasoning and robot motion.
        </p>

        <div class="research-links">
          <a href="https://baobao0926.github.io/Goal2Pixel/">Project Page</a>
          &nbsp;/&nbsp;
          <a href="https://arxiv.org/abs/2606.01621">Paper</a>
          &nbsp;/&nbsp;
          <a href="https://github.com/BaoBao0926/Goal2Pixel">Code</a>
        </div>
      </td>
    </tr>

    <!-- Vision Mamba Survey -->
    <tr>
      <td class="research-image-cell">
        <img
          class="research-image"
          src="https://raw.githubusercontent.com/BaoBao0926/Awesome-Mamba-in-Remote-Sensing/main/Assets/outline.png"
          alt="Vision Mamba in Remote Sensing survey"
        />
      </td>

      <td class="research-text-cell">
        <a href="https://arxiv.org/abs/2505.00630">
          <span class="research-title">
            Vision Mamba in Remote Sensing: A Comprehensive Survey of Techniques,
            Applications and Outlook
          </span>
        </a>

        <div class="research-authors">
          <strong>Muyi Bao</strong>,
          Shuchang Lyu,
          Zhaoyang Xu,
          Huiyu Zhou,
          Jinchang Ren,
          Shiming Xiang,
          Xiangtai Li,
          Guangliang Cheng
        </div>

        <div class="research-venue">
          <em>Remote Sensing, 2026</em>
        </div>

        <p class="research-description">
          This work presents a comprehensive survey of Vision Mamba models for
          remote sensing. It reviews their architectural foundations, application
          areas, representative methods, current limitations, and future research
          directions.
        </p>

        <div class="research-links">
          <a href="https://arxiv.org/abs/2505.00630">Paper</a>
          &nbsp;/&nbsp;
          <a href="https://github.com/BaoBao0926/Awesome-Mamba-in-Remote-Sensing">
            Repository
          </a>
        </div>
      </td>
    </tr>

    <!-- FTCFormer -->
    <tr>
      <td class="research-image-cell">
        <img
          class="research-image"
          src="https://raw.githubusercontent.com/BaoBao0926/FTCFormer/main/Assets/architecture.png"
          alt="FTCFormer architecture"
        />
      </td>

      <td class="research-text-cell">
        <a href="https://arxiv.org/abs/2507.10283">
          <span class="research-title">
            FTCFormer: Fuzzy Token Clustering Transformer for Image Classification
          </span>
        </a>

        <div class="research-authors">
          <strong>Muyi Bao</strong>,
          Changyu Zeng,
          Yifan Wang,
          Zhengni Yang,
          Zimu Wang,
          Guangliang Cheng,
          Jun Qi,
          Wei Wang
        </div>

        <div class="research-venue">
          <em>European Conference on Artificial Intelligence (ECAI), 2025</em>
        </div>

        <p class="research-description">
          FTCFormer introduces fuzzy token clustering as a content-adaptive
          downsampling mechanism for vision transformers. Instead of relying on
          fixed grid-based operations such as pooling, it groups visually related
          tokens to preserve informative image structures during hierarchical
          feature extraction.
        </p>

        <div class="research-links">
          <a href="https://arxiv.org/abs/2507.10283">Paper</a>
          &nbsp;/&nbsp;
          <a href="https://github.com/BaoBao0926/FTCFormer">Code</a>
        </div>
      </td>
    </tr>

    <!-- ASP-VMUNet -->
    <tr>
      <td class="research-image-cell">
        <img
          class="research-image"
          src="https://raw.githubusercontent.com/BaoBao0926/ASP-VMUNet/main/figure/ASPVMUnet.png"
          alt="ASP-VMUNet architecture"
        />
      </td>

      <td class="research-text-cell">
        <a href="https://arxiv.org/abs/2503.19427">
          <span class="research-title">
            ASP-VMUNet: Atrous Shifted Parallel Vision Mamba U-Net for Skin Lesion
            Segmentation
          </span>
        </a>

        <div class="research-authors">
          <strong>Muyi Bao</strong>,
          Shuchang Lyu,
          Zhaoyang Xu,
          Qi Zhao,
          Changyu Zeng,
          Wenpei Bai,
          Guangliang Cheng
        </div>

        <div class="research-venue">
          <em>arXiv, 2025</em>
        </div>

        <p class="research-description">
          ASP-VMUNet is a hybrid Mamba–CNN architecture for skin lesion
          segmentation. It combines long-range visual modeling with local
          convolutional features and multi-scale context aggregation for accurate
          medical image segmentation.
        </p>

        <div class="research-links">
          <a href="https://arxiv.org/abs/2503.19427">Paper</a>
          &nbsp;/&nbsp;
          <a href="https://github.com/BaoBao0926/ASP-VMUNet">Code</a>
        </div>
      </td>
    </tr>

    <!-- Rendering Optimization -->
    <tr>
      <td class="research-image-cell">
        <img
          class="research-image"
          src="https://raw.githubusercontent.com/BaoBao0926/Comparative-Performance-Analysis-of-Rendering-Optimization-Method/main/figure/show.png"
          alt="Rendering optimization comparison"
        />
      </td>

      <td class="research-text-cell">
        <a href="https://ieeexplore.ieee.org/abstract/document/10925167">
          <span class="research-title">
            Comparative Performance Analysis of Rendering Optimization Methods in
            Unity Tuanjie Engine, Unity Global and Unreal Engine
          </span>
        </a>

        <div class="research-authors">
          <strong>Muyi Bao</strong>,
          Zeren Tao,
          Xiaohan Wang,
          Jiashuo Liu,
          Qilei Sun
        </div>

        <div class="research-venue">
          <em>
            IEEE International Conference on Ubiquitous Intelligence and Computing
            (UIC), 2024
          </em>
        </div>

        <p class="research-description">
          This work compares modern rendering optimization techniques across
          multiple game engines, including Level of Detail in Unity, Virtual
          Geometry in the Tuanjie Engine, and Nanite in Unreal Engine.
        </p>

        <div class="research-links">
          <a href="https://ieeexplore.ieee.org/abstract/document/10925167">
            Paper
          </a>
          &nbsp;/&nbsp;
          <a href="https://github.com/BaoBao0926/Comparative-Performance-Analysis-of-Rendering-Optimization-Method">
            Repository
          </a>
        </div>
      </td>
    </tr>

    <!-- AlexCapsNet -->
    <tr>
      <td class="research-image-cell">
        <img
          class="research-image"
          src="https://raw.githubusercontent.com/BaoBao0926/AlexCapsNet/main/figure/show1.png"
          alt="AlexCapsNet architecture"
        />
      </td>

      <td class="research-text-cell">
        <a href="https://ieeexplore.ieee.org/abstract/document/10900363">
          <span class="research-title">
            AlexCapsNet: An Integrated Architecture for Image Classification with
            Background Noise
          </span>
        </a>

        <div class="research-authors">
          <strong>Muyi Bao</strong>,
          Ming Xu,
          Nanlin Jin
        </div>

        <div class="research-venue">
          <em>IEEE Access, 2025</em>
        </div>

        <p class="research-description">
          AlexCapsNet integrates convolutional feature extraction with capsule
          networks for robust image classification. The model is designed to
          improve recognition performance when images contain complex or noisy
          backgrounds.
        </p>

        <div class="research-links">
          <a href="https://ieeexplore.ieee.org/abstract/document/10900363">
            Paper
          </a>
          &nbsp;/&nbsp;
          <a href="https://github.com/BaoBao0926/AlexCapsNet">Code</a>
        </div>
      </td>
    </tr>

  </tbody>
</table>
