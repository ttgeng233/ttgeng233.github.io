---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I am Tiantian, a PhD candidate in computer science at University of Birmingham (2022-2026), supervised by [Prof. Jinming Duan](https://j-duan.github.io/) and [Prof. Feng Zheng](https://faculty.sustech.edu.cn/?tagid=fengzheng&iscss=1&snapid=1&orderby=date&go=2) (SUSTech). Before that, I received my Bachelor’s degree and Master’s degree from University of Electronic Science and Technology of China (UESTC) in 2019 and 2022.

My research interests are focused on computer vision, multi-modal learning, video understanding. I am also interested in multi-modal large models and embodied AI. 

<h1 id="-news">News</h1>
<ul>
  <li><em>2025.11</em>: 🎉 One paper has been accepted to <strong>AAAI 2026</strong>.</li>
  <li><em>2025.07</em>: 🎉 One paper has been accepted to <strong>TPAMI 2025</strong>.</li>
  <li><em>2025.02</em>: 🎉 One paper has been accepted to <strong>CVPR 2025</strong>.</li>
  <li><em>2025.01</em>: 🎉 One paper has been accepted to <strong>ICLR 2025 Spotlight</strong>.</li>
</ul>



<!-- # Publications -->

<h1 id="-publications">Publications</h1>
<style>
ul.paper-list {
  list-style-type: none;
  padding: 0;
}

.paper-item {
  display: flex;
  align-items: flex-start;
  margin-bottom: 20px;
}

.paper-thumb {
  width: 150px;
  height: 100px;
  flex-shrink: 0;
  margin-right: 15px;
  border: 1px solid #ccc;
  border-radius: 5px;
  object-fit: cover;
  cursor: pointer;
}

.paper-info {
  font-family: Arial, sans-serif;
}

.paper-title {
  font-weight: bold;
  font-size: 18px;
  margin: 0 0 6px;
}

.paper-title a {
  text-decoration: none;
  color: #095b7c;
}

.paper-authors {
  font-weight: 500;
  color: #666;
  margin-bottom: 4px;
}

.paper-meta {
  font-size: 13px;
  display: flex;
  align-items: center;
}

.paper-conf {
  font-weight: 500;
  color: #b31b1b;
  margin-right: 12px;
}

.paper-links {
  display: flex;
  align-items: center;
}

.paper-links a {
  color: #095b7c;
  text-decoration: none;
  font-size: 13px;
  margin-right: 8px;
}

/* overlay image viewer */
#overlay {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0,0,0,0.8);
  display: flex;
  align-items: center;
  justify-content: center;
  z-index: 9999;
  visibility: hidden;
}

#overlay img {
  max-width: 80%;
  max-height: 80%;
  border-radius: 5px;
  box-shadow: 0 4px 10px rgba(255,255,255,0.4);
  cursor: pointer;
}
</style>

<ul class="paper-list">

<li class="paper-item">

<img class="paper-thumb"
src="/images/papers/unavale.png"
data-large-src="/images/papers/unavale.png">

<div class="paper-info">

<p class="paper-title">
<a href="#" target="_blank">
UniAV: Unified Audio-Visual Perception for Multi-Task Video Event Localization
</a>
</p>

<p class="paper-authors">
<b>Tiantian Wang</b>, ...
</p>

<p class="paper-meta">
<span class="paper-conf">TPAMI 2025</span>
<span class="paper-links">
<a href="#">[Paper]</a>
<a href="#">[Project]</a>
<a href="#">[Code]</a>
</span>
</p>

</div>
</li>


<li class="paper-item">

<img class="paper-thumb"
src="/images/fig_longvale.jpg"
data-large-src="/images/fig_longvale.jpg">

<div class="paper-info">

<p class="paper-title">
<a href="https://openaccess.thecvf.com/content/CVPR2025/html/Geng_LongVALE_Vision-Audio-Language-Event_Benchmark_Towards_Time-Aware_Omni-Modal_Perception_of_Long_Videos_CVPR_2025_paper.html" target="_blank">
LongVALE: Vision-Audio-Language-Event Benchmark Towards Time-Aware Omni-Modal Perception of Long Videos
</a>
</p>

<p class="paper-authors">
<b>Tiantian Geng</b>, Jinrui Zhang, Qingni Wang, Teng Wang, Jinming Duan, Feng Zheng
</p>

<p class="paper-meta">
<span class="paper-conf">CVPR 2025</span>
<span class="paper-links">
<a href="https://openaccess.thecvf.com/content/CVPR2025/papers/Geng_LongVALE_Vision-Audio-Language-Event_Benchmark_Towards_Time-Aware_Omni-Modal_Perception_of_Long_Videos_CVPR_2025_paper.pdf">[Paper]</a>
<a href="https://ttgeng233.github.io/LongVALE/">[Project]</a>
<a href="https://github.com/ttgeng233/LongVALE">[Code]</a>
<a href="https://huggingface.co/datasets/ttgeng233/LongVALE">[Data]</a>
</span>
</p>

</div>
</li>


<li class="paper-item">

<img class="paper-thumb"
src="/images/papers/unav100.png"
data-large-src="/images/papers/unav100.png">

<div class="paper-info">

<p class="paper-title">
<a href="#" target="_blank">
Dense-Localizing Audio-Visual Events in Untrimmed Videos: A Large-Scale Benchmark and Baseline
</a>
</p>

<p class="paper-authors">
<b>Tiantian Wang</b>, ...
</p>

<p class="paper-meta">
<span class="paper-conf">ICLR 2025 Spotlight</span>
<span class="paper-links">
<a href="#">[Paper]</a>
<a href="#">[Project]</a>
<a href="#">[Code]</a>
</span>
</p>

</div>
</li>

</ul>

<div id="overlay">
<img id="overlay-img">
</div>


<script>

document.addEventListener("DOMContentLoaded", function() {

  const thumbs = document.querySelectorAll(".paper-thumb");
  const overlay = document.getElementById("overlay");
  const overlayImg = document.getElementById("overlay-img");

  thumbs.forEach(function(img) {
    img.addEventListener("click", function() {
      overlayImg.src = img.getAttribute("data-large-src");
      overlay.style.visibility = "visible";
    });
  });

  overlay.addEventListener("click", function() {
    overlay.style.visibility = "hidden";
  });

});

</script>



