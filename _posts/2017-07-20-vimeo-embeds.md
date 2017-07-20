---
inFeed: true
description: >-
  interestingly it asks for the size as you get the embed code.. but that
  doesn’t mean we can’t change it… right ? The original embed code from vimeo is
  :
dateModified: '2017-07-20T13:01:16.762Z'
datePublished: '2017-07-20T13:01:17.679Z'
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

<iframe src="https://the-grid.github.io/ed-userhtml/?g=eJx1kMFugzAQRO_-CstSe2tMkEgVAvRbDF7CqoZF9gZEq_x7LUCplKp78oystzNbBF4cVOLQ0MAGB_DyW8g4IwVkpCGXHpxhnOCy-jNa7nJ5TJKXzegArx3nMtnkaKzF4fpWEzP1ucxOhzSLX-_iMKEF-oM3dSB34x3PND5QDtpf7r97N-cuCr1XKSxOsnEmhFI9WqnoY-tNDzL4plQd8xhyrUdnFvAxWg8Ub9DrNaROj-f35Jyesg9GdlAmr_XiIic-RvLsDXKZKLkCa_IWfKminqH-RDbO0dzenAuNBxhkT1_P1rPe467LVVXoLWrMrGOZSogfJE6Gag" height="610" style=""></iframe>

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