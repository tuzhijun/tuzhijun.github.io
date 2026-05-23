---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am Zhijun Tu, a researcher at Huawei Fundation Model Department. My research interests lie in efficient systems for large language model and multimodal generation, and model compression.

I received my B.S. and M.S. degrees from Xi'an Jiaotong University in 2019 and 2022, respectively, where I was advised by [Prof. Pengju Ren](https://scholar.google.com/citations?user=qVYDbvIAAAAJ&hl=en). In 2021, I was a research intern at Huawei Noah's Ark Lab, advised by [Dr. Xinghao Chen](https://scholar.google.com/citations?user=tuGWUVIAAAAJ&hl=en) and led by [Dr. Yunhe Wang](https://scholar.google.com/citations?user=isizOkYAAAAJ&hl=en).

My primary focus is to advance modern foundation models and generative AI for real-world mobile ecosystems, ultimately democratizing powerful intelligence on everyday devices. To this end, our team is seeking self-motivated Research Interns to collaborate on pioneering projects in efficient multimodal systems. If you are driven to advance cutting-edge multimodal systems and next-generation generative AI, feel free to drop me an email with your CV.


## 🔥 News
* **[2026.05]** One paper accepted by **ICML 2026** (BinaryLLM).
* **[2026.03]** One paper accepted by **IEEE Transactions on Image Processing** (TAD-SR).
* **[2025.11]** One paper accepted by **AAAI 2026** (MoR).
* **[2025.05]** One paper accepted by **ICML 2025** (Diff-MoE).
* **[2025.02]** Two papers accepted by **CVPR 2025** (RaSS).
* **[2025.01]** Two papers accepted by **ICLR 2025** (CBQ, AugKD).
* **[2024.11]** One paper accepted by **AAAI 2025** (DiT-SR).
* **[2024.09]** One paper accepted by **NeurIPS 2024** (U-DiTs).
* **[2024.07]** One paper accepted by **ECCV 2024** (PQ-SAM).
* **[2024.02]** Released our new survey paper: "A Survey on Transformer Compression".
* **[2023.09]** One paper accepted by **NeurIPS 2023 Track on Datasets and Benchmarks** (GenImage).
* **[2023.04]** Won the Winner Award in **NTIRE Challenge on Image Denoising@CVPR2023**.
* **[2023.02]** One paper accepted by **CVPR 2023** (PTQ4SR).
* **[2022.07]** One paper accepted by **ECCV 2022** (AdaBin).

## Selected Publications
<!-- BinaryLLM -->
<div style="display: flex; flex-wrap: wrap; margin-bottom: 30px; align-items: flex-start;">
  <!-- 左侧：论文缩略图 -->
  <div style="flex: 1; min-width: 150px; max-width: 200px; margin-right: 20px; margin-bottom: 10px;">
    <img src="{{ base_path }}/images/BinaryLLM.png" alt="Paper Teaser" style="width: 100%; border: 1px solid #ddd; border-radius: 4px; box-shadow: 0 1px 3px rgba(0,0,0,0.05);" />
  </div>
  <!-- 右侧：论文文字信息 -->
  <div style="flex: 3; min-width: 280px;">
    <h3 style="margin-top: 0; margin-bottom: 5px; font-size: 1.1em; font-weight: bold;">
      Rethinking 1-bit Optimization Leveraging Pre-trained Large Language Models
    </h3>
    <div style="margin-bottom: 5px;">
      <strong>Zhijun Tu</strong>, Jian Li, Yuanyuan Xi, Siqi Liu, Chuanjian Liu, Hanting Chen, Jie Hu, Yunhe Wang
    </div>
    <!-- 会议与链接合并到同一行 -->
    <div style="margin-bottom: 8px;">
      <span style="font-style: italic; color: #555;">ICML 2026</span>
      <a href="https://arxiv.org/pdf/2508.06974?" style="text-decoration: none; font-size: 0.9em; margin-left: 12px; font-weight: 500;">[Paper]</a>
      <!-- <a href="https://github.com/..." style="text-decoration: none; font-size: 0.9em; margin-left: 10px;">[Code]</a> -->
      <!-- <a href="https://..." style="text-decoration: none; font-size: 0.9em; margin-left: 10px;">[Project Page]</a> -->
    </div>
  </div>
</div>

<!-- U-DiTs -->
<div style="display: flex; flex-wrap: wrap; margin-bottom: 30px; align-items: flex-start;">
  <!-- 左侧：论文缩略图 -->
  <div style="flex: 1; min-width: 150px; max-width: 200px; margin-right: 20px; margin-bottom: 10px;">
    <img src="{{ base_path }}/images/UDiTs.png" alt="Paper Teaser" style="width: 100%; border: 1px solid #ddd; border-radius: 4px; box-shadow: 0 1px 3px rgba(0,0,0,0.05);" />
  </div>
  <!-- 右侧：论文文字信息 -->
  <div style="flex: 3; min-width: 280px;">
    <h3 style="margin-top: 0; margin-bottom: 5px; font-size: 1.1em; font-weight: bold;">
      U-DiTs: Downsample Tokens in U-Shaped Diffusion Transformers
    </h3>
    <div style="margin-bottom: 5px;">
      Yuchuan Tian*, <strong>Zhijun Tu*</strong>, Hanting Chen, Jie Hu,Chao Xu, Yunhe Wang
    </div>
    <!-- 会议与链接合并到同一行 -->
    <div style="margin-bottom: 8px;">
      <span style="font-style: italic; color: #555;">NeurIPS 2024</span>
      <a href="https://proceedings.neurips.cc/paper_files/paper/2024/file/5d2e24df9cfaad3189833b819c40b392-Paper-Conference.pdf" style="text-decoration: none; font-size: 0.9em; margin-left: 12px; font-weight: 500;">[Paper]</a>
      <a href="https://github.com/YuchuanTian/U-DiT" style="text-decoration: none; font-size: 0.9em; margin-left: 10px;">[Code]</a>
      <!-- <a href="https://..." style="text-decoration: none; font-size: 0.9em; margin-left: 10px;">[Project Page]</a> -->
    </div>
  </div>
</div>

<!-- PTQ4SR -->
<div style="display: flex; flex-wrap: wrap; margin-bottom: 30px; align-items: flex-start;">
  <!-- 左侧：论文缩略图 -->
  <div style="flex: 1; min-width: 150px; max-width: 200px; margin-right: 20px; margin-bottom: 10px;">
    <img src="{{ base_path }}/images/PTQ4SR.png" alt="Paper Teaser" style="width: 100%; border: 1px solid #ddd; border-radius: 4px; box-shadow: 0 1px 3px rgba(0,0,0,0.05);" />
  </div>
  <!-- 右侧：论文文字信息 -->
  <div style="flex: 3; min-width: 280px;">
    <h3 style="margin-top: 0; margin-bottom: 5px; font-size: 1.1em; font-weight: bold;">
      Toward Accurate Post-Training Quantization for Image Super Resolution
    </h3>
    <div style="margin-bottom: 5px;">
      <strong>Zhijun Tu</strong>, Jie Hu, Hanting Chen, Yunhe Wang
    </div>
    <!-- 会议与链接合并到同一行 -->
    <div style="margin-bottom: 8px;">
      <span style="font-style: italic; color: #555;">CVPR 2023</span>
      <a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Tu_Toward_Accurate_Post-Training_Quantization_for_Image_Super_Resolution_CVPR_2023_paper.pdf" style="text-decoration: none; font-size: 0.9em; margin-left: 12px; font-weight: 500;">[Paper]</a>
      <a href="https://github.com/huawei-noah/Efficient-Computing/tree/master/Quantization/PTQ4SR" style="text-decoration: none; font-size: 0.9em; margin-left: 10px;">[Code]</a>
      <!-- <a href="https://..." style="text-decoration: none; font-size: 0.9em; margin-left: 10px;">[Project Page]</a> -->
    </div>
  </div>
</div>

<!-- AdaBin -->
<div style="display: flex; flex-wrap: wrap; margin-bottom: 30px; align-items: flex-start;">
  <!-- 左侧：论文缩略图 -->
  <div style="flex: 1; min-width: 150px; max-width: 200px; margin-right: 20px; margin-bottom: 10px;">
    <img src="{{ base_path }}/images/AdaBin.png" alt="Paper Teaser" style="width: 100%; border: 1px solid #ddd; border-radius: 4px; box-shadow: 0 1px 3px rgba(0,0,0,0.05);" />
  </div>
  <!-- 右侧：论文文字信息 -->
  <div style="flex: 3; min-width: 280px;">
    <h3 style="margin-top: 0; margin-bottom: 5px; font-size: 1.1em; font-weight: bold;">
      AdaBin: Improving Binary Neural Networks with Adaptive Binary Sets
    </h3>
    <div style="margin-bottom: 5px;">
      <strong>Zhijun Tu</strong>, Xinghao Chen, Pengju Ren, Yunhe Wang
    </div>
    <!-- 会议与链接合并到同一行 -->
    <div style="margin-bottom: 8px;">
      <span style="font-style: italic; color: #555;">ECCV 2022</span>
      <a href="https://arxiv.org/pdf/2208.08084" style="text-decoration: none; font-size: 0.9em; margin-left: 12px; font-weight: 500;">[Paper]</a>
      <a href="https://github.com/huawei-noah/Efficient-Computing/tree/master/BinaryNetworks/AdaBin" style="text-decoration: none; font-size: 0.9em; margin-left: 10px;">[Code]</a>
      <!-- <a href="https://..." style="text-decoration: none; font-size: 0.9em; margin-left: 10px;">[Project Page]</a> -->
    </div>
  </div>
</div>
