---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

{% assign cv_pdf = '/assets/files/NanXiao_CV.pdf' | relative_url %}

<div class="cv-embed" style="margin-bottom:1rem;">
  <iframe
    src="{{ cv_pdf }}"
    width="100%"
    height="900px"
    style="border:1px solid #e5e7eb;border-radius:8px;">
  </iframe>
</div>

<p>
  <a class="btn btn--primary" href="{{ cv_pdf }}" target="_blank" rel="noopener">
    Download CV (PDF)
  </a>
</p>
