---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# Education

- Ph.D in Operations Research, UIUC, Ongoing
- M.S. in Operations Research, UIUC, 2022
- B.Tech. in Production and Industrial Engineering, IIT Delhi, 2018

# Publications

  <ul class="numbered-list" style="line-height: 0.5;">
  {% assign sorted_publications = site.publications | sort: 'date' | reverse %}
  {% for post in sorted_publications %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>

<h1 style="margin-top: 2em;">Professional Experience</h1>
  <ul class="unnumbered-list" style = "line-height: 0.5">
  {% assign sorted_experience = site.experience | sort: 'date' | reverse %}
  {% for post in sorted_experience %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>

<h1 style="margin-top: 2em;">Teaching/Research experience</h1>

- **Teaching Assistant**, UIUC (Fall 2020 - Ongoing)

  - Featured in the list of teachers ranked **Excellent** by students ([Fall 22](https://citl.illinois.edu/docs/default-source/teachers-ranked-as-excellent/tre-2022-fall.pdf), [Spring 23](https://citl.illinois.edu/docs/default-source/teachers-ranked-as-excellent/tre-2023-spring.pdf))
  - Graduate Courses: \
    Big Graphs and Social Networks ([IE533](https://courses.illinois.edu/schedule/2023/spring/IE/533))
  - Undergraduate Courses: \
    Facilities Layout and Planning ([IE360](https://courses.illinois.edu/schedule/2023/fall/IE/360)) \
    Analysis of Data ([IE300](https://courses.illinois.edu/schedule/2023/spring/IE/300)) \
    Production Planning and Control ([IE361](https://courses.illinois.edu/schedule/2023/spring/IE/361)) \
    Engineering Graphics and Design ([SE101](https://courses.illinois.edu/schedule/2023/spring/SE/101))

- **Research Assistant**, UIUC (Summer 2021 - Fall 2021)
  - IBM-ILLINOIS Center for Cognitive Computing Systems Research

<h1 style="margin-top: 2em;">Skills</h1>

- Areas
  - High-performance computing
  - Optimization
- Programming
  - C++, CUDA, Python, Java
- Tools
  - Optimization packages - Gurobi, AMPL, NetworkX, CVX
  - Data Analytics - SQL, scikit-learn,
  - Parallel Programming - CUB, METIS, Nsight Compute, OpenMP

<h1 style="margin-top: 2em;">Leadership</h1>

- Graduate Mentor, UIUC
- Empowerment Team Leader, Schlumberger
- Undergraduate Secretary, Academic Interaction Council IIT Delhi
- Publicity Coordinator, Literati IIT Delhi
