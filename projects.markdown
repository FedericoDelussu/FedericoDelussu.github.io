---
layout: page
title: Projects
permalink: /projects/
---

<a href="https://github.com/FedericoDelussu/EpiMob_Transfer_Entropy" target="_blank" class="project-row">
  <div class="project-row-thumb">
    <img src="/project_pics/entropy.png" alt="EpiMob Transfer Entropy">
  </div>
  <div class="project-row-body">
    <h3>EpiMob Transfer Entropy</h3>
    <p>A framework for quantifying directional information flow between mobility and epidemic dynamics using transfer entropy. Analyzes how human movement patterns drive disease spread across populations.</p>
  </div>
</a>

<style>
.project-row {
  display: flex;
  flex-direction: row;
  align-items: stretch;
  gap: 0;
  text-decoration: none;
  color: inherit;
  border: 1px solid #ddd;
  border-radius: 8px;
  overflow: hidden;
  transition: box-shadow 0.2s, transform 0.2s;
  margin-top: 24px;
}

.project-row:hover {
  box-shadow: 0 4px 16px rgba(0,0,0,0.15);
  transform: translateY(-2px);
}

.project-row-thumb {
  flex: 0 0 140px;
  width: 140px;
  background: #f5f5f5;
  display: flex;
  align-items: center;
  justify-content: center;
}

.project-row-thumb img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}

.project-row-body {
  flex: 1;
  padding: 16px 20px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.project-row-body h3 {
  margin: 0 0 8px 0;
  font-size: 16px;
}

.project-row-body p {
  margin: 0;
  font-size: 14px;
  color: #555;
  line-height: 1.5;
}
</style>
