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

---

<div class="img-card">
  <a href="https://doi-org.proxy.library.nyu.edu/10.1177/23998083221103261">
    <img src="/images/mobility_pattern.jpg"
         alt="Land use patterns"
         style="width:100%">
    <div class="overlay"><span class="btn-view">More Details</span></div>
  </a>
</div>
<strong>
      <span>
        Human Mobility and Land Use Patterns
      </span>
    </strong><br>
Land use functions can categorize places where people perform different socioeconomic activities. However, mobility patterns might vary significantly even within the same land use function as conventionally defined. This project explores land use subcategorization using mobile phone-derived human activities. 

<br>

<div class="img-card">
  <a href="https://urban.shanghai.nyu.edu/planning-environmentally">
    <img src="/images/rhythmized_parks.jpg"
         alt="Rythmized Parks"
         style="width:100%">
    <div class="overlay"><span class="btn-view">More Details</span></div>
  </a>
</div>
<strong>
      <span>
        Planning for Rhythmized Urban Parks
      </span>
    </strong><br>
This project proposes a paradigm shift in classifying, programming, and designing parks. Utilizing 1.5 million mobile phone records, we classified 254 urban parks in Tokyo based on their visitation patterns across different times of the day, week, and year. 

<br>

<div class="img-card">
  <a href="https://salatainstitute.harvard.edu/economics-and-policy-of-electric-transportation-charging-infrastructure/">
    <img src="/images/synthetic_EV.jpg"
         alt="EV"
         style="width:100%">
    <div class="overlay"><span class="btn-view">More Details</span></div>
  </a>
</div>
<strong>
      <span>
        New York City Synthetic Electric Vehicles
      </span>
    </strong><br>
This project uses National Household Travel Survey (NHTS) data, Atlas EV Registration data, and machine learning models to forecast EV ownership for a synthetic population. The proposed model predicts the number of EVs per zip code and assigns EVs to households.

<br>

<div class="img-card">
  <a href="https://aaa">
    <img src="/images/twitter_topics.jpg"
         alt="Twitter topics"
         style="width:100%">
    <div class="overlay"><span class="btn-view">More Details</span></div>
  </a>
</div>
<strong>
      <span>
        Detecting Climate Change Perception Gaps using LLMs
      </span>
    </strong><br>
Our team integrated 195 Nationally Determined Contributions (NDCs) with approximately 400,000 climate-related Twitter posts from January to December 2022. We employed ClimateBERT to quantify global and city-level gaps between governmental action and public perception.

<br>

### Choice Modeling with Large-scale Dataset

---

<div class="img-card">
  <a href="https://doi.org/10.1016/j.trb.2022.11.005">
    <img src="/images/AMXL_distribution.jpg"
         alt="AMXL Distribution"
         style="width:100%">
    <div class="overlay"><span class="btn-view">More Details</span></div>
  </a>
</div>
<strong>
      <span>
        Agent-based Mixed Logit Model (AMXL)
      </span>
    </strong><br>
We propose an agent-based mixed-logit model (AMXL) that is estimated with inverse optimization (IO) estimation. The method provides joint, individual-specific, and deterministic estimation, which overcomes the limitations of discrete choice models (DCMs) given ubiquitous datasets.

<br>

<div class="img-card">
  <a href="https://doi.org/10.1016/j.trb.2025.103220">
    <img src="/images/GLAM_distribution.jpg"
         alt="GLAM Distribution"
         style="width:100%">
    <div class="overlay"><span class="btn-view">More Details</span></div>
  </a>
</div>
<strong>
      <span>
        Market-level Nonparametric Mixed Logit Model
      </span>
    </strong><br>
This project proposes a nonparametric mixed logit model that is estimated using market-level choice share data. The model treats each market as an agent and represents taste heterogeneity through market-specific parameters by solving a multiagent inverse utility maximization problem.

<br>

<div class="img-card">
  <a href="https://aaa">
    <img src="/images/EVCS_location.jpg"
         alt="EVCS"
         style="width:100%">
    <div class="overlay"><span class="btn-view">More Details</span></div>
  </a>
</div>
<strong>
      <span>
        Modeling EV Charging Behavior using Individual Mobility Data
      </span>
    </strong><br>
This NSF-SAI project focuses on an equitable and efficient allocation of EVCSs that benefits not only EV drivers but also supports the economic growth of the community. We leverage mobility phone data and apply AMXL to EV charging behavior modeling in Bay Area.

<br>

### Equity-aware Transportation Logistics

---

<div class="img-card">
  <a href="https://doi.org/10.1016/j.trd.2024.104255">
    <img src="/images/service_design.jpg"
         alt="Decision Support Tool"
         style="width:100%">
    <div class="overlay"><span class="btn-view">More Details</span></div>
  </a>
</div>
<strong>
      <span>
        Mobility Service Decision Support Tool
      </span>
    </strong><br>
We integrate synthetic population data and a choice-based optimization model to support large-scale mobility service region design with equity concerns. We test using New York State synthetic data and illustrate its application by considering new ride-hailing and microtransit services.

<br>

<div class="img-card">
  <a href="https://doi.org/10.48550/arXiv.2408.12577">
    <img src="/images/microtransit.jpg"
         alt="Microtransit"
         style="width:100%">
    <div class="overlay"><span class="btn-view">More Details</span></div>
  </a>
</div>
<strong>
      <span>
        Microtransit Revenue Management for Arlington Via
      </span>
    </strong><br>
We propose a nested nonparametric model for joint travel mode and ride pass subscription choice, estimated using marginal subscription data and synthetic populations. We apply our methodology to a case study in Arlington, TX, using synthetic data from Replica Inc. and microtransit data from Via.

<br>

<div class="img-card">
  <a href="https://aaa">
    <img src="/images/mobility_hub.jpg"
         alt="Mobility_hub"
         style="width:100%">
    <div class="overlay"><span class="btn-view">More Details</span></div>
  </a>
</div>
<strong>
      <span>
        Mobility Hub Location Selection
      </span>
    </strong><br>
We combine data from a survey conducted by the Capital District Transportation Authority (CDTA) with a mode choice model estimated using Replica Inc.’s synthetic data. The framework is applied to the evaluation of potential hub candidates in the Albany-Schenectady-Troy metropolitan area.
