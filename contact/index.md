---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

You are welcome to reach out with questions! 

{%
  include button.html
  type="email"
  text="jandjweddinghotline@gmail.com"
  link="jandjweddinghotline@gmail.com"
%}

{%
  include button.html
  type="address"
  tooltip="The wedding will be held at Pie Ranch in Pescadero, CA. The google maps link is below for easy navigation."
  link="https://www.google.com/maps/place/Pie+Ranch/@37.1321082,-122.3163959,17z/data=!4m6!3m5!1s0x808e55caafeb2abb:0xcf813edfe879e0f3!8m2!3d37.132104!4d-122.313821!16s%2Fg%2F1thw6zd3?entry=ttu&g_ep=EgoyMDI2MDYyOS4wIKXMDSoASAFQAw%3D%3D"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
