---
layout: single
title: "Speakers"
permalink: /speakers/
---

<style>
  .speaker-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 30px; margin-bottom: 40px; }
  .speaker-card { text-align: center; background: #ffffff; }
  .speaker-card img { border-radius: 50%; width: 150px; height: 150px; object-fit: cover; margin-bottom: 15px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); }
  .speaker-card h3 { margin-bottom: 5px; font-size: 1.2em; }
  .speaker-card details { text-align: left; background: #f8f9fa; padding: 12px; border-radius: 8px; margin-top: 15px; font-size: 0.9em; }
  .speaker-card summary { cursor: pointer; font-weight: bold; color: #007bff; }
  @media (max-width: 900px) { .speaker-grid { grid-template-columns: repeat(2, 1fr); } }
  @media (max-width: 600px) { .speaker-grid { grid-template-columns: 1fr; } }
</style>

## Speakers

<div class="speaker-grid">

  <!-- Nathalie Beaujean -->
  <div class="speaker-card">
    <img src="{{ '/assets/images/speakers_pic/Nathalie.jpg' | relative_url }}" alt="Nathalie Beaujean">
    <h3>Nathalie Beaujean</h3>
    <p><em>Slide-Seq: From Sample Preparation to Spatial Transcriptome Analysis</em></p>
    <details>
      <summary>Abstract</summary>
      <p>Slide-Seq is a sequencing-based spatial transcriptomics technology that enables high-resolution mapping of gene expression within tissues. The bioinformatics pipeline will be described, with a focus on the challenges of cell segmentation and ongoing efforts to optimize this step.</p>
    </details>
  </div>

  <!-- Hugo Blanc -->
  <div class="speaker-card">
    <img src="{{ '/assets/images/speakers_pic/Hugo.jpg' | relative_url }}" alt="Hugo Blanc">
    <h3>Hugo Blanc</h3>
    <p><em>From Pixels to RNAs: a hands-on MERFISH image-processing workshop</em></p>
    <details>
      <summary>Abstract</summary>
      <p>This hands-on workshop walks researchers through the MERFISH pipeline, including coding theory, raw-data filtering, iterative per-bit normalization, pixel-based decoding, and stitching.</p>
    </details>
  </div>

  <!-- Quentin Blampey -->
  <div class="speaker-card">
    <img src="{{ '/assets/images/speakers_pic/Quentin_blampey.png' | relative_url }}" alt="Quentin Blampey">
    <h3>Quentin Blampey</h3>
    <p><em>Deep learning and computational methods for spatial data analysis</em></p>
    <details>
      <summary>Abstract</summary>
      <p>This talk introduces SpatialData, Sopa for image-based spatial omics segmentation, and Novae, a graph-based foundation model for spatial transcriptomics.</p>
    </details>
  </div>

  <!-- Laura Cantini -->
  <div class="speaker-card">
    <img src="{{ '/assets/images/speakers_pic/laura_cantin.jpg' | relative_url }}" alt="Laura Cantini">
    <h3>Laura Cantini</h3>
    <p><em>Multi-modal learning for single-cell data integration</em></p>
    <details>
      <summary>Abstract</summary>
      <p>I will discuss three computational directions: (i) dimensionality reduction for multi-omics, (ii) gene network inference, and (iii) spatially-informed trajectory inference.</p>
    </details>
  </div>

  <!-- Zayna Chaker -->
  <div class="speaker-card">
    <img src="{{ '/assets/images/speakers_pic/zayna.png' | relative_url }}" alt="Zayna Chaker">
    <h3>Zayna Chaker</h3>
    <p><em>Spatial transcriptomics reveal a novel compartmentalisation of adult brain stem cell niches</em></p>
    <details>
      <summary>Abstract</summary>
      <p>We aim at comparing the molecular landscape of the two niches of the adult brain at subcellular resolution and find shared and distinct molecular mechanisms of adult neurogenesis during pregnancy.</p>
    </details>
  </div>

  <!-- Jonathan Enriquez -->
  <div class="speaker-card">
    <img src="{{ '/assets/images/speakers_pic/placeholder.jpg' | relative_url }}" alt="Jonathan Enriquez">
    <h3>Jonathan Enriquez</h3>
    <p><em>TBD</em></p>
    <details>
      <summary>Abstract</summary>
      <p>TBD</p>
    </details>
  </div>

  <!-- Yad Ghavi-Helm -->
  <div class="speaker-card">
    <img src="{{ '/assets/images/speakers_pic/Yad.jpg' | relative_url }}" alt="Yad Ghavi-Helm">
    <h3>Yad Ghavi-Helm</h3>
    <p><em>From single-cell to spatial transcriptomics: reconstructing gene expression and enhancer activity</em></p>
    <details>
      <summary>Abstract</summary>
      <p>I will showcase spatial-scERA, a novel in vivo/in silico single-cell method for spatial single-cell enhancer-reporter assays designed to reconstruct the spatial activity of candidate enhancer regions.</p>
    </details>
  </div>

  <!-- Jennifer Love and Nour Bazzi -->
  <div class="speaker-card">
    <img src="{{ '/assets/images/speakers_pic/Jenny.png' | relative_url }}" alt="Jennifer Love">
    <h3>Jennifer Love and Nour Bazzi</h3>
    <p><em>Experimental design for combining modalities in spatial transcriptomics</em></p>
    <details>
      <summary>Abstract</summary>
      <p>This workshop will focus on experimental design combining in situ hybridisation approaches and immunostaining to visualise different stages of the central dogma in spatial transcriptomics experiments.</p>
    </details>
  </div>

  <!-- Hilde Nelissen -->
  <div class="speaker-card">
    <img src="{{ '/assets/images/speakers_pic/Hilde_Nelissen.jpg' | relative_url }}" alt="Hilde Nelissen">
    <h3>Hilde Nelissen</h3>
    <p><em>Linking Spatial Context to Cell Fate: Trajectories in the Maize Shoot Apical Meristem</em></p>
    <details>
      <summary>Abstract</summary>
      <p>In this presentation, I will present our efforts to dissect the balance between stem cell maintenance and differentiation in the maize shoot apical meristem using spatial transcriptomics.</p>
    </details>
  </div>

  <!-- Marcelo Nollman -->
  <div class="speaker-card">
    <img src="{{ '/assets/images/speakers_pic/Nollmann.png' | relative_url }}" alt="Marcelo Nollman">
    <h3>Marcelo Nollman</h3>
    <p><em>Spatial genomics by chromatin tracing: linking transcription to 3D genome organization</em></p>
    <details>
      <summary>Abstract</summary>
      <p>I will present Hi-M, a multiplexed imaging approach that combines sequential labeling, microfluidics, and high-resolution microscopy to map the 3D organization of chromatin.</p>
    </details>
  </div>

  <!-- Anthony Ozier-Lafontaine -->
  <div class="speaker-card">
    <img src="{{ '/assets/images/speakers_pic/nthony-ozier-lafontaine.webp' | relative_url }}" alt="Anthony Ozier-Lafontaine">
    <h3>Anthony Ozier-Lafontaine</h3>
    <p><em>Biologically interpretable spatial domain identification in spatial transcriptomics data</em></p>
    <details>
      <summary>Abstract</summary>
      <p>We will introduce Kontext, a tool designed to identify spatial domains in a biologically interpretable way and uncover tissue organization patterns.</p>
    </details>
  </div>

  <!-- Sophie Pantalacci -->
  <div class="speaker-card">
    <img src="{{ '/assets/images/speakers_pic/Sophie.jpg' | relative_url }}" alt="Sophie Pantalacci">
    <h3>Sophie Pantalacci</h3>
    <p><em>Challenges of annotating and comparing scRNAseq datasets in a spatio-temporal context</em></p>
    <details>
      <summary>Abstract</summary>
      <p>I will highlight the challenges in annotating scRNAseq data from a tissue developing in 3D and comparing multiple samples from the same or different species.</p>
    </details>
  </div>

  <!-- Anna Pascual Reguant -->
  <div class="speaker-card">
    <img src="{{ '/assets/images/speakers_pic/Anna_Pascual_Reguant.png' | relative_url }}" alt="Anna Pascual Reguant">
    <h3>Anna Pascual Reguant</h3>
    <p><em>Spatial-omics framework for colorectal malignancy transformation</em></p>
    <details>
      <summary>Abstract</summary>
      <p>I will present a spatial-omics framework to analyse colorectal malignancy transformation from cell to tissue level by integrating whole-transcriptome spatial molecular imaging, single-nucleus RNA sequencing, and digital histopathology.</p>
    </details>
  </div>

  <!-- Sergio Salas -->
  <div class="speaker-card">
    <img src="{{ '/assets/images/speakers_pic/Sergio_salas.png' | relative_url }}" alt="Sergio Salas">
    <h3>Sergio Salas</h3>
    <p><em>Segmentation strategies for accurate transcript-cell assignment in image-based spatial transcriptomics data</em></p>
    <details>
      <summary>Abstract</summary>
      <p>We will go through different segmentation strategies, pros and cons, evaluation methods and learn how to apply and assess the outcome of state-of-the-art segmentation algorithms.</p>
    </details>
  </div>

  <!-- Ahilya N. Sawh -->
  <div class="speaker-card">
    <img src="{{ '/assets/images/speakers_pic/AHILYA_SAWH.jpg' | relative_url }}" alt="Ahilya N. Sawh">
    <h3>Ahilya N. Sawh</h3>
    <p><em>Chromosome acrobatics during development</em></p>
    <details>
      <summary>Abstract</summary>
      <p>My research group investigates the genetic and molecular determinants of large-scale chromosome conformations, and studies the relationships between conformation and genome function during embryonic development.</p>
    </details>
  </div>

  <!-- Teva Vernoux -->
  <div class="speaker-card">
    <img src="{{ '/assets/images/speakers_pic/placeholder.jpg' | relative_url }}" alt="Teva Vernoux">
    <h3>Teva Vernoux</h3>
    <p><em>TBD</em></p>
    <details>
      <summary>Abstract</summary>
      <p>TBD</p>
    </details>
  </div>

  <!-- Nadav Yayon -->
  <div class="speaker-card">
    <img src="{{ '/assets/images/speakers_pic/nadav_yayon.jpg' | relative_url }}" alt="Nadav Yayon">
    <h3>Nadav Yayon</h3>
    <p><em>Harnessing morphological information for spatial biology analysis</em></p>
    <details>
      <summary>Abstract</summary>
      <p>I will present an overview of tools developed to use morphological information for spatial biology analysis, including Bin2Cell, MorphoFM, and TissueTag.</p>
    </details>
  </div>

</div>