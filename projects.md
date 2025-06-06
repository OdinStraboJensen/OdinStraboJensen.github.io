---
layout: home
title: "Projects"
permalink: /projects/
author_profile: true
---

Here are some of my completed and ongoing projects.

<style>
.video-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr); /* Force exactly 3 columns */
  gap: 1.5rem;
  margin-top: 2rem;
}
.video-card {
  background: var(--mm-surface);
  padding: 1rem;
  border-radius: 10px;
  box-shadow: 0 1px 6px rgba(0,0,0,0.1);
}
.video-card iframe {
  width: 100%;
  aspect-ratio: 16 / 9;
  border: none;
  border-radius: 8px;
}
.video-card p {
  margin-top: 0.75rem;
}
@media (max-width: 768px) {
  .video-grid {
    grid-template-columns: 1fr; /* Stack on mobile */
  }
}
</style>


<div class="video-grid">

  <div class="video-card">
    <iframe 
      src="https://www.youtube.com/embed/dQw4w9WgXcQ" 
      allowfullscreen>
    </iframe>
    <p><strong>Project 1: Game AI Demo</strong><br>Showcasing voxel-based AI pathfinding in Unity.</p>
  </div>

  <div class="video-card">
    <iframe 
      src="https://www.youtube.com/embed/9bZkp7q19f0" 
      allowfullscreen>
    </iframe>
    <p><strong>Project 2: Custom Engine</strong><br>Rendering and physics in a C++ Vulkan-based engine.</p>
  </div>

  <div class="video-card">
    <iframe 
      src="https://www.youtube.com/embed/3JZ_D3ELwOQ" 
      allowfullscreen>
    </iframe>
    <p><strong>Project 3: Dev Tools</strong><br>Tools I built for rapid game iteration and debugging.</p>
  </div>

</div>
