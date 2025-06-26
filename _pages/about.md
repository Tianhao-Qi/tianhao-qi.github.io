---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Tianhao Qi is a final-year Ph.D. candidate in the Department of Electronic Engineering and Information Science, University of Science and Technology of China, supervised by [Prof. Hongtao Xie](https://imcc.ustc.edu.cn/_upload/tpl/0d/13/3347/template3347/xiehongtao.html) and [Prof. Yongdong Zhang](https://imcc.ustc.edu.cn/_upload/tpl/0d/13/3347/template3347/zhangyongdong.html) in the National Engineering Laboratory for Brain-inspired Intelligence Technology and Application ([NEL-BITA](https://leinao.ustc.edu.cn/main.htm)) and Intelligent Multimedia Content Computing Laboratory ([IMCC](https://imcc.ustc.edu.cn/main.htm)). Before that, I graduated from the Department of Automation, University of Science and Technology of China with a bachelor's degree. Currently, my research interests include cross-modal image/video generation and long-tailed object detection.

<style>
  @keyframes blink {
    0%, 100% { opacity: 1; }
    50% { opacity: 0.2; }
  }

  .blinking-mail {
    animation: blink 1.2s infinite;
    display: inline-block;
    margin-right: 6px;
  }

  .gradient-text {
    background: linear-gradient(90deg, #d9480f, #f59f00);  /* 更温和的橙色系 */
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    font-weight: bold;
    white-space: nowrap; /* 强制不换行 */
  }
</style>

<div style="border: 2px solid #f59f00; border-radius: 10px; padding: 20px; margin: 30px auto; max-width: 720px; background-color: #fffaf0; text-align: center; font-family: 'Helvetica Neue', sans-serif;">
  <p class="gradient-text" style="font-size: 20px; margin-bottom: 10px;">
    📢 Seeking Postdoc Opportunities in North America – Spring 2026
  </p>
  <p style="font-size: 15px; color: #333; line-height: 1.6;">
    I am actively looking for a <strong>postdoctoral position starting Spring 2026</strong>.<br>
    If you are recruiting or open to collaboration, feel free to reach out!
  </p>
  <p style="font-size: 15px; margin-top: 16px;">
    <span class="blinking-mail">📬</span>
    <a href="mailto:qth@mail.ustc.edu.cn" style="color: #d9480f; text-decoration: none; font-weight: bold;">
      qth@mail.ustc.edu.cn
    </a>
  </p>
</div>


# 🔥 News
- *2025.06*: &nbsp;🎉🎉 One paper is accepted by ICCV 2025.
- *2025.02*: &nbsp;🎉🎉 One paper is accepted by CVPR 2025.
- *2025.01*: &nbsp;🎉🎉 One paper is accepted by ICLR 2025.
- *2024.02*: &nbsp;🎉🎉 One paper is accepted by CVPR 2024 as <span style="color:red">Highlight</span> (11.9%).
- *2023.08*: &nbsp;🎉🎉 One paper is accepted by TMM.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/I2VControl.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[I2VControl: Disentangled and Unified Video Motion Synthesis Control](https://arxiv.org/abs/2411.17765)

Wanquan Feng, **Tianhao Qi**, Jiawei Liu, Mingzhen Sun, Pengqi Tu, Tianxiang Ma, Fei Dai, Songtao Zhao, Siyu Zhou, Qian He

[**Project Page**](https://wanquanf.github.io/I2VControl/)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/Mask2DiT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Mask<sup>2</sup>DiT: Dual Mask-based Diffusion Transformer for Multi-Scene Long Video Generation](http://arxiv.org/abs/2503.19881)

**Tianhao Qi**, Jianlong Yuan, Wanquan Feng, Shancheng Fang, Jiawei Liu, Siyu Zhou, Qian He, Hongtao Xie, Yongdong Zhang

[**Project Page**](https://tianhao-qi.github.io/Mask2DiTProject/) \| [![](https://img.shields.io/github/stars/Tianhao-Qi/Mask2DiT?style=social&label=Code+Stars)](https://github.com/Tianhao-Qi/Mask2DiT) 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/I2VControl-Camera.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[I2VControl-Camera: Precise Video Camera Control with Adjustable Motion Strength](https://arxiv.org/abs/2411.06525)

Wanquan Feng, Jiawei Liu, Pengqi Tu, **Tianhao Qi**, Mingzhen Sun, Tianxiang Ma, Songtao Zhao, Siyu Zhou, Qian He

[**Project Page**](https://wanquanf.github.io/I2VControlCamera) \| [![](https://img.shields.io/github/stars/WanquanF/I2VControl-Camera?style=social&label=Code+Stars)](https://github.com/WanquanF/I2VControl-Camera.git) 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/DEADiff.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DEADiff: An Efficient Stylization Diffusion Model with Disentangled Representations](https://arxiv.org/abs/2403.06951)

**Tianhao Qi**, Shancheng Fang, Yanze Wu, Hongtao Xie, Jiawei Liu, Lang Chen, Qian He, Yongdong Zhang

[**Project Page**](https://tianhao-qi.github.io/DEADiff/) \| [![](https://img.shields.io/github/stars/bytedance/DEADiff?style=social&label=Code+Stars)](https://github.com/bytedance/DEADiff) 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMM 2023</div><img src='images/BACL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Balanced Classification: A Unified Framework for Long-Tailed Object Detection](https://ieeexplore.ieee.org/abstract/document/10225715)

**Tianhao Qi**, Hongtao Xie, Pandeng Li, Jiannan Ge, Yongdong Zhang

[![](https://img.shields.io/github/stars/Tianhao-Qi/BACL?style=social&label=Code+Stars)](https://github.com/Tianhao-Qi/BACL) 
</div>
</div>

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2020.09 - now*, Ph.D., University of Science and Technology of China, Department of Electronic Engineering and Information Science, Hefei, China. 
- *2016.09 - 2020.06*, Bachelor, University of Science and Technology of China, Department of Automation, Hefei, China. 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2023.02 - now*, [ByteDance](https://www.bytedance.com/) <img src='images/bytedance.png' style='width: 6em;'>, China.
- *2019.07 - 2019.08*, Multimedia Communications and Networking Laboratory (MCN), University of Florida (directed by [Dr. Dapeng Oliver Wu](http://www.wu.ece.ufl.edu/)), USA.

# 🏫 Academic Services
- ICLR Reviewer: 2025
- ACM MM Reviewer: 2025
- Journal Reviewer: IJCV, TMM