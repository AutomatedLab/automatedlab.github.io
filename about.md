---
title: About
permalink: /about/
---
# About us

This site is our GitHub page for [AutomatedLab]. Here you will find all necessary infos regarding the lab automation framework [AutomatedLab].

## Authors

{% for author in site.authors %}
  Name: {{ author[1].name }} <br />
  Twitter: <a href="https://www.twitter.com/{{author[1].twitter}}" target="_blank">https://www.twitter.com/{{author[1].twitter}}</a>
  GitHub: <a href="https://www.twitter.com/{{author[1].github}}" target="_blank">https://www.twitter.com/{{author[1].github}}</a>
{% endfor %}

[AutomatedLab]: https://github.com/AutomatedLab/AutomatedLab
