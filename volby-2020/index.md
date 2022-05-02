---
layout: elections-2020
title: Odvaha změnit Přerov
heroBgImg: articles/2022/banner_prerov.jpg
campaignGroupUid: volby-2020
campaignCategoryUid: kraj2020
candidateListUid: kraj2020
hideCandidateSocialProfiles: true
# customizeHeader: true
---

{% assign candidates = site.candidatelists | where: "uid", page.candidateListUid | first %}

{% capture subContent %}
  <h2 class="head-xs md:head-base mt-2 text-center">Přerov <strong>má na víc!</strong></h2>
{% endcapture %}

{% include elections-header.html img=page.img bgImg=page.heroBgImg mainContent=mainContent subContent=subContent candidateListNumber=candidates.number %}
