---
layout: home
title: "Projects"
permalink: /projects/
author_profile: true
---

Here are some of my completed and ongoing projects. Use the index below to jump directly to each project:

---

<div class="sticky-project-dropdown">
  <label for="project-jump"><strong>Jump to project:</strong></label>
  <select id="project-jump" onchange="location.hash=this.value">
    <option value="">Select a project...</option>
    <option value="#tomo">Tomo: Endless Blue</option>
    <option value="#xenophear">Xenophear</option>
    <option value="#winterfury">WinterFury</option>
    <option value="#undead-rampage-vr">Undead Rampage VR</option>
    <option value="#blastworld">Blastworld</option>
    <option value="#tiny-zombie-experiment-vr">Tiny Zombie Experiment VR</option>
    <option value="#hugo-and-the-quest">Hugo and the Quest for the Sunstones</option>
    <option value="#dungeon-generator">Dungeon Generator</option>
    <option value="#mansion-from-hell">Mansion From Hell</option>
    <option value="#mathcaverpg">MathCaveRPG</option>
    <option value="#tank">Tank</option>
    <option value="#andromeda">Andromeda</option>
    <option value="#odinscript">OdinScript</option>
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

  <div class="video-card" id="tomo">
    <iframe src="https://www.youtube.com/embed/Bv85AsWsna8" allowfullscreen></iframe>
    <p><strong>Tomo: Endless Blue</strong><br>Recently announced pal/voxel based multiplayer game, I'm currently working on.</p>
  </div>

  <div class="video-card" id="xenophear">
    <iframe src="https://www.youtube.com/embed/zPWFNZ_WVLU" allowfullscreen></iframe>
    <p><strong>Xenophear</strong><br>Multiplayer alien shooter completed solo in 5 months. Inspired by Warhammer and Space Hulk.</p>
  </div>

  <div class="video-card" id="winterfury">
    <iframe src="https://www.youtube.com/embed/M-ZAOmgmXIA" allowfullscreen></iframe>
    <p><strong>WinterFury</strong><br>VR WWII on-rails shooter. I'm currently working on the multiplayer version.</p>
  </div>

  <div class="video-card" id="undead-rampage-vr">
    <iframe src="https://www.youtube.com/embed/SOCEzR2JdUs" allowfullscreen></iframe>
    <p><strong>Undead Rampage VR</strong><br>Endless zombie shooter powered by ChatGPT-generated logic.</p>
  </div>

  <div class="video-card" id="blastworld">
    <iframe src="https://www.youtube.com/embed/zsUR8mbkk7U" allowfullscreen></iframe>
    <p><strong>Blastworld</strong><br>Battle royale built in 5 weeks to hone my multiplayer programming skills.</p>
  </div>

  <div class="video-card" id="tiny-zombie-experiment-vr">
    <iframe src="https://www.youtube.com/embed/T9wvSPwp5tE" allowfullscreen></iframe>
    <p><strong>Tiny Zombie Experiment VR</strong><br>Part zombie shooter, part zombie infection simulator, Works in VR too.</p>
  </div>

  <div class="video-card" id="hugo-and-the-quest">
    <iframe src="https://www.youtube.com/embed/GI-guSmPKIo" allowfullscreen></iframe>
    <p><strong>Hugo and the Quest for the Sunstones</strong><br>PlayStation 1 title. I created the PC version, level compiler, and tools.</p>
  </div>

  <div class="video-card" id="dungeon-generator">
    <iframe src="https://www.youtube.com/embed/kAPA-jgyark" allowfullscreen></iframe>
    <p><strong>Dungeon Generator</strong><br>Procedural dungeon layout with room elevation and connect points.</p>
  </div>

  <div class="video-card" id="mansion-from-hell">
    <iframe src="https://www.youtube.com/embed/S1lDgBKzeqU" allowfullscreen></iframe>
    <p><strong>Mansion From Hell</strong><br>VR horror title in progress with procedural mansion generation.</p>
  </div>

  <div class="video-card" id="mathcaverpg">
    <iframe src="https://www.youtube.com/embed/5EU12Vbuc6I" allowfullscreen></iframe>
    <p><strong>MathCaveRPG</strong><br>Use math to fight in real-time. Launched on mobile, now free online.</p>
  </div>

  <div class="video-card" id="tank">
    <iframe src="https://www.youtube.com/embed/IPbtSauC73A" allowfullscreen></iframe>
    <p><strong>Tank</strong><br>DOS tank game coded on a 286.</p>
  </div>

  <div class="video-card" id="andromeda">
    <iframe src="https://www.youtube.com/embed/nLN4kTqeYv4" allowfullscreen></iframe>
    <p><strong>Andromeda</strong><br>Unreleased space RPG with planetary travel and tile-based world design.</p>
  </div>

  <div class="video-card" id="odinscript">
    <iframe src="https://www.youtube.com/embed/-8jytbNTWzs" allowfullscreen></iframe>
    <p><strong>OdinScript</strong><br>Daily task planner app for neurodiverse users. Designed and shipped by me.</p>
  </div>

</div>
