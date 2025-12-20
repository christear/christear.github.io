---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Reach out to us in regards to research, media, and project sponsorship. We are always looking for new collaborators and students to join our team.

Prof. Zhang’s Office Address: Building 1B, Mohamed bin Zayed University of Artificial Intelligence, Masdar City, Abu Dhabi, United Arab Emirates

{%
  include button.html
  type="email"
  text="bin.zhang@mbzuai.ac.ae"
  link="bin.zhang@mbzuai.ac.ae"
%}
<!-- {%
  include button.html
  type="phone"
  text="(555) 867-5309"
  link="+1-555-867-5309"
%} -->
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/uzsQhx2Ti8A9pDuS9"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/mbzuai_photo1.jpg"
  caption="Campus"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/mbzuai_photo2.png"
  caption="1B OFFICE BUILDING"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
The future depends on some graduate student who is deeply suspicious of everything I have said. —— Geoffrey Hinton
{% endcapture %}

{% capture col2 %}
Anything found to be true of E. coli must also be true of elephants. —— Jacques Monod
{% endcapture %}

{% capture col3 %}
Mathematics is the door and the key to science. —— Roger Bacon
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
