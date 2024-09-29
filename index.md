---
layout: default
title: Home
---

<div style="display: flex; align-items: center; flex-wrap: wrap; justify-content: center;">
  <div style="flex: 1;">
    <h3>Welcome!</h3>
    <p>I am a postdoc at <a href="https://math.ethz.ch">ETH Zürich</a>, my mentor is <a href="https://people.math.ethz.ch/~serraj/">Prof. Joaquim Serra</a>.</p> 
    <p>Previously, I was a Ph.D. student at <a href="https://www.bath.ac.uk/departments/department-of-mathematical-sciences/">University of Bath</a> under the supervision of <a href="https://researchportal.bath.ac.uk/en/persons/manuel-del-pino">Prof. Manuel del Pino</a>.</p>
    <p>I am interested in geometric analysis and partial differential equations.</p>
    <p>You can find a recent CV <a href="CV/CV.pdf" target="_blank">here</a>.</p>
  </div>
  <div>
    <img src="{{ site.baseurl }}/img.jpg" alt="My Image" title="My Image"
         style="border-radius: 50%; width: auto; height: 200px; object-fit: cover; aspect-ratio: 1 / 1;"/>
    <br><br>
  <p style="text-align: center;">marco.badran[at]math.ethz.ch</p>
  </div>
</div>

<style>
  /* Media query for screens smaller than 768px (phones, small tablets) */
  @media (max-width: 768px) {
    div[style*="display: flex;"] {
      flex-direction: column; /* Stack items vertically */
      align-items: center; /* Center items */
    }
    img {
      margin-bottom: 20px; /* Adds space between the image and text */
    }
  }
</style>

