---
layout: default
title: RC-Docs project test
sidebar:
  nav: "docs"
---

# Introduction

Blah

## Contents auto-generated

<h2>{{ site.data.navigation.docs_list_title }}</h2>
<ul>
   {% for item in site.data.navigation.docs %}
      <li><a href="{{ item.url }}">{{ item.title }}</a></li>
   {% endfor %}
</ul>

---
The end.
