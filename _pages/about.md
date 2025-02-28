---
layout: about
title: About me
permalink: /
subtitle: <a PhD Candidate at the href='#'>Darmstadt University of Applied Sciences</a>.

profile:
  align: right
  image: prof_pic.jpg
  image_circular: true # crops the image to make it circular
  more_info: >
    <p>Office 1.32/C10</p>
    <p>Schoefferstr. 3, 64295,</p>
    <p>Darmstadt, Germany </p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder
---

<!-- Horizontal Timeline CSS -->
<style>
.timeline-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  overflow-x: auto;
  white-space: nowrap;
  padding: 20px 0;
}

.timeline-item {
  text-align: center;
  min-width: 150px;
  max-width: 200px;
  margin: 0 10px;
  position: relative;
}

.timeline-item::before {
  content: "";
  position: absolute;
  width: 100%;
  height: 4px;
  background-color: #007bff;
  top: 30px;
  left: 50%;
  transform: translateX(-50%);
  z-index: -1;
}

.timeline-date {
  font-weight: bold;
  color: #007bff;
  display: block;
  margin-bottom: 5px;
}

.timeline-circle {
  width: 16px;
  height: 16px;
  background-color: #007bff;
  border-radius: 50%;
  display: inline-block;
  position: relative;
  top: 25px;
  margin-bottom: 10px;
}

.timeline-text {
  font-size: 0.9rem;
  margin-top: 10px;
}
</style>

<!-- Horizontal Timeline HTML -->
<div class="timeline-container">
  <div class="timeline-item">
    <span class="timeline-date">2013-2016</span>
    <span class="timeline-circle"></span>
    <p class="timeline-text">BSc Mathematics<br>University of Padova</p>
  </div>
  <div class="timeline-item">
    <span class="timeline-date">2016-2018</span>
    <span class="timeline-circle"></span>
    <p class="timeline-text">MSc Mathematics<br>University of Padova</p>
  </div>
  <div class="timeline-item">
    <span class="timeline-date">2019-Present</span>
    <span class="timeline-circle"></span>
    <p class="timeline-text">PhD in MPI<br>Germany</p>
  </div>
  <div class="timeline-item">
    <span class="timeline-date">2022</span>
    <span class="timeline-circle"></span>
    <p class="timeline-text">First Journal Paper<br>MDPI Mathematics</p>
  </div>
  <div class="timeline-item">
    <span class="timeline-date">2024</span>
    <span class="timeline-circle"></span>
    <p class="timeline-text">J. Comp. Applied Math<br>Elsevier</p>
  </div>
</div>


I am Vladyslav, a mathematician with a passion for applications. In my PhD project I develop algorithms for the imaging reconstruction problem in Magnetic Particle Imaging for both the model-based and system-matrix-based approaches. For a list of publications, click [here](/vladyslavgapyak/publications/).
I approach this problem using both classical and machine-learning-driven methods.

I am a member of the [ACIDA Lab - "Algorithms for Computer Vision, Imaging and Data Analysis"](https://fbmn.h-da.de/acida).

