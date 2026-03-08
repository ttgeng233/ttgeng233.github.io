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
<!-- <!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>Publications</title> -->

<style>

.paper-list {
  list-style: none;
  padding: 0;
}

.paper-item {
  display: flex;
  align-items: flex-start;
  gap: 18px;
  margin-bottom: 28px;
}

.paper-thumb {
  width: 160px;
  border-radius: 6px;
  cursor: pointer;
  transition: transform 0.2s ease;
}

.paper-thumb:hover {
  transform: scale(1.03);
}

.paper-info {
  flex: 1;
}

.paper-title {
  font-size: 16px;
  font-weight: 600;
  margin: 0 0 4px 0;
}

.paper-title a {
  text-decoration: none;
  color: #222;
}

.paper-title a:hover {
  text-decoration: underline;
}

.paper-authors {
  font-size: 12px;
  color: #666;
  margin-bottom: 4px;
}

.paper-meta {
  display: flex;
  align-items: center;
  font-size: 13px;
}

.paper-conf {
  font-weight: 600;
  color: #b31b1b;
  margin-right: 12px;
}

.paper-links {
  display: flex;
  align-items: center;
}

.paper-links a {
  font-size: 13px;
  margin-right: 8px;
  text-decoration: none;
  color: #095b7c;
}

.paper-links a:hover {
  text-decoration: underline;
}

/* 图片放大 overlay */

#overlay {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0,0,0,0.85);
  display: none;
  align-items: center;
  justify-content: center;
  z-index: 9999;
}

#overlay img {
  max-width: 90%;
  max-height: 90%;
  border-radius: 6px;
}

/* 手机适配 */

@media (max-width: 768px) {

  .paper-item {
    flex-direction: column;
  }

  .paper-thumb {
    width: 100%;
    max-width: 320px;
  }

}

</style>
</head>

<body>

<h2>Publications</h2>

<ul class="paper-list">

<li class="paper-item">

<img class="paper-thumb"
src="/images/fig_longvale.jpg"
data-large-src="/images/fig_longvale.jpg"
alt="LongVALE">

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

</ul>

<!-- 图片放大层 -->

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
overlay.style.display = "flex";

});

});

overlay.addEventListener("click", function() {

overlay.style.display = "none";

});

});

</script>

</body>
</html>