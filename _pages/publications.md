---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
 Campillo, J., Domínguez-Jimenez, J. A., & Cabrera, J. (2019, March). Sustainable Boat Transportation Throughout Electrification of Propulsion Systems: Challenges and Opportunities. In 2019 2nd Latin American Conference on Intelligent Transportation Systems (ITS LATAM) (pp. 1-6). IEEE.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
