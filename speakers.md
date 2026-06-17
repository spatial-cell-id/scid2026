---
layout: single
title: "Speakers"
permalink: /speakers/
---

<style>
  .speaker-grid { display: grid; grid-template-columns: 1fr; gap: 40px; margin-top: 20px; }
  .speaker-card { background: #fff; padding: 25px; border: 1px solid #eee; border-radius: 8px; }
  .speaker-card h3 { margin-top: 0; color: #007bff; }
  .speaker-card p { font-style: italic; margin-bottom: 15px; }
  .speaker-card details { margin-top: 10px; font-size: 0.95em; line-height: 1.6; }
  .speaker-card summary { cursor: pointer; font-weight: bold; padding: 5px 0; outline: none; }
</style>

<div class="speaker-grid">

  <div class="speaker-card">
    <h3>Quentin Blampey</h3>
    <p>Deep learning and computational methods for spatial data analysis</p>
    <details>
      <summary>Abstract</summary>
      <p>This talk introduces three packages for spatial analysis, from upstream to more downstream. First, I will introduce SpatialData, an open and interoperable data framework for spatial omics data. Then, I will introduce Sopa (https://github.com/gustaveroussy/sopa), a technology-invariant, memory-efficient pipeline for image-based spatial omics. Sopa is a general toolkit for cell segmentation, transcript/channel aggregation, annotation, and geometric analysis across multiple platforms. Finally, I will present Novae (https://github.com/MICS-Lab/novae), a graph-based foundation model for spatial transcriptomics. Novae generalizes across tissues, technologies, and gene panels, enabling zero-shot domain inference, batch correction, and the construction of hierarchical spatial domains. It further supports downstream analyses such as spatially variable gene/pathway discovery and spatial domain trajectory analysis. Together, Sopa and Novae demonstrate how SpatialData can serve as a foundation for a large variety of tasks, from preprocessing and cell segmentation to downstream analysis.</p>
    </details>
  </div>

  <div class="speaker-card">
    <h3>Ahilya N. Sawh</h3>
    <p>Chromosome acrobatics during development</p>
    <details>
      <summary>Abstract</summary>
      <p>How one genome generates a large diversity of cell types, each with unique spatiotemporal gene expression patterns and physiological roles, is a fundamental question in cell and developmental biology. Recent work has indicated that nuclear organization plays an important role in controlling genome functions (transcription, replication, recombination, repair), and defects in genome organization are implicated in aberrant developmental and diseased states. However, the mechanisms of action are not well understood, nor is it clear what chromosome conformations are prevalent, or how they are formed in vivo. Advanced single-molecule imaging and computational approaches are needed to probe conformational dynamics and study the forms and functions of genome organization in animal models. We have previously uncovered high chromosome-scale structural variability in C. elegans embryos, and a novel topological role for the nuclear lamina in systemically stretching chromosomes, increasing structural heterogeneity, and weakening compartments. Currently, my new research group investigates the genetic and molecular determinants of large-scale chromosome conformations, and studies the relationships between conformation and genome function during embryonic development.</p>
    </details>
  </div>

  <div class="speaker-card">
    <h3>Anna Pascual Reguant</h3>
    <p>Spatial Omics analysis of colorectal malignancy transformation from cell to tissue scale</p>
    <details>
      <summary>Abstract</summary>
      <p>Understanding how molecular programs and tissue architecture interact during cancer development requires technologies that resolve biology across spatial scales. I will present a spatial-omics framework to analyse colorectal malignancy transformation from cell to tissue level by integrating whole-transcriptome spatial molecular imaging, single-nucleus RNA sequencing, and digital histopathology. The 24 datasets represent the colorectal cancerization continuum within intact human tissues, from healthy colons to very early hyperplastic lesions to adenomas, to carcinomas and to metastatic spread reaching the draining lymph nodes and the liver. To interpret these data, we implement spatial-centric analytical strategies combining metrics of tissue organization (e.g. cellular density and entropy), trajectory inference, and niche modelling that quantitatively capture architectural changes aligned with histopathology and transcriptional programs. This framework reveals emergent spatial patterns, including rare “transition crypts” detectable only through large-scale continuous tissue analysis, and spatially restricted molecular and cellular programs associated with metastatic dissemination. Ongoing cohort expansion and integration of orthogonal modalities—including spatial proteomics, post-translational modifications, and genomic characterization—enable cross-platform validation and provide a scalable analytical foundation for studying tissue transformation at unprecedented resolution.</p>
    </details>
  </div>

  <div class="speaker-card">
    <h3>Hilde Nelissen</h3>
    <p>Linking Spatial Context to Cell Fate: Trajectories in the Maize Shoot Apical Meristem</p>
    <details>
      <summary>Abstract</summary>
      <p>Understanding how stem cells transition toward differentiation requires resolving gene expression dynamics with high spatial and cellular resolution. In plants, the shoot apical meristem represents a powerful model to study this process, as it continuously generates new organs while maintaining a pool of stem cells. However, linking transcriptional states to precise spatial context and developmental trajectories remains a major challenge. In this presentation, I will present our efforts to dissect the balance between stem cell maintenance and differentiation in the maize shoot apical meristem using spatial transcriptomics. We developed and implemented cell segmentation pipelines to accurately assign transcripts to individual cells, enabling the reconstruction of transcriptional changes along developmental trajectories. Furthermore, by comparing spatial transcriptomic profiles between wild-type and mutant plants, we uncovered interdependencies within regulatory networks and by combining single-cell data with spatial transcriptomics we identified novel factors involved in meristem function and cell fate transitions.</p>
    </details>
  </div>

  <div class="speaker-card">
    <h3>Laura Cantini</h3>
    <p>Multi-modal learning for single-cell data integration</p>
    <details>
      <summary>Abstract</summary>
      <p>Single-cell RNA sequencing (scRNAseq) is revolutionizing biology and medicine. The possibility to assess cellular heterogeneity at a previously inaccessible resolution has profoundly impacted our understanding of development, of the immune system functioning and of many diseases. While scRNAseq is now mature, the single-cell technological development has shifted to other large-scale quantitative measurements, a.k.a. ‘omics’, and even spatial positioning. Each single-cell omics presents intrinsic limitations and provides a different and complementary information on the same cell. The current main challenge in computational biology is to design appropriate methods to integrate this wealth of information and translate it into actionable biological knowledge. In this talk, I will discuss three main computational directions currently explored in my team: (i) dimensionality reduction to study cellular heterogeneity simultaneously from multiple omics; (ii) gene network inference to integrate a large range of interactions between the features of various omics and isolate the regulators underlying cellular heterogeneity and (iii) spatially-informed trajectory inference methods to reconstruct the spatiotemporal landscape underlying cell dynamics.</p>
    </details>
  </div>

  <div class="speaker-card">
    <h3>Yad Ghavi-Helm</h3>
    <p>From single-cell to spatial transcriptomics: reconstructing gene expression and enhancer activity in a developing embryo</p>
    <details>
      <summary>Abstract</summary>
      <p>Understanding the spatial and temporal regulation of gene expression is essential for unraveling the mechanisms underlying development. Enhancers play a critical role in orchestrating these processes, but comprehensively identifying their spatio-temporal activity remains a significant challenge in developmental biology. To address this challenge, we developed spatial-scERA, a novel in vivo/in silico single-cell method for spatial single-cell enhancer- reporter assays (spatial-scERA) designed to reconstruct the spatial activity of candidate enhancer regions in parallel in multicellular organisms. Spatial-scERA integrates parallel reporter assays with single-cell RNA sequencing and spatial reconstruction using optimal transport, to map cell-type-specific enhancer activity at the single-cell level on a 3D virtual sample. In this lecture, I will showcase how spatial-scERA works and what we have learned from using it in Drosophila embryos, and expand on how single-cell OMICs, imaging and computational methods can be combined to reconstruct 3D gene expression in complex samples.</p>
    </details>
  </div>

  <div class="speaker-card">
    <h3>Sergio Salas</h3>
    <p>Segmentation strategies for accurate transcript-cell assignment in image-based spatial transcriptomics data</p>
    <details>
      <summary>Abstract</summary>
      <p>Segmentation is one of the most important, yet unsolved, preprocessing steps in spatial omics data analysis. We will go through different segmentation strategies, pros and cons, evaluation methods and learn how to apply and assess the outcome of state-of-the-art segmentation algorithms, using tools such as cellpose, segger or troutpy.</p>
    </details>
  </div>

  <div class="speaker-card">
    <h3>Sophie Pantalacci</h3>
    <p>Challenges of annotating and comparing scRNAseq datasets in a spatio-temporal context</p>
    <details>
      <summary>Abstract</summary>
      <p>I will highlight the challenges in annotating scRNAseq data from a tissue developing in 3D, and comparing multiple samples from the same or different species. I will also discuss the choice of the technology (10x genomics, Parse) and a technology which can be coupled to the latter to get a spatial annotation of the dataset (e.g., Curio Trekker).</p>
    </details>
  </div>

  <div class="speaker-card">
    <h3>Nadav Yayon</h3>
    <p>Harnessing morphological information for spatial biology analysis</p>
    <details>
      <summary>Abstract</summary>
      <p>Recent advances in spatial omics technologies are producing increasingly complex multimodal datasets, creating a need for computational methods that integrate imaging and molecular information. Morphology is often the shared layer of information between many spatial technologies and can therefore serve as a useful basis for integration and interpretation. In this workshop, I will present a practical overview of several tools we developed to use morphological information for spatial biology analysis. We will begin with Bin2Cell, a framework for converting binned spatial transcriptomics data into object-level representations for segmentation, downstream analysis, and integration with single-cell reference atlases. We will then introduce MorphoFM, a framework currently under development for extracting cellular and neighbourhood morphological features from spatial imaging data. Finally, we will demonstrate TissueTag, a server friendly platform for tissue annotation that combines morphology, spatial context, and molecular information to support tissue interpretation across datasets. The session will focus on practical applications, methodological considerations and limitations of these approaches into spatial biology workflows.</p>
    </details>
  </div>

  <div class="speaker-card">
    <h3>Zayna Chaker</h3>
    <p>Reshuffling the cards: Spatial transcriptomics reveal a novel compartmentalisation of adult brain stem cell niches during pregnancy</p>
    <details>
      <summary>Abstract</summary>
      <p>Stem cells are the pillar of tissue repair and regeneration in adults. However, unlike other organs, the brain has a very low regenerative capacity. In the mammalian brain, only two specific zones, remnants of embryonic neurogenic regions, retain the ability to proliferate and give rise to new neurons in the adult brain: the Ventricular-Sub-Ventricular Zone (V-SVZ) and the Sub-Granular Zone (SGZ) of the hippocampal Dentate Gyrus (DG). In both V-SVZ and DG, NSCs are all of glial nature and interact with highly similar niche cell types. Importantly, adult NSCs are highly heterogeneous and co-exist in both quiescent and actively dividing states. First, stem cell proliferation occurs more slowly in the DG and the medial wall of the V-SVZ compared to the lateral, more neurogenic region of the V-SVZ niche. Second, NSCs in the V-SVZ, and possibly in the DG, exhibit regional and molecular diversity, leading to the generation of distinct subtypes of adult-born interneurons. However, it remains unclear whether such heterogeneity arises from NSCs in specific niche domains being intrinsically-distinct, or whether their behavior is rather influenced by extrinsic factors tied to the regionalized nature of the niches themselves. By leveraging Spatial Transcriptomics, advanced data analysis methods and novel Machine Learning-based computational tools, we aim at comparing the molecular landscape of the two niches of the adult brain at subcellular resolution, and find shared and distinct molecular mechanisms of adult neurogenesis. More specifically, we investigate whether some V-SVZ and SGZ spatial domains cross-talk and synchronize their proliferation during an important physiological period of life, namely pregnancy.</p>
    </details>
  </div>

  <div class="speaker-card">
    <h3>Nathalie Beaujean</h3>
    <p>Slide-Seq: From Sample Preparation to Spatial Transcriptome Analysis</p>
    <details>
      <summary>Abstract</summary>
      <p>Slide-Seq is a sequencing-based spatial transcriptomics technology that enables high-resolution mapping of gene expression within tissues. This method leverages barcoded beads or nanoballs to capture RNA transcripts directly from tissue sections, allowing for sub-cellular resolution and comprehensive spatial profiling. This presentation outlines the end-to-end workflow of Slide-Seq, starting from sample preparation (including cryosectioning, permeabilization, and tissue placement on specialized slides) to imaging, RNA transcript recovery and sequencing. The critical steps of staining, imaging with advanced microscopes and the importance of precise alignment between histological images and spatial transcriptomic data will be highlighted. The bioinformatics pipeline will also be described, with a focus on the challenges of cell segmentation and ongoing efforts to optimize this step and integrate single-cell data with spatial transcriptomics. The pipeline supports multi-resolution analysis, from 100 µm to <1 µm, and is compatible with both fresh-frozen and FFPE samples. Applications include the study of complex biological systems such as embryos, organoids, and various tissue types (e.g., brain, lung, pancreas).</p>
    </details>
  </div>

  <div class="speaker-card">
    <h3>Hugo Blanc</h3>
    <p>From Pixels to RNAs: a hands-on MERFISH image-processing workshop</p>
    <details>
      <summary>Abstract</summary>
      <p>Multiplexed Error-Robust FISH (MERFISH) resolves the expression of hundreds to thousands of RNA species directly inside intact tissues, but turning raw multi-round microscopy data into a spatial gene-expression map is a non-trivial image-processing problem. This hands-on workshop walks researchers and students through every step of that pipeline. Participants work through Jupyter notebooks built on the starfish ecosystem. We cover MERFISH coding theory and codebook structure, raw-data filtering, iterative per-bit normalization, pixel-based decoding to gen identities, quality control, and stitching. By the end of the session, participants will understand what each pipeline step does, why it matters, and how to adapt the workflow to their own MERFISH or related image-based spatial-transcriptomics data.</p>
    </details>
  </div>

  <div class="speaker-card">
    <h3>Marcelo Nollman</h3>
    <p>Spatial genomics by chromatin tracing: linking transcription to 3D genome organization</p>
    <details>
      <summary>Abstract</summary>
      <p>Understanding how spatial genome organization relates to gene regulation remains a central challenge in cell biology. Recent advances in multiplexed imaging now enable the simultaneous visualization of many molecular species in single cells, overcoming the spectral limitations of conventional fluorescence microscopy. In this talk, I will present Hi-M, a multiplexed imaging approach that combines sequential labeling, microfluidics, and high-resolution microscopy to map the three-dimensional organization of chromatin together with transcriptional activity in intact tissues and organisms. Hi-M provides nanometer-scale measurements of chromatin architecture at the single-allele level while preserving spatial and cellular context. I will first describe the methodological principles underlying Hi-M and recent developments that extend its scalability and analytical power. I will then illustrate how this approach can uncover new principles of genome organization using two examples. In the adult Drosophila brain, multiplexed chromatin tracing reveals how enhancer–promoter interactions are organized across neuronal cell types, showing that spatial proximity defines a permissive regulatory state but does not quantitatively predict transcriptional output. In parallel, large-scale analyses of chromatin folding across tissues demonstrate that genome architecture can be described by a limited repertoire of recurrent structural motifs, whose combinatorial usage varies across cell types and disease states. Together, these results highlight how multiplexed imaging approaches such as Hi-M provide a direct and quantitative link between genome structure and function in single cells. More broadly, they illustrate how spatial genomics can move beyond descriptive maps to uncover the principles governing gene regulation in complex biological systems.</p>
    </details>
  </div>

  <div class="speaker-card">
    <h3>Anthony Ozier-Lafontaine</h3>
    <p>Biologically interpretable spatial domain identification in spatial transcriptomics data.</p>
    <details>
      <summary>Abstract</summary>
      <p>Identifying spatially coherent tissue domains is a key challenge in the analysis of spatial transcriptomics data. We will introduce Kontext, a tool currently under development in our team, designed to identify spatial domains in a biologically interpretable way. We will present the tool and walk through different examples of applications to spatial transcriptomics datasets, illustrating how Kontext can be used to uncover tissue organization and intercellular communication patterns across diverse biological contexts.</p>
    </details>
  </div>

  <div class="speaker-card">
    <h3>Jennifer Love and Nour Bazzi</h3>
    <p>Experimental design for combining modalities in spatial transcriptomics.</p>
    <details>
      <summary>Abstract</summary>
      <p>This workshop will focus on experimental design combining in situ hybridisation approaches and immunostaining to visualise different stages of the central dogma in spatial transcriptomics experiments. Participants will be introduced to the fundamental design principles of each element of these experiments. Case studies will be presented, including combining DNA and RNA FISH to study chromatin conformation and gene expression, as well as integration of chromosome painting and immunostaining. Discussions will be focused on group experimental design of new approaches tailored to the participants research questions. This workshop is designed for both biologists planning or troubleshooting multimodal spatial assays, and bioinformaticians looking to deepen their understanding of the upstream experimental design and underlying biology.</p>
    </details>
  </div>

  <div class="speaker-card">
    <h3>Jonathan Enriquez</h3>
    <p>Using OMICS to Decipher Cell Diversity in Space and Time.</p>
    <details>
      <summary>Abstract</summary>
      <p>In our lab, we study how the architecture of the locomotor system is established during development and maintained throughout adult life. A central question in our research is how cellular diversity is generated in space and time to build a functional locomotor system.
      In this talk, I will present how we combine genetics, single-cell sequencing, and computational approaches to decipher how muscle diversity emerges during development. In particular, I will discuss how genetic tools can be used to 1. recover spatial information lost during cell dissociation and 2. validate lineage relationships predicted bioinformatically.
      Because these genetic approaches are powerful but extremely time-consuming, we decided to develop at Spatial Cell ID, a 3D MERFISH-based pipeline that enables direct in situ mapping of the expression of hundreds of genes. I will introduce the main image-based spatial transcriptomics approaches currently available and provide an overview of our 3D MERFISH pipeline, from probe design to image acquisition and data analysis.</p>
    </details>
  </div>

</div>