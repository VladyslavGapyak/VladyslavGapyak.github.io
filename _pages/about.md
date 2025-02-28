---
layout: about
title: About me
permalink: /
subtitle: <a href='#'>Darmstadt University of Applied Sciences</a>.

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

I am Vladyslav, a mathematician with a passion for applications. In my PhD project I develop algorithms for the imaging reconstruction problem in Magnetic Particle Imaging for both the model-based and system-matrix-based approaches. For a list of publications, click [here](/vladyslavgapyak/publications/).
I approach this problem using both classical and machine-learning-driven methods.

I am a member of the [ACIDA Lab](https://fbmn.h-da.de/acida)-Algorithms for Computer Vision, Imaging and Data Analysis.

<!-- Timeline CSS -->
<style>
/* Timeline Container: Fixed on the Left */
.timeline-container {
  position: absolute;
  left: 0;
  top: 50px; /* Adjust to align with content */
  width: 180px; /* Adjust width to fit nicely */
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: flex-start;
}

/* Vertical Timeline Line */
.timeline-line {
  position: absolute;
  width: 4px;
  background-color: #007bff;
  top: 0;
  bottom: 0;
  left: 50%;
  transform: translateX(-50%);
}

/* Timeline Items (Dates & Events) */
.timeline-item {
  position: relative;
  width: 100%;
  text-align: center;
  margin-bottom: 30px;
}

.timeline-date {
  font-weight: bold;
  color: #007bff;
  font-size: 1rem;
  transition: color 0.3s ease-in-out;
}

.timeline-item:hover .timeline-date {
  color: #ff5733; /* Changes color on hover */
}

/* Small Circles for Events */
.timeline-circle {
  width: 12px;
  height: 12px;
  background-color: #007bff;
  border-radius: 50%;
  display: block;
  margin: 5px auto;
  transition: transform 0.3s ease-in-out;
}

.timeline-item:hover .timeline-circle {
  transform: scale(1.3); /* Enlarges on hover */
}

/* Timeline Text (Event Descriptions) */
.timeline-text {
  font-size: 0.8rem;
  max-width: 150px;
  margin-top: 5px;
  transition: opacity 0.3s ease-in-out;
}

.timeline-item:hover .timeline-text {
  opacity: 0.7; /* Slight fade effect on hover */
}
<!-- Vertical Timeline on the Left -->
<div class="timeline-container">
  <div class="timeline-line"></div>

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

  <div class="timeline-item">
    <span class="timeline-date">2025</span>
    <span class="timeline-circle"></span>
    <p class="timeline-text">Physics in Med. & Bio.<br>IOP</p>
  </div>
</div>
