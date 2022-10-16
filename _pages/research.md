---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Working Papers 

  * **Ni, Jiaqian.** "Behavior, Identity, and Incongruency: When and How are Political Attitudes Moved?"

  * [Kai Quek](https://ppaweb.hku.hk/f/quek), and **Jiaqian Ni**. "International Apologies and Reconciliation."
  
  * **Ni, Jiaqian.**, Felix Wang, and [Kai Quek](https://ppaweb.hku.hk/f/quek). "The Sources of National Pride: Survey Evidence from China and the United States"
       

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
