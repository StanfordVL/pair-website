---
layout: base
title: Publications
about: "PAIR Publications"
---
<!-- Page Content -->
<div class="container">

  <!-- Page Heading/Breadcrumbs -->
  <div class="row">
    <div class="col-lg-12">
      <h1 class="page-header">Publications</h1>
      <ol class="breadcrumb">
        <li><a href="/">Stanford PAIR</a></li>
        <li class="active">Publications</li>
      </ol>
    </div>
  </div>

  {% capture written_year %}'None'{% endcapture %}

  {% for publication in site.categories.publications %}  
    {% capture year %}{{ publication.date | date: '%Y' }}{% endcapture %}
      {% if year != written_year %}
        {% include _publication_list_year.html %}
      {% endif %}
      {% capture written_year %}{{ year }}{% endcapture %}
      {% include _publication_list_entry.html %}
  {% endfor %}

  <hr>

  <!-- Footer -->
  <footer>
    <div class="row">
      <strong>* indicates equal contribution.</strong>
      <div class="col-lg-12">
      </div>
    </div>
  </footer>

</div>
<!-- /.container -->
