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
* **B.S. in Computer Science and Technology**, Northwestern Polytechnical University (NWPU), Xi'an, China, Sep. 2023 – Present
  * GPA: 3.95 / 4.1 &nbsp;&nbsp; Rank: 1 / 193
  * Core Courses: Calculus (95), Linear Algebra (97), Probability and Statistics (95), Advanced Programming (96), Discrete Mathematics (95), Data Structures (90), Digital Logic Design (94), Computer Organization and Architecture (91), Operating System (91), Fundamentals of Computer Systems (94)
  * Language: CET-4: 648, CET-6: 569

Research Experience
======
* **Multi-Modal Aerial-Ground Cross-View Place Recognition** (Aug. 2025 – Jan. 2026)
  * School of Computer Science, NWPU &nbsp; Advisor: Prof. Jiaqi Yang
  * Proposed a multi-modal fusion framework for aerial-ground cross-view place recognition, addressing viewpoint discrepancy and distribution shift between ground sensors and aerial maps
  * Designed a physical prior-guided MoE model that extracts physical statistics from raw inputs as routing conditions, enabling adaptive expert selection for varying environmental conditions
  * Introduced information bottleneck regularization to model cross-view alignment as an information distillation process, filtering ground-view-specific noise while preserving essential information shared with the aerial view

* **NAO Humanoid Robot: Penalty Kick & Sprint** (Apr. 2024 – Aug. 2025)
  * NWPU Soccer Robot Base
  * Developed motion control modules for penalty kick and sprint based on BHuman framework and NAOqi SDK, implementing gait planning, posture balancing, and real-time motion adjustment
  * Built OpenCV-based goal detection, ball localization, and distance estimation algorithms using HSV color filtering, contour detection, and perspective transformation; designed a finite state machine for the penalty kick decision pipeline

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Competitions
======
* 1st Prize, National Robotics Championship & International Humanoid Olympiad, 2024
* 2nd Prize, 27th China Robot & Artificial Intelligence Competition, 2024
* 2nd Prize, National English Competition for College Students (NECCS), 2025
* 3rd Prize, China Robot Competition & RoboCup China Open, 2025

Honors and Awards
======
* China National Scholarship (Twice)
* Outstanding Student & First-Class Scholarship, NWPU (Twice)
* Annual Academic Excellence Individual

Skills
======
* Programming: Python, C++
* Frameworks: PyTorch, OpenCV
* Languages: Chinese (Native), English (CET-4: 648, CET-6: 569)
