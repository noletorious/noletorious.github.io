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
<div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
  </ol>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img class="d-block w-100 card-img-top" src="{{'/assets/images/portland-hood-720x280.jpg' | prepend: site.baseurl}}" alt="First slide">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100 card-img-top" src="{{'/assets/images/trimet.jpg' | prepend: site.baseurl}}" alt="Second slide">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100 card-img-top" src="{{'/assets/images/cascadiathreads.jpg' | prepend: site.baseurl}}" alt="Third slide">
    </div>
  </div>
</div>
      <div class="card-block bg-light" style="z-index:2000;">
        <div class="card-body">
          <img src="/assets/images/noletorious.jpg" width="75" class="rounded-circle float-right" alt="" style="margin:-3rem 0 1rem;"/>
          <!--{{'/assets/vendor/fa-all.min.js' | prepend: site.baseurl}}-->
          <h5 class="card-title">{{ site.title }}</h5>
          <p class="card-text">{{ site.description }}</p>
          <a href="/projects/" class="btn btn-primary float-right anchored-btn">View Projects</a>
        </div>
      </div>
    </div>
</div>


