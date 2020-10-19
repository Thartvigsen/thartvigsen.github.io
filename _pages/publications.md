---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

Publication Summary: (conference: number of papers)

KDD: 2, ACL: 1, CIKM: 1, IEEE BigData: 2, HEALTHINF: 2, URTC: 2, IEEE BHI: 1, ECML: 1

<div class="multi-search multi-search--issue-item">
    <ul class="rlist ">
        <li class="grid-item separated-block--dashed--bottom">
            <div class="issue-item clearfix">
                <div class="issue-item__citation">
                    <div class="issue-heading">research-article</div>
                </div>
                <div class="issue-item__content">
                    <h5 class="issue-item__title"><a
                            href="https://dl.acm.org/doi/10.1145/3394486.3403191?cid=99659453882">Recurrent
                            Halting Chain for Early Multi-label
                            Classification</a></h5>

                    <ul class="rlist--inline loa truncate-list"
                        title="list of authors" data-lines="2">
                        <li><a href="https://dl.acm.org/profile/99659453882"
                                title="Thomas Hartvigsen"><img
                                    class="author-picture"
                                    src="https://dl.acm.org/do/10.1145/contrib-99659453882/rel-imgonly/headshot.png"
                                    alt="Thomas Hartvigsen profile image" /><span>Thomas
                                    Hartvigsen</span></a><span
                                class="loa_author_inst hidden">
                                <p data-doi="10.1145/contrib-99659453882">
                                    Worcester Polytechnic Institute, Worcester,
                                    MA, USA</p>
                            </span><span>, </span></li>
                        <li><a href="https://dl.acm.org/profile/99659455092"
                                title="Cansu Sen"><img class="author-picture"
                                    src="https://dl.acm.org/pb-assets/icons/DOs/default-profile-1543932446943.svg"
                                    alt="Cansu Sen profile image" /><span>Cansu
                                    Sen</span></a><span
                                class="loa_author_inst hidden">
                                <p data-doi="10.1145/contrib-99659455092">
                                    Worcester Polytechnic Institute, Worcester,
                                    MA, USA</p>
                            </span><span>, </span></li>
                        <li><a href="https://dl.acm.org/profile/81466643630"
                                title="Xiangnan Kong"><img
                                    class="author-picture"
                                    src="https://dl.acm.org/pb-assets/icons/DOs/default-profile-1543932446943.svg"
                                    alt="Xiangnan Kong profile image" /><span>Xiangnan
                                    Kong</span></a><span
                                class="loa_author_inst hidden">
                                <p data-doi="10.1145/contrib-81466643630">
                                    Worcester Polytechnic Institute, Worcester,
                                    MA, USA</p>
                            </span><span>, </span></li>
                        <li><a href="https://dl.acm.org/profile/81408601880"
                                title="Elke Rundensteiner"><img
                                    class="author-picture"
                                    src="https://dl.acm.org/pb-assets/icons/DOs/default-profile-1543932446943.svg"
                                    alt="Elke Rundensteiner profile image" /><span>Elke
                                    Rundensteiner</span></a><span
                                class="loa_author_inst hidden">
                                <p data-doi="10.1145/contrib-81408601880">
                                    Worcester Polytechnic Institute, Worcester,
                                    MA, USA</p>
                            </span></li>
                    </ul>

                    <div class="issue-item__detail"><span>August
                            2020</span><span class="dot-separator">pp 1382-1392
                        </span><span><a
                                href="https://doi.org/10.1145/3394486.3403191"
                                class="issue-item__doi  dot-separator">https://doi.org/10.1145/3394486.3403191</a></span>
                    </div>
                    <div data-lines='4'
                        class="issue-item__abstract truncate-text">
                        <div class="issue-item__abstract truncate-text"
                            data-lines="4">

                            <p>Early multi-label classification of time series,
                                the assignment of a label set to
                                a time series before the series is entirely
                                observed, is critical for time-sensitive
                                domains such as healthcare. In such cases,
                                waiting too long to classify can render
                                ...
                            </p>
                        </div>
                    </div><iframe
                        src="https://dl.acm.org/action/renderAuthorizerContentBib?doi=10.1145/3394486.3403191"
                        frameborder="0" width="100%" height="100%"
                        class="bibliometrics-iframe"></iframe>
                </div>
            </div>
        </li>
    </ul>
</div>
<link rel="stylesheet"
    href="https://dl.acm.org/specs/products/acm/widgets/authorizer/scss/style.css" />

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

