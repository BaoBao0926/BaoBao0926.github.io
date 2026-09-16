---
permalink: /
author_profile: true
title: "Hi there, I'am Muyi Bao(包沐亦)"
redirect_from: 
  - /about/
  - /about.html
---


<div class="about-intro" markdown="1">

I am currently an M.S. student in Electrical and Computer Engineering at Carnegie Mellon University. My research interests lie in Embodied AI, focusing on building vision-language agents that can understand natural language instructions, interpret visual observations, and produce semantically aligned and physically executable behavior in embodied environments. 
<!-- In particular, I am interested in developing model designs and learning algorithms that improve the performance, efficiency, reliability, and safety of embodied agents.  -->

At CMU, I am working with Dr. [Ji Zhang](https://frc.ri.cmu.edu/~zhangji/) and Dr. [Wenshan Wang](http://www.wangwenshan.com/) on Embodied Navigation. Before joining CMU, I received my B.Eng. degree in Computer Science and Technology from Xi'an Jiaotong-Liverpool University in 2025. During my undergraduate studies, I focused on computer vision and worked with Prof. [Guangliang Cheng](https://sites.google.com/view/guangliangcheng/homepage), Prof. [Wei Wang](https://scholar.xjtlu.edu.cn/en/persons/WeiWang03), and Prof. [Ming Xu](https://scholar.xjtlu.edu.cn/en/persons/MingXu).

My resume can be found [here](https://github.com/BaoBao0926/BaoBao0926.github.io/blob/master/assets/Muyi%20Bao%20CV.pdf) (updated in 2026.07.20) and my email is [muyib@andrew.cmu.edu](mailto:muyib@andrew.cmu.edu).

</div>


<p style="color:red;">
I am actively looking for Ph.D. opportunities starting in Fall 2027, with research interests in Embodied AI.
</p>



<h2 class="about-wide-item">News</h2>

<ul class="news-list about-wide-item">
  <li><strong>[2026/09]</strong> 📄 <a href="https://anonymous.4open.science/w/IntentNav/">IntentNav</a> was accepted to <em>CoRL 2026</em>.</li>
  <li><strong>[2026/02]</strong> 📄 Our survey paper, <a href="https://github.com/BaoBao0926/Awesome-Mamba-in-Remote-Sensing/tree/main">Vision Mamba in Remote Sensing</a>, was accepted by <em>Remote Sensing</em>.</li>
  <li><strong>[2025/11]</strong> 📄 <a href="https://aclanthology.org/2025.findings-emnlp.1229/">NUMINA</a> was accepted to <em>Findings of EMNLP 2025</em>.</li>
  <li><strong>[2025/08]</strong> 🎓 I joined Carnegie Mellon University as an M.S. student in Electrical and Computer Engineering.</li>
  <li><strong>[2025/07]</strong> 📄 <a href="https://github.com/BaoBao0926/FTCFormer/tree/main">FTCFormer</a> was accepted by <em>ECAI 2025</em>.</li>
  <li><strong>[2025/06]</strong> 🎓 I received my B.Eng. degree in Computer Science and Technology from Xi'an Jiaotong-Liverpool University.</li>
  <li><strong>[2025/02]</strong> 📄 <a href="https://github.com/BaoBao0926/AlexCapsNet">AlexCapsNet</a> was accepted by <em>IEEE Access</em>.</li>
  <li><strong>[2024/12]</strong> 📄 <a href="https://github.com/BaoBao0926/Comparative-Performance-Analysis-of-Rendering-Optimization-Method">Performance Analysis of Rendering Optimization</a> was accepted by <em>UIC 2024</em>.</li>
  <li><strong>[2021/06]</strong> 🎓 I joined Xi'an Jiaotong Liverpool Unverisity as a Bachelor of Engineering in Computer Science and Technology.</li>
</ul>

<style>
  @media screen and (min-width: 1280px) {
    #main {
      max-width: 1300px;
    }
  }

  .about-intro {
    max-width: 760px; /* 控制开头三段正文的最大宽度：数字越小，文字行越短 */
    font-size: 0.9em; /* 控制开头三段正文的字号：0.9em = 比普通正文小一点 */
    line-height: 1.5; /* 控制开头三段正文的行距：数字越大，行间距越松 */
    margin: 0 auto 1.5em; /* 控制位置和下方间距：左右 auto 表示居中 */
  }

  .about-wide-item {
    --about-wide-extra: 140px; /* 控制 News 和 Research 向右额外扩展多少空间 */
    --about-wide-max: 1040px; /* 控制 News 和 Research 扩展后的最大宽度 */
    max-width: var(--about-wide-max); /* 限制最大宽度，防止在超宽屏上拉得太长 */
  }

  @media screen and (min-width: 1024px) {
    .about-wide-item,
    .research-table.about-wide-item {
      width: calc(100% + var(--about-wide-extra)); /* 保持左边位置不动，主要向右扩展 */
    }
  }

  .news-list {
    font-size: 0.8em; /* 控制 News 列表字号 */
    line-height: 1.45; /* 控制 News 列表行距 */
    margin-top: 0; /* 控制 News 标题和列表之间的距离 */
  }

  .research-table {
    width: 100%; /* 控制 Research Projects 表格占满它所在内容区的宽度 */
    border: 0 !important; /* 去掉整个表格外框线 */
    border-spacing: 0; /* 去掉单元格之间的空隙 */
    border-collapse: separate !important; /* 保持单元格独立，方便只显示项目之间的分隔线 */
    margin: 0 auto 1em; /* 控制表格位置和下方间距：左右 auto 表示居中 */
    font-size: 0.95em; /* 控制 Research Projects 区域整体字号 */
  }

  .research-table tr,
  .research-table td {
    border: 0 !important;
    background: transparent !important;
  }

  .research-table tr + tr td {
    border-top: 1px solid #eeeeee !important;
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

  .research-note {
    font-size: 0.45em;
    font-weight: 400;
    color: #6f777d;
  }

  .research-authors {
    margin-top: 5px;
    line-height: 1.4;
    font-size: 0.88em;
  }

  .research-venue {
    margin-top: 5px;
    line-height: 1.4;
    font-size: 0.88em;
  }

  .page__content p.research-description {
    margin-top: 12px;
    margin-bottom: 8px;
    line-height: 1.35;
    font-size: 0.80em;
  }

  .research-links {
    margin-top: 6px;
  }

  .research-filter {
    display: flex;
    flex-wrap: wrap;
    gap: 12px 18px;
    align-items: center;
    margin: -0.4em auto 0.9em;
    font-size: 0.82em;
  }

  .research-filter label {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    color: #494e52;
    cursor: pointer;
  }

  .research-filter input {
    accent-color: #52adc8;
  }

  .research-project-row[hidden] {
    display: none !important;
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

<h2 class="about-wide-item">Research Projects <span class="research-note">(<sup>*</sup> Equal contribution)</span></h2>

<div class="research-filter about-wide-item" aria-label="Research project filters">
  <label><input type="checkbox" name="research-filter" value="all" checked> All</label>
  <label><input type="checkbox" name="research-filter" value="embodied-navigation"> Embodied Navigation</label>
  <label><input type="checkbox" name="research-filter" value="computer-vision"> Computer Vision</label>
</div>

<table class="research-table about-wide-item">
  <tbody>

    <!-- Map2Route -->
    <tr class="research-project-row" data-category="embodied-navigation">
      <td class="research-image-cell">
        <img
          class="research-image"
          src="https://raw.githubusercontent.com/BaoBao0926/Map2Route/main/git_resources/figures/teaser.png"
          alt="Map2Route overview"
        />
      </td>

      <td class="research-text-cell">
        <a href="https://baobao0926.github.io/Map2Route/">
          <span class="research-title">
            Map2Route: Benchmarking Compositional Language-Grounded Route Planning over Semantic Maps
          </span>
        </a>

        <div class="research-authors">
          <strong>Muyi Bao</strong>,
          Hang Xu,
          Jingfan Tang,
          Zihan Liu,
          Yuxin Cai,
          Chen Lv,
          Wenshan Wang,
          Ji Zhang
        </div>

        <div class="research-venue">
          <em>arXiv, 2026</em>
        </div>

        <p class="research-description">
          Map2Route is a human-curated benchmark for compositional language-grounded route planning over pre-built semantic maps. Given a semantic map, an initial robot position, and a natural-language instruction without explicit goal coordinates, the task is to generate a complete route that faithfully realizes the instruction. We evaluate several representative baselines and Grounding2Route, our proposed method, showing that Map2Route remains a challenging benchmark and is still far from saturated.
        </p>

        <div class="research-links">
          <a href="https://baobao0926.github.io/Map2Route/">Project Page</a>
          &nbsp;/&nbsp;
          <a href="https://github.com/BaoBao0926/Map2Route/blob/main/Map2Route.pdf">Paper</a>
          &nbsp;/&nbsp;
          <a href="https://github.com/BaoBao0926/Map2Route">Code</a>
          &nbsp;/&nbsp;
          <a href="https://huggingface.co/datasets/Muyiaaaa/Map2Route">Dataset</a>
        </div>
      </td>
    </tr>

    <!-- Goal2Pixel -->
    <tr class="research-project-row" data-category="embodied-navigation">
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

        <div class="research-venue">
          <em>arXiv, 2026</em>
        </div>

        <p class="research-description">
          Goal2Pixel reformulates Vision-and-Language Navigation in Continuous Environments (VLN-CE) as a pure navigable-pixel grounding problem, using the image plane as a unified spatial interface between VLM reasoning and robot motion. For history representation, Goal2Pixel introduces Visibility-Aware Keyframe Memory (ViKeyMem), cutting training/inference time by around 50%. Goal2Pixel achieves 54.1%/48.1% SR on R2R-CE/RxR.
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

    <!-- IntentNav -->
    <tr class="research-project-row" data-category="embodied-navigation">
      <td class="research-image-cell">
        <img
          class="research-image"
          src="/assets/paper_images/intentnav.png"
          alt="IntentNav framework"
        />
      </td>

      <td class="research-text-cell">
        <a href="https://anonymous.4open.science/w/IntentNav/">
          <span class="research-title">
            IntentNav: Learning Spatial-Visual Object Navigation from Human Demonstrations
          </span>
        </a>

        <div class="research-authors">
          Yuxin Cai<sup>*</sup>,
          Zongtai Li<sup>*</sup>,
          Maonan Wang,
          <strong>Muyi Bao</strong>,
          Haokun Zhu,
          Ruofei Bai,
          Ding Zhao,
          Zirui Li,
          Wenshan Wang,
          Wei-Yun Yau,
          Ji Zhang,
          Chen Lv
        </div>

        <div class="research-venue">
          <em>Conference on Robot Learning (CoRL), 2026</em>
        </div>

        <p class="research-description">
          IntentNav learns human-like ObjectNav policies from 2.36 million samples, without relying on oracle shortest paths. The model unifies frontier exploration and target commitment in a BEV-grounded spatial-visual decision space and achieves 53.8% SR on MP3D, 70.5% SR on HM3D-v1, and 82.2% SR on HM3D-v2.
        </p>

        <div class="research-links">
          <a href="https://anonymous.4open.science/w/IntentNav/">
            Project Page
          </a>
          &nbsp;/&nbsp;
          <a href="https://arxiv.org/abs/2606.08029">Paper</a>
        </div>
      </td>
    </tr>


    <!-- Vision Mamba Survey -->
    <tr class="research-project-row" data-category="computer-vision">
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
          This is the first survey to systematically review approximately 120+ Mamba-based studies in remote sensing. It provides a structured overview of the field organized into seven parts, covering foundations, model architectures, downstream applications, and future research directions.
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
    <tr class="research-project-row" data-category="computer-vision">
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
          <strong>Muyi Bao</strong><sup>*</sup>,
          Changyu Zeng<sup>*</sup>,
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
          FTCFormer introduces a clustering-based token downsampling mechanism that dynamically allocates more tokens to informative image regions and fewer tokens to less important areas. Evaluated on 32 image classification datasets across diverse domains, FTCFormer consistently outperforms the TCFormer baseline.
        </p>

        <div class="research-links">
          <a href="https://arxiv.org/abs/2507.10283">Paper</a>
          &nbsp;/&nbsp;
          <a href="https://github.com/BaoBao0926/FTCFormer">Code</a>
        </div>
      </td>
    </tr>

    <!-- NUMINA -->
    <tr class="research-project-row" data-category="computer-vision">
      <td class="research-image-cell">
        <img
          class="research-image"
          src="/assets/paper_images/NUMINA.png"
          alt="NUMINA benchmark overview"
        />
      </td>

      <td class="research-text-cell">
        <a href="https://aclanthology.org/anthology-files/anthology-files/pdf/findings/2025.findings-emnlp.1229.pdf">
          <span class="research-title">
            NUMINA: A Natural Understanding Benchmark for Multi-dimensional
            Intelligence and Numerical Reasoning Abilities
          </span>
        </a>

        <div class="research-authors">
          Changyu Zeng<sup>*</sup>,
          Yifan Wang<sup>*</sup>,
          Zimu Wang<sup>*</sup>,
          Wei Wang,
          Zhengni Yang,
          <strong>Muyi Bao</strong>,
          Jiming Xiao,
          Anh Nguyen,
          Yutao Yue
        </div>

        <div class="research-venue">
          <em>Findings of EMNLP, 2025</em>
        </div>

        <p class="research-description">
          NUMINA is a large-scale benchmark for fine-grained spatial understanding and numerical reasoning in 3D indoor environments. It contains 74,526 question-answer pairs across fact validation, prompt matching, and numerical inference, revealing clear limitations of current models on precise quantity, distance, and volume reasoning.
        </p>

        <div class="research-links">
          <a href="https://aclanthology.org/anthology-files/anthology-files/pdf/findings/2025.findings-emnlp.1229.pdf">
            Paper
          </a>
        </div>
      </td>
    </tr>

    <!-- ASP-VMUNet -->
    <tr class="research-project-row" data-category="computer-vision">
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
          ASP-VMUNet introduces a hybrid CNN-Mamba architecture for skin lesion segmentation, featuring: 1) an atrous scan strategy to suppress background interference and enlarge the receptive field; 2) a shift-round operation for cross-segment feature interaction; and 3) attention-based fusion of local and global features. ASP-VMUNet achieves state-of-the-art performance on PH2/ISIC 2016-2018.
        </p>

        <div class="research-links">
          <a href="https://arxiv.org/abs/2503.19427">Paper</a>
          &nbsp;/&nbsp;
          <a href="https://github.com/BaoBao0926/ASP-VMUNet">Code</a>
        </div>
      </td>
    </tr>

    <!-- Rendering Optimization -->
    <tr class="research-project-row" data-category="other">
      <td class="research-image-cell">
        <img
          class="research-image"
          src="https://raw.githubusercontent.com/BaoBao0926/Comparative-Performance-Analysis-of-Rendering-Optimization-Method/main/figure/show.png"
          alt="Rendering optimization comparison"
        />
      </td>

      <td class="research-text-cell">
        <a href="https://github.com/BaoBao0926/Comparative-Performance-Analysis-of-Rendering-Optimization-Method">
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
          This work compares Unity Global's Level of Detail, Tuanjie Engine's Virtual Geometry, and Unreal Engine 5's Nanite across FPS, GPU, CPU, and memory usage. The results show that Nanite achieves the best overall performance, while Tuanjie's Virtual Geometry is stronger than Unity LOD at distant views but weaker at close range.
        </p>

        <div class="research-links">
          <a href="https://ieeexplore.ieee.org/abstract/document/10925167">Paper</a>
          &nbsp;/&nbsp;
          <a href="https://github.com/BaoBao0926/Comparative-Performance-Analysis-of-Rendering-Optimization-Method">
            Repository
          </a>
        </div>
      </td>
    </tr>

    <!-- AlexCapsNet -->
    <tr class="research-project-row" data-category="computer-vision">
      <td class="research-image-cell">
        <img
          class="research-image"
          src="https://raw.githubusercontent.com/BaoBao0926/AlexCapsNet/main/figure/show1.png"
          alt="AlexCapsNet architecture"
        />
      </td>

      <td class="research-text-cell">
        <a href="https://github.com/BaoBao0926/AlexCapsNet">
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
          AlexCapsNet combines AlexNet-based feature extraction with CapsNet to improve image classification under background noise. Across seven datasets, it improves robustness over the original CapsNet, and removing the reconstruction module further benefits complex-background settings.
        </p>

        <div class="research-links">
          <a href="https://ieeexplore.ieee.org/abstract/document/10900363">Paper</a>
          &nbsp;/&nbsp;
          <a href="https://github.com/BaoBao0926/AlexCapsNet">Code</a>
        </div>
      </td>
    </tr>

  </tbody>
</table>

<script>
  (function () {
    const filters = Array.from(document.querySelectorAll('input[name="research-filter"]'));
    const rows = Array.from(document.querySelectorAll(".research-project-row"));
    const allFilter = filters.find((filter) => filter.value === "all");

    if (!filters.length || !rows.length || !allFilter) return;

    function updateProjects(changedFilter) {
      if (changedFilter === allFilter && allFilter.checked) {
        filters.forEach((filter) => {
          if (filter !== allFilter) filter.checked = false;
        });
      }

      if (changedFilter !== allFilter && changedFilter.checked) {
        allFilter.checked = false;
      }

      const selectedCategories = filters
        .filter((filter) => filter !== allFilter && filter.checked)
        .map((filter) => filter.value);

      if (!selectedCategories.length) {
        allFilter.checked = true;
        rows.forEach((row) => {
          row.hidden = false;
        });
        return;
      }

      rows.forEach((row) => {
        const rowCategories = (row.dataset.category || "").split(/\s+/);
        row.hidden = !selectedCategories.some((category) => rowCategories.includes(category));
      });
    }

    filters.forEach((filter) => {
      filter.addEventListener("change", () => updateProjects(filter));
    });

    updateProjects(allFilter);
  })();
</script>
