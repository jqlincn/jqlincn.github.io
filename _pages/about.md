---
permalink: /
title: ""
excerpt: "About me"
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

I am currently pursuing the Ph.D. degree in artificial intelligence with the Huazhong University of Science and Technology, under the supervision of [Prof. Linqiang Pan](http://faculty.hust.edu.cn/panlinqiang/zh_CN/index.htm). I received my M.S. degree in the School of Automation from Central South University in 2020 under the supervision of [Prof. Yong Wang](https://faculty.csu.edu.cn/wangyong/zh_CN/index.htm).

My research interest includes computational intelligence, multiobjective optimization, and surrogate-assisted evolutionary optimization. 
<!-- I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

# 📖 Experiences
- *2021 – Now*, Doctor of Philosophy, Huazhong University of Science and Technology, Wuhan, China.
- *2020 – 2021*, Research Assistant, Southern University of Science and Technology, Shenzhen, China.
- *2017 – 2020*, Master of Engineering, Central South University, Changsha, China.
- *2013 – 2017*, Bachelor of Engineering, Tiangong University, Tianjin, China.

<!-- # 🔥 News -->
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 

## Journal Papers
<!--- **Surrogate-assisted Multiobjective Genes Selection Method for Cell Classification from Single-cell RNA Sequencing Data **  <br>  -->
<!--  <ins>Jianqing Lin</ins>, Cheng He, Hanjing Jiang, and Linqiang Pan  <br>  -->
<!--  _TBD, in press_ --> 
<!--- **Variable Reconstruction for Evolutionary Large-scale Expensive Multiobjective Optimization**  <br>  -->
<!--  <ins>Jianqing Lin</ins>, Cheng He, Ye Tian, and Linqiang Pan  <br>  -->
<!--  _IEEE/CAA Journal of Automatica Sinica, in press_ --> 
- **Computationally Expensive High-dimensional Multiobjective Optimization via Surrogate-assisted Reformulation and Decomposition**  <br>
  Linqiang Pan (Supervisor), <ins>Jianqing Lin</ins>, Handing Wang, Cheng He*, Kay Chen Tan, and Yaochu Jin  <br>
  _IEEE Transactions on Evolutionary Computation, 2024_  <br>
  [[PDF]](https://ieeexplore.ieee.org/document/10477568) [[Code]](https://github.com/jqlincn/TP-SAEA)
- **Supervised Reconstruction for High-dimensional Expensive Multiobjective Optimization**  <br> 
  Hongbin Li, <ins>Jianqing Lin* </ins>, Qing Chen, Cheng He, Linqiang Pan*  <br> 
  _IEEE Transactions on Emerging Topics in Computational Intelligence, 2024_ <br>
  [[PDF]](https://ieeexplore.ieee.org/abstract/document/10428945) [[Code]](https://github.com/jqlincn/SR-SAEA)
- **Multiobjective Trajectory Optimization with a Cutting and Padding Encoding Strategy for Single-UAV-Assisted Mobile Edge Computing System**  <br>
  <ins>Jianqing Lin</ins> and Linqiang Pan*  <br>
  _Swarm and Evolutionary Computation, 2022_  <br> 
  [[PDF]](https://drive.google.com/file/d/1UD1vfxuLSYFMlKe8_gNxVJ2rbqBqHDJ1/view?usp=share_link) <p style="color:blue"> We no longer provide the source code of this paper. </p>
- **Surrogate-Assisted Differential Evolution with Region Division for Expensive Optimization Problems with Discontinuous Responses**  <br>
  Yong Wang (Supervisor), <ins>Jianqing Lin</ins>, Jiao Liu*, Guangyong Sun, and Tong Pang  <br>
  _IEEE Transactions on Evolutionary Computation, 2021_  <br>
  [[PDF]](https://drive.google.com/file/d/1lKJT3K6nAR8dxn4ZcAHp9yDdmlcxZPLQ/view?usp=share_link)
- **Adaptive Dropout for High-dimensional Expensive Multiobjective Optimization**  <br>
  <ins>Jianqing Lin</ins>, Cheng He, and Ran Cheng*  <br>
  _Complex & Intelligent Systems, 2021_  <br>
  [[PDF]](https://link.springer.com/content/pdf/10.1007/s40747-021-00362-5.pdf?pdf=button) [[Code]](https://github.com/jqlincn/ADSAPSO)

## Conference Papers
- **Reference Vector Guided Variables Selection for Expensive Large-scale Multiobjective Optimization**  <br>
  <ins>Jianqing Lin</ins>, Cheng He, Xueming Liu, and Linqiang Pan*   <br>
   _In IEEE World Congress on Computational Intelligence (IEEE WCCI), 2024_
- **Selection of Cancer Biomarkers from Microarray Gene Expression Data Utilizing the Bi-Objective Optimization Method**  <br>
  Hanjing Jiang, <ins>Jianqing Lin</ins>, Huachao Zhu, and Yabing Huang*   <br>
  _In IEEE International Conference on Bioinformatics and Biomedicine (IEEE BIBM), 2023_  <br>
  [[PDF]](https://ieeexplore.ieee.org/abstract/document/10385464)
- **Long Short-Term Memory Network Assisted Evolutionary Algorithm for Computational Expensive Multiobjective Optimization**  <br>
  Cheng He, Hongbin Li*, <ins>Jianqing Lin</ins>, and Zhichao Lu   <br>
  _In IEEE Symposium Series on Computational Intelligence (IEEE SSCI), 2023_  <br>
  [[PDF]](https://ieeexplore.ieee.org/abstract/document/10371889)
- **Dimension Dropout for Evolutionary High-Dimensional Expensive Multiobjective Optimization**  <br>
  <ins>Jianqing Lin</ins>, Cheng He, and Ran Cheng*  <br>
  _In International Conference on Evolutionary Multi-Criterion Optimization (EMO), 2021_  <br>
  [[PDF]](https://drive.google.com/file/d/1BIKD8evvXME8rigSdMiWBVb89YH2w8wI/view?usp=share_link)

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div> -->
<!-- <div class='paper-box-text' markdown="1"> -->

<!-- [Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf) -->

<!-- **Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun -->

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
<!-- - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
<!-- </div> -->
<!-- </div> -->

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- # 🎖 Honors and Awards -->
<!-- - *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
<!-- - *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # 💬 Invited Talks -->
<!-- - *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
<!-- - *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships -->
<!-- - *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->

# 📌 Professional Services
- **Journal Reviewer:**   <br>
  _IEEE Transactions on Evolutionary Computation_   <br>
  _Swarm and Evolutionary Computation_   <br>
  _Complex & Intelligent System_   <br>
