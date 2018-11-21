---
layout: base
title: Robots
about: "PAIR robots"
permalink: /robots
---
<!-- Page Content -->
<div class="container-fluid">

  <div class="container">
      <!-- Page Heading/Breadcrumbs -->
      <div class="row">
          <div class="col-lg-12">
              <h1 class="page-header">Robots
                  <small></small>
              </h1>
              <ol class="breadcrumb">
                  <li><a href="/">Stanford PAIR</a></li>
                  <li class="active">Robots</li>
              </ol>
          </div>
      </div>

      <div class="row">
          <div class="col-lg-12">
              <span class="brand-sitename-title">Arms</span>
              <h2 class=""><small>Sawyer</small></h2>
          </div>

          {% for robot_kv in site.data.robots.sawyers %} 
              {% assign robot = robot_kv[1] %}
              <div class="col-md-4">
                  <div class="hover_img_switch">
                       <img class="img-responsive img-seen-default img-portfolio" src="/img/robots/{{ robot.img }}" alt="">
                       <img class="img-responsive img-seen-hover img-portfolio" src="/img/robots/{{ robot.img_alt }}" alt="">
                  </div>
                  <h3>{{ robot.name }}</h3>
                  <p class="person-title">{{ robot.title }}</p>
              </div>
          {% endfor %}

      </div>


      <div class="row">
          <div class="col-lg-12">
              <h2 class=""><small>Panda</small></h2>
          </div>

          {% for robot_kv in site.data.robots.pandas %} 
              {% assign robot = robot_kv[1] %}
              <div class="col-md-4">
                  <div class="hover_img_switch">
                       <img class="img-responsive img-seen-default img-portfolio" src="/img/robots/{{ robot.img }}" alt="">
                       <img class="img-responsive img-seen-hover img-portfolio" src="/img/robots/{{ robot.img_alt }}" alt="">
                  </div>
                  <h3>{{ robot.name }}</h3>
                  <p class="person-title">{{ robot.title }}</p>
              </div>
          {% endfor %}
      </div>
      <br/>
  </div>
</div>


<div class="container-fluid container-colored">
    <br/><br/>
    <div class="container">
      <div class="row" id="cerc">
          <div class="col-lg-12">

          <span class="brand-sitename-title">Mobile Manipulators</span>
          <div class="page-header-people-dark"></div>

          {% for robot_kv in site.data.robots.mobile %} 
              {% assign robot = robot_kv[1] %}
              <div class="col-md-4">
                  <img class="img-responsive img-hover img-portfolio" src="/img/robots/{{ robot.img }}" alt="">
                  <h3>{{ robot.name }}</h3>
                  <p class="person-title">{{ robot.title }}</p>
              </div>
          {% endfor %}
          </div>
      </div>
      <br/>
    </div>
</div>
<!-- /.container -->
