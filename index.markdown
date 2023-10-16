---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Home
---




hi
<!--<form action="https://getform.io/f/c59903cf-f72a-4120-ade8-a1b147a1bb7c" method="POST">
    <input type="text" name="name">
    <input type="email" name="email">
    <input type="text" name="message">
    <input type="hidden" name="_gotcha" style="display:none !important">
    <input type="checkbox" name="subscribe" value="yes" checked>
    <input type="hidden" name="subscribe" value="no">
    <button type="submit">Send</button>-->
<div id="news">
{% for post in site.posts limit: 3 %}
  <div class="post_info">
    <li>
         <a href="{{ post.url }}">{{ post.title }}</a>
         <span>({{ post.date | date:"%Y-%m-%d" }})</span>
    </li>
    </div>
  {% endfor %}
</div>