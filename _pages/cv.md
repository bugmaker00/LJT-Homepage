---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

* **Ph.D. in Computer Science**, Hong Kong University of Science and Technology (HKUST), 2024 - Present
  * Supervisor: Professor Junxian He

* **B.Eng. in Computer Science**, Shanghai Jiao Tong University (SJTU), 2020 - 2024
  * Graduated with honors, received the Zhiyuan Honor Scholarship

## Work Experience

* **Research Intern**, MINIMAX, February 2025 - Present
  * Research intern focusing on large language models and reinforcement learning

* **Research Intern**, Tencent WXG, June 2024 - September 2024
  * Supervisor: Zifei Shan

* **Research Intern**, Shanghai AI Lab, June 2023 - December 2023
  * Supervisor: Prof. Yu Cheng

## Skills

* **Natural Language Processing**: LLM Reasoning, Reinforcement Learning, Hallucination Mitigation, Vision-Language Models
* **Machine Learning**: Deep Learning, Model Interpretability, Truthfulness
* **Programming**: Python, PyTorch, JAX

## Publications

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

## Talks

<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html  %}
{% endfor %}</ul>

## Teaching

<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
