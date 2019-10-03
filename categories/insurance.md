---
layout: page-doc
title: Insurance
subheading: Actuarial trainings and the changing world.
description: Actuarial trainings and the changing world.
color: grad-blog
image: "/images/icons/insurance.svg"
permalink: /insurance
---

<div class="home-container">
  <div class="home-articles">
    <div class="home-wrapper">
      <div class="page-holder">
        <ul>
        {% for post in site.posts %}
          {% if post.categories contains 'insurance' %}
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