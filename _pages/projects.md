---
layout: splash
title: Projects
permalink: /projects/
author_profile: true

header:
  overlay_color: "#000"
  overlay_filter: "0.35"
  overlay_image: /assets/images/lake.png
  caption: ""

intro:
  - excerpt: "A few things I’ve built / worked on. (More coming soon.)"

feature_row:
  - image_path: /assets/images/wiibowling.jpg
    alt: "Project card"
    title: "MediaPipe → Arduino LED Tracker"
    excerpt: "Computer vision hand tracking that drives LED patterns."
    url: "https://github.com/AsbahTalal"
    btn_label: "View"
    btn_class: "btn--primary"

  - image_path: /assets/images/anatolia.jpg
    alt: "Project card"
    title: "Personal Website (Jekyll + GitHub Pages)"
    excerpt: "Built and customized a Minimal Mistakes blog with archives + styling."
    url: "https://asbahtalal.github.io/blog/"
    btn_label: "Visit"
    btn_class: "btn--primary"

  - image_path: /assets/images/ghibli.jpg
    alt: "Project card"
    title: "More Projects Coming"
    excerpt: "I’m actively building—this section will keep growing."
    url: "/posts/"
    btn_label: "See posts"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}
