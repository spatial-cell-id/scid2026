---
layout: single
title: "Speakers"
permalink: /speakers/
---

<style>
  /* Regole per la griglia a 3 colonne */
  .speaker-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr); /* 3 colonne di uguale larghezza */
    gap: 30px; /* Spazio tra gli speaker */
    margin-bottom: 40px;
  }
  
  /* Stile per il singolo speaker */
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

  /* Rende il bottone dell'abstract carino */
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
    <h3>Dr.ssa Jane Doe</h3>
    <p><em>Titolo dell'intervento</em></p>
    <details>
      <summary>Leggi l'Abstract</summary>
      <p>Questo è il testo dell'abstract della Dr.ssa Doe. Puoi inserire qui tutta la descrizione del suo talk sulle Spatial OMICs.</p>
    </details>
  </div>
  <div class="speaker-card">
    <img src="/assets/images/speaker2.png" alt="Mario Rossi">
    <h3>Prof. Mario Rossi</h3>
    <p><em>Titolo dell'intervento</em></p>
    <details>
      <summary>Leggi l'Abstract</summary>
      <p>Testo dell'abstract del Prof. Rossi. Più è lungo, più il riquadro si espanderà verso il basso spingendo i contenuti.</p>
    </details>
  </div>
  <div class="speaker-card">
    <img src="/assets/images/speaker3.png" alt="Anna Bianchi">
    <h3>Dr.ssa Anna Bianchi</h3>
    <p><em>Titolo dell'intervento</em></p>
    <details>
      <summary>Leggi l'Abstract</summary>
      <p>Abstract della Dr.ssa Bianchi.</p>
    </details>
  </div>
  </div>


## Workshops

<div class="speaker-grid">

  <div class="speaker-card">
    <img src="/assets/images/speaker4.png" alt="John Smith">
    <h3>Prof. John Smith</h3>
    <p><em>Titolo del Workshop</em></p>
    <details>
      <summary>Leggi l'Abstract</summary>
      <p>Testo dell'abstract del workshop pratico.</p>
    </details>
  </div>
  </div>
