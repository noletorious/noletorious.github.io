---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Noel's Blog
permalink: /blog/
---

<div class="container">
    <div class="row">
        <div class="col">
          {% for post in site.posts %}
            <a href="{{ post.url }}" >
              <div class="card mb-3 bg-light">
                <div class="card-body">
                      <span>{{ post.date | date: "%B %d, %Y" }} </span>
                      <h2 class="font-weight-bold mb-0">{{ post.title }}</h2>
                      <p class="mb-0">{{ post.description }}</p>
                </div>
              </div>
            </a>
          {% endfor %}
        </div>
    </div>
</div>



