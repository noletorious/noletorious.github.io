---
layout: default
title: Projects
permalink: /projects/
---
<div class="container projects">
    <div class="row">
        {% for project in site.data.projects %}
            <div class="col-sm-6 mb-3">
                <a href="{{ project.permalink }}">
                    <div class="card">
                        <img class="card-img-top" src="{{ project.featuredImage}}" alt="Card image cap">
                        <div class="card-body bg-light">
                        <h4 class="card-title mb-0">{{ project.title }}</h4>
                        <p class="card-text text-truncate">{{ project.description }}</p>
                        </div>
                    </div>
                </a>
            </div>
        {% endfor %}
    </div>
</div>