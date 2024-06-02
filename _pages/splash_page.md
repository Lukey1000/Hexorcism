---
# title: "Hexorcism"
layout: splash
permalink: /
date: 2024-06-02
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/ghostintheshell.jpg
#  actions:
#    - label: "Download"
#      url: "https://github.com/mmistakes/minimal-mistakes/"
#excerpt: "Bacon ipsum dolor sit amet salami ham hock ham, hamburger corned beef short ribs kielbasa biltong t-bone drumstick tri-tip tail sirloin pork chop."
intro: 
  - excerpt: 'Unpacking the dark arts of DFIR, Red Teaming, and the cybersecurity industry.'
feature_row:
  - image_path: assets/images/event-viewer-98.gif
    alt: "Who needs a SIEM when you have Event Viewer?"
    title: "DFIR"
    excerpt: "Digital Forensics & Incident Response resources"
    url: "/dfir/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/red-team.png
    alt: "Red GPT"
    title: "Red Teaming"
    excerpt: "Penetration testing and red teaming resources"
    url: "/redteam/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}