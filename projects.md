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

.modal {
  display: none;
  position: fixed;
  z-index: 1000;
  left: 0; top: 0;
  width: 100%; height: 100%;
  background-color: rgba(0,0,0,0.8);
}

.modal-content {
  background-color: #111;
  margin: 10% auto;
  padding: 20px;
  border: 2px solid #00ffe7;
  width: 80%;
  color: #e0f7fa;
  box-shadow: 0 0 20px #00ffe7;
}

.close {
  color: #00ffe7;
  float: right;
  font-size: 28px;
  cursor: pointer;
}

function closeModal(id) {
  document.getElementById(id).style.display = "none";
}
</script>
