---
inFeed: true
description: >-
  We can do similar with youtube embedding. If you go to your video in youtube,
  they will give you an embed code like this :
dateModified: '2017-08-29T14:39:07.383Z'
datePublished: '2017-08-29T14:39:07.498Z'
title: YouTube embedding
author: []
publisher: {}
via: {}
isBasedOnUrl: >-
  https://the-grid.github.io/ed-userhtml/?g=eJx1kDFrxDAMhff8CmPo2DgtXIc0yVgodGyHjnasXMQ5UbCVmGu5_16ThCtcqTZ9SE_vqQp8dtBkeUsjaxzBi-9MpJooICONpfDgNOMCzyuPaLkvxUNR3G2gBzz2XIpiaydtLY7He0PMNJTi8JQ_HtLoJcsXtEB_5LUJ5Gbe5Zmmq5SD7lf337sbuWSV2qNUFhfROh1CLa-pZOLYeT2ACL6tZc88hVKpGGN-pplnA-kFg4LBgFWT_rRv5v3lQ79KsW4Z8hZ8LQspIpgTsnaOYjc7F1oPMIqBvm7Rbb97Wt8gm0ptfpIxlRw3PyXyfhE
sourcePath: _posts/2017-08-29-youtube-embedding.md
starred: false
datePublishedOriginal: '2017-08-29T14:38:58.386Z'
_type: MediaObject

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