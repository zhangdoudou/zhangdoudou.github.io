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

# News
- *2025.09*: &nbsp;🎉 Our paper "Orchestrating Audio: Multi-Agent Framework for Long-Video Audio Synthesis" was accepted to EMNLP 2025.
- *2025.07*: &nbsp;🎉 Our paper "MagicCity: Geometry-Aware 3D City Generation from Satellite Imagery with Multi-View Consistency" was accepted to ICCV 2025.
- *2024.09*: &nbsp;🎉🎉 I started my M.Phil. study at HKUST(GZ) under the supervision of Prof.Ying-Cong Chen.


# Publications
&dagger;: equal contribution, * : corresponding author

<hr>

<dl>
  <!-- <dt><img align="left" width="400" src="../images/papers/magiccity.png" alt="MagicCity"></dt> -->
  <dd><a href="https://openaccess.thecvf.com/content/ICCV2025/html/Yao_MagicCity_Geometry-Aware_3D_City_Generation_from_Satellite_Imagery_with_Multi-View_ICCV_2025_paper.html" class="publication-title">MagicCity: Geometry-Aware 3D City Generation from Satellite Imagery with
Multi-View Consistency</a></dd>
  <dd>Xingbo Yao<sup>&dagger;</sup>, XuanminWang<sup>&dagger;</sup>, Hao WU<sup>&dagger;</sup>, Chengliang PING, <strong>Doudou ZHANG</strong>,Hui Xiong<sup>*</sup></dd>
  <dd>International Conference on Computer Vision <strong>(ICCV)</strong>, 2025</dd>
  <dd style="color:#B02418;"><strong>Poster</strong></dd>
</dl>

<hr>

<dl>
  <!-- <dt></dt> -->
  <dd><a href="https://aclanthology.org/2025.emnlp-main.1133/" class="publication-title">Orchestrating Audio: Multi-Agent Framework for Long-Video Audio Synthesis</a></dd>
  <dd>Yehang Zhang<sup>&dagger;</sup>, Xinli Xu<sup>&dagger;</sup>, Xiaojie Xu<sup>&dagger;</sup>, <strong>Doudou Zhang</strong>, Li Liu<sup>*</sup>, Ying-Cong Chen<sup>*</sup></dd>
  <dd>Conference on Empirical Methods in Natural Language Processing <strong>(EMNLP)</strong>, 2025</dd>
  <dd style="color:#B02418;"><strong>Conference</strong></dd>
</dl>


<!--
# 🎖 Honors and Awards
- First Class Scholarship of Wuhan University (Award Rate: 5% school-wide), Wuhan University
- Excellent Undergraduate Graduate Award (Top 10%), Wuhan University
- First Prize in National College Students' Mathematical Modeling Contest (November 2021), [China Society for Industrial and Applied Mathematics](https://csiam.org.cn/)
- First Prize in Hubei Province College Students' Mathematics Competition (December 2020), [Hubei Province Mathematical Society](https://www.hbmath.com.cn/)
- First Prize in Asia-Pacific Mathematical Modeling Contest (Top 5%, December 2020), [Beijing Society Of Image And Graphics](https://www.bsig.org.cn/)

# 📖 Educations
- 2024.09 - Now, M.Phil, Artificial Intelligence, Hong Kong University of Science and Technology (Guangzhou).
- 2018.09 - 2023.06, Bachelor, Network Engineering, Wuhan University. 
-->

<hr>

<div style="text-align: center; margin-top: 10px;">
  <span>Website visitors:</span><br>
  <script type="text/javascript" src="https://www.free-counters.org/count/jc8o"></script><br>
 <a href='http://www.counter-zaehler.de'>wordpress counter</a> <script type='text/javascript' src='https://whomania.com/ctr?id=ccce772c68d7b53b8c64bab19f459e873e9f95e8'></script>
</div>