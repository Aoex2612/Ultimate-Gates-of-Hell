+++
title = "Matchups"
description = ""
layout = "single"
hidemeta = true
omitTimestamps = true
toc = false
showToC = false
+++

<style>
  .mu-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 16px;
    margin-top: 20px;
    width: 100%;
  }

  .mu-card {
    position: relative;
    display: block;
    aspect-ratio: 1 / 1;
    background: #141414;
    border: 3px solid #2a2a2a;
    border-radius: 8px;
    overflow: hidden;
    transition: transform 0.2s ease;
  }

  .mu-card:hover {
    transform: scale(1.04);
  }

  .mu-card img {
    width: 100%;
    height: 100%;
    object-fit: contain;
    display: block;
    opacity: 0.85;
    pointer-events: none;
  }

  .mu-card span {
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    padding: 10px 4px;
    color: #ffffff;
    font-size: 1rem;
    font-weight: 600;
    text-align: center;
    background: linear-gradient(to top, rgba(0, 0, 0, 0.85), transparent);
  }
</style>

<div class="mu-grid">
  <a href="banjo/" class="mu-card">
    <img src="../images/fighters/Banjo.png" alt="Banjo & Kazooie">
    <span>Banjo & Kazooie</span>
  </a>

  <a href="bayonetta/" class="mu-card">
    <img src="../images/fighters/Bayonetta.png" alt="Bayonetta">
    <span>Bayonetta</span>
  </a>

  <a href="bowser/" class="mu-card">
    <img src="../images/fighters/Bowser.png" alt="Bowser">
    <span>Bowser</span>
  </a>

  <a href="junior/" class="mu-card">
    <img src="../images/fighters/Junior.webp" alt="Bowser Jr.">
    <span>Bowser Jr.</span>
  </a>

  <a href="byleth/" class="mu-card">
    <img src="../images/fighters/Byleth.png" alt="Byleth">
    <span>Byleth</span>
  </a>

  <a href="falcon/" class="mu-card">
    <img src="../images/fighters/Falcon.png" alt="Captain Falcon">
    <span>Captain Falcon</span>
  </a>

  <a href="ness/" class="mu-card">
    <img src="../images/fighters/ness.png" alt="Ness">
    <span>Ness</span>
  </a>

  <a href="gaw/" class="mu-card">
    <img src="../images/fighters/gaw.png" alt="Mr. Game & Watch">
    <span>Mr. Game & Watch</span>
  </a>

  <a href="falco/" class="mu-card">
    <img src="../images/fighters/falco.png" alt="Falco">
    <span>Falco</span>
  </a>
</div>
