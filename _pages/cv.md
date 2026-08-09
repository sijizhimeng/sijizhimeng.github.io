---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

[Download CV (PDF)](/files/Mengyu_JI_CV.pdf){: .btn .btn--primary }

Education
======

- **Ph.D. in Computer Science and Technology**, Zhejiang University, joint program with Westlake University, September 2020–December 2026 (expected)<br>
  Supervisor: Prof. Shiyu Zhao
- **M.Eng. in Aerospace Engineering**, University of Chinese Academy of Sciences, September 2017–June 2020<br>
  GPA: 3.61/4.00
- **B.Eng. in Aerospace Engineering**, Harbin Engineering University, September 2013–June 2017<br>
  GPA: 3.84/4.00

Exchange Experience
======

- **Technion – Israel Institute of Technology**, Haifa, Israel, August 2018<br>
  Participated in academic seminars on distributed space systems.
- **Harbin Institute of Technology**, Harbin, China, September 2015–July 2016<br>
  Completed coursework in flight mechanics and control systems.

Research Interests
======

- Robust flight control and physical interaction control for aerial manipulators
- Learning-based manipulation of unknown ground objects
- System-level implementation for robotic systems

Research Experience
======

- **Aerial Cart-Pulling: Inverse-Model-Based Interaction Control without Force Sensors** (2025–2026)
  - Developed a trajectory-based interaction control strategy using meta-learning to generate desired pulling forces for different payloads.
  - Mapped desired pulling force directly to the end-effector trajectory through an inverse model, eliminating reliance on real-time force measurements.
- **Motion Control for Underactuated Aerial Manipulators** (2023–2025)
  - Developed a partially decoupled motion-control framework using a variable-gain extended state observer and error-trajectory constraints.
  - Built a quadcopter with a six-degree-of-freedom robotic arm and validated it in aerial staff twirling, aerial mixology, and aerial cart-pulling tasks.
- **Tracking Control for Underactuated Aerial Manipulators** (2020–2023)
  - Designed a partially decoupled motion-control method based on the Recursive Newton–Euler approach for high-precision tracking of multi-degree-of-freedom aerial robotic systems.
- **Path Planning for Robot Arms** (2018–2020)
  - Proposed a Q-learning-based path-planning method for a three-degree-of-freedom fixed-base robotic arm.

Publications
======

<ul>{% assign publications = site.publications | sort: 'date' | reverse %}{% for post in publications %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Conference Presentations
======

<ul>{% assign talks = site.talks | sort: 'date' | reverse %}{% for post in talks %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

Teaching Experience
======

<ul>{% assign teaching = site.teaching | sort: 'date' | reverse %}{% for post in teaching %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Honors and Awards
======

- Research on aerial manipulators featured by national media, including CCTV-13 and [Bilibili](https://www.bilibili.com/video/BV1e92eBTE7a/), 2026
- Best Presentation Award, Three-Minute Presentation Competition, Westlake University, 2024
- Best Oral Presenter Award, 3rd International Conference on Robotics and Automation Sciences, 2019

Research Skills
======

- **Programming:** C/C++, Python, MATLAB/Simulink
- **Robotics and simulation:** ROS, Gazebo
- **Languages:** Chinese (native), English (fluent)
