---
title: "SMARIN - Team"
layout: gridlay
excerpt: "SMARIN at University of Miami."
sitemap: false
permalink: /team/
---
<h4>Current Openings</h4>
<p><font size=4>PhD or Postdoc positions are available. Please contact for details via xxs784@miami.edu.</font></p>
<hr />

<h4>Research Staff</h4>
{% assign number_printed = 0 %}
{% for member in site.data.team2 %}
{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic2/{{ member.photo }}" class="img-responsive" width="28%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <p>{{ member.info1 }}</p>
  <p>{{ member.email }}</p>
  <p>{{ member.info2 }}</p>


  {% if member.number_educ == 1 %}
  <p> {{ member.education1 }} </p>
  {% endif %}

  {% if member.number_educ == 2 %}
  <p> {{ member.education1 }} </p>
  <p> {{ member.education2 }} </p>
  {% endif %}

  {% if member.number_educ == 3 %}
  <p> {{ member.education1 }} </p>
  <p> {{ member.education2 }} </p>
  <p> {{ member.education3 }} </p>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}
<hr />

<h4>Graduate Students</h4>
{% assign number_printed = 0 %}
{% for member in site.data.team1 %}
{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic2/{{ member.photo }}" class="img-responsive" width="28%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <p>{{ member.info1 }}</p>
  <p>{{ member.email }}</p>
  <p>{{ member.info2 }}</p>


  {% if member.number_educ == 1 %}
  <p> {{ member.education1 }} </p>
  {% endif %}

  {% if member.number_educ == 2 %}
  <p> {{ member.education1 }} </p>
  <p> {{ member.education2 }} </p>
  {% endif %}

  {% if member.number_educ == 3 %}
  <p> {{ member.education1 }} </p>
  <p> {{ member.education2 }} </p>
  <p> {{ member.education3 }} </p>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}
<hr />

<h4>Undergraduate Students</h4>
{% assign number_printed = 0 %}
{% for member in site.data.team3 %}
{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic2/{{ member.photo }}" class="img-responsive" width="28%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <p>{{ member.info1 }}</p>
  <p>{{ member.email }}</p>
  <p>{{ member.info2 }}</p>


  {% if member.number_educ == 1 %}
  <p> {{ member.education1 }} </p>
  {% endif %}

  {% if member.number_educ == 2 %}
  <p> {{ member.education1 }} </p>
  <p> {{ member.education2 }} </p>
  {% endif %}

  {% if member.number_educ == 3 %}
  <p> {{ member.education1 }} </p>
  <p> {{ member.education2 }} </p>
  <p> {{ member.education3 }} </p>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}
<hr />

<h4>Alumni -Academia, Industry, Professional, and Leadership</h4>
{% assign number_printed = 0 %}
{% for member in site.data.team4 %}
{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic2/{{ member.photo }}" class="img-responsive" width="35%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <p>{{ member.info1 }}</p>
  <p>{{ member.email }}</p>
  <p>{{ member.info2 }}</p>


  {% if member.number_educ == 1 %}
  <p> {{ member.education1 }} </p>
  {% endif %}

  {% if member.number_educ == 2 %}
  <p> {{ member.education1 }} </p>
  <p> {{ member.education2 }} </p>
  {% endif %}

  {% if member.number_educ == 3 %}
  <p> {{ member.education1 }} </p>
  <p> {{ member.education2 }} </p>
  <p> {{ member.education3 }} </p>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}
<hr />
