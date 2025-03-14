---
layout: post
title: "Relevance Matters: How TF-IDF Finds What Counts"
date: 2025-03-13 00:00:00-0000
description: Starting from text and implementing TF-IDF
tags: math python
categories: information-retrieval
giscus_comments: true
related_posts: false
---

{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/building_up_to_tf_idf.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/building_up_to_tf_idf.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
{% jupyter_notebook jupyter_path %}
{% else %}

<p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}
