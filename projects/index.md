---
title: Research
nav:
  order: 1
  tooltip: Our research projects
---

## Current Research Themes

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  <!-- include button.html -->
  <!-- link="projects" -->
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  <!-- include feature.html -->
  image="images/photo.jpg"
  <!-- link="projects" -->
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}


<!-- # {% include icon.html icon="fa-solid fa-wrench" %}Projects -->

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. -->

<!-- {% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %} -->
