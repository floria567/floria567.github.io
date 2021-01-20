---
title: "Project"
layout: splash
permalink: /project-page/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: assets/images/project_header.jpg
  # actions:
    # - label: "Download"
      # url: "https://github.com/mmistakes/minimal-mistakes/"
  # caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "Here is the portfolio of my past projects."

intro: 
  - excerpt: 'Topics include recommender systems, data visualization and software engineering.'

project_row:
  - image_path: assets/images/recommendation.PNG
    title: "Movie Recommendation System"
    excerpt: "Built a movie recommendation engine for personalized top recommended movies and conducted extensive experiments."
    url: "https://github.com/ds-personalization/final-project-top-recommended-final"
    btn_label: "Read More"
    btn_class: "btn--primary"

  - image_path: assets/images/edav.PNG
    title: "NYC citibike share"
    excerpt: "Analyzed and visualized the COVID-19 pandemic's influence on New York City residents who use Citi Bike as part of their commuting tools."
    url: "https://ds-eda-viz.github.io/NYC-Bike-Share/"
    btn_label: "Read More"
    btn_class: "btn--primary"

  - image_path: assets/images/stock.PNG
    title: "Text Mining for Seeking Alpha in Stock Market"
    excerpt: "Developed a prediction system by leveraging Yahoo Finance News for stock price prediction, simulated a systematic trading strategy"
    url: "https://github.com/floria567/Text-Mining"
    btn_label: "Read More"
    btn_class: "btn--primary"

intro2:
  - excerpt: 'Topics include NLP.'

project_row2:
  - image_path: assets/images/placeholder.PNG
    title: "PySpark Webpage Ranking"
    excerpt: "Built a PySpark application"
    url: "https://github.com/floria567/PySpark-webpage-ranking"
    bnt_label: "Read More"
    bnt_class: "btn--primary"
    
  - image_path: assets/images/placeholder.PNG
    title: "Bank Customer Segmentation and Fraud Detection"
    excerpt: "Built a PySpark application"
    url: "https://github.com/NLP-paper/NLP-paper"
    bnt_label: "Read More"
    bnt_class: "btn--primary"


---

{% include feature_row id="intro" type="left" %}

{% include feature_row id="project_row"%}

{% include feature_row id="intro2" type="left" %}

{% include feature_row id="project_row2"%}


<!-- {% include feature_row id="feature_row2" type="left" %} -->

<!-- {% include feature_row id="feature_row3" type="right" %} -->

<!-- {% include feature_row id="feature_row4" type="center" %} -->