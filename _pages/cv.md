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
  Teaching/Research experience
  ======

* **Teaching Assistant**, UIUC (Fall 2020 - Ongoing)
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

<style>
  ul.numbered-list{
    list-style: decimal;
    margin-left: 1.5em;
    padding-left: 0;
  }

  ul.numbered-list li {
    margin-left: 1.5em;
    margin-top: -0.5em;
    margin-bottom: -0.5em;
  }
</style>

<style>
  ul.unnumbered-list{
    list-style: disc;
    margin-left: 1.5em;
    padding-left: 0;
  }

  ul.unnumbered-list li {
    margin-left: 1.5em;
    margin-top: -0.5em;
    margin-bottom: -1em;
  }
</style>

# Publications

  <ul class="numbered-list">
  {% assign sorted_publications = site.publications | sort: 'date' | reverse %}
  {% for post in sorted_publications %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>

<h1 style="margin-top: 2em;">Professional Experience</h1>
  <ul class="unnumbered-list">
  {% assign sorted_experience = site.experience | sort: 'date' | reverse %}
  {% for post in sorted_experience %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>

<h1 style="margin-top: 2em;">Skills</h1>

- Areas
  - High-performance computing
  - Optimization
- Programming
  - C++, CUDA, Python
- Tools
  - Optimization packages - Gurobi, AMPL, NetworkX, CVX
  - Data Analytics - SQL, scikit-learn,
  - GPU Programming - CUB, METIS, Nsight Compute

* **Teaching Assistant**, UIUC (Fall 2020 - Ongoing)

# Leadership

- Graduate Mentor, UIUC
- Empowerment Team Leader, Schlumberger
- Undergraduate Secretary, Academic Interaction Council IIT Delhi
- Publicity Coordinator, Literati IIT Delhi
