---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# Team

Our lab is made up of a highly engaged and collaborative team of researchers. We recognize that diverse teams do better research. We foster an environment where team members are treated equally, and where we respect and admire our differences. The team includes postdocs, students at all levels, staff, and our lab mascots.

{% include section.html %}

## Faculty
{% include list.html data="members" component="portrait" filter="role == 'Faculty'" %}

## Current Students
{% include list.html data="members" component="portrait" filter="role == 'Current Students'" %}

## Postdoctoral Researchers
{% include list.html data="members" component="portrait" filter="role == 'Postdoctoral Researchers'" %}

## Alumni
{% include list.html data="members" component="portrait" filter="role == 'Alumni'" %}

{% include section.html background="images/background.png" dark=true %}

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. -->

{% include section.html %}

{% capture content %}

<!-- {% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %} -->

{% endcapture %}

{% include grid.html style="square" content=content %}
