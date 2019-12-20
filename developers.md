---
layout: page
title: Our Developers
permalink: /devs/
---

The list of our developers are being fetched from a csv file. 
<ul> {% for data in site.data.member %}
<li> Name= {{data.name}}           |  Tech = {{data.technology}} </li>
{% endfor %}
</ul>

<body background="https://images.pexels.com/photos/242236/pexels-photo-242236.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940">