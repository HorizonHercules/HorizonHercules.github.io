---
title: Interactive Models
permalink: /showcase/interactive/boombox/
layout: single
author_profile: false
read_time: false
show_date: false
share: false
related: false
header:
   overlay_image: /assets/images/default/hercules_logo_full.png
---

<model-viewer id="static-model" src="/showcase/interactive/boombox/boombox.glb" shadow-intensity="1" camera-controls touch-action="pan-y" alt="A 3D model of an astronaut">
  <div class="controls">
    <button onclick="exportGLB()">Export GLB</button>
  </div>
</model-viewer>
<script>
  async function exportGLB(){
    const modelViewer = document.getElementById("static-model");
    const glTF = await modelViewer.exportScene();
    const file = new File([glTF], "export.glb");
    const link = document.createElement("a");
    link.download =file.name;
    link.href = URL.createObjectURL(file);
    link.click();
  }
</script>