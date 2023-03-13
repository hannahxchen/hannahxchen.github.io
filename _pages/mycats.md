---
layout: page
permalink: /mycats/
title: my cats
description: Cute pictures of my cats.
nav: true
---

<!-- pages/mycats.md -->
<div class="mycats">
    <p>Their instagram account: <a href="https://www.instagram.com/the_asshole_cat/">@the_asshole_cat</a>. I made it initially for Marshall as you can see based on the account handle. (Hayley's an angel not an a-hole.) Now they share the same account. I post some pictures and stories and make some funny reels about them occasionally.</p>
    <h2 class="category">Marshall</h2>
    <div class="container">
        <div class="row  row-cols-1 row-cols-md-2">
        {%- for cat in site.data.cats.marshall -%}
        {% include mycats.html %}
        {%- endfor %}
        </div>
    </div>
    <h2 class="category">Hayley</h2>
    <div class="container">
        <div class="row  row-cols-1 row-cols-md-2">
        {%- for cat in site.data.cats.hayley -%}
        {% include mycats.html %}
        {%- endfor %}
        </div>
    </div>
    <h2 class="category">Marshall & Hayley</h2>
    <div class="container">
        <div class="row  row-cols-1 row-cols-md-2">
        {%- for cat in site.data.cats.marshall_and_hayley -%}
        {% include mycats.html %}
        {%- endfor %}
        </div>
    </div>
</div>
