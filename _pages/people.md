---
layout: base
title: People
about: "PAIR People"
permalink: /people
---
<!-- Page Content -->
<div class="container-fluid">

  <div class="container">
      <!-- Page Heading/Breadcrumbs -->
      <div class="row">
          <div class="col-lg-12">
              <h1 class="page-header">People
                  <small></small>
              </h1>
              <ol class="breadcrumb">
                  <li><a href="/">Stanford PAIR</a></li>
                  <li class="active">People</li>
              </ol>
          </div>
      </div>

      <div class="row">
          <div class="col-lg-12">
              <span class="brand-sitename-title">Current Members</span>
              <h2 class=""><small>Faculty Members</small></h2>
          </div>

          {% for person_kv in site.data.people.faculty %} 
              {% assign person = person_kv[1] %}
              <div class="col-md-4">
                  <a href="{{ person.link }}" target="_blank">
                      <img class="img-responsive img-hover img-portfolio" src="/img/people/700x400/{{ person.img }}" alt="">
                  </a>
                  <h3><a href="{{ person.link }}" target="_blank">{{ person.name }}</a></h3>
                  <p class="person-title">{{ person.title }}</p>
                  <p class="person-email">{{ person.email }}</p>
              </div>
          {% endfor %}

      </div>


      <div class="row">
          <div class="col-lg-12">
              <h2 class=""><small>Postdocs and Visiting Scholars</small></h2>
          </div>

          {% for person_kv in site.data.people.postdocs %} 
              {% assign person = person_kv[1] %}
              <div class="col-md-4">
                  <a href="{{ person.link }}" target="_blank">
                      <img class="img-responsive img-hover img-portfolio" src="/img/people/700x400/{{ person.img }}" alt="">
                  </a>
                  <h3><a href="{{ person.link }}" target="_blank">{{ person.name }}</a></h3>
                  <p class="person-title">{{ person.title }}</p>
                  <p class="person-email">{{ person.email }}</p>
              </div>
          {% endfor %}
      </div>

      <div class="row">
          <div class="col-lg-12">
              <h2 class=""><small>Students</small></h2>
          </div>


          {% for person_kv in site.data.people.current_students %} 
              {% assign person = person_kv[1] %}
              <div class="col-md-4">
                  <a href="{{ person.link }}" target="_blank">
                      <img class="img-responsive img-hover img-portfolio" src="/img/people/700x400/{{ person.img }}" alt="">
                  </a>
                  <h3><a href="{{ person.link }}" target="_blank">{{ person.name }}</a></h3>
                  <p class="person-title">{{ person.title }}</p>
                  <p class="person-email">{{ person.email }}</p>
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

              <span class="brand-sitename-title">Alumni</span>
              <div class="page-header-people-dark"></div>

              {% for person_kv in site.data.people.alumni %} 
              {% assign person = person_kv[1] %}
                  <div class="col-md-4 img-portfolio">
                      <h3><a href="{{ person.link }}" target="_blank">{{ person.name }}</a></h3>
                      <p class="person-title">{{ person.title }}</p>
                  </div>
              {% endfor %}
          </div>
      </div>
      <br/>
    </div>
</div>


<div class="container-fluid">
    <br/><br/>
    <div class="container">
    <div class="row" id="cerc">
        <div class="col-lg-12">
            <span class="brand-sitename-title">Academic & Industry Collaborators</span>
            <div class="page-header-people"></div>

              {% for person_kv in site.data.people.collab %} 
              {% assign person = person_kv[1] %}
                  <div class="col-md-4 img-portfolio">
                      <h3><a href="{{ person.link }}" target="_blank">{{ person.name }}</a></h3>
                      <p class="person-title">{{ person.title }}</p>
                  </div>
              {% endfor %}
        </div>
    </div>
</div>
<!-- /.container -->
