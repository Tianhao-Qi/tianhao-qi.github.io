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

I am a Postdoctoral Scholar in the Department of Computer Science and Engineering at the University of California, Santa Cruz, where I work with [Prof. Yuyin Zhou](https://yuyinzhou.github.io/) and [Prof. Cihang Xie](https://cihangxie.github.io/) in the [VLAA Lab](https://ucsc-vlaa.github.io/). My research focuses on controllable image and video generation, world models, and AI agents.

I received my Ph.D. degree in Information and Communication Engineering from the University of Science and Technology of China in March 2026, under the supervision of [Prof. Yongdong Zhang](https://imcc.ustc.edu.cn/_upload/tpl/0d/13/3347/template3347/zhangyongdong.html) and [Prof. Hongtao Xie](https://imcc.ustc.edu.cn/_upload/tpl/0d/13/3347/template3347/xiehongtao.html) at the National Engineering Laboratory for Brain-inspired Intelligence Technology and Application ([NEL-BITA](https://leinao.ustc.edu.cn/main.htm)) and the Intelligent Multimedia Content Computing Laboratory ([IMCC](https://imcc.ustc.edu.cn/main.htm)). Prior to that, I obtained my bachelor's degree in Automation from the University of Science and Technology of China.

If you would like a copy of my CV or are interested in working together, please use the <a href="{{ '/#-contact' | relative_url }}" target="_self">request form</a> below.

# 🔥 News
- *2026.10.11*: &nbsp;🎉🎉 One paper is accepted by IEEE TCSVT.
- *2026.08.01*: &nbsp;🎉🎉 I joined the University of California, Santa Cruz as a Postdoctoral Scholar.
- *2026.06.18*: &nbsp;🎉🎉 One paper is accepted by ECCV 2026.
- *2026.03.20*: &nbsp;🎓🎓 I graduated from the University of Science and Technology of China.
- *2025.10.20*: &nbsp;🎉🎉 Presented my CVPR 2025 paper *“Mask²DiT: Dual Mask-based Diffusion Transformer for Multi-Scene Long Video Generation”* at the [**1st Workshop on Long Multi-Scene Video Foundations (LongVid@ICCV 2025)**](https://ramoscsv.github.io/longvid_foundations/).
- *2025.06.26*: &nbsp;🎉🎉 One paper is accepted by ICCV 2025.
- *2025.02.27*: &nbsp;🎉🎉 One paper is accepted by CVPR 2025.
- *2025.01.23*: &nbsp;🎉🎉 One paper is accepted by ICLR 2025.
- *2024.02.27*: &nbsp;🎉🎉 One paper is accepted by CVPR 2024 as <span style="color:red">Highlight</span> (2.8% of submissions).
- *2023.08.22*: &nbsp;🎉🎉 One paper is accepted by TMM.

<span class='anchor' id='-publications'></span>

# 📝 Selected Publications

<a href="{{ '/publications/' | relative_url }}" target="_self">Full publication list, including preprints →</a>

\* indicates equal contribution; <sup>†</sup> indicates corresponding author.

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2026</div><img src='images/LibraGen.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LibraGen: Playing a Balance Game in Subject-Driven Video Generation](https://link.springer.com/chapter/10.1007/978-3-032-37271-0_18)

Jiahao Zhu\*, Shanshan Lao\*, Lijie Liu\*, Gen Li\*, **Tianhao Qi**\*, Wei Han\*, Bingchuan Li\*, Fangfang Liu, Zhuowei Chen, Tianxiang Ma, Qian He, Yi Zhou<sup>†</sup>, Xiaohua Xie<sup>†</sup>

[**Project Page**](https://phantom-video.github.io/LibraGen/) \| [**arXiv**](https://arxiv.org/abs/2603.13506) \| [![](https://img.shields.io/github/stars/Phantom-video/LibraGen?style=social&label=Code+Stars)](https://github.com/Phantom-video/LibraGen)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/I2VControl.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[I2VControl: Disentangled and Unified Video Motion Synthesis Control](https://openaccess.thecvf.com/content/ICCV2025/html/Feng_I2VControl_Disentangled_and_Unified_Video_Motion_Synthesis_Control_ICCV_2025_paper.html)

Wanquan Feng<sup>†</sup>, **Tianhao Qi**, Jiawei Liu, Mingzhen Sun, Pengqi Tu, Tianxiang Ma, Fei Dai, Songtao Zhao, Siyu Zhou, Qian He

[**Project Page**](https://wanquanf.github.io/I2VControl) \| [**arXiv**](https://arxiv.org/abs/2411.17765)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/Mask2DiT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Mask<sup>2</sup>DiT: Dual Mask-based Diffusion Transformer for Multi-Scene Long Video Generation](https://openaccess.thecvf.com/content/CVPR2025/html/Qi_Mask2DiT_Dual_Mask-based_Diffusion_Transformer_for_Multi-Scene_Long_Video_Generation_CVPR_2025_paper.html)

**Tianhao Qi**, Jianlong Yuan, Wanquan Feng, Shancheng Fang<sup>†</sup>, Jiawei Liu, Siyu Zhou, Qian He, Hongtao Xie, Yongdong Zhang

[**Project Page**](https://tianhao-qi.github.io/Mask2DiTProject) \| [**arXiv**](https://arxiv.org/abs/2503.19881) \| [![](https://img.shields.io/github/stars/Tianhao-Qi/Mask2DiT?style=social&label=Code+Stars)](https://github.com/Tianhao-Qi/Mask2DiT)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/I2VControl-Camera.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[I2VControl-Camera: Precise Video Camera Control with Adjustable Motion Strength](https://proceedings.iclr.cc/paper_files/paper/2025/hash/7bd4a7d0e6773072c2e3c77b11d93065-Abstract-Conference.html)

Wanquan Feng<sup>†</sup>, Jiawei Liu, Pengqi Tu, **Tianhao Qi**, Mingzhen Sun, Tianxiang Ma, Songtao Zhao, Siyu Zhou, Qian He

[**Project Page**](https://wanquanf.github.io/I2VControlCamera) \| [**arXiv**](https://arxiv.org/abs/2411.06525) \| [![](https://img.shields.io/github/stars/WanquanF/I2VControl-Camera?style=social&label=Code+Stars)](https://github.com/WanquanF/I2VControl-Camera)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024 Highlight</div><img src='images/DEADiff.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DEADiff: An Efficient Stylization Diffusion Model with Disentangled Representations](https://openaccess.thecvf.com/content/CVPR2024/html/Qi_DEADiff_An_Efficient_Stylization_Diffusion_Model_with_Disentangled_Representations_CVPR_2024_paper.html)

**Tianhao Qi**, Shancheng Fang, Yanze Wu, Hongtao Xie<sup>†</sup>, Jiawei Liu, Lang Chen, Qian He, Yongdong Zhang

[**Project Page**](https://tianhao-qi.github.io/DEADiff) \| [**arXiv**](https://arxiv.org/abs/2403.06951) \| [![](https://img.shields.io/github/stars/bytedance/DEADiff?style=social&label=Code+Stars)](https://github.com/bytedance/DEADiff)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMM 2023</div><img src='images/BACL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Balanced Classification: A Unified Framework for Long-Tailed Object Detection](https://ieeexplore.ieee.org/abstract/document/10225715)

**Tianhao Qi**, Hongtao Xie<sup>†</sup>, Pandeng Li, Jiannan Ge, Yongdong Zhang

[**arXiv**](https://arxiv.org/abs/2308.02213) \| [![](https://img.shields.io/github/stars/Tianhao-Qi/BACL?style=social&label=Code+Stars)](https://github.com/Tianhao-Qi/BACL)
</div>
</div>

# 🎖 Honors and Awards
- *2025.05.17*: Best Presentation Award, AI Future--The 7th Academic Forum on Artificial Intelligence of Beijing Universities (Sub-forum: Large Models and Frontier Technologies) ([report](https://mp.weixin.qq.com/s/X_QtBxNh6veYT9VFC3FhWQ)).
- *2018.10.21*: Runner-up, "Brave the Peak" category, the 18th RoboGame Robotics Competition, University of Science and Technology of China ([Rookie Team](https://news.ustc.edu.cn/info/1032/22010.htm), [video](https://www.bilibili.com/video/BV12yGU6SEoq/), [photo](images/robogame_rookie_robot.jpg)).

# 📖 Educations
- *2020.09.01 – 2026.03.20*, Ph.D. in Information and Communication Engineering, University of Science and Technology of China, Hefei, China.
  - Thesis: *Research on Consistency Modeling Methods for Cross-Modal Visual Generation Models*
  - Advisors: [Prof. Yongdong Zhang](https://imcc.ustc.edu.cn/_upload/tpl/0d/13/3347/template3347/zhangyongdong.html) and [Prof. Hongtao Xie](https://imcc.ustc.edu.cn/_upload/tpl/0d/13/3347/template3347/xiehongtao.html) ([IMCC Lab](https://imcc.ustc.edu.cn/))
- *2016.09.01 – 2020.06.30*, B.E. in Automation, University of Science and Technology of China, Hefei, China.
  - Thesis: *Object Detection for Long-Tailed Data Distribution*
  - Advisor: [Prof. Hongtao Xie](https://imcc.ustc.edu.cn/_upload/tpl/0d/13/3347/template3347/xiehongtao.html) ([IMCC Lab](https://imcc.ustc.edu.cn/))

# 💬 Talks
- *2025.10.20*, Oral presentation, *Mask<sup>2</sup>DiT: Dual Mask-based Diffusion Transformer for Multi-Scene Long Video Generation*, [1st Workshop on Long Multi-Scene Video Foundations (LongVid)](https://ramoscsv.github.io/longvid_foundations/), ICCV 2025, Honolulu, HI, USA.

# 💼 Work Experience
- *2026.08.01 – present*, Postdoctoral Scholar, Department of Computer Science and Engineering, [University of California, Santa Cruz](https://www.ucsc.edu/), USA.
  - Mentors: [Prof. Yuyin Zhou](https://yuyinzhou.github.io/) and [Prof. Cihang Xie](https://cihangxie.github.io/) ([VLAA Lab](https://ucsc-vlaa.github.io/))
- *2023.02.06 – 2026.07.17*, Algorithm Research Intern, Intelligent Creation, [ByteDance](https://www.bytedance.com/) <img src='images/bytedance.png' style='width: 6em;'>, China.
- *2019.07.15 – 2019.08.23*, Summer Research Intern, Department of Electrical and Computer Engineering, University of Florida, USA.
  - Mentor: [Prof. Dapeng Oliver Wu](https://www.cs.cityu.edu.hk/~dapengwu/) (MCN Lab)

# 🏫 Academic Services
- **Conference Reviewer:** ICLR (2025–2026), CVPR (2026), ECCV (2026), AAAI (2026–2027), ACM MM (2025–2026)
- **Journal Reviewer:** IEEE TPAMI, IJCV, IEEE TMM

# 📬 Contact
To request my CV or to discuss a collaboration, please fill in the form below and I will reply by email.

{% include request-form.html %}

<div style="margin: 45px auto 0; max-width: 520px; text-align: center;">
  <script type="text/javascript" id="mapmyvisitors" src="https://mapmyvisitors.com/map.js?d=I4kKDp6ugK_jHZD7oy9sEfLu-hVTug_OPz58yboogOo&cl=ffffff&w=a"></script>
</div>
