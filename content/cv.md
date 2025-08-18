---
title: "Curriculum Vitae"
description: "My resume and professional background"
---

<div class="pdf-container">
  <iframe id="pdf-iframe" src="/assets/documents/resume_alexandros_anastasiou.pdf" width="100%" height="874px"></iframe>
  <button onclick="openFullScreen()">Open in Full Screen</button>
</div>

<style>
.pdf-container {
  position: relative;
  text-align: center;
}

#pdf-iframe {
  width: 100%;
  height: 874px;
  max-width: 100%;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
  border: none;
}

button {
  margin-top: 10px;
  padding: 10px 20px;
  font-size: 16px;
  cursor: pointer;
  background-color: #0066cc;
  color: white;
  border: none;
  border-radius: 5px;
}

button:hover {
  background-color: #0052a3;
}
</style>

<script>
function openFullScreen() {
  var iframe = document.getElementById("pdf-iframe");
  if (iframe.requestFullscreen) {
    iframe.requestFullscreen();
  } else if (iframe.mozRequestFullScreen) { /* Firefox */
    iframe.mozRequestFullScreen();
  } else if (iframe.webkitRequestFullscreen) { /* Chrome, Safari and Opera */
    iframe.webkitRequestFullscreen();
  } else if (iframe.msRequestFullscreen) { /* IE/Edge */
    iframe.msRequestFullscreen();
  }
}
</script>
