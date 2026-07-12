---
permalink: /
title: "My journey"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div class="journey">
  <div class="journey-item">
    <div class="journey-logo">
      <i class="fa-solid fa-graduation-cap" aria-hidden="true"></i>
    </div>
    <div class="journey-body">
      <span class="journey-date">2021 - 2023</span>
      <h3 class="journey-title">Bachelor of Science</h3>
      <p class="journey-desc">Undergraduate program - Marrakech / Rabat, Morocco</p>
    </div>
  </div>

  <div class="journey-item">
    <div class="journey-logo">
      <img src="/images/logos/telecom-paris.png" alt="Télécom Paris" />
    </div>
    <div class="journey-body">
      <span class="journey-date">2023 - 2026</span>
      <h3 class="journey-title">Télécom Paris</h3>
      <p class="journey-desc">Diplôme d'Ingénieur - Palaiseau, France</p>
    </div>
  </div>

  <div class="journey-item">
    <div class="journey-logo">
      <img src="/images/logos/mva.jpg" alt="Master MVA" />
    </div>
    <div class="journey-body">
      <span class="journey-date">2025 - 2026</span>
      <h3 class="journey-title">Master MVA - Mathématiques, Vision, Apprentissage</h3>
      <p class="journey-desc">Research master's (M2) in machine learning and computer vision</p>
      <img class="journey-sublogo" src="/images/logos/ens-paris-saclay.png" alt="ENS Paris-Saclay" />
    </div>
  </div>

  <div class="journey-item">
    <div class="journey-logo">
      <img src="/images/logos/harvard.svg" alt="Harvard University" />
    </div>
    <div class="journey-body">
      <span class="journey-date">April 2026 - Present</span>
      <h3 class="journey-title">Harvard AI &amp; Robotics Lab</h3>
      <p class="journey-desc">Visiting Research Intern - Cambridge, MA</p>
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
    background: rgba(128, 128, 128, 0.4);
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
    border: 1px solid rgba(128, 128, 128, 0.45);
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
  .journey-logo i {
    font-size: 1.5rem;
    color: #333;
  }
  .journey-date {
    display: inline-block;
    font-size: 0.75rem;
    font-weight: 600;
    letter-spacing: 0.03em;
    padding: 0.1rem 0.55rem;
    border-radius: 999px;
    background: rgba(128, 128, 128, 0.2);
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
