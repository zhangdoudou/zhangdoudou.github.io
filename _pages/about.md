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
  dl {
    margin-top: 1px;
    margin-bottom: 5px; /* 调整这个值以获得合适的间距 */
    clear: both;
  }

  img {
    display: block;
    margin: 0px 10px 10px 0px; /* 图片居中 上右下左*/ 
    max-width: 100%; /* 限制图片最大宽度 */
  }

  hr {
    border: 1px solid #ebebeb; /* 调整分隔线的颜色和样式 */
    /* margin: 10px;  */
    clear: both; 
  }


  dl dd {
  color: #; 
  margin-top: 1px; 
  margin-bottom: 1px;
}

  dl dd strong {
  font-weight: bold;
  }


  .publication-title {
    font-weight: bold;
  }

  .image-container {
    display: flex;
    justify-content: center;
    gap: 10px; /* 控制图片间距 */
    margin: 20px 0;
  }

  .image-container img {
    max-width: 150px; /* 控制最大宽度 */
    height: auto;
    margin: 0; /* 移除原来的 margin */
  }

  .co-first {
    color: #B02418;
  }

  /* 限制访问者地图的大小 */
  #mapmyvisitors {
    max-width: 100%;
    width: 100%;
    height: auto;
  }

  /* 地图容器样式 */
  .visitor-map-container {
    max-width: 200px;
    width: 100%;
    margin: 10px auto;
    overflow: hidden;
  }

  .visitor-map-container iframe,
  .visitor-map-container div[id*="map"] {
    max-width: 100% !important;
    width: 100% !important;
    height: 150px !important;
  }
  
</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a second year M.Phil. student in Artificial Intelligence at [Hong Kong University of Science and Technology (Guangzhou)](https://www.hkust-gz.edu.cn/), supervised by [Prof.Ying-Cong Chen](https://www.yingcong.me/), he is super nice! Previously, I obtained a bachelor degree in Network Engneering at [Wuhan University](https://www.whu.edu.cn/) with Honors. 

My research interests focus on Diffusion Model and generative models, and particularly on the following topics:
- Controllable Generation
- Generalization of Diffusion Model

<span class='anchor' id='news'></span>
# News
- *2025.09*: &nbsp;🎉 Our paper "Orchestrating Audio: Multi-Agent Framework for Long-Video Audio Synthesis" was accepted to EMNLP 2025.
- *2025.07*: &nbsp;🎉 Our paper "MagicCity: Geometry-Aware 3D City Generation from Satellite Imagery with Multi-View Consistency" was accepted to ICCV 2025.
- *2024.09*: &nbsp;🎉 I started my M.Phil. study at HKUST(GZ) under the supervision of Prof.Ying-Cong Chen.


<span class='anchor' id='publications'></span>
# Publications
&dagger;: equal contribution, * : corresponding author

<hr>

- **MagicCity: Geometry-Aware 3D City Generation from Satellite Imagery with Multi-View Consistency**<br>
  Xingbo Yao<sup>&dagger;</sup>, XuanminWang<sup>&dagger;</sup>, Hao WU<sup>&dagger;</sup>, Chengliang PING, <strong>Doudou ZHANG</strong>,Hui Xiong<sup>*</sup><br>
  International Conference on Computer Vision <strong>(ICCV)</strong>, 2025<br>
  [<a href="https://openaccess.thecvf.com/content/ICCV2025/html/Yao_MagicCity_Geometry-Aware_3D_City_Generation_from_Satellite_Imagery_with_Multi-View_ICCV_2025_paper.html" target="_blank">paper</a>]
<hr>

- **Orchestrating Audio: Multi-Agent Framework for Long-Video Audio Synthesis**<br>
  Yehang Zhang<sup>&dagger;</sup>, Xinli Xu<sup>&dagger;</sup>, Xiaojie Xu<sup>&dagger;</sup>, <strong>Doudou Zhang</strong>, Li Liu<sup>*</sup>, Ying-Cong Chen<sup>*</sup><br>
  Conference on Empirical Methods in Natural Language Processing <strong>(EMNLP)</strong>, 2025<br>
  [<a href="https://aclanthology.org/2025.emnlp-main.1133/" target="_blank">paper</a>] [<a href="https://github.com/Yehang-Zhang/Orchestrating-Audio" target="_blank">project page</a>]



# Internships
- 2025.08 - 2025.12, Intern, [Tencent](https://www.tencent.com/), Beijing, China.

<div class="visitor-map-container" style="text-align: center; margin-top: 30px;">
  <script type="text/javascript" id="mapmyvisitors" src="//mapmyvisitors.com/map.js?d=0htbO1aW3-I8XHiS_BNNqtV-BaMFOWnlRk40-OGO_R0&cl=ffffff&w=a"></script>
</div>