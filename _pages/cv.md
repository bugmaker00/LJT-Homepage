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
* **Ph.D. in Computer Science**, Hong Kong University of Science and Technology (HKUST), 2024 – Present
  * HKUST NLP Group, supervised by Prof. Junxian He

* **B.Eng. in Computer Science**, Shanghai Jiao Tong University (SJTU), 2020 – 2024
  * GPA: Top 10% | Received Zhiyuan Honor Scholarship

Work experience
======
* **Research Intern**, MINIMAX, Feb. 2025 – Present
  * Working on LLM reasoning and reinforcement learning

* **Research Intern**, Tencent WXG, Jun. 2024 – Sep. 2024
  * Advisor: Zifei Shan
  * Focused on hallucination mitigation in vision-language models

* **Research Intern**, Shanghai AI Lab, Jun. 2023 – Dec. 2023
  * Advisor: Prof. Yu Cheng
  * Developed parameter-efficient module composition methods

Skills
======
* **Programming**: Python, PyTorch, TensorFlow, C/C++, Java
* **Deep Learning**: Large Language Models, Reinforcement Learning, Vision-Language Models
* **NLP**: Natural Language Understanding, Reasoning, Evaluation Benchmarks, Interpretability
* **Tools**: Git, Docker, Linux, AWS, GCP, Jupyter

Publications
======

<ul>{% for post in site.publications reversed %}
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
* HKUST NLP Group member (2024 – Present)
