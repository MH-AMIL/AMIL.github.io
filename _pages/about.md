---
permalink: /
title: "Welcome to the Additive Manufacturing and Innovation Laboratory (AMIL)!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


<div style="display: flex; align-items: flex-start; gap: 20px;">
  <div>
    <p>Our research focuses on combining advanced manufacturing, especially additive manufacturing (AM, both 3D and 4D Printing), with artificial intelligence (AI)/machine learning (ML), and data analytics. Our goal is to improve how products are designed and manufactured in ways that are smarter, more efficient, and better for the environment. We look at things such as quality, functionality, scalability, energy efficiency, cost-effectiveness, and how our work can make a positive impact on the society.</p>
  </div>
  <img src="/images/lab_logo.png" alt="Lab Logo" style="width: 160px; height: auto;" />
</div>


Research Directions
======

<div class="research-direction">
  <h3><strong>1. Additive Manufacturing of Smart Functional Structures</strong></h3>
  <p>Additive manufacturing builds parts layer by layer, offering great design freedom and control over functional performance. At AMIL, we advance AM capabilities further by designing and printing stimuli-responsive (“smart”) materials for self-actuating or adaptive structures. Through combined experiments and computational modeling, we map the process-material-property relationships that govern print quality, mechanical strength, and overall performance of the final parts.</p>
  <img src="/images/R1.jpg" alt="Smart Additive Manufacturing" style="width:70%; margin-bottom: 2em;">
</div>

<div class="research-direction">
  <h3><strong>2. Smart & Resilient Supply Chains Enabled by AM</strong></h3>
  <p>From a systems perspective, AM also supports distributed, cloud-based production services. We build analytical and sequential decision-making tools to show how distributed AM facilities can share capacity, cut waste, and strengthen supply chains under uncertain demand and supply. Our models guide logistics network design, on-demand capacity sharing, and circular material flows, helping industries move toward integrated, resource-efficient, resilient manufacturing systems.</p>
  <img src="/images/R2.jpg" alt="Resilient Supply Chains" style="width:70%; margin-bottom: 2em;">
</div>

<div class="research-direction">
  <h3><strong>3. Sustainability and Life-Cycle Engineering</strong></h3>
  <p>At AMIL, we integrate sustainability thinking into modern manufacturing at both the process level and across the entire life cycle. We develop predictive models and data-driven tools to quantify energy use, emissions, material flows, and techno-economic viability from design through production, use, and recovery. Coupled with life-cycle assessment (LCA) and techno-economic analysis (TEA), these insights guide the transition toward circular economy and deliver actionable knowledge for sustainable future manufacturing.</p>
  <img src="/images/R3.jpg" alt="Life Cycle Engineering" style="width:70%; margin-bottom: 2em;">
</div>


AMIL Events
======
<div class="amil-gallery" style="max-width: 800px; margin: auto;">
  <div class="slideshow-container" style="position: relative; max-width: 800px; margin: auto;">
    <div class="mySlides fade">
      <img src="/images/events/Labimage.jpg" style="width:100%; height:400px; object-fit:cover;">
    </div>
    <div class="mySlides fade">
      <img src="/images/events/iise2025.jpg" style="width:100%; height:400px; object-fit:cover;">
    </div>
    <div class="mySlides fade">
      <img src="/images/events/anika_coe_2025.jpg" style="width:100%; height:400px; object-fit:cover;">
    </div>

<!-- Next and previous buttons -->
<a class="prev" onclick="plusSlides(-1)" style="position: absolute; top: 50%; left: 0; transform: translateY(-50%); font-size: 2em; color: white; text-decoration: none; padding: 8px;">&#10094;</a>
<a class="next" onclick="plusSlides(1)" style="position: absolute; top: 50%; right: 0; transform: translateY(-50%); font-size: 2em; color: white; text-decoration: none; padding: 8px;">&#10095;</a>
  </div>
</div>

<style>
.mySlides {display: none;}
.fade {animation: fade 1.5s;}
@keyframes fade {from {opacity: .4} to {opacity: 1}}
</style>

<script>
    let slideIndex = 1;
    showSlides(slideIndex);

    function plusSlides(n) {
      showSlides(slideIndex += n);
    }

    function showSlides(n) {
      let slides = document.getElementsByClassName("mySlides");
      if (n > slides.length) {slideIndex = 1}
      if (n < 1) {slideIndex = slides.length}
      for (let i = 0; i < slides.length; i++) {
        slides[i].style.display = "none";  
      }
      slides[slideIndex-1].style.display = "block";  
    }

    // Optional auto-advance
    setInterval(() => {
      plusSlides(1);
    }, 3000);
</script>
<div style="margin-bottom: 3em;"></div>

Our sponsors
======
<div style="text-align: center; margin-top: 2em;">
  <h2><strong> </strong></h2>
  <div style="display: flex; justify-content: center; gap: 20px; align-items: center; flex-wrap: wrap; margin-top: 1em;">
    <img src="/images/Sponsors/NCAT_logo.png" alt="Sponsor 1" style="height: 120px;">
    <img src="/images/Sponsors/nsf-logo.png" alt="Sponsor 2" style="height: 140px;">

[//]: # (    <img src="/images/Sponsors/csi-logo.png" alt="Sponsor 3" style="height: 120px;">)
  </div>
</div>
<div style="margin-bottom: 3em;"></div>