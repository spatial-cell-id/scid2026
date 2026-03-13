---
layout: single
title: "Speakers"
permalink: /speakers_/
---

<style>
  .speaker-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr); /* 3 colonne di uguale larghezza */
    gap: 30px; /* Spazio tra gli speaker */
    margin-bottom: 40px;
  }
  
  .speaker-card {
    text-align: center;
    background: #ffffff; /* Sfondo bianco opzionale */
  }
  
  .speaker-card img {
    border-radius: 50%;
    width: 150px;
    height: 150px;
    object-fit: cover;
    margin-bottom: 15px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1); /* Piccola ombra elegante (opzionale) */
  }

  .speaker-card h3 {
    margin-bottom: 5px;
    font-size: 1.2em;
  }

  .speaker-card details {
    text-align: left;
    background: #f8f9fa;
    padding: 12px;
    border-radius: 8px;
    margin-top: 15px;
    font-size: 0.9em;
  }
  
  .speaker-card summary {
    cursor: pointer;
    font-weight: bold;
    color: #007bff; /* Colore del link, cambialo se serve */
  }

  /* Adatta la griglia sui cellulari (1 colonna) e tablet (2 colonne) */
  @media (max-width: 900px) {
    .speaker-grid { grid-template-columns: repeat(2, 1fr); }
  }
  @media (max-width: 600px) {
    .speaker-grid { grid-template-columns: 1fr; }
  }
</style>


## Lectures

<div class="speaker-grid">

  <div class="speaker-card">
    <img src="/assets/images/speaker1.png" alt="Jane Doe">
    <h3>Dr. Jane Doe</h3>
    <p><em>Lecture title</em></p>
    <details>
      <summary>Abstract</summary>
      <p>Test text </p>
    </details>
  </div>
  <div class="speaker-card">
    <img src="/assets/images/speaker2.png" alt="Jon Doe">
    <h3>Prof. Jon Doe</h3>
    <p><em>Title</em></p>
    <details>
      <summary>Abstract</summary>
      <p>Test text</p>
    </details>
  </div>
  <div class="speaker-card">
    <img src="/assets/images/speaker3.png" alt="Anna Bianchi">
    <h3>Dr. Anne White</h3>
    <p><em>Title</em></p>
    <details>
      <summary>Abstract</summary>
      <p>Test text.</p>
    </details>
  </div>
  </div>


## Workshops

<div class="speaker-grid">

  <div class="speaker-card">
    <img src="/assets/images/speaker4.png" alt="John Smith">
    <h3>Prof. John Smith</h3>
    <p><em>Title</em></p>
    <details>
      <summary>Abstract</summary>
      <p>Test text.</p>
    </details>
  </div>
  </div>
