---
---
{% include section.html %}
{% capture text %}
Who: Friends + Family <br>
What: A Wedding <br>
Where: Pie Ranch in Pescadero, CA <br>
When: Sunday June 13th, 2027  <br>
Why: Because Why Not? <br>

{%
  include button.html
  link="research"
  text="RSVP"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/paddleboarding.jpeg"
  link="research"
  title="Overview"
  text=text
%}
