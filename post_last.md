---
layout: posts
permalink: /posts/last/
title: Last entry
---
<!DOCTYPE html>
<html>
  <head>
    <meta http-equiv="refresh" content="0; url={{ site.posts[0].url | relative_url }}">
    <script>window.location.href = "{{ site.posts[0].url | relative_url }}";</script>
    <title>Redirecting...</title>
  </head>
  <body>
    <p>Redirecting to the latest post: <a href="{{ site.posts[0].url | relative_url }}">{{ site.posts[0].title }}</a></p>
  </body>
</html>
