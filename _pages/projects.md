---
layout: archive
title: "Applications"
classes: wide
permalink: /projects/
author_profile: true
DSTC9:
  - alt: "DSTC9"
    title: "Task-Oriented Dialogue System with Unstructured Knowledge Access"
    # authors: "Chun Hei Lo, Wai Lam, and Hong Cheng"
    venue: "2021"
    description: "This is a joint work with the CUHK team in participating the Ninth Dialog System Technology Challenge (DSTC9). I worked on ranked retrieval of knowledge snippets that best answers the user's query given the dialogue history. We ranked 12 out of the 24 participating teams. Visit the links below to see how we appproached it!"
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
CVJD:
  - alt: "CVJD"
    title: "CV–JD Recommendation System"
    # authors: "Chun Hei Lo, Wai Lam, and Hong Cheng"
    venue: "2019"
    description: "I wrote a crawler to scrap over 40,000 publicly available CVs and 20,000 job descriptions (JD). Word-level and document-level representations are learnt using the scrapped data using unsupervised methods. A CV–JD matching algorithm based on the learnt representations was developed. A comprehensive evaluation was attempted and the results look coherent!"
    image_path: /assets/CVJD/cv_sample.png
    url_paper: "assets/CVJD/cvjd_report.pdf"
    url_slides: "/assets/CVJD/cvjd_slides.ppsx"
    url_sample_out: "assets/CVJD/cvjd_eval.pdf"
    url_plot: "assets/CVJD/jd2vec.html"
    # url_video: "https://aclanthology.org/2022.acl-long.372.mp4"
    btn_label_paper: "Paper"
    btn_label_slides: "Slides"
    btn_label_sample_out: "Sample Output"
    btn_label_plot: "Plot"
    # btn_label_video: "Video"
    btn_class: "btn--inverse"
---

<!-- {% for post in site.posts limit: 5 %}
  {% include archive-single.html %}
{% endfor %} -->

{% include feature_row_projects id="DSTC9" type="right" %}

{% include feature_row_projects id="CVJD" type="left" %}
