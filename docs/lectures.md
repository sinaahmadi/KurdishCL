---
layout: page
title: Lectures
permalink: /lectures/
---

<!-- <ul id="archive">


{% for gallery in site.data.lectures %}
  {% if lectures.id == page.galleryid %}
    <h1>{{ lectures.description }}</h1>
    {% for image in sortedimages %}
      <li class="archiveposturl">
        <span><a href="{{ site.url }}/graphs/{{ image.file }}">{{image.title }}</a></span><br>
<span class = "postlower">{{ image.caption }}<br />
<strong>Tags:</strong> {{ image.tags }}</span>
      </li>
    {% endfor %}
  {% endif %}
{% endfor %}

</ul> -->

This page contains link to the lectures I give throughout the semester. The slides in their expanded form are available in PDF. Also, the handout of the lecture is available in PDF; the handout is bascially the slides without any effects (therefore easier to be read and printed). If the lecture has additional files, it is also provided. 

### 1. Introduction / دەسپێک
<ul id="archive">
  <li><i class="fas fa-file-pdf"></i> Slides (<a href="https://github.com/sinaahmadi/KurdishCL/raw/master/lectures/lecture_1_introduction.pdf" target="_blank">PDF</a>)</li>
  <li><i class="fas fa-file-pdf"></i> Handout (<a href="https://github.com/sinaahmadi/KurdishCL/raw/master/lectures/lecture_1_introduction_handout.pdf" target="_blank">PDF</a>)</li>
  <li><i class="fab fa-github"></i> <strike>Code (github)</strike></li>
</ul>

<!-- <ul id="archive">
{% for lectures in site.data.lectures %}
      <li class="archiveposturl">
        <span><a href="{{ site.url }}/{{ lectures.dirname }}/{{ lectures.filename }}.pdf">{{ lectures.title }}</a></span><br>
<span class = "postlower">
<strong>tl;dr:</strong> {{ lectures.tldr }}</span>
<strong style="font-size:100%; font-family: 'Titillium Web', sans-serif; float:right; padding-right: .5em">
	<a href="https://github.com/{{ site.githubdir}}/tree/master/{{ lectures.dirname }}"><i class="fab fa-github"></i></a>&nbsp;&nbsp;
<a href="https://github.com/{{ site.githubdir}}/tree/master/{{ lectures.dirname }}/{{ lectures.filename}}.Rmd"><i class="fab fa-r-project"></i></a>&nbsp;&nbsp;
<a href="https://github.com/{{ site.githubdir}}/blob/master/{{ lectures.dirname }}/{{ lectures.filename}}.pdf"><i class="fas fa-file-pdf"></i></a>
</strong> 
      </li>
{% endfor %}
</ul> -->
