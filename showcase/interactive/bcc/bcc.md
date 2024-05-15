---
title: Interactive Models
permalink: /showcase/interactive/bcc/
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

<model-viewer src="/showcase/interactive/bcc/bcc.glb" ar ar-modes="webxr scene-viewer quick-look" camera-controls tone-mapping="neutral" poster="poster.webp" shadow-intensity="1" environment-image="legacy">
    <button class="Hotspot" slot="hotspot-1" data-position="0m 133.85847579784968m 124.4954458423365m" data-normal="-1m 0m 0m" data-visibility-attribute="visible">
        <div class="HotspotAnnotation">Inlet</div>
    </button><button class="Hotspot" slot="hotspot-2" data-position="3072m 135.74029655213164m 133.47539641326168m" data-normal="1m 0m 0m" data-visibility-attribute="visible">
        <div class="HotspotAnnotation">Outlet</div>
    </button><button class="Hotspot" slot="hotspot-3" data-position="1476.78064214785m 256m 92.78246061138725m" data-normal="0m 1m 0m" data-visibility-attribute="visible">
        <div class="HotspotAnnotation">Symmetry</div>
    </button><button class="Hotspot" slot="hotspot-4" data-position="771.394920693028m 222.45230884283728m 206.41360726196262m" data-normal="-0.057578996599841684m 0.5478026410872094m 0.8346238227899042m" data-visibility-attribute="visible">
        <div class="HotspotAnnotation">Wall</div>
    </button>
    <div class="progress-bar hide" slot="progress-bar">
        <div class="update-bar"></div>
    </div>
</model-viewer>
