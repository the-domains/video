---
inFeed: true
description: >-
  We can do similar with youtube embedding. If you go to your video in youtube,
  they will give you an embed code like this :
dateModified: '2018-04-28T06:33:42.024Z'
datePublished: '2018-04-28T06:33:42.899Z'
title: YouTube embedding
author: []
publisher: {}
via: {}
sourcePath: _posts/2017-08-29-youtube-embedding.md
hasPage: true
starred: false
datePublishedOriginal: '2017-08-29T14:38:58.386Z'
url: youtube-embedding/index.html
_type: Article

---
# YouTube embedding

We can do similar with youtube embedding. If you go to your video in youtube, they will give you an embed code like this :

    <iframe width="560" height="315" src="https://www.youtube.com/embed/paYdLbTFUaI" frameborder="0" allowfullscreen></iframe>
    

You can simply paste that into an embedded window on a grid site, and it will appear...

Few issues though, it won't size well on a mobile device, it will be small and look terrible, and basically if you're going to do it.. do it right...

<iframe src="https://the-grid.github.io/ed-userhtml/?g=eJx1kDFrxDAMhff8CmPo2DgtXIc0yVgodGyHjnasXMQ5UbCVmGu5_16ThCtcqTZ9SE_vqQp8dtBkeUsjaxzBi-9MpJooICONpfDgNOMCzyuPaLkvxUNR3G2gBzz2XIpiaydtLY7He0PMNJTi8JQ_HtLoJcsXtEB_5LUJ5Gbe5Zmmq5SD7lf337sbuWSV2qNUFhfROh1CLa-pZOLYeT2ACL6tZc88hVKpGGN-pplnA-kFg4LBgFWT_rRv5v3lQ79KsW4Z8hZ8LQspIpgTsnaOYjc7F1oPMIqBvm7Rbb97Wt8gm0ptfpIxlRw3PyXyfhE" height="450" style=""></iframe>

Using the code below.. we now have a responsive video, whether here on the homepage, on a mobile phone, or on it's own page...

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
    <iframe src="https://www.youtube.com/embed/paYdLbTFUaI" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen class="video"></iframe>
    </div>

<iframe src="https://the-grid.github.io/ed-userhtml/?g=eJx1j8FqhEAQRO9-RTOwxzhuYHMw6gcEArkkh9xGp9VORltmWmUT9t8jKhvYkL7Vo6iuyoKcHRZRXHEvhnr08B3BcgMHEuI-BY_OCE34uPKZrLQpHJPksIEWqWklhWSTg7GW-uauZBHuUjg9xPenxXqJ4oks8p94UwZ2o-zxwsM1ymH9m_vv341cokzvUzJLE1TOhJCr6yq1cKq96RCCr3LVigwh1frMo4xxifrp1by1zx_u5b1RsBpL9hZ9rhIFM5afJMY5nuvRuVB5xB46_rpFt3qvsS5XRaa3CksXvZQsfgDLYXkw" height="450" style=""></iframe>