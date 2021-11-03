---
title: Team
layout: gridlay
permalink: /team/
---

{% for member in site.data.team_members %}
<div class="col-sm-6 clearfix">
  <img src="/images/teampic/touxiang copy.jpg" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">
    
  <li> {{ member.education }} </li>
  <li> {{ member.company }} </li>
  <li> {{ member.LinkedIn }} </li>
  <li> {{ member.Homepage }} </li>
  </ul>
</div>
{% endfor %}
