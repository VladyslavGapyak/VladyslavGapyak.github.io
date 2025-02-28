---
layout: about
title: About me
permalink: /
subtitle: <a href='#'>Darmstadt University of Applied Sciences</a>.

profile:
  align: left
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

<!-- Timeline CSS -->
<style>
.timeline-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  position: relative;
  width: 100%;
  max-width: 900px;
  margin: 40px auto;
}

.timeline-line {
  position: absolute;
  top: 50%;
  left: 0;
  width: 100%;
  height: 4px;
  background-color: #007bff;
  z-index: -1;
}

.timeline-item {
  position: relative;
  text-align: center;
  width: 150px;
}

.timeline-date {
  font-weight: bold;
  color: #007bff;
  font-size: 1.2rem;
  transition: color 0.3s ease-in-out;
}

.timeline-item:hover .timeline-date {
  color: #ff5733; /* Changes color on hover */
}

.timeline-circle {
  width: 12px;
  height: 12px;
  background-color: #007bff;
  border-radius: 50%;
  display: block;
  margin: 10px auto;
  transition: transform 0.3s ease-in-out;
}

.timeline-item:hover .timeline-circle {
  transform: scale(1.3); /* Enlarges on hover */
}

.timeline-text {
  font-size: 0.85rem;
  max-width: 160px;
  margin-top: 10px;
  transition: opacity 0.3s ease-in-out;
}

.timeline-item:hover .timeline-text {
  opacity: 0.7; /* Slight fade effect on hover */
}

.timeline-content {
  position: absolute;
  width: 150px;
}

.timeline-content.top {
  top: -60px;
}

.timeline-content.bottom {
  top: 40px;
}

.timeline-connector {
  width: 2px;
  height: 20px;
  background-color: #007bff;
  margin: 0 auto;
}
</style>

<!-- Timeline HTML -->
<div class="timeline-container">
  <div class="timeline-line"></div>

  <div class="timeline-item">
    <div class="timeline-content top">
      <p class="timeline-text">BSc Mathematics<br>University of Padova</p>
    </div>
    <span class="timeline-date">2013-2016</span>
    <div class="timeline-connector"></div>
    <span class="timeline-circle"></span>
  </div>

  <div class="timeline-item">
    <div class="timeline-content bottom">
      <p class="timeline-text">MSc Mathematics<br>University of Padova</p>
    </div>
    <span class="timeline-date">2016-2018</span>
    <div class="timeline-connector"></div>
    <span class="timeline-circle"></span>
  </div>

  <div class="timeline-item">
    <div class="timeline-content top">
      <p class="timeline-text">PhD in MPI<br>Germany</p>
    </div>
    <span class="timeline-date">2019-Present</span>
    <div class="timeline-connector"></div>
    <span class="timeline-circle"></span>
  </div>

  <div class="timeline-item">
    <div class="timeline-content bottom">
      <p class="timeline-text">First Journal Paper<br>MDPI Mathematics</p>
    </div>
    <span class="timeline-date">2022</span>
    <div class="timeline-connector"></div>
    <span class="timeline-circle"></span>
  </div>

  <div class="timeline-item">
    <div class="timeline-content top">
      <p class="timeline-text">J. Comp. Applied Math<br>Elsevier</p>
    </div>
    <span class="timeline-date">2024</span>
    <div class="timeline-connector"></div>
    <span class="timeline-circle"></span>
  </div>

  <div class="timeline-item">
    <div class="timeline-content bottom">
      <p class="timeline-text">Physics in Med. & Bio.<br>IOP</p>
    </div>
    <span class="timeline-date">2025</span>
    <div class="timeline-connector"></div>
    <span class="timeline-circle"></span>
  </div>
</div>




I am Vladyslav, a mathematician with a passion for applications. In my PhD project I develop algorithms for the imaging reconstruction problem in Magnetic Particle Imaging for both the model-based and system-matrix-based approaches. For a list of publications, click [here](/vladyslavgapyak/publications/).
I approach this problem using both classical and machine-learning-driven methods.

I am a member of the [ACIDA Lab](https://fbmn.h-da.de/acida)-Algorithms for Computer Vision, Imaging and Data Analysis.

