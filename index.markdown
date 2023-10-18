---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Home
header:
  image: /assets/images/home.PNG
---


<div id=welcome>
  <h1> Welcome!</h1>
  <p class="font-weight-bold">The Walbottle Village Tenants and Residents Association was founded in 2020 during Covid lockdown to bring relief to residents of Walbottle Village by encouraging a community spirit and assisting the most vulnerable members of the community.</p>

  <p class="font-weight-light">The remit is expanding post lockdown to include a gardening club, a history group a food bank collection and organising social events which are open to all.  We pride ourselves in being fully inclusive, having minority groups on the committee.</p>

  <p class="font-italic font-weight-light">Creating a more neighbourly village and a safe, beautiful place to live</p>
</div>

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
