---
title: Interactive Models
permalink: /showcase/interactive/twoLayerInternalInsulationConcept_V1.1/
layout: single
author_profile: false
read_time: false
show_date: false
share: false
related: false
header:
   overlay_image: /assets/images/default/hercules_logo_full.png
---

<style>
    model-viewer {
        width: 800px;
        height: 600px;
        border: 5px solid black;
        border-radius: 20px;
        background-color: #792a33;
    }
</style>

<script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.min.js"></script>

<model-viewer 
    src="/showcase/interactive/twoLayerInternalInsulationConcept_v1.1/Two-Layer_InternalInsulationConcept_v1.1.glb" 
    color="red"
    width="800px"
    height="600px"
    ar 
    ar-modes="webxr scene-viewer quick-look" 
    camera-controls 
    tone-mapping="neutral" 
    poster="poster.webp" 
    shadow-intensity="1" 
    environment-image="legacy">
    <div class="progress-bar hide" slot="progress-bar">
        <div class="update-bar"></div>
    </div>
</model-viewer>
