---
layout: archive
title: "学生可视化作品集"
date: 2017-12-30T11:40:45-04:00
modified:
excerpt: "我的可视化作品"
tags: []
image: 
  feature:feke.png
  teaser:feke.png
---

在此展示我的可视化作品集！！
<html>
<head>

</head>
<body> 
<div class='tableauPlaceholder' id='viz1515301759738' style='position: relative'><noscript><a href='#'><img alt='仪表板 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;_1&#47;_15835&#47;1_2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='_15835&#47;1_2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;_1&#47;_15835&#47;1_2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='filter' value='publish=yes' /></object></div><script type='text/javascript'>var divElement = document.getElementById('viz1515301759738');var vizElement = divElement.getElementsByTagName('object')[0];vizElement.style.width='1000px';vizElement.style.height='827px';var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';vizElement.parentNode.insertBefore(scriptElement, vizElement);</script>
<br>
<br>
<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
 </body>
 </html>

