---
title: CV
navbar_title: CV
permalink: /cv/
description: "Curriculum vitae · 2026"
---

<p><a class="cv-button" href="{{ site.data.profile.cv_link | relative_url }}"><i class="fas fa-file-pdf cv-button-icon" aria-hidden="true"></i> Download full CV (PDF)</a></p>

## Education

{% for item in site.data.profile.education %}
### {{ item.institution }}

{{ item.degree }} · {{ item.dates }}<br>
{{ item.detail }}
{% endfor %}

At Sabancı University, I received a full scholarship for academic excellence and was on the Dean’s High Honour List. My undergraduate advisor was Gözde Özaydın İnce.

<h2 id="awards">Awards & grants</h2>

{% include cv-records.html items=site.data.awards %}

## Research experience

{% include cv-records.html items=site.data.experience %}

## Publications

{% include publication-list.html items=site.data.publications %}

## Conferences & talks

{% include cv-records.html items=site.data.talks %}

Conference attendance also includes MRS Spring Meeting (2024), the Workshop on Simulating Soft Matter with Dissipative Particle Dynamics (2022), and METU Astrobiology Conferences (2018, 2019).

## Teaching & mentoring

{% include cv-records.html items=site.data.teaching %}

## Service & outreach

{% include cv-records.html items=site.data.service %}

## Workshops

{% include cv-records.html items=site.data.workshops %}

## Skills

**Languages:** Turkish (native), English (advanced; TOEFL iBT 100), Spanish (intermediate; DELE B1).

**Laboratory:** Atomic force microscopy, small/wide-angle X-ray scattering, cryogenic electron microscopy, fluorescence correlation spectroscopy, confocal microscopy, single particle profiler, small-angle neutron scattering, blow spinning, electrospinning, iCVD, and cell culture.

**Programming:** Python, MATLAB.<br>
**Data analysis & design:** AutoCAD, Gwyddion, Igor, BioXTAS RAW.
