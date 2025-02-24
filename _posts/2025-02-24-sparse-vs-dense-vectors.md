---
layout: post
title: "Vector Efficiency: Why Zeros Are Costing You Memory"
date: 2025-02-24 00:00:00-0000
description: What are sparse and dense vectors? What are vector representations?
tags: math python
categories: information-retrieval
giscus_comments: true
related_posts: false
---

{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/dense_vs_sparse_vectors.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/dense_vs_sparse_vectors.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
{% jupyter_notebook jupyter_path %}
{% else %}

<p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}
