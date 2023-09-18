---
layout: archive
title: "Selected Papers"
classes: wide
permalink: /research/
author_profile: true
FDSHyper:
  - alt: "FDSHyper"
    title: "Distributional Inclusion Hypothesis and Quantifications: Probing Hypernymy in Functinoal Distributional Semantics"
    authors: "Chun Hei Lo, and Guy Emerson"
    venue: "In _arXiv_"
    tldr: "This work shows that Functional Distributional Semantics (FDS) captures hypernymy if trained on a corpus that follows the Distributional Inclusion Hypothesis (DIH) and proposes an alternative training objective for FDS that handles simple universal quantifications for hypernymy learning under the reverse of DIH."
    image_path: /assets/FDShyper/FDShyper.png
    # gif_width: 200
    # gif_caption: "his work shows that Functional Distributional Semantics (FDS) can capture hypernymy if trained on a corpus that follows the Distributional Inclusion Hypothesis (DIH), and proposes a training objective that handles simple universal quantifications and allow hypernymy learning under the reverse of DIH."
    url_paper: "https://arxiv.org/abs/2309.08325"
    # url_slides: "/assets/ppts/FDSAS_slides_starsem.ppsx"
    # url_poster: "/assets/pdfs/FDSAS_poster.pdf"
    # url_video: "https://aclanthology.org/2022.acl-long.372.mp4"
    btn_label_paper: "Paper"
    # btn_label_slides: "Slides"
    # btn_label_poster: "Poster"
    # btn_label_video: "Video"
    btn_class: "btn--inverse"
  - image_path: /assets/FDShyper/FDShyper.gif
TCSFromDMRS:
  - alt: "TCSFromDMRS"
    title: "Functional Distributional Semantics at Scale"
    authors: "Chun Hei Lo, Hong Cheng, Wai Lam, and Guy Emerson"
    venue: "In _*SEM 2023_"
    tldr: "Functional Distributional Semantics (FDS) attempts learn probabilistic truth-conditional semantics from distributional information in a corpus. This work extends the applicability of FDS to sentences with more complex structures."
    image_path: /assets/FDSAS/FDSAS.gif
    url_paper: "https://aclanthology.org/2023.starsem-1.37.pdf"
    url_slides: "/assets/FDSAS/FDSAS_slides_starsem.ppsx"
    url_poster: "/assets/FDSAS/FDSAS_poster.pdf"
    # url_video: "https://aclanthology.org/2022.acl-long.372.mp4"
    btn_label_paper: "Paper"
    btn_label_slides: "Slides"
    btn_label_poster: "Poster"
    # btn_label_video: "Video"
    btn_class: "btn--inverse"
pshrgOnDMRS:
  - alt: "pshrgOnDMRS"
    title: "Semantic Composition with PSHRG for Derivation Tree Reconstruction from Graph-Based Meaning Representations"
    authors: "Chun Hei Lo, Wai Lam, and Hong Cheng"
    venue: "In _ACL 2022_"
    tldr: "This work explores the use of a formal graph grammar in approximating the composition of meaning representation graphs and recovering their synatctic derivations. Surface realization becomes more explainable with the syntax trees."
    image_path: /assets/PSHRGOnDMRS/PSHRG.gif
    url_paper: "https://aclanthology.org/2022.acl-long.372.pdf"
    url_slides: "/assets/PSHRG/PSHRGOnDMRS_slides.pptx"
    url_video: "https://aclanthology.org/2022.acl-long.372.mp4"
    btn_label_paper: "Paper"
    btn_label_slides: "Slides"
    btn_label_video: "Video"
    btn_class: "btn--inverse"
---

<!-- {% for post in site.posts limit: 5 %}
  {% include archive-single.html %}
{% endfor %} -->

{% include gallery_custom id="FDSHyper" layout="half" type="left" %}

{% include feature_row_custom id="TCSFromDMRS" type="right" %}

{% include feature_row_custom id="pshrgOnDMRS" type="left" %}