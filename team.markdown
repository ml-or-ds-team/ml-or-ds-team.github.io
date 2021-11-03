---
title: Team
layout: page
permalink: /team/
---

<div class="row">
  <div class="column">
    <img src="/teampics/touxiang.jpg" width=150 height=150 style="float: left" alt="">
  </div>
  <div class="column">
    <img src="/teampics/andrew.jpg" width=150 height=150 style="float: left" alt="">
  </div>
  <div class="column">
    <img src="/teampics/andrew.jpg" width=150 height=150 style="float: left" alt="">
  </div>
  
</div>

.column {
  float: left;
  width: 33.33%;
  padding: 5px;
}

/* Clear floats after image containers */
.row::after {
  content: "";
  clear: both;
  display: table;
}
