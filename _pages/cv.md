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
* Master's Degree MBA, MIT Sloan School of Management
  * Sloan Fellows Program in Innovation and Global Leadership
* Executive degree, IMD Lausanne
* Master's degree in Risk Management, Safety, Prevention, and Ergonomics, UPC
* Master's degree in Industrial Engineering and Operations Research, UPC

Work experience
======
* Executive Director, MIT Jameel Clinic
  * Leads operational and strategic work for MIT's center for AI and healthcare.
  * Supports interdisciplinary research across machine learning, biology, chemistry, and clinical sciences.
  * Works with hospital, government, industry, academic, philanthropic, investor, and policy partners to translate AI research into practice.
  * Supports government partnership work, including engagement with ARPA-H and the Department of the Interior on the Aurora project.
  * Supports fundraising, donor and foundation engagement, and external partnerships with industry, venture capital groups, and investors.
  * Convenes and organizes education programs in AI and health with MIT Sloan Executive Education and MIT Professional Education.
  * Advances public-service-oriented work using technology, finance, education, and institutional partnerships to broaden access and impact.

* Director, MIT Jameel Clinic

* Chief Operating Officer, MIT Quest for Intelligence

* Prior leadership roles in strategy, risk management, and change management across Generali Group, General Electric, and Santander.
  
Skills
======
* AI and health strategy
* Clinical translation
* Digital health transformation
* Government partnerships
* Fundraising and philanthropic partnerships
* Industry, venture capital, and investor engagement
* Public service and mission-driven institution building
* Finance and technology for democratizing access
* Community-centered leadership
* Executive and professional education
* Youth STEM mentorship
* Innovation and entrepreneurship
* Risk management and governance
* Research operations
* Cross-sector partnership development

Languages
======
* Spanish: native or bilingual proficiency
* French: native or bilingual proficiency
* English: full professional proficiency
* Italian: professional working proficiency

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
* More than 10 years of public service with the Red Cross
* Educator with early teaching experience beginning as a teaching assistant at 18
* Acknowledged contributor, "Deciphering Undersegmented Ancient Scripts Using Phonetic Prior," TACL 2021; the work on computational decipherment of ancient scripts, including Iberian, was recognized with the UNESCO/Netexplo Award in 2021
* Convener and organizer, Transforming Healthcare with AI programming with MIT Sloan Executive Education
* Convener and organizer, MIT Sloan Executive Education online programs delivered with GetSmarter, including Artificial Intelligence in Health Care and Artificial Intelligence in Pharma and Biotech
* Convener and organizer, MIT Professional Education June machine learning sequence, including Foundations and Advanced, with Regina Barzilay, Tommi Jaakkola, and colleagues
* Organizer, high school summer programming for students exploring AI, health, and research
* Mentor to young and curious minds pursuing AI, health, and research projects
* Founding organizer, yearly MIT-MGB AI Cures series
* Founding organizer, MoML @ MIT molecular machine learning conference
* Government partnership work with ARPA-H and the Department of the Interior on the Aurora project
* Partnerships and fundraising work with foundations, donors, philanthropists, industry partners, venture capital groups, and investors
* Member, World Economic Forum Digital Health Transformation Initiative, AI Strategic Advisory Group
* Advisor, World Economic Forum on Digital Healthcare Transformation
* Co-chair and board member, BSS Finance and Compensation Committee, MIT Club of Boston
* Volunteer, MIT Alumni Association
* Member, DCRO Cyber Risk Governance Council, The Directors and Chief Risk Officers Group
