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

I am a first year M.Phil. student in Artificial Intelligence at [Hong Kong University of Science and Technology (Guangzhou)](https://www.hkust-gz.edu.cn/), supervised by [Prof.Ying-Cong Chen](https://www.yingcong.me/), he is super nice! Previously, I obtained a bachelor degree in Network Engneering at [Wuhan University](https://www.whu.edu.cn/) with Honors. 

My research interests include video generation, computer vision.

// # 🔥 News


# 📝 Publications
&dagger;: equal contribution, * : corresponding author

<hr>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MagicCity: Geometry-Aware 3D City Generation from Satellite Imagery with
Multi-View Consistency]()

<dd>Xingbo Yao<sup>&dagger;</sup>, XuanminWang<sup>&dagger;</sup>, Hao WU<sup>&dagger;</sup>, Chengliang PING, Doudou ZHANG, Hui Xiong</dd> 

<dl>
  <dt><img align="left" width="400" src="../images/paper/magiccity.png" alt="MagicCity"></dt>
  <dd><a href="https://arxiv.org/abs/2503.16843" class="publication-title">MagicCity: Geometry-Aware 3D City Generation from Satellite Imagery with
Multi-View Consistency</a></dd>
  <dd>Xingbo Yao<sup>&dagger;</sup>, XuanminWang<sup>&dagger;</sup>, Hao WU<sup>&dagger;</sup>, Chengliang PING, <strong>Doudou ZHANG</strong>,Hui Xiong*</dd>
  <dd>International Conference on Computer Vision <strong>(ICCV)</strong>, 2025</dd>
  <dd style="color:#B02418;"><strong>Oral Presentation</strong></dd>
</dl>


# 🎖 Honors and Awards
- First Class Scholarship of Wuhan University (Award Rate: 5% school-wide), Wuhan University
- Excellent Undergraduate Graduate Award (Top 10%), Wuhan University
- First Prize in National College Students' Mathematical Modeling Contest (November 2021), [China Society for Industrial and Applied Mathematics](https://csiam.org.cn/)
- First Prize in Hubei Province College Students' Mathematics Competition (December 2020), [Hubei Province Mathematical Society](https://www.hbmath.com.cn/)
- First Prize in Asia-Pacific Mathematical Modeling Contest (Top 5%, December 2020), [Beijing Society Of Image And Graphics](https://www.bsig.org.cn/)

# 📖 Educations
- 2024.09 - Now, M.Phil, Artificial Intelligence, Hong Kong University of Science and Technology (Guangzhou).
- 2018.09 - 2023.06, Bachelor, Network Engineering, Wuhan University. 