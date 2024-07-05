---
layout: archive
title: "Selected Papers"
classes: wide
permalink: /research/
author_profile: true
FDSHyper:
  - alt: "FDSHyper"
    title: "Distributional Inclusion Hypothesis and Quantifications: Probing for Hypernymy in Functinoal Distributional Semantics"
    authors: "Chun Hei Lo, Wai Lam, Hong Cheng, and Guy Emerson"
    venue: "In _ACL 2024_; **Area Chair Award**"
    tldr: "This work reveals that Functional Distributional Semantics (FDS) captures hypernymy if trained on a corpus that follows the Distributional Inclusion Hypothesis (DIH). We further propose an alternative FDS training objective that handles simple universal quantifications, which enables hypernymy learning under the reverse of the DIH and is shown to improve hypernymy detection from corpora."
    image_path: /assets/FDShyper/FDShyper.png
    # gif_width: 200
    # gif_caption: "his work shows that Functional Distributional Semantics (FDS) can capture hypernymy if trained on a corpus that follows the Distributional Inclusion Hypothesis (DIH), and proposes a training objective that handles simple universal quantifications and allow hypernymy learning under the reverse of DIH."
    url_paper: "https://aclanthology.org/2024.acl-long.784/"
    url_slides: "/assets/FDShyper/FDShyper_slides_acl2024.pdf"
    url_poster: "/assets/FDShyper/FDShyper_poster.pdf"
    url_video: "/assets/FDShyper/FDShyper_pres.mp4"
    btn_label_paper: "Paper"
    btn_label_slides: "Slides"
    btn_label_poster: "Poster"
    btn_label_video: "Video"
    btn_class: "btn--inverse"
  - image_path: /assets/FDShyper/FDShyper.gif
TCSFromDMRS:
  - alt: "TCSFromDMRS"
    title: "Functional Distributional Semantics at Scale"
    authors: "Chun Hei Lo, Hong Cheng, Wai Lam, and Guy Emerson"
    venue: "In _*SEM 2023_"
    tldr: "Functional Distributional Semantics (FDS) attempts to learn truth-conditional meanings of words from distributional information in a corpus. This work extends the applicability of FDS to sentences with more complex structures."
    image_path: /assets/FDSAS/FDSAS.gif
    url_paper: "https://aclanthology.org/2023.starsem-1.37.pdf"
    url_slides: "/assets/FDSAS/FDSAS_slides_starsem.ppsx"
    url_poster: "/assets/FDSAS/FDSAS_poster.pdf"
    url_code: "https://github.com/aaronlolo326/TCSfromDMRS/tree/main"
    # url_video: "https://aclanthology.org/2022.acl-long.372.mp4"
    btn_label_paper: "Paper"
    btn_label_slides: "Slides"
    btn_label_poster: "Poster"
    btn_label_code: "Code"
    btn_class: "btn--inverse"
pshrgOnDMRS:
  - alt: "pshrgOnDMRS"
    title: "Semantic Composition with PSHRG for Derivation Tree Reconstruction from Graph-Based Meaning Representations"
    authors: "Chun Hei Lo, Wai Lam, and Hong Cheng"
    venue: "In _ACL 2022_"
    tldr: "This work explores the use of a formal graph grammar in approximating the composition of meaning representation graphs and recovering their synatctic derivations. Surface realization becomes more explainable with the syntax trees."
    image_path: /assets/PSHRGOnDMRS/PSHRG.gif
    url_paper: "https://aclanthology.org/2022.acl-long.372.pdf"
    url_slides: "/assets/PSHRG/PSHRGOnDMRS_slides.ppsx"
    url_video: "https://aclanthology.org/2022.acl-long.372.mp4"
    btn_label_paper: "Paper"
    btn_label_slides: "Slides"
    btn_label_video: "Video"
    btn_class: "btn--inverse"
DSTC9:
  - alt: "DSTC9"
    title: "Task-Oriented Dialogue System with Unstructured Knowledge Access"
    authors: "Mudit Chaudhary, Borislav Dzodzo, Sida Huang, Chun Hei Lo, Mingzhi Lyu, Lun Yiu Nie, Jinbo Xing, Tianhua Zhang, Xiaoying Zhang, Jingyan Zhou, Hong Cheng, Wai Lam, Helen Meng"
    venue: "In arXiv"
    tldr: "This is a joint work with the CUHK team in participating the Ninth Dialog System Technology Challenge (DSTC9). We developed a dialog system using retrieval-augmented generation. I am responsbile for developing the retrieval algorithm of knowledge snippets that best answer the user's query given the dialogue history. We ranked 12 out of the 24 participating teams. Visit the links below to see how we appproached it!"
    image_path: /assets/DSTC9/dstc9.gif
    url_task: "https://github.com/alexa/alexa-with-dstc9-track1-dataset"
    url_paper: "https://arxiv.org/abs/2101.06066#:~:text=15%20Jan%202021%5D-,Unstructured%20Knowledge%20Access%20in%20Task%2Doriented%20Dialog%20Modeling%20using%20Language,and%20Knowledge%2DIntegrative%20Response%20Generation&text=Dialog%20systems%20enriched%20with%20external,of%20the%20supporting%20databases%2FAPIs."
    url_code: "https://github.com/muditchaudhary/CUHK-DSTC9"
    # url_video: "https://aclanthology.org/2022.acl-long.372.mp4"
    btn_label_task: "Task"
    btn_label_paper: "Paper"
    btn_label_code: "Code"
    # btn_label_video: "Video"
    btn_class: "btn--inverse"
---

<!-- {% for post in site.posts limit: 5 %}
  {% include archive-single.html %}
{% endfor %} -->

{% include gallery_research id="FDSHyper" layout="half" type="left" %}

{% include feature_row_research id="TCSFromDMRS" type="right" %}

{% include feature_row_research id="pshrgOnDMRS" type="left" %}

{% include feature_row_projects id="DSTC9" type="right" %}