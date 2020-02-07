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
* __Ph.D.__ in Civil Engineering, York University, 2023 (expected)
* __M.A.Sc.__ in Civil Engineering, York University, 2019
* __B.Eng.-C.__ in Water Resources Engineering, University of Guelph, 2017

Work experience
======
__City of Ottawa__
_Water Resources Engineering Intern (2016)_
* Updated citywide watercourse and infrastructure mapping based on hydrological simulations.
* Wrote Python scripts to automate repetitive tasks, conduct QA/QC, and clean datasets.
* Drafted detailed maps and retrieved spatial statistics upon request.
* Recorded pressure differentials between hydrants throughout the city’s water distribution system in order to calculate system losses.

__Dalhousie University Centre for Water Resources__
_Undergraduate Research Assistant (2015)_
* Assisted in the research of lead release within drinking water systems due to galvanic corrosion caused by partial lead service line replacement.
* Wrote literature reviews as requested by graduate students.
* Collected and analyzed water samples for trace metal concentrations on the order of 1 ng/L.

__XCG Consultants Ltd.__
_Environmental Science and Site Assessment Intern (2015)_
* Conducted phase one and two environmental site assessments, assisting in field work, data analysis, and completing written reports for clients.
* Created templates in Excel to interpret laboratory results and flag exceedances based on a variety of different standards for soil and water quality.
* Generated site maps in AutoCAD that identify monitoring locations, groundwater flow patterns, and potentially contaminated areas.

__Viqua, Trojan Technologies__
_Research and Development Engineering Intern (2014)_
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
  <ul>
  {% assign posts_sorted = site.publications | sort: "date" %}
    {% for post in posts_sorted %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>
  {% assign posts_sorted = site.talks | sort: "date" %}
  {% for post in posts_sorted %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>
  {% assign posts_sorted = site.teaching | sort: "date" %}
  {% for post in posts_sorted reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  