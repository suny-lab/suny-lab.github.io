---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

## Research questions

![]({{ site.url }}{{ site.baseurl }}/images/research/Geometric_coding_cells.jpg){: style="display:block; margin:auto; width:60%; max-width:600px;" }

The Sun lab aims to elucidate the neural circuit mechanisms that underlie learning and memory, with a focus on spatial navigation and contextual representation in both health and disease. Understanding one's environment and remembering relevant context are essential for survival, and the hippocampus plays a central role in these processes. We are particularly interested in how the hippocampus and subiculum encode complex features of the environment, such as boundaries, corners, and 3D geometry, and how these representations guide behavior and memory formation.

Our lab combines in vivo calcium imaging, viral-genetic circuit mapping, single-cell and spatial transcriptomics, and computational modeling to investigate how specific cell types in the hippocampal formation contribute to spatial coding, memory, and disease-related circuit alterations. For example, we recently discovered that distinct populations of subicular neurons encode concave and convex geometric features, providing insight into how the brain reconstructs spatial layout (Sun et al., 2024). We also identified hippocampal neurons that are selectively engaged during drug-context associations, laying the groundwork for developing targeted interventions for addiction (Sun and Giocomo, 2022).

Students and postdocs in our lab may work on projects involving in vivo calcium imaging of neural activity in freely behaving mice, mapping neural circuits using viral-genetic tools, analyzing high-dimensional neural and behavioral data, building AI-empowered computational models, or performing molecular profiling of behaviorally relevant neurons. Trainees will gain hands-on experience in modern neuroscience techniques, advanced data science tools, and hypothesis-driven experimental design.

## Techniques

* In vivo 1-photon and 2-photon miniscope imaging in freely behaving animals, with multicolor and optogenetic options. 

<div style="max-width:600px; width:60%; margin: 0 auto; text-align:center;">

  <!-- Top image -->
  <img src="{{ site.url }}{{ site.baseurl }}/images/research/miniscope_mouse.png"
       alt="Top illustration"
       style="width:40%; height:auto; display:block; margin:0 auto 0;">

  <!-- GIF -->
  <img src="{{ site.url }}{{ site.baseurl }}/images/research/miniscope_video.gif"
       alt="Motion correction demo"
       style="width:100%; height:auto; display:block;">

  <!-- Caption (wraps to the same width) -->
  <div style="margin-top:8px; font-style:italic; font-size:80%;">
    Raw vs. motion corrected in vivo miniscope (1-photon) calcium imaging of hippocampal CA1 (Sun and Giocomo, 2022, Nat Commun)
  </div>
</div>
<br>

* Computational modeling of single-cell and population-level neural dynamics

<div style="width:90%; margin: 0 auto; text-align:center;">
  <img src="{{ site.url }}{{ site.baseurl }}/images/research/umap.jpg"
       alt="Manifold embedding"
       style="width:100%; height:auto; display:block;">
  <div style="margin-top:8px; font-style:italic; font-size:80%;">
    Three-dimensional (3D) embedding of the subiculum population activity in the triangle, square and hexagon. Each dot is the population state at one time point. Time points within 5cm of the corners are color coded as shown in the inset (Sun et al., 2024, Nature)
  </div>
</div>