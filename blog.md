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
          <ul>
            {% for post in site.posts %}
              <li>
                <a href="{{ post.url }}">
                  <span>{{ post.date }}</span>
                  <h2>{{ post.title }}</h2>
                  <p>{{ post.description }}</p>
                </a>
              </li>
            {% endfor %}
          </ul>
        </div>
    </div>
</div>



