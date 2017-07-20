---
inFeed: true
description: >-
  interestingly it asks for the size as you get the embed code.. but that
  doesn’t mean we can’t change it… right ? The original embed code from vimeo is
  :
dateModified: '2017-07-20T12:59:40.146Z'
datePublished: '2017-07-20T12:59:41.013Z'
title: Vimeo embeds..
author: []
publisher: {}
via: {}
hasPage: true
sourcePath: _posts/2017-07-20-vimeo-embeds.md
starred: false
datePublishedOriginal: '2017-07-20T12:22:49.611Z'
url: vimeo-embeds/index.html
_type: Article

---
# Vimeo embeds..

interestingly it asks for the size as you get the embed code.. but that doesn't mean we can't change it... right ? The original embed code from vimeo is :

    <iframe src="https://player.vimeo.com/video/219709265?title=0&byline=0&portrait=0" width="640" height="360" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

The width and height are fixed, but we can just use the same code as we did before to get the fluid resizing from the home page to it's own page..

<iframe src="https://the-grid.github.io/ed-userhtml/?g=eJx1UMtuwyAQvPMVK6T21uBESqq4xj31F3rH9iZeFQyCjSO3yr-X2mkqRSonZkDzqhJPFmtROWQDIfqAkSct_bFkYosSWj8wDqzlOzn08OYa7JIEVYvVz5OhASN8Ccgn-ERMfighojVMI77M_Jk67ktYF8XDQvRIx55LKBYYTNfRcHxqPLN3JWx3q802f72I1UhdNr2XN03y9sRXefbhJmXx8Kf7r-_CXESlfut3NEJrTUpa3lrJzNMhGoeQYqtlzxxSqVSwZsKYo-U98gZOzSHVZr1_Lvab3fZ1Xk4Xj81ks06-BB85GmJdSJgFGx87jFpmfMbmg9hY68-Hk7WpjYgDOP95T93ja9zZXNaVWqLmzCqXqYX4BqAdmEg" height="610" style=""></iframe>

embed code used :

    <style>
    .container {
        position: relative;
        width: 100%;
        height: 0;
        padding-bottom: 56.25%;
    }
    .video {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
    }
    </style>
    <div class="container">
    <iframe src="https://player.vimeo.com/video/219709265?title=0&byline=0&portrait=0" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen class="video"></iframe>
    </div>