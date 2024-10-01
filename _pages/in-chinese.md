---
layout: default
title: IN CHINESE
permalink: /in-chinese/
tags: [IN CHINESE]  
---

<!-- begin content -->
<section class="section">
  <div class="container">
    <div class="row">
      {% for post in site.tags["IN CHINESE"] %}  <!-- 使用大写标签 -->
        {% if post.title != null %}
          <div class="col col-4 col-d-6 col-t-12">
            {% include article.html %}
          </div>
        {% else %}
          <p>No title found for this post.</p>  <!-- 调试输出 -->
        {% endif %}
      {% endfor %}
      {% if site.tags["IN CHINESE"] | size == 0 %}
        
      {% endif %}
    </div>
  </div>
</section>
<!-- end content -->
