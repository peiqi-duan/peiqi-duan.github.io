
---
permalink: /
title: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a Research Assistant Professor at the School of Computer Science, Peking University (PKU), working with Prof. <a href="https://scholar.google.com/citations?hl=zh-CN&user=K1LjZxcAAAAJ">Boxin Shi</a> in the <a href="https://camera.pku.edu.cn/">Camera Intelligence Lab</a>. I received my Ph.D. degree in Computer Science from Peking University in 2023, where I subsequently served as a Boya Postdoctoral Fellow. My research interests include computational photography, event-based imaging and vision, and imaging and sensing under challenging conditions.

<style>
/* ===== Homepage News ===== */

.home-news {
  width: 100%;
  margin: 28px 0 36px;
  font-family: inherit;
}

.home-news .news-heading {
  margin: 0 0 12px;
  padding-bottom: 10px;
  font-size: 1.5em;
  font-weight: 700;
  border-bottom: 1px solid #e5e7eb;
}

.home-news .news-item {
  display: grid;
  grid-template-columns: 88px minmax(0, 1fr);
  column-gap: 18px;
  padding: 17px 0;
  border-bottom: 1px solid #edf0f2;
}

.home-news .news-date {
  padding-top: 3px;
  color: #8b949e;
  font-size: 0.72em;
  font-weight: 600;
  letter-spacing: 0.4px;
  line-height: 1.6;
  white-space: nowrap;
}

.home-news .news-content {
  min-width: 0;
}

.home-news .news-title {
  margin: 0 0 5px;
  color: inherit;
  font-size: 0.96em;
  font-weight: 600;
  line-height: 1.55;
}

.home-news .news-desc {
  margin: 0;
  color: #687180;
  font-size: 0.85em;
  font-weight: 400;
  line-height: 1.75;
}

.home-news .news-desc a {
  color: #2864a0;
  text-decoration: none;
  border-bottom: 1px solid transparent;
  transition: border-color 0.2s ease;
}

.home-news .news-desc a:hover {
  border-bottom-color: currentColor;
}

.home-news .news-older {
  margin-top: 12px;
}

.home-news .news-older summary {
  display: list-item;
  width: fit-content;
  padding: 9px 0;
  color: #687180;
  font-size: 0.83em;
  font-weight: 500;
  cursor: pointer;
}

.home-news .news-older summary:hover {
  color: #2864a0;
}

.home-news .news-older[open] summary {
  margin-bottom: 4px;
}

.home-news .news-older .news-item:last-child {
  border-bottom: none;
}

/* Dark mode support */
@media (prefers-color-scheme: dark) {
  .home-news .news-heading {
    border-bottom-color: #424750;
  }

  .home-news .news-item {
    border-bottom-color: #373c44;
  }

  .home-news .news-date {
    color: #a0a7b2;
  }

  .home-news .news-desc,
  .home-news .news-older summary {
    color: #b1b8c2;
  }

  .home-news .news-desc a {
    color: #8dbcf0;
  }
}

/* Mobile layout */
@media (max-width: 600px) {
  .home-news .news-item {
    grid-template-columns: minmax(0, 1fr);
    row-gap: 4px;
    padding: 14px 0;
  }

  .home-news .news-date {
    padding-top: 0;
    font-size: 0.7em;
  }

  .home-news .news-title {
    font-size: 0.95em;
  }

  .home-news .news-desc {
    font-size: 0.85em;
  }
}
</style>

<section class="home-news">

  <h2 class="news-heading">News</h2>

  <!-- ECCV 2026 -->
  <div class="news-item">
    <div class="news-date">SEP 2026</div>
    <div class="news-content">
      <div class="news-title">
        Two papers at ECCV 2026, including one Spotlight.
      </div>
      <div class="news-desc">
        Event-based schlieren tomography and diffusion-based
        event augmentation.
        <br>
        Co-organized the
        <a href="https://eventbasemultimodalvision.github.io/"
           target="_blank" rel="noopener noreferrer">EBMV Workshop</a>
        and organized the
        <a href="https://www.codabench.org/competitions/16375/"
           target="_blank" rel="noopener noreferrer">EventAid Frame Interpolation Challenge</a>.
      </div>
    </div>
  </div>

  <!-- CVPR 2026 & TIP 2026 -->
  <div class="news-item">
    <div class="news-date">APR 2026</div>
    <div class="news-content">
      <div class="news-title">
        Four papers at CVPR 2026 and IEEE TIP,
        including one Oral and one Highlight.
      </div>
      <div class="news-desc">
        Dark-scene radiance field reconstruction,
        aperture-modulated video reconstruction,
        text-driven event simulation,
        and high-speed stereo vision.
      </div>
    </div>
  </div>

  <!-- NeurIPS 2025 -->
  <div class="news-item">
    <div class="news-date">SEP 2025</div>
    <div class="news-content">
      <div class="news-title">
        One paper at NeurIPS 2025.
      </div>
      <div class="news-desc">
        Dense metric depth estimation via event-based
        differential focus volumes
        (co-corresponding author with Boxin Shi).
      </div>
    </div>
  </div>

  <!-- ICCV 2025 -->
  <div class="news-item">
    <div class="news-date">JUN 2025</div>
    <div class="news-content">
      <div class="news-title">
        Three papers at ICCV 2025,
        including one Oral and two Highlights.
      </div>
      <div class="news-desc">
        Event-based visual vibrometry,
        asynchronous event noise modeling,
        and uncalibrated photometric stereo.
      </div>
    </div>
  </div>

  <!-- TPAMI 2025 -->
  <div class="news-item">
    <div class="news-date">APR 2025</div>
    <div class="news-content">
      <div class="news-title">
        EventAid accepted by IEEE TPAMI.
      </div>
      <div class="news-desc">
        A co-first-authored paper with Boyu Li introducing
        a real-captured benchmark for event-aided
        image and video enhancement.
      </div>
    </div>
  </div>

  <!-- CVPR 2025 -->
  <div class="news-item">
    <div class="news-date">MAR 2025</div>
    <div class="news-content">
      <div class="news-title">
        One paper at CVPR 2025.
      </div>
      <div class="news-desc">
        Unified event-based static and dynamic scene
        reconstruction (co-first-authored with Qiyao Gao).
      </div>
    </div>
  </div>

  <!-- Older News -->
  <details class="news-older">
    <summary>Older News (2023–2024)</summary>

    <!-- ACM MM 2024 -->
    <div class="news-item">
      <div class="news-date">MAY 2024</div>
      <div class="news-content">
        <div class="news-title">
          One paper at ACM MM 2024.
        </div>
        <div class="news-desc">
          Event demosaicing and image deblurring
          (co-first-authored with Yi Ma).
        </div>
      </div>
    </div>

    <!-- CVPR 2024 -->
    <div class="news-item">
      <div class="news-date">FEB 2024</div>
      <div class="news-content">
        <div class="news-title">
          One paper at CVPR 2024.
        </div>
        <div class="news-desc">
          Event-guided direct and global component separation,
          co-authored with Xinyu Zhou, Boyu Li, and Chu Zhou.
          Received full marks during peer review.
        </div>
      </div>
    </div>

    <!-- TPAMI 2023 HDR -->
    <div class="news-item">
      <div class="news-date">DEC 2023</div>
      <div class="news-content">
        <div class="news-title">
          One paper accepted by IEEE TPAMI.
        </div>
        <div class="news-desc">
          Event-based HDR image reconstruction,
          co-authored with Jin Han and Yixin Yang.
        </div>
      </div>
    </div>

    <!-- TPAMI 2023 NeuroZoom -->
    <div class="news-item">
      <div class="news-date">JUL 2023</div>
      <div class="news-content">
        <div class="news-title">
          One first-authored paper accepted by IEEE TPAMI.
        </div>
        <div class="news-desc">
          Neuromorphic event and spike denoising
          and super-resolution.
        </div>
      </div>
    </div>

  </details>

</section>
