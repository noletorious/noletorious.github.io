---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: flex
title: Noel Torres - Portfolio
---


<div class="
  d-flex 
  flex-grow-1 
  flex-row 
  align-items-center
  align-content-center 
  justify-content-center">
    <div class="card" style="width: 35rem;">
    <img class="card-img-top" 
      src="{{'/assets/images/portland-hood-1920x1080.jpg' | prepend: site.baseurl}}" alt="Portland SE" />
      <div class="card-block">
        <div class="card-body">
          <h5 class="card-title">{{ site.title }}</h5>
          <p class="card-text">{{ site.description }}</p>
          <a href="/projects/" class="btn btn-primary">View Projects</a>
        </div>
      </div>
    </div>
</div>


