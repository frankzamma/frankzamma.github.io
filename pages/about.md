---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:<br>

I'm actually studying Cyber Security at University of Salerno.<br>
I'm a tech lover and this are some of my skills 👇


<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>
<h1>Professional Experience</h1>
<!--- Inserimento attività professionali --->
<div class="row">
<div class="col mt-4">
  <div class="timeline-body bg-themed">
      <div class="timeline-item">
        <div class="content">
          <h2>Tutor of bachelor's degree course "Element of Computation Theory", University of Salerno, Fisciano (SA)</h2>
          <h6 class="date">April 2024 — September 2024</h6>
          <p></p>
        </div>
      </div>
  </div>
</div>
</div>
<h1>Education</h1>
<div class="row">
{% include about/timeline.html %}
</div>
<h1>Other Experience</h1>
<!--- Inserimento attività professionali --->
<div class="row">
<div class="col mt-4">
  <div class="timeline-body bg-themed">
      <div class="timeline-item">
        <div class="content">
          <h2>Automotive CyberSecurity Accademy (ACSA) 2024 - Erasmus+ Summer School, Fisciano(SA)</h2>
          <h6 class="date">April 2024 — September 2024</h6>
          <p>For further information: <a href="https://www.autocybersec.ro/all-acsas/acsa-2024">ACSA site</a> </p>
        </div>
      </div>
  </div>
</div>
</div>