---
layout: project
title: TriMet
permalink: /projects/trimet/
---

<div class="container pt-5 pb-5">
    <div class="row">
        <div class="col">
        <h1>{{ page.title }}</h1>
        <p>As one of TriMet's designers, I focus on digital interfaces and creating new visuals usually having to do with 2D animation.</p>
        </div>
    </div>
</div>
<div class="container">
    <div class="row">
        <div class="col-sm">
            <table class="table table-striped">
              <tbody>
              {% for project in site.data.projects %}
                {% for projectItem in project.projectList %}
                  <tr>
                      <td>{{ projectItem.projectTitle }}</td>
                      <td>
                        <a href="{{ projectItem.projectLink }}">
                            <i class="fas fa-external-link-square-alt"></i>
                        </a>
                    </td>
                  </tr>
                {% endfor %}
              {% endfor %}
              </tbody>
            </table>
        </div>
        <div class="col-sm">
            <img class="d-block w-100 img-rounded" src="https://via.placeholder.com/720x280" alt="Third" />
        </div>
    </div>
</div>
