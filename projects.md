---
layout: page
permalink: /projects/index.html
title: Projects
---


<style>
/* ① 卡片容器 */
.img-card {
  position: relative;
  display: inline-block;      /* 让多张卡片自动排布 */
  overflow: hidden;           /* 裁掉圆角外溢部分 */
  border-radius: 15px;       /* 圆角大小 */
}

/* ② 图片本身 */
.img-card img {
  width: 100%;
  height: auto;
  display: block;
}

/* ③ 悬停遮罩 */
.img-card .overlay {
  position: absolute;
  inset: 0;                   /* 等价于 top/right/bottom/left:0 */
  background: rgba(0,0,0,0.55);
  color: #fff;
  font-size: 20px;
  font-weight: 600;
  display: flex;
  align-items: center;
  justify-content: center;
  opacity: 0;                 /* 默认透明 */
  transition: opacity .25s ease;
}

/* ④ 当鼠标悬停在卡片上，显示 “view” */
.img-card:hover .overlay {
  opacity: 1;
}

.img-card .btn-view {
  padding: 6px 22px;
  border: 2px solid #fff;
  border-radius: 4px;
  font-size: 18px;
  font-weight: 600;
  color: #fff;
  background: transparent;   /* keeps only the white border */
}

</style>


### Urban Computing and AI
<a href="https://doi-org.proxy.library.nyu.edu/10.1177/23998083221103261">
  <div class="img-card">
    <img src="images/mobility_pattern.jpg"
         alt="Capture Pedestrian Flows"
         style="width:100%">
    <div class="overlay"><span class="btn-view">More Details</span></div>
  </div>
</a>
<br>
<strong>
      <span>
        Human Mobility and Land Use Patterns
      </span>
    </strong><br>
Land use functions can categorize places where people perform different socioeconomic activities. However, mobility patterns might vary significantly even within the same land use function as conventionally defined. This project explores land use subcategorization using mobile phone-derived human activities. 


<br>
<br>

<a href="https://doi-org.proxy.library.nyu.edu/10.1177/23998083221103261">
  <div class="img-card">
    <img src="images/mobility_pattern.jpg"
         alt="Capture Pedestrian Flows"
         style="width:100%">
    <div class="overlay"><span class="btn-view">More Details</span></div>
  </div>
</a>
<br>
<strong>
      <span>
        Human Mobility and Land Use Patterns
      </span>
    </strong><br>
Explore the land use functional variance based on mobile phone derived human activity in Shanghai

