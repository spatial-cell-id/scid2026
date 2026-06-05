---
layout: single
title: "Speakers"
permalink: /speakers/
---

<style>
  .speaker-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 30px; margin-top: 20px; }
  .speaker-card { text-align: center; background: #fff; padding: 15px; border: 1px solid #eee; border-radius: 8px; }
  .speaker-card img { border-radius: 50%; width: 140px; height: 140px; object-fit: cover; margin: 0 auto 15px auto; display: block; }
  .speaker-card h3 { margin: 10px 0; font-size: 1.1em; line-height: 1.2; }
  .speaker-card p { font-size: 0.85em; font-style: italic; margin: 5px 0; }
  .speaker-card details { text-align: left; margin-top: 10px; font-size: 0.8em; border-top: 1px solid #eee; padding-top: 10px; }
  .speaker-card summary { cursor: pointer; font-weight: bold; color: #007bff; }
</style>

<div class="speaker-grid">

  {% assign speakers = [
    {name: "Nathalie Beaujean", file: "Nathalie.jpg", title: "Slide-Seq: From Sample Preparation to Spatial Transcriptome Analysis", abstract: "Slide-Seq is a sequencing-based spatial transcriptomics technology that enables high-resolution mapping of gene expression within tissues. This presentation outlines the end-to-end workflow, from sample preparation to imaging, RNA transcript recovery and sequencing."},
    {name: "Hugo Blanc", file: "Hugo.jpg", title: "From Pixels to RNAs: a hands-on MERFISH image-processing workshop", abstract: "Multiplexed Error-Robust FISH (MERFISH) resolves the expression of hundreds to thousands of RNA species directly inside intact tissues. This hands-on workshop walks researchers and students through every step of that pipeline: MERFISH coding theory, raw-data filtering, iterative per-bit normalization, pixel-based decoding, and stitching."},
    {name: "Quentin Blampey", file: "Quentin_blampey.png", title: "Deep learning and computational methods for spatial data analysis", abstract: "This talk introduces SpatialData, an open and interoperable data framework; Sopa, a technology-invariant pipeline for image-based spatial omics; and Novae, a graph-based foundation model for spatial transcriptomics enabling zero-shot domain inference and batch correction."},
    {name: "Laura Cantini", file: "laura_cantin.jpg", title: "Multi-modal learning for single-cell data integration", abstract: "I will discuss three computational directions: (i) dimensionality reduction to study cellular heterogeneity simultaneously from multiple omics; (ii) gene network inference; and (iii) spatially-informed trajectory inference methods to reconstruct cell dynamics."},
    {name: "Zayna Chaker", file: "zayna.png", title: "Spatial transcriptomics reveal a novel compartmentalisation of adult brain stem cell niches", abstract: "By leveraging Spatial Transcriptomics and Machine Learning, we aim at comparing the molecular landscape of the two niches of the adult brain at subcellular resolution to find mechanisms of adult neurogenesis and synchronize proliferation during pregnancy."},
    {name: "Jonathan Enriquez", file: "placeholder.jpg", title: "TBD", abstract: "TBD"},
    {name: "Yad Ghavi-Helm", file: "Yad.jpg", title: "From single-cell to spatial transcriptomics: reconstructing gene expression", abstract: "We developed spatial-scERA, a novel in vivo/in silico single-cell method to reconstruct the spatial activity of candidate enhancer regions in Drosophila embryos."},
    {name: "Jennifer Love & Nour Bazzi", file: "Jenny.png", title: "Experimental design for combining modalities in spatial transcriptomics", abstract: "This workshop focuses on experimental design combining in situ hybridisation and immunostaining to visualise different stages of the central dogma, including DNA/RNA FISH integration."},
    {name: "Hilde Nelissen", file: "Hilde_Nelissen.jpg", title: "Linking Spatial Context to Cell Fate: Trajectories in the Maize Shoot Apical Meristem", abstract: "We developed cell segmentation pipelines to assign transcripts to individual cells, enabling the reconstruction of transcriptional changes along developmental trajectories and identifying novel factors involved in cell fate."},
    {name: "Marcelo Nollman", file: "Nollmann.png", title: "Spatial genomics by chromatin tracing: linking transcription to 3D genome organization", abstract: "I will present Hi-M, a multiplexed imaging approach that combines sequential labeling, microfluidics, and high-resolution microscopy to map the 3D organization of chromatin at the single-allele level."},
    {name: "Anthony Ozier-Lafontaine", file: "nthony-ozier-lafontaine.webp", title: "Biologically interpretable spatial domain identification", abstract: "We will introduce Kontext, a tool designed to identify spatial domains in a biologically interpretable way and uncover tissue organization and intercellular communication patterns."},
    {name: "Sophie Pantalacci", file: "Sophie.jpg", title: "Challenges of annotating and comparing scRNAseq datasets", abstract: "I will highlight the challenges in annotating scRNAseq data from a tissue developing in 3D, and comparing multiple samples from the same or different species."},
    {name: "Anna Pascual Reguant", file: "Anna_Pascual_Reguant.png", title: "Spatial-omics framework for colorectal malignancy transformation", abstract: "I will present a framework to analyse colorectal malignancy transformation by integrating whole-transcriptome spatial molecular imaging, single-nucleus RNA sequencing, and digital histopathology."},
    {name: "Sergio Salas", file: "Sergio_salas.png", title: "Segmentation strategies for accurate transcript-cell assignment", abstract: "Segmentation is one of the most important, yet unsolved, preprocessing steps in spatial omics. We will go through different strategies, pros and cons, and evaluation methods."},
    {name: "Ahilya N. Sawh", file: "AHILYA_SAWH.jpg", title: "Chromosome acrobatics during development", abstract: "My group investigates the genetic and molecular determinants of large-scale chromosome conformations and studies the relationships between conformation and genome function."},
    {name: "Teva Vernoux", file: "placeholder.jpg", title: "TBD", abstract: "TBD"},
    {name: "Nadav Yayon", file: "nadav_yayon.jpg", title: "Harnessing morphological information for spatial biology analysis", abstract: "I will present several tools: Bin2Cell, for converting spatial data into object-level representations; MorphoFM, for extracting morphological features; and TissueTag."}
  ] %}

  {% for s in speakers %}
  <div class="speaker-card">
    <img src="{{ site.baseurl }}/assets/images/speakers_pic/{{ s.file }}" alt="{{ s.name }}">
    <h3>{{ s.name }}</h3>
    <p>{{ s.title }}</p>
    <details>
      <summary>Abstract</summary>
      <p>{{ s.abstract }}</p>
    </details>
  </div>
  {% endfor %}

</div>