---
layout: about
title: about
permalink: /
subtitle: MVA master's student at <a href='https://www.master-mva.com/'>ENS Paris-Saclay</a> · Engineering student at <a href='https://www.telecom-paris.fr/'>Télécom Paris</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Paris, France</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

Hi! I'm Iliass, a third-year engineering student at **Télécom Paris**, currently enrolled in the [**MVA**](https://www.master-mva.com/) (Mathématiques, Vision, Apprentissage) research master's program at ENS Paris-Saclay.

I'm passionate about **applied mathematics** and **computer science**. I love building impactful projects in **Python** and **C++**, and exploring the depths of **machine learning research** — from statistical modeling and ML theory to deep learning and signal processing. I was also active in the **Télécom Robotics** club, where I worked on real-world robotics challenges with ROS.

Always eager to learn, collaborate, and tackle new technical problems. Take a look at my [projects](/projects/), or reach out by [email](mailto:iliass.khoutaibi@telecom-paris.fr)!

## 🎓 my journey

<div class="journey">
  <div class="journey-item">
    <div class="journey-logo">
      <img src="/assets/img/logos/telecom-paris.png" alt="Télécom Paris" />
    </div>
    <div class="journey-body">
      <span class="journey-date">2023 – 2026</span>
      <h3 class="journey-title">Télécom Paris</h3>
      <p class="journey-desc">Diplôme d'Ingénieur · Palaiseau, France</p>
    </div>
  </div>

  <div class="journey-item">
    <div class="journey-logo">
      <img src="/assets/img/logos/mva.jpg" alt="Master MVA" />
    </div>
    <div class="journey-body">
      <span class="journey-date">2025 – 2026</span>
      <h3 class="journey-title">Master MVA — Mathématiques, Vision, Apprentissage</h3>
      <p class="journey-desc">Research master's (M2) in machine learning and computer vision</p>
      <img class="journey-sublogo" src="/assets/img/logos/ens-paris-saclay.png" alt="ENS Paris-Saclay" />
    </div>
  </div>

  <div class="journey-item">
    <div class="journey-logo">
      <img src="/assets/img/logos/harvard.svg" alt="Harvard University" />
    </div>
    <div class="journey-body">
      <span class="journey-date">2026</span>
      <h3 class="journey-title">Harvard AI &amp; Robotics Lab</h3>
      <p class="journey-desc">Research internship · Cambridge, MA</p>
    </div>
  </div>
</div>

<style>
  .journey {
    position: relative;
    margin: 1.5rem 0 1rem;
  }
  .journey::before {
    content: "";
    position: absolute;
    left: 31px;
    top: 8px;
    bottom: 8px;
    width: 2px;
    background: rgba(128, 128, 128, 0.3);
  }
  .journey-item {
    position: relative;
    display: flex;
    align-items: flex-start;
    gap: 1.1rem;
    padding-bottom: 2rem;
  }
  .journey-item:last-child {
    padding-bottom: 0;
  }
  .journey-logo {
    flex: 0 0 64px;
    height: 64px;
    background: #fff;
    border: 1px solid rgba(128, 128, 128, 0.35);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    overflow: hidden;
    z-index: 1;
  }
  .journey-logo img {
    max-width: 44px;
    max-height: 44px;
    object-fit: contain;
  }
  .journey-date {
    display: inline-block;
    font-size: 0.75rem;
    font-weight: 600;
    letter-spacing: 0.03em;
    padding: 0.1rem 0.55rem;
    border-radius: 999px;
    background: rgba(128, 128, 128, 0.15);
    margin-bottom: 0.25rem;
  }
  .journey-title {
    font-size: 1.05rem;
    font-weight: 600;
    margin: 0.15rem 0 0.2rem;
  }
  .journey-desc {
    margin: 0;
    font-size: 0.9rem;
    opacity: 0.85;
  }
  .journey-sublogo {
    display: block;
    height: 22px;
    margin-top: 0.5rem;
    background: #fff;
    border-radius: 4px;
    padding: 2px 6px;
  }
</style>
