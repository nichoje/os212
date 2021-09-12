---
permalink: /ABOUT/
---

# About

Hi! my name is Nicholas Jonathan Kinandana. You can call me Nicholas or Okin it's ok. I'm from South Jakarta. 
I'm a CS sophomore at Universitas Indonesia. Feel free to explore my page! Cheers🥂

<br>
# More Information

<ul><li>
{% for ii in site.navbarlinks %}
  {% if ii.navbar == "GitHub Page" %}
    <a href="{{ ii.link | relative_url }}">{{ ii.navbar }}</a>
  {% endif %}
{% endfor %}
</li><li>
{% for ii in site.navbarlinks %}
  {% if ii.navbar == "GitHub" %}
    <a href="{{ ii.link | relative_url }}">{{ ii.navbar }}</a>
  {% endif %}
{% endfor %}
</li></ul><br>

# Qapla!



