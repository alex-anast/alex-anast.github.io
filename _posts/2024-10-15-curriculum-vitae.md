---
layout: single
title: "Curriculum Vitae"
permalink: /curriculum_vitae/
---

<iframe src="/assets/documents/resume_alexandros_anastasiou.pdf" width="100%" height="874px"> </iframe>


<br>
<br>
<br>
# UNDER CONSTRUCTION

The idea is that some things happened in parallel, and it would be nice to showcase it visually.

<style>
.timeline-container {
  display: flex;
  max-width: 1200px;
  margin: 0 auto;
  font-family: Arial, sans-serif;
}

.timeline-years {
  flex: 0 0 120px;
  position: relative;
  margin-right: 40px;
}

.timeline-line {
  position: absolute;
  left: 50%;
  top: 0;
  bottom: 0;
  width: 2px;
  background: #2196F3;
  transform: translateX(-50%);
}

.year-marker {
  position: absolute;
  left: 0;
  right: 0;
  text-align: center;
  padding: 10px 0;
  font-weight: bold;
  color: #2196F3;
}

.timeline-events {
  flex: 1;
  position: relative;
  min-height: 2000px; /* Adjust based on total timeline duration */
}

.timeline-event {
  position: absolute;
  width: calc(50% - 20px);
  background: #f9f9f9;
  border-radius: 8px;
  padding: 15px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  border-left: 4px solid #2196F3;
}

.timeline-event.left {
  left: 0;
}

.timeline-event.right {
  right: 0;
}

/* Vertical spacing calculations - adjust these values based on your actual dates */
#event-1 { top: 5%; height: 8%; }
#event-2 { top: 13%; height: 10%; }
#event-3 { top: 18%; height: 3%; }
#event-4 { top: 22%; height: 6%; }
#event-5 { top: 29%; height: 15%; }
#event-6 { top: 75%; height: 12%; left: 25%; }
#event-7 { top: 45%; height: 8%; }
</style>

<div class="timeline-container">
  <div class="timeline-years">
    <div class="timeline-line"></div>
    <div class="year-marker" style="top: 5%">2018</div>
    <div class="year-marker" style="top: 20%">2019</div>
    <div class="year-marker" style="top: 35%">2020</div>
    <div class="year-marker" style="top: 50%">2021</div>
    <div class="year-marker" style="top: 65%">2022</div>
    <div class="year-marker" style="top: 80%">2023</div>
    <div class="year-marker" style="top: 95%">2024</div>
  </div>

  <div class="timeline-events">
    <div class="timeline-event left" id="event-1">
      <h3>09/2018 - 12/2019</h3>
      <p>Electronics Engineer at UoP Racing, Greece</p>
    </div>

    <div class="timeline-event right" id="event-2">
      <h3>10/2021 - 04/2022</h3>
      <p>Research Engineer @ Toyota Motor Europe, Belgium</p>
    </div>

    <div class="timeline-event left" id="event-3">
      <h3>09/2022 - 11/2022</h3>
      <p>Software Engineer @ Nalys (Consulting), Belgium</p>
    </div>

    <div class="timeline-event right" id="event-4">
      <h3>11/2022 - 10/2023</h3>
      <p>Embedded Software Engineer @ Ekinops, Belgium</p>
    </div>

    <div class="timeline-event left" id="event-5">
      <h3>11/2023 - 07/2024</h3>
      <p>DevOps CI Engineer @ Ekinops, Belgium</p>
    </div>

    <div class="timeline-event" id="event-6">
      <h3>2022</h3>
      <p>MSc, Electrical & Computer Engineering<br>
      University of Patras, Greece</p>
    </div>

    <div class="timeline-event right" id="event-7">
      <h3>2025</h3>
      <p>Advanced Master of Artificial Intelligence<br>
      Katholieke Universiteit Leuven, Belgium</p>
    </div>
  </div>
</div>