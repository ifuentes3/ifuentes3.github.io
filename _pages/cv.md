---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* MBA, MIT Sloan School of Management
* Master's degree in Risk Management, Safety, Prevention, and Ergonomics, Universitat Politecnica de Catalunya
* Degree in Industrial Engineering and Operations Research, Universitat Politecnica de Catalunya

Work experience
======
* Executive Director, MIT Jameel Clinic
  * Leads operational and strategic work for MIT's center for AI and healthcare.
  * Supports interdisciplinary research across machine learning, biology, chemistry, and clinical sciences.
  * Works with hospital, industry, academic, and policy partners to translate AI research into practice.
  * Convenes and organizes education programs in AI and health with MIT Sloan Executive Education and MIT Professional Education.

* Director, MIT Jameel Clinic

* Chief Operating Officer, MIT Quest for Intelligence

* Prior leadership roles in strategy, risk management, and change management across Generali Group, General Electric, and Santander.
  
Skills
======
* AI and health strategy
* Clinical translation
* Digital health transformation
* Executive and professional education
* Innovation and entrepreneurship
* Risk management and governance
* Research operations
* Cross-sector partnership development

Publications
======
  <ul>{% assign featured_publications = site.publications | where: "featured", true %}
  {% for post in featured_publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
  {% for post in site.publications reversed %}
    {% unless post.featured %}
      {% unless post.list_last %}
        {% include archive-single-cv.html %}
      {% endunless %}
    {% endunless %}
  {% endfor %}
  {% assign last_publications = site.publications | where: "list_last", true %}
  {% for post in last_publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Acknowledged contributor, "Deciphering Undersegmented Ancient Scripts Using Phonetic Prior," TACL 2021; the work on computational decipherment of ancient scripts, including Iberian, was recognized with the UNESCO/Netexplo Award in 2021
* Convener and organizer, Transforming Healthcare with AI programming with MIT Sloan Executive Education
* Convener and organizer, MIT Sloan Executive Education online programs delivered with GetSmarter, including Artificial Intelligence in Health Care and Artificial Intelligence in Pharma and Biotech
* Convener and organizer, MIT Professional Education June machine learning sequence, including Foundations earlier in the week and Advanced later in the week, with Regina Barzilay, Tommi Jaakkola, and colleagues
* Member, World Economic Forum Digital Health Transformation Initiative, AI Strategic Advisory Group
* Advisor, World Economic Forum on Digital Healthcare Transformation
* Co-chair and board member, BSS Finance and Compensation Committee
* Member, DCRO Cyber Risk Governance Council
