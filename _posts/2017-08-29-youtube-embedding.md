---
inFeed: true
description: >-
  We can do similar with youtube embedding. If you go to your video in youtube,
  they will give you an embed code like this :
dateModified: '2018-04-28T07:05:59.184Z'
datePublished: '2018-04-28T07:06:00.195Z'
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

<iframe src="https://the-grid.github.io/ed-userhtml/?g=eJx1kMFKxDAQhu99iiHg0aYK66G2fQBB8KIHb0kz3UbTTkmmDavsuxvassKKc5uPmX_-f6rAJ4dNlrc0srIjevjOINVEwbKlsQSPTrFd8HHl0RruS7gripsN9GiPPZdQbO2kjLHj8VYTMw0lHB7y-0MaPWf5Yg3SH3mlA7mZd3mm6SLlsPvV_ffuRs5ZJfcolbELtE6FUItLKpG47bwaEIJva9EzT6GUMsaYn2jmWWN6wSBx0Gjk06t6658_3Mv7UcC6pckb9LUoBETUn5aVcxS72bnQesQRBvq6Rtf97ml9g2gquflJxmRy3PwAMOJ-Lg" height="450" style=""></iframe>