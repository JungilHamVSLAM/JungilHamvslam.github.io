---
layout: about
title: About
permalink: /
subtitle: Ph.D. Candidate in Mechanical and Robotics Engineering
profile:
  align: right
  image: jungil_prof.jpg
  image_circular: false # crops the image to make it circular
  address: >
    <p>Gwangju, South Korea. 61005</p>

news: true  # includes a list of news items
publications: true
latest_posts: false  # includes a list of the newest posts
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

<style>
/* Everything here reads from the theme's CSS variables so it follows light/dark.
   The previous version hardcoded #fff and #9a9a9a, which put a bright white slab
   behind the logos in dark mode, and white-on-brand-colour badge text that sat at
   3.6:1 contrast. The badges now match the PDF/Code buttons on the publications
   page, so the whole site uses one button style. */
.intro-badges{display:flex;flex-wrap:wrap;gap:8px;margin:.4rem 0 1.3rem;}
.lnk-badge{display:inline-flex;align-items:center;gap:6px;font-size:13px;font-weight:400;
  padding:.25rem 1rem;border-radius:.125rem;text-decoration:none;white-space:nowrap;
  color:var(--global-text-color);border:1px solid var(--global-text-color);
  transition:color .2s ease-in-out,border-color .2s ease-in-out;}
.lnk-badge:hover{color:var(--global-theme-color);border-color:var(--global-theme-color);text-decoration:none;}
.lnk-badge i{font-size:14px;line-height:1;}
.affil-wrap{margin:.2rem 0 1.5rem;}
.affil-label{font-size:11.5px;letter-spacing:.05em;text-transform:uppercase;color:var(--global-marker-color);margin-bottom:8px;}
.affil-chip{display:inline-flex;align-items:center;gap:24px;padding:4px 0;}
.affil-chip img{height:42px;width:auto;filter:grayscale(100%);opacity:.72;transition:opacity .25s ease-in-out;}
.affil-chip img:hover{opacity:1;}
/* gist.png is an alpha silhouette, so inverting it in dark mode lightens the marks
   without dragging a white background square along with them. */
html[data-theme='dark'] .affil-chip img{filter:grayscale(100%) invert(1);}
</style>

<p style="font-size:1.12rem;line-height:1.6;margin-bottom:.3rem;">I work on <strong>spatial AI for robots</strong> — robust visual localization, mapping, and state estimation grounded in the geometry of the world — from the <strong>International Space Station</strong> to aerial and field robots.</p>

<div class="intro-badges">
<a class="lnk-badge" style="background:#4b5563" href="/cv/"><i class="fas fa-file-pdf"></i>CV</a>
<a class="lnk-badge" style="background:#4285F4" href="https://scholar.google.com/citations?user=-cCSLacAAAAJ"><i class="ai ai-google-scholar"></i>Google Scholar</a>
<a class="lnk-badge" style="background:#24292e" href="https://github.com/jungilha"><i class="fab fa-github"></i>GitHub</a>
<a class="lnk-badge" style="background:#0A66C2" href="https://www.linkedin.com/in/jungil-ham"><i class="fab fa-linkedin"></i>LinkedIn</a>
<a class="lnk-badge" style="background:#0b5394" href="https://dblp.org/pid/393/9998.html"><i class="ai ai-dblp"></i>DBLP</a>
<a class="lnk-badge" style="background:#ea4335" href="mailto:jungilham@gm.gist.ac.kr"><i class="fas fa-envelope"></i>Email</a>
</div>

<div class="affil-wrap">
<div class="affil-label">Affiliations &amp; Collaborations</div>
<div class="affil-chip">
<img src="/assets/img/gist.png" alt="Gwangju Institute of Science and Technology">
<img src="/assets/img/nasa.svg" alt="NASA">
</div>
</div>

Jungil Ham is a Ph.D. candidate in Mechanical and Robotics Engineering at the [Gwangju Institute of Science and Technology (GIST)](https://www.gist.ac.kr/), in the [Machine Perception and Intelligence Lab (MPIL)](https://mpil-gist.github.io/) advised by Pyojin Kim.

He designed highly accurate [visual compasses leveraging structural priors](https://sanfranciscoworld.github.io/) in stair-dominant environments and [digital twins of the International Space Station (ISS)](https://dtor-visualcompass.github.io/). During his master's studies, he also led the end-to-end development of a [pedestrian-following aerial robot](/assets/pdf/etri2.pdf), from drone design and fabrication to perception and control algorithms.

Jungil has conducted research through internships at the [Robotics Innovatory (Robotory)](https://mecha.skku.ac.kr/roboticsinnovatory/index.do) at [Sungkyunkwan University](https://www.skku.edu/) with Prof. Hyouk Ryeol Choi, and at the [Center for Intelligent &amp; Interactive Robotics](https://www.kist.re.kr/ko/research/introduction-intel-robot.do) at the [Korea Institute of Science and Technology (KIST)](https://www.kist.re.kr/eng/) with Dr. Jung Min Park, where he broadened his perspective on robotics systems, perception, and applied research. He also collaborated closely with the [NASA Ames Research Center Intelligent Robotics Group](https://www.nasa.gov/intelligent-systems-division/autonomous-systems-and-robotics/intelligent-robotics-group/) as a research intern. He received his M.S. in Mechanical and Robotics Engineering from GIST and his B.S. in Electronics and Information Engineering from [Kwangwoon University](https://www.kw.ac.kr/).
