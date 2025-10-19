---
title: "Projects"
layout: archive
permalink: /projects/
author_profile: true
---


## Featured Projects

<div class="project-cards">
  <a href="#" class="card" onclick="openModal('microchat-modal')">Micro Chat</a>
  <a href="#" class="card" onclick="openModal('flappybird-modal')">Flappy Bird</a>
  <a href="#" class="card" onclick="openModal('outdoorkit-modal')">Outdoor Kit</a>
</div>

<div id="microchat-modal" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeModal('microchat-modal')">&times;</span>
    <h2>Micro Chat</h2>
    <p>A micro:bit-powered messaging system using the built-in radio. This is only compatible with v2.</p>
    <a href="https://github.com/microbitcoder652/microbit-v2-micro-chat">View on GitHub</a>
  </div>
</div>

<div id="flappybird-modal" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeModal('microchat-modal')">&times;</span>
    <h2>Flappy Bird</h2>
    <p>A micro:bit-powered recreation of Flappy Bird.</p>
    <a href="https://github.com/microbitcoder652/microbit-v2-micro-chat">View on GitHub</a>
  </div>
</div>

<div id="outdoorkit-modal" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeModal('microchat-modal')">&times;</span>
    <h2>Outdoor Kit</h2>
    <p>A all-in-one kit for outdoors. This is only compatible with v2.</p>
    <a href="https://github.com/microbitcoder652/microbit-v2-micro-chat">View on GitHub</a>
  </div>
</div>

<script>
function openModal(id) {
  document.getElementById(id).style.display = "block";
}
function closeModal(id) {
  document.getElementById(id).style.display = "none";
}
</script>
