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
  border-radius: 8px;         /* 圆角大小 */
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
</style>


### Urban Computing and AI

<table>
<tr>
  <!-- 1 ▸ Human Mobility and Land Use -->
  <td width="50%" valign="top">
    <a href="https://doi-org.proxy.library.nyu.edu/10.1177/23998083221103261">
      <img src="/images/mobility_pattern.jpg"
           alt="Mobility patterns"
           style="width:93%; border-radius:4px;">
    </a><br>
    <strong>
      <a href="https://doi-org.proxy.library.nyu.edu/10.1177/23998083221103261">
        Human Mobility and Land Use Patterns
      </a>
    </strong><br>
    Explore the land use functional variance based on mobile phone derived human activity in Shanghai
  </td>

  <!-- 2 ▸ Human Mobility and Land Use -->
  <td width="50%" valign="top">
    <a href="https://doi-org.proxy.library.nyu.edu/10.1177/23998083221103261">
      <img src="/images/mobility_pattern.jpg"
           alt="Mobility patterns"
           style="width:93%; border-radius:4px;">
    </a><br>
    <strong>
      <a href="https://doi-org.proxy.library.nyu.edu/10.1177/23998083221103261">
        Human Mobility and Land Use Patterns
      </a>
    </strong><br>
    Explore the land use functional variance based on mobile phone derived human activity in Shanghai
  </td>
</tr>

<table>
<tr>
  <!-- 1 ▸ Human Mobility and Land Use -->
  <td width="50%" valign="top">
    <a href="https://doi-org.proxy.library.nyu.edu/10.1177/23998083221103261">
      <img src="images/mobility_pattern.jpg"
           alt="Mobility patterns"
           style="width:90%; border-radius:4px;">
    </a><br>
    <strong>
      <span>
        Human Mobility and Land Use Patterns
      </span>
    </strong><br>
    Explore the land use functional variance based on mobile phone derived human activity in Shanghai
  </td>
</tr>

<br>
