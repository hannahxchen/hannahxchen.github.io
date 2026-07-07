---
layout: page
permalink: /misc/
title: misc
description: 
nav: true
nav_order: 5
---

<!-- pages/mycats.md -->
<div class="mycats">
    <h3>My Cats</h3>
    <br/>
    <h4 class="category">Marshall</h4>
    <div class="container">
        <div class="row  row-cols-1 row-cols-md-4">
        {%- for cat in site.data.cats.marshall -%}
        {% include mycats.liquid %}
        {%- endfor %}
        </div>
    </div>
    <h4 class="category">Hayley</h4>
    <div class="container">
        <div class="row  row-cols-1 row-cols-md-4">
        {%- for cat in site.data.cats.hayley -%}
        {% include mycats.liquid %}
        {%- endfor %}
        </div>
    </div>
    <h4 class="category">Marshall & Hayley</h4>
    <div class="container">
        <div class="row  row-cols-1 row-cols-md-4">
        {%- for cat in site.data.cats.marshall_and_hayley -%}
        {% include mycats.liquid %}
        {%- endfor %}
        </div>
    </div>
    <p>Checkout <a href="https://www.instagram.com/the_asshole_cat/">@the_asshole_cat</a> for more!</p>
</div>
