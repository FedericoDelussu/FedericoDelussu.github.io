---
layout: page
title: Projects
permalink: /projects/
---

<div class="project-row">
  <div class="project-row-thumb">
    <img src="/project_pics/entropy.png" alt="EpiMob Transfer Entropy">
  </div>
  <div class="project-row-body">
    <h3><a href="https://github.com/FedericoDelussu/EpiMob_Transfer_Entropy" target="_blank">EpiMob Transfer Entropy</a></h3>
    <p>A framework for quantifying directional information flow between mobility and epidemic dynamics using transfer entropy. Analyzes how human movement patterns drive disease spread across populations.</p>
  </div>
</div>

<div class="project-row">
  <div class="project-row-thumb">
    <img src="/project_pics/sparsity.png" alt="Epidemic Modeling on Sparse GPS Trajectories">
  </div>
  <div class="project-row-body">
    <h3><a href="https://github.com/FedericoDelussu/Epidemic_modeling_on_sparse_GPS_trajectories" target="_blank">Epidemic Modeling on Sparse GPS Trajectories</a></h3>
    <p>A method for simulating epidemic spread using sparse GPS trajectory data. Reconstructs mobility networks from incomplete location samples to model disease transmission at the population level.</p>
  </div>
</div>

<style>
.project-row {
  display: flex;
  flex-direction: row;
  align-items: stretch;
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

.project-row-body a {
  text-decoration: none;
  color: inherit;
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
