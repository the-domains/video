---
inFeed: true
description: >-
  well this works.. from homepage to own page.. notice it resizes itself..
  always fitting the embedded window … new code I would suggest using this :
dateModified: '2017-07-20T11:29:00.992Z'
datePublished: '2017-07-20T11:29:01.740Z'
title: TED demo.. for all resolutions..
author: []
publisher: {}
via: {}
hasPage: true
sourcePath: _posts/2017-07-19-ted-test-for-all-resolutions.md
starred: false
datePublishedOriginal: '2017-07-19T11:48:00.852Z'
url: ted-test-for-all-resolutions/index.html
_type: Article

---
# TED demo.. for all resolutions..

<iframe src="https://the-grid.github.io/ed-userhtml/?g=eJx1kEFqwzAQAO9-hRD0WMstpAfXDuTSD_QBRpY28ZK11kjrmLTk71XjkEJLBTpoWEbMNknOBNuidBzEYoCoPguVz8QJBTnUKgJZwRO8XvmCXoZaPVXVwwoGwMMgtarW52S9x3B47FmEx1ptXsrnTR69FOUJPfAfve0T0yw3vfB0VxHsf7z__ruSS9GYW0rj8aQc2ZRafa_SmeM-2hFUiq7Vg8iUamNg7MGXkq_j0YilYzI2IHUJZOgGXrozz7HrY7Z0gyWaHQYrkFae_ckhz6mLYAnlrNX1k56jh9jqSqvkIhPllbQ6sFYL9EeUHREvbzPRu4sAQY38Yb_RPqO0Ivtr5FZ0XaLeNmatyVkm926_AMxvluY" height="600" style=""></iframe>

well this works.. from homepage to own page.. notice it resizes itself.. always fitting the embedded window ... new code I would suggest using this :

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
    <iframe src="https://embed.ted.com/talks/anil_seth_how_your_brain_hallucinates_your_conscious_reality" frameborder="0" scrolling="no" webkitAllowFullScreen mozallowfullscreen allowFullScreen class="video"></iframe>
    </div>