---
layout: single
title: "Other Projects"
permalink: /other/
author_profile: true
---

Other projects such as AI etc.

---

<div class="sticky-project-dropdown">
  <label for="project-jump"><strong>Jump to project:</strong></label>
 <select id="project-jump" onchange="location.hash=this.value">
  <option value="">Select a project...</option>
  <option value="#ollama">Running OLlama models on local PC</option>
  <option value="#stablediffusion">Run stable diffusion image generation on local PC</option>    
</select>
</div>

<style>
.sticky-project-dropdown {
  position: sticky;
  top: 1rem;
  z-index: 1000;
  background: var(--mm-surface, #1e1e1e);
  padding: 0.75rem 1rem;
  margin-bottom: 1.5rem;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.2);
}
.sticky-project-dropdown label {
  margin-right: 0.5rem;
}
.sticky-project-dropdown select {
  font-size: 1rem;
  padding: 0.5rem;
  border-radius: 6px;
  border: none;
  background-color: #2b2b2b;
  color: white;
}
</style>


<style>
.video-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}
.video-card {
  background: var(--mm-surface, #1e1e1e);
  padding: 1rem;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.2);
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
</style>

<style>
.video-card {
  position: relative;
  scroll-margin-top: 150px; /* Offset scroll anchor to avoid sticky menu overlap */
}
</style>


<div class="video-grid">
<div class="video-card" id="ollama">
  <iframe src="https://www.youtube.com/embed/N5DAkLFrO0o" allowfullscreen></iframe>
  <p><strong>Running OLlama models on local PC</strong><br>In this video, I demonstrate what it takes to run a local OLLama LLM model on your local PC.</p>
</div>

<div class="video-card" id="stablediffusion">
  <iframe src="https://www.youtube.com/embed/J014HFrFaxI" allowfullscreen></iframe>
  <p><strong>Run stable diffusion image generation on local PC</strong><br>In this video, I look at how to run stable diffusion image models on your local PC.</p>
</div>

</div>
