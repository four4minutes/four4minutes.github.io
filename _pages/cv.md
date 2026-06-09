---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Younghun Lim  
Graduate Student, Yokohama National University  
Yokohama, Japan · [lim-younghun-sw@ynu.jp](mailto:lim-younghun-sw@ynu.jp) · [four4minutes.github.io](https://four4minutes.github.io)

Research Interests
======

My research focuses on methods that allow AI systems, especially large language models, to handle real-world knowledge more accurately and flexibly. I am interested in reducing hallucination and contextual inconsistency by combining natural language processing, information extraction, retrieval-augmented generation, and knowledge graph construction.

Education
======

<div class="cv-education-item">
  <h3 class="cv-education-heading">Ph.D. Student</h3>
  <div class="cv-education-body">
    <span class="cv-meta">2026.04 - present</span><br>
    Graduate School of Environment and Information Sciences, Yokohama National University, Yokohama, Japan<br>
    <span class="cv-subtext">横浜国立大学 大学院環境情報学府 博士課程後期</span><br>
    Advisor: Tatsunori Mori
  </div>
</div>

<div class="cv-education-item">
  <h3 class="cv-education-heading">Master of Informatics</h3>
  <div class="cv-education-body">
    <span class="cv-meta">2024.04 - 2026.03</span><br>
    Graduate School of Environment and Information Sciences, Yokohama National University, Yokohama, Japan<br>
    <span class="cv-subtext">横浜国立大学 大学院環境情報学府 修士課程</span><br>
    Advisor: Tatsunori Mori
  </div>
</div>

<div class="cv-education-item">
  <h3 class="cv-education-heading">Bachelor of Engineering</h3>
  <div class="cv-education-body">
    <span class="cv-meta">2017.04 - 2021.03</span><br>
    College of Engineering Science, Yokohama National University, Yokohama, Japan<br>
    <span class="cv-subtext">横浜国立大学 理工学部 数物・電子情報系学科 情報工学EP</span><br>
    Thesis: Entity Linking of Legal Reference Expressions in Assembly Minutes<br>
    <span class="cv-subtext">議会議事録における法令の参照表現のエンティティリンキングに関する研究</span><br>
    Advisor: Tatsunori Mori
  </div>
</div>

<div class="cv-education-item">
  <h3 class="cv-education-heading">Japanese Language Preparation</h3>
  <div class="cv-education-body">
    <span class="cv-meta">2016.10 - 2017.03</span><br>
    Japanese Language Training Program, International Student Center, Yokohama National University, Yokohama, Japan<br>
    <span class="cv-subtext">横浜国立大学 国際教育センター 学部入学前予備教育プログラム</span>
  </div>
</div>

<div class="cv-education-item">
  <h3 class="cv-education-heading">Japanese Language Preparation</h3>
  <div class="cv-education-body">
    <span class="cv-meta">2016.03 - 2016.09</span><br>
    Japanese Language Training Program, Institute of International Education, Kyung Hee University, Seoul, Republic of Korea<br>
    <span class="cv-subtext">慶熙大学校 国際教育院 日韓共同理工系学部留学生予備教育課程</span>
  </div>
</div>

Publications
======

<div class="cv-publications">
{% for category in site.publication_category %}
  {% assign title_shown = false %}
  {% for post in site.publications reversed %}
    {% if post.category != category[0] %}
      {% continue %}
    {% endif %}
    {% unless title_shown %}
      <h3 class="cv-publication-heading">{{ category[1].title }}</h3>
      <ol class="cv-publication-list">
      {% assign title_shown = true %}
    {% endunless %}
    {% include archive-single-cv.html %}
  {% endfor %}
  {% if title_shown %}
    </ol>
  {% endif %}
{% endfor %}
</div>

Research Experience
======

<div class="cv-entry">
  <div class="cv-date">2024.12 - 2025.03</div>
  <div class="cv-entry-body">
    <strong>Technical Assistant</strong>, Yokohama National University<br>
    Project: A study on retrieval, summarization, and visualization of technical documents for technology transfer<br>
    <span class="cv-subtext">技術継承に資する技術文書の検索・要約・可視化に関する検討</span><br>
    Principal Investigator: Tatsunori Mori<br>
    Developed a text embedding and similarity calculation program using Sentence-BERT to evaluate relationships between document summaries and full texts.
  </div>
</div>

Grants and Scholarships
======

<div class="cv-entry">
  <div class="cv-date">2026.04 - present</div>
  <div class="cv-entry-body">
    <strong>YNU-BOOST student</strong>, Yokohama National University <span class="cv-subtext">(expected through 2029.03)</span><br>
    <span class="cv-subtext">多様なAIの共創により社会課題解決に挑む次世代AI人材育成プロジェクト</span>
  </div>
</div>

<div class="cv-entry">
  <div class="cv-date">2025.08.22 - present</div>
  <div class="cv-entry-body">
    <strong>ROSE Program student</strong>, Yokohama National University <span class="cv-subtext">(expected through 2029.03)</span><br>
    <span class="cv-subtext">ROSE（Research Opportunities for Students Excellence）プログラム</span>
  </div>
</div>

<div class="cv-entry">
  <div class="cv-date">2025.04 - 2026.03</div>
  <div class="cv-entry-body">
    <strong>Rotary Yoneyama Memorial Scholarship for master's students</strong>, Rotary Yoneyama Memorial Foundation<br>
    <span class="cv-subtext">ロータリー米山記念奨学生（修士）, 公益財団法人ロータリー米山記念奨学会</span>
  </div>
</div>

<div class="cv-entry">
  <div class="cv-date">2016.10 - 2021.03</div>
  <div class="cv-entry-body">
    <strong>Japan-Korea Joint Government Scholarship Program for the Students in Science and Engineering Departments</strong><br>
    <span class="cv-subtext">日韓共同理工系学部留学生</span>
  </div>
</div>

Additional Experience
======

<div class="cv-entry cv-entry-compact">
  <div class="cv-date">2021.07 - 2023.01</div>
  <div class="cv-entry-body">
    Republic of Korea Army, compulsory military service.
  </div>
</div>
