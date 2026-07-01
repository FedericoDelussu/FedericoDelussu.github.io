---
layout: page
title: ""
---

# Federico Delussu

PhD in Computer Science, Technical University of Denmark

---

## Projects

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

---

## Publications

**[The Effect of Mobility Trajectory Sparsity on Epidemic Modeling Outcomes](https://arxiv.org/abs/2605.31282)** Arxiv

Analyzed structural biases in sparse GPS traces, leading to robust bias correction strategies for epidemic modeling outcomes.


**[Experiments and Comparison of Digital Twinning of Photovoltaic Panels by Machine Learning Models and a Cyber-Physical Model in Modelica.](https://ieeexplore.ieee.org/document/9525233/authors#authors)** IEEE Transactions on Industrial Informatics

Built a hybrid model combining a physics-based digital twin and a temporal neural network to forecast photovoltaic energy production, outperforming each individual component.

**[Fuel Prediction and Reduction in Public Transportation by Sensor Monitoring and Bayesian Networks.](https://www.mdpi.com/1424-8220/21/14/4733)** Sensors
Modeled fuel consumption in a public transport bus fleet using Bayesian Networks and Granger Causality on bus sensor data.

**[The Limits of Human mobility traces to predict the spread of COVID-19: A Transfer Entropy approach.](https://pubmed.ncbi.nlm.nih.gov/37811338/)** PNAS Nexus
Quantified how human mobility time-series actually predict COVID-19 spread

**[Evidence of pandemic fatigue associated with stricter tiered COVID-19 restrictions.](https://journals.plos.org/digitalhealth/article?id=10.1371/journal.pdig.0000035)** PLOS Digital Health
col
Measured behavioral compliance across Italian provinces during tiered COVID-19 restrictions, finding evidence of fatigue under stricter lockdown conditions.

---

## Contact

<p class="contact-line">
  <svg class="contact-icon" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M6.62 10.79a15.15 15.15 0 006.59 6.59l2.2-2.2a1 1 0 011.02-.24 11.36 11.36 0 003.56.57 1 1 0 011 1V20a1 1 0 01-1 1A17 17 0 013 4a1 1 0 011-1h3.5a1 1 0 011 1 11.36 11.36 0 00.57 3.56 1 1 0 01-.24 1.02l-2.21 2.21z"/></svg>
  <span>+45 52658812</span>
</p>
<p class="contact-line">
  <svg class="contact-icon" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M20 4H4a2 2 0 00-2 2v12a2 2 0 002 2h16a2 2 0 002-2V6a2 2 0 00-2-2zm0 4l-8 5-8-5V6l8 5 8-5z"/></svg>
  <a href="mailto:federico.delussu@gmail.com">federico.delussu@gmail.com</a>
</p>


<style>
.contact-line {
  display: flex;
  align-items: center;
  gap: 10px;
  margin: 8px 0;
}

.contact-icon {
  width: 18px;
  height: 18px;
  flex: 0 0 18px;
  color: #555;
}

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
