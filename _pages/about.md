---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  .conference-badge {
      background: #1f77b4;      /* 蓝色背景 */
      color: white;             /* 白色文字 */
      font-size: 12px;          /* 字体大小 */
      padding: 2px 6px;         /* 内边距，上下2px，左右6px */
      border-radius: 4px;       /* 圆角 */
      font-weight: bold;        /* 加粗 */
      display: inline-block;    /* 行内块，方便排版 */
  }
</style>


<span class='anchor' id='about-me'></span>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

I am currently a first-year Ph.D. student in the School of Computer Science at Shanghai Jiao Tong University, advised by [Prof. Jingwen Leng](https://www.cs.sjtu.edu.cn/~leng-jw/). I received the B.Eng. degree in Computer Science and Technology (IEEE Pilot Class) from SJTU.

My research interests include machine learning compilers and high-performance computing. 

<!-- I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2025.09*: &nbsp;🎉 One paper is accepted by NeurIPS 2025.

# 📝 Publications 

- <span class="conference-badge">NeurIPS 2025</span> **Xinhao Luo**, Zihan Liu, Yangjie Zhou, Shihan Fang, Ziyu Huang, Yu Feng, Chen Zhang, Shixuan Sun, Zhenzhe Zheng, Jingwen Leng, Minyi Guo; [ClusterFusion: Expanding Operator Fusion Scope for LLM Inference via Cluster-Level Collective Primitive](https://arxiv.org/pdf/2508.18850).
[![](https://img.shields.io/github/stars/xinhao-luo/ClusterFusion?style=social&label=Code+Stars)](https://github.com/xinhao-luo/ClusterFusion)
- <span class="conference-badge">HPCA 2025</span> Zihan Liu, **Xinhao Luo**, Junxian Guo, Wentao Ni, Yangjie Zhou, Yue Guan, Cong Guo, Weihao Cui, Yu Feng, Minyi Guo, Yuhao Zhu, Minjia Zhang, Jingwen Leng, Chen Jin; [VQ-LLM: High-performance Code Generation for Vector Quantization Augmented LLM Inference](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10946800).

# 🎖 Honors and Awards
- *2025.06* SJTU Zhiyuan Honor Bachelor's Degree.
- *2021-2025* SJTU Zhiyuan Honor Scholarship.
- *2021-2025* SJTU Excellent Undergraduate Scholarship.
- *2024.03* SJTU Outstanding Undergraduate Scholarship of Class ’88 Alumni, Department of Computer Science.

# 📖 Educations
- *2025.09 - now*, Ph.D. Student in Computer Science and Technology, School of Computer Science, Shanghai Jiao Tong University.
- *2021.09 - 2025.06*, B.S. in Computer Science and Technology (IEEE), School of Computer Science, Shanghai Jiao Tong University.

# 💻 Internships
- *2024.11 - now*, Research intern, Shanghai Qi Zhi Institute.
- *2025.03 - now*, Academic Research Intern, Alibaba.
- *2024.07 - 2024.09*, Research intern, Microsoft Research Asia (Shanghai).