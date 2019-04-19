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
<div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel" style="z-index:0;">
  <ol class="carousel-indicators">
    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
  </ol>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img class="d-block w-100 card-img-top" src="{{'/assets/images/trimet.jpg' | prepend: site.baseurl}}" alt="First slide">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100 card-img-top" src="{{'/assets/images/cascadiathreads.jpg' | prepend: site.baseurl}}" alt="Third slide">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100 card-img-top" src="{{'/assets/images/portland-hood-720x280.jpg' | prepend: site.baseurl}}" alt="Second slide">
    </div>
  </div>
</div>
      <div class="card-block bg-light" style="z-index:1;">
        <div class="card-body" >
            <img
            id="noletorious-home"
            src="/assets/images/noletorious.jpg" 
            width="90" 
            class="rounded-circle float-right" 
            alt="" 
            style="margin:-4rem 1rem 1rem 0rem;"
            data-toggle="tooltip"
            data-placement="bottom"
            title="Work: <i class='far fa-eye-slash'></i>"
            />
          <h3 class="card-title font-weight-bold mb-0">{{ site.title }}</h3>
          <p class="card-text">{{ site.description }}</p>
          <ul class="list-group list-group-flush text-muted">
            <li class="list-group-item"><i class="fas fa-terminal fa-xs"></i> &nbsp; Javascript, React, Gatsby</li>
            <li class="list-group-item"><i class="fab fa-adobe fa-sm"></i> &nbsp; PS, AI, XD, AE, DW</li>
          </ul>
          <a style="border-radius:0 0 .25rem .25rem" href="/projects/" class="btn btn-secondary btn-sm">View Projects</a>
        </div>
      </div>
    </div>
</div>



