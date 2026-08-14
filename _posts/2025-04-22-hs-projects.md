---
layout: post
title:  "Project Portfolio (High School)"
date:   2026-04-22
categories: jekyll update
---

<style>
  body{
        background:none transparent;
  }

  .timeline {
    --dot-size: 0.9rem;
    --dot-gap: 1rem;
    position: relative;
    list-style: none;
    margin: 1.5rem 0 0;
    padding: 0;
  }
  .timeline::before {           /* vertical line — position derived from dot size, not guessed */
    content: '';
    position: absolute;
    left: calc(var(--dot-size) / 2);
    top: 0;
    bottom: 0;
    width: 2px;
    background: #ddd;
  }

  .tl-entry {
    margin-bottom: 3rem;
  }
  .tl-entry:last-child {
    margin-bottom: 0;
  }

  .tl-marker-row {               /* dot + date, centered against each other by flexbox */
    position: relative;
    display: flex;
    align-items: center;
    gap: var(--dot-gap);
    margin: 0 0 0.3rem;
  }

  .tl-dot {
    flex-shrink: 0;
    width: var(--dot-size);
    height: var(--dot-size);
    border-radius: 50%;
    background: #fff;
    border: 2px solid #ddd;
    box-shadow: 0 0 0 2px #fff;
    z-index: 1;
  }

  .tl-date {
    font-size: 0.85rem;
    color: #888;
    margin: 0;
  }

  .tl-body {
    padding-left: calc(var(--dot-size) + var(--dot-gap));
  }

  .tl-title {
    margin: 0 0 1rem;
  }

  .slides-figure {
    margin: 1.5rem 0;
  }

  .slides-container {
    position: relative;
    width: 100%;
    padding-bottom: 57%; /* 569/960 aspect ratio */
    height: 0;
    overflow: hidden;
    border-radius: 16px;
    box-shadow: 0 4px 24px rgba(0, 0, 0, 0.10);
    background: white;
    border-bottom: 1px solid black;
    border-left: 1px solid black;
    border-right: 1px solid black;
  }

  .slides-container iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 0;
  }

  .slides-figure figcaption {
    text-align: center;
    font-size: 0.85rem;
    color: #666;
    margin-top: 8px;
  }

</style>

Here are some of my projects from before I started University! I'm proud of a lot of them and still want to show them off here. 

<ul class="timeline">

  <li class="tl-entry">
    <div class="tl-marker-row">
      <span class="tl-dot"></span>
      <p class="tl-date">July 2025</p>
    </div>
    <div class="tl-body">
      <h2 class="tl-title">Make it Real (Autodesk Contest)</h2>
      <figure class="slides-figure">
        <div class="slides-container">
          <iframe src="https://docs.google.com/presentation/d/e/2PACX-1vSQnbfIs2bZZjJif3JQMnuOWmT9UnFQpkIm7Y-OyrP0GbxdwE5j3QRDhn_Xv0GgYs0NDxjZePGiLvIt/pubembed?start=false&loop=true&delayms=3000" allowtransparency="true" frameborder="0" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
        </div>
      </figure>
    </div>
  </li>

  <li class="tl-entry">
    <div class="tl-marker-row">
      <span class="tl-dot"></span>
      <p class="tl-date">January 2025 – February 2025</p>
    </div>
    <div class="tl-body">
      <h2 class="tl-title">Robot End Effector (FIRST Robotics)</h2>
      <figure class="slides-figure">
        <div class="slides-container">
          <iframe src="https://docs.google.com/presentation/d/e/2PACX-1vSHBolERgB87Z8FpHHxuavxRaRZHeFrLYbYMATR-cGsE0pdGnIO2Jjcn2fgxb0fkA5OtHZsV5qqJelP/pubembed?start=false&loop=true&delayms=3000" frameborder="0" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
        </div>
      </figure>
    </div>
  </li>

  <li class="tl-entry">
    <div class="tl-marker-row">
      <span class="tl-dot"></span>
      <p class="tl-date">August 2024 – September 2024</p>
    </div>
    <div class="tl-body">
      <h2 class="tl-title">Metal Backed Bumpers (FIRST Robotics)</h2>
      <figure class="slides-figure">
        <div class="slides-container">
          <iframe src="https://docs.google.com/presentation/d/e/2PACX-1vTTC4FWZ06ThkjP9DuRcQIcjBp6ozqO2NPl5kTLc7s6eCv4ivrnOW5Bs4kVC4tG1Vwd3jHZR9XHJC9Z/pubembed?start=false&loop=true&delayms=30000" frameborder="0" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
        </div>
      </figure>
    </div>
  </li>

</ul>