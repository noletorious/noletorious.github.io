---
layout: default
title: Projects
permalink: /projects/
---
<div class="container">
    <div class="row">
        {% for project in site.data.projects %}
            <div class="col-sm-4">
                <div class="card">
                  <img class="card-img-top" src="https://via.placeholder.com/300x150" alt="Card image cap">
                  <div class="card-body">
                    <h5 class="card-title">{{ project.title }}</h5>
                    <p class="card-text text-truncate">{{ project.description }}</p>
                    <a href="{{ project.permalink }}" class="btn btn-primary">View Project</a>
                  </div>
                </div>
            </div>
        {% endfor %}
    </div>
</div>