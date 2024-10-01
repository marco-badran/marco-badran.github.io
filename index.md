---
layout: default
title: Home
---


<div style="display: flex; align-items: center; justify-content: center; flex-wrap: wrap;">
  <div style="flex: 0; order: 2;">
    <img src="{{ site.baseurl }}/img.jpg" alt="My Image" title="My Image"
         style="border-radius: 50%; width: auto; height: 200px; object-fit: cover; aspect-ratio: 1 / 1;" />
         <br><br>
        <p style="text-align: center;"><span style="font-size: 80%;">marco.badran[at]math.ethz.ch</span></p>
  </div>
  <div style="flex: 1; order: 1;">
    <h3>Welcome!</h3>
    <p>I am a postdoc at <a href="https://math.ethz.ch">ETH Zürich</a>, my mentor is <a href="https://people.math.ethz.ch/~serraj/">Prof. Joaquim Serra</a>.</p> 
    <p>Previously, I was a Ph.D. student at <a href="https://www.bath.ac.uk/departments/department-of-mathematical-sciences/">University of Bath</a> under the supervision of <a href="https://researchportal.bath.ac.uk/en/persons/manuel-del-pino">Prof. Manuel del Pino</a>.</p>
    <p>I am interested in geometric analysis and partial differential equations. Recently I have been working on
     <ul>
  <li>Harmonic maps to the circle and their relaxations,</li>
  <li>Allen-Cahn and Ginzburg-Landau theories,</li>
  <li>Fractional minimal surfaces.</li>
  </ul>
    </p>
  </div>
</div>

<style>
  /* Media query for screens smaller than 768px (phones, small tablets) */
  @media (max-width: 768px) {
    div[style*="display: flex;"] {
      flex-direction: column; /* Stack items vertically */
      align-items: center; /* Center items */
    }
    div[style*="flex: 0;"] {
      order: 1; /* Image comes first */
    }
    div[style*="flex: 1;"] {
      order: 2; /* Text comes second */
    }
    img {
      margin-bottom: 20px; /* Adds space between the image and text */
    }
  }

  /* For larger screens (default layout) */
  @media (min-width: 769px) {
    div[style*="display: flex;"] {
      flex-direction: row; /* Side by side */
    }
    div[style*="flex: 1;"] {
      order: 1; /* Text on the left */
    }
    div[style*="flex: 0;"] {
      order: 2; /* Image on the right */
    }
  }
</style>
