---
layout: page-doc
title: Machine Learning
subheading: Fundamental concepts and different techniques in Python, R and SAS.
description: Fundamental concepts and different techniques in Python, R and SAS.
color: grad-blog
image: "/images/icons/machine-learning.svg"
permalink: /machine-learning
---

<div class="home-container">
  <div class="home-articles">
    <div class="home-wrapper">
      <div class="page-holder">
        <ul>
        {% for post in site.posts %}
            {% if post.categories contains 'machine learning' %}
                <li>
                  <a class="post-link" href="{{ site.baseurl }}{{ post.url }}">
                    <div class="page-treasure-wrapper">
                      <div class="page-treasure-image" >
                        <div style="background-image: url('{{ post.image }}')"></div>
                      </div>
                      <div class="page-treasure">
                        <h2>{{ post.title }}</h2>
                        <p>{{ post.description }}</p>
                      </div>
                    </div>
                  </a>
                </li>
            {% endif %}
        {% endfor %}
        </ul>
      </div>
    </div>
  </div>
</div>