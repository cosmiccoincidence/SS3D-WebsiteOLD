---
layout: home
title: Home
---
<centred><h4><i>"Welcome to the station crew. Enjoy your stay."</i></h4></centred>

<div>
    <iframe class="video" width="580px" height="272px" src="https://www.youtube-nocookie.com/embed/uzLdgxOBPrc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    <h5><i>Video credit - Grimmie</i></h5>
</div>

Space Station 3D is a 3D take on the infamous Space Station 13 (tm). It is in pre-alpha still so there isn't much content yet, but if you want to play-test it, the download link below is for the latest release.

{% assign download_page = site.pages | where: "title", "Download" | first %}
<centred>
    <h6>
        <u><a href="{{ site.github_url }}/SS3D/releases/download/{{ download_page.release_latest }}/SS3D_{{ download_page.release_latest }}.zip">ss3d {{ download_page.release_latest }}</a></u>
    </h6>
</centred>
