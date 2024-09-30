---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>

  <div class="flex-row" onmouseout="par2net_stop()" onmouseover="par2net_start()">
    <div class="image-container">
      <img src="../images/500x300.png" width="160" alt="Image">
    </div>
    <div class="text-container">
      <papertitle>Color4E: Event demosaicing for full-color event guided image deblurring</papertitle>
      <br>
      Yi Ma<sup>#</sup>,<strong>Peiqi Duan<sup>#</sup></strong>, Yuchen Hong, Chu Zhou, Yu Zhang, Jimmy Ren, and Boxin Shi<sup>*</sup>
      <br>
      <em>ACM MM</em>, 2024
      <br>
    </div>
  </div>

  <div class="flex-row" onmouseout="par2net_stop()" onmouseover="par2net_start()">
  <div class="image-container">
    <img src="../images/500x300.png" width="160" alt="Image">
  </div>
  <div class="text-container">
    <papertitle>EvDiG: Event-guided direct and global components separation</papertitle>
    <br>
    Xinyu Zhou, <strong>Peiqi Duan</strong>strong>, Boyu Li, Chu Zhou, Chao Xu, and Boxin Shi<sup>*</sup>
    <br>
    <em>CVPR</em>, 2023
    <br>
    <a href="https://assets.ctfassets.net/yreyglvi5sud/4rrKmGuR98bvBBmLlZK7i3/7c2a00d49adde30a4caba7cdec852f24/Zhou_CVPR24.pdf">[paper]</a> 
    <a href="https://www.youtube.com/watch?v=y0bMZnUJt14">[video]</a>
  </div>

    
</div>

<style>
    /* Flexbox 容器 */
    .flex-row {
      display: flex;
      align-items: center; /* 垂直居中 */
      padding: 20px;
      /* 可选：添加背景颜色或其他样式 */
      /* background-color: #f9f9f9; */
    }

    /* 图片容器 */
    .image-container {
      flex: 0 0 160px; /* 固定宽度 */
      margin-right: 20px; /* 图片与文字之间的间距 */
    }

    /* 确保图片不带边框且适应容器 */
    .image-container img {
      display: block;
      width: 160px;
      height: auto;
    }

    /* 文字容器 */
    .text-container {
      flex: 1; /* 占据剩余空间 */
    }

    /* 自定义 papertitle 样式 */
    papertitle {
      font-size: 1.2em;
      font-weight: bold;
    }

    /* 移除默认的表格样式（如果仍在使用表格） */
    table, td {
      border: none;
      padding: 0;
    }
  </style>
