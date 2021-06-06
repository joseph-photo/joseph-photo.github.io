---
layout: page
title: joseph
permalink: /joseph
order: 4
---


{% for image in site.static_files %}
<!--
    {% if image.path contains 'joseph' %}

-->
<div class="project">
    <div class= "thumbnail">
        <a href="{{ site.baseurl }}{{ image.path }}">
            <img src="{{ site.baseurl }}{{ image.path }}" />
        </a>
    </div>
</div>

<!--
    {% endif %}
-->
{% endfor %}




<!-- this is for the lightbox --> 
<script type="text/javascript" src="/js/lightbox.js"></script>
<link rel="stylesheet" href="/css/lightbox.css">