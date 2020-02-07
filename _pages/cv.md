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
* Ph.D. in Civil Engineering, York University, 2023 (expected)
* M.A.Sc. in Civil Engineering, York University, 2019
* B.Eng.-C. in Water Resources Engineering, University of Guelph, 2017

Work experience
======
* City of Ottawa
* Water Resources Engineering Intern (2016)
  * Updated citywide watercourse and infrastructure mapping based on hydrological simulations.
  * Wrote Python scripts to automate repetitive tasks, conduct QA/QC, and clean datasets.
  * Drafted detailed maps and retrieved spatial statistics upon request.
  * Recorded pressure differentials between hydrants throughout the city’s water distribution system in order to calculate system losses.

* Dalhousie University Centre for Water Resources
* Undergraduate Research Assistant (2015)
  * Assisted in the research of lead release within drinking water systems due to galvanic corrosion caused by partial lead service line replacement.
  * Wrote literature reviews as requested by graduate students.
  * Collected and analyzed water samples for trace metal concentrations on the order of 1 ng/L.

* XCG Consultants Ltd.
* Environmental Science and Site Assessment Intern (2015)
  * Conducted phase one and two environmental site assessments, assisting in field work, data analysis, and completing written reports for clients.
  * Created templates in Excel to interpret laboratory results and flag exceedances based on a variety of different standards for soil and water quality.
 * Generated site maps in AutoCAD that identify monitoring locations, groundwater flow patterns, and potentially contaminated areas.

* Viqua, Trojan Technologies
* Research and Development Engineering Intern (2014)
  * Standardized components across different UV disinfection products to reduce manufacturing costs.
  * Improved test lab productivity by restructuring the lab’s organizational system, developing standardized testing apparatuses, and coordinating lab use with other departments.
  * Carried out a wide variety product tests including failure analysis, electrical testing, thermal testing, UV sensor response, pressure testing, and accelerated life testing.
  
Skills
======
* Software Proficiency
  * ArcGIS
  * Microsoft Office
  * AutoCAD
  * SWMM5
* Programming Languages
  * MATLAB
  * Python
  * R
  * SQL
  * VBA
  * LaTeX

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>
  {% assign posts_sorted = site.teaching | sort: "date" %}
  {% for posts_sorted in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  