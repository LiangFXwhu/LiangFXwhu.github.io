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

I am currently a **Postdoc** in the State Key Laboratory of Information Engineering in Surveying, Mapping and Remote Sensing ([LIESMARS](http://www.lmars.whu.edu.cn/en/)), [Wuhan University](https://en.whu.edu.cn/), supervised by [Prof. Bisheng Yang(杨必胜)](https://3s.whu.edu.cn/ybs/index.htm) and [Prof. Zhen Dong(董震)](https://dongzhenwhu.github.io/). I received my Ph.D. in **Photogrammetry and Remote Sensing** at Wuhan University in 2022, under the supervision of Prof. Bisheng Yang.

My research interest includes point cloud processing and its application in urban sustainability. I have published more than 20 SCI-indexed articles with total <a href='https://scholar.google.com/citations?user=0Ds4eg8AAAAJ'>google scholar citations <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.


# 🔥 News
- *2024.12*: &nbsp;🎉🎉 [Ubiquitous Point Cloud: Theory, Model, and Applications.](https://www.routledge.com/Ubiquitous-Point-Cloud-Theory-Model-and-Applications/Yang-Dong-Liang-Mi/p/book/9781032780467?srsltid=AfmBOopMlU9_-C1wwiMrj6V2uylpxPnOAX43h4ODcvQWSRe0Khah0930) Co-authored with Prof. Bisheng Yang, Prof. Zhen Dong, and Dr. Xiaoxin Mi, our book has been published. 
- *2024.11*: &nbsp;🎉🎉 ["Advances in 3D Reconstruction Based on Remote Sensing Imagery and Lidar Point Cloud"](https://www.mdpi.com/journal/remotesensing/special_issues/75XR49T52J), a new Special Issue has been published in the journal Remote Sensing (ISSN 2072-4292). My pleasure to serve as a Guest Editor with [Dr. Shuang Song](https://u.osu.edu/qin.324/members/) and [Dr. Bing Wang](https://www.polyu.edu.hk/aae/people/academic-staff/dr-wang-bing/).


# 📝 Selected Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CRC Press</div><img src='images/UbiquitousPointCloud-mini.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Ubiquitous Point Cloud: Theory, Model, and Applications](https://www.routledge.com/Ubiquitous-Point-Cloud-Theory-Model-and-Applications/Yang-Dong-Liang-Mi/p/book/9781032780467?srsltid=AfmBOopMlU9_-C1wwiMrj6V2uylpxPnOAX43h4ODcvQWSRe0Khah0930)

Bisheng Yang, Zhen Dong, **Fuxun Liang**, Xiaoxin Mi
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISPRS 2024</div><img src='images/2024-ISPRS-LAWS.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Look at the whole scene: General point cloud place recognition by classification proxy](https://www.sciencedirect.com/science/article/pii/S0924271624002557)(SCI1-TOP, IF:10.6)

Yue Xie, Bing Wang, Haiping Wang, **Fuxun Liang**, Wenxiao Zhang, Zhen Dong, Bisheng Yang (Corresponding author)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISPRS 2020</div><img src='images/2020-ISPRS-SkylineContext.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A novel skyline context descriptor for rapid localization of terrestrial laser scans to airborne laser scanning point clouds](https://www.sciencedirect.com/science/article/abs/pii/S0924271620301155)(SCI1-TOP, IF:12.7)

**Fuxun Liang**, Bisheng Yang, Zhen Dong, Ronggang Huang, Yufu Zang, Yue Pan
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISPRS 2020</div><img src='images/2020-ISPRS-WHU-TLS.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Registration of large-scale terrestrial laser scanner point clouds: A review and benchmarkc](https://www.sciencedirect.com/science/article/abs/pii/S0924271620300836)(SCI1-TOP, IF:10.6)

Zhen Dong, **Fuxun Liang**, Bisheng Yang, Yusheng Xu, Yufu Zang, Jianping Li, Yuan Wang, Wenxia Dai, Hongchao Fan, Juha Hyyppä, Uwe Stilla
</div>
</div>

+ ``RAL 2024``  [CoFiI2P: Coarse-to-Fine Correspondences-Based Image-to-Point Cloud Registration.](https://ieeexplore.ieee.org/document/10685082)(SCI2-TOP, IF:  4.6)   
[Shuhao Kang](https://kang-1-2-3.github.io/),[Youqi Liao](https://martin-liao.github.io/), [Jianping Li](https://kafeiyin00.github.io/), **FuxunLiang**, Yuhao Li, Xianghong Zou, Fangning Li, Xieyuanli Chen, [Zhen Dong](https://dongzhenwhu.github.io/), [Bisheng Yang](https://3s.whu.edu.cn/ybs/index.htm).     
[Arxiv](https://arxiv.org/abs/2309.14660v2) \| [ProjectPage](https://whu-usi3dv.github.io/CoFiI2P/) \| [Code](https://github.com/WHU-USI3DV/CoFiI2P).

+ ``RS 2024`` [Investigating Dual-Source Satellite Image Data and ALS Data for Estimating Aboveground Biomass.](https://www.mdpi.com/2072-4292/16/10/1804)(SCI2, IF:  4.2)    
Wen Fan, Jiaojiao Tian, Thomas Knoke, Bisheng Yang, **Fuxun Liang**, Zhen Dong.  

+ ``ISPRS 2023`` [PatchAugNet: Patch feature augmentation-based heterogeneous point cloud place recognition in large-scale street scenes.](https://www.sciencedirect.com/science/article/abs/pii/S0924271623003106)(SCI1-TOP, IF:12.7).  
Xianghong Zou, Jianping Li, Yuan Wang, **Fuxun Liang**, Weitong Wu, Haiping Wang, Bisheng Yang, Zhen Dong. 

+ ``ISPRS 2023`` [MuCoGraph: A multi-scale constraint enhanced pose-graph framework for MLS point cloud inconsistency correction.](https://www.sciencedirect.com/science/article/abs/pii/S0924271623002599) (SCI1-TOP, IF:12.7)    
Yuhao Li, Xianghong Zou, Tian Li, Sihan Sun, Yuan Wang, **Fuxun Liang**, Jiangping Li, Bisheng Yang, Zhen Dong. 

+ ``GPS Solutions 2023`` [Satellite visibility analysis considering signal attenuation by trees using airborne laser scanning point cloud.](https://link.springer.com/article/10.1007/s10291-023-01404-w) (SCI1-TOP, IF:4.9)    
Ruixiong Kou, Renchun Tan, Shiyun Wang, Bisheng Yang, Zhen Dong, Shuwen Yang, **Fuxun Liang**. 

+ ``BnE 2023`` [Modeling urban canopy air temperature at city-block scale based on urban 3D morphology parameters–A study in Tianjin, North China.](https://www.sciencedirect.com/science/article/abs/pii/S0360132323000276) (SCI1-TOP, IF:7.4)    
Xiaorui Li, Bisheng Yang, **Fuxun Liang**, Hongsheng Zhang, Yong Xu, Zhen Dong. 

+ ``ISPRS 2023`` [CAOM: Change-aware online 3D mapping with heterogeneous multi-beam and push-broom LiDAR point clouds.](https://www.sciencedirect.com/science/article/abs/pii/S0924271622003100) (SCI1-TOP, IF:12.7)    
Yangzi Cong, Chi Chen, Bisheng Yang, **Fuxun Liang**, Ruiqi Ma, Fei Zhang. 

# 🎖 Selected Honors and Awards
- *2023*, Science and Technology Progress Award in Natural Resources, **Second** Class Prize.  
(2023年自然资源科技进步二等奖，10/10)
- *2019*, Science and Technology Progress Award in Surveying and Mapping, **Outstanding award**.   
(2019年测绘科技进步特等奖，15/15)

# 📖 Educations
- *2014.09 - 2022.06*, Ph.D in Photogrammetry and Remote Sensing, LIESMARS, Wuhan University, Wuhan.   
(武汉大学，测绘遥感信息工程国家重点实验室，摄影测量与遥感专业，博士)
- *2007.09 - 2011.06*, B.S., School of Geodesy and Geomatics, Wuhan University, Wuhan.  
(武汉大学，测绘学院，学士)