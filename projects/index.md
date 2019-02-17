---
layout: default
title: Projects
permalink: /projects/
---
<div class="container">
    <div class="row">
        {% for project in site.data.projects %}
            <div class="col-sm-6 mb-3">
                <div class="card">
                    <img class="card-img-top" src="{{ project.featuredImage}}" alt="Card image cap">
                    <div class="card-body" style="padding:1.25rem 1.25rem 0 1.25rem">
                    <h5 class="card-title">{{ project.title }}</h5>
                    <p class="card-text text-truncate">{{ project.description }}</p>
                    <a href="{{ project.permalink }}" class="btn btn-primary float-right anchored-btn"><i class="fas fa-external-link-square-alt"></i></a>
                  </div>
                </div>
            </div>
        {% endfor %}
    </div>
</div>