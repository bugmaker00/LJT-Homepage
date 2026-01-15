---
permalink: /
title: "Junteng Liu"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% include toc %}

## About Me

I am a first-year PhD candidate at the [HKUST NLP Group](https://nlp.cs.ust.hk/), advised by [Professor Junxian He](https://scholar.google.com/citations?user=KQe2tDgAAAAJ&hl=en). I graduated from [Shanghai Jiao Tong University](https://www.sjtu.edu.cn/) (SJTU) in June 2024 with a B.Eng. degree in Computer Science.

My research focuses on natural language processing and machine learning, with specific interests in:

- LLM Reasoning and Reinforcement Learning
- Hallucination in Vision-Language Models (VLM)
- LLM Truthfulness and Interpretability

## Academic Background

- **Ph.D. in Computer Science** (2024-Present) at Hong Kong University of Science and Technology (HKUST)
- **B.Eng. in Computer Science** (2020-2024) at Shanghai Jiao Tong University (SJTU)

## Research Experience

- **Research Intern** at [MINIMAX](https://www.minimaxi.com/) (February 2025 - Present)
- **Research Intern** at Tencent WXG (June 2024 - September 2024)
- **Research Intern** at Shanghai AI Lab (June 2023 - December 2023)

## Publications

{% for pub in site.publications %}
<div class="publication">
  <h3>{{ pub.title }}</h3>
  <p><strong>{{ pub.year }}</strong> - {{ pub.venue }}</p>
  <p>{{ pub.author }}</p>
  {% if pub.link %}<p><a href="{{ pub.link }}">Paper</a></p>{% endif %}
  {% if pub.code %}<p><a href="{{ pub.code }}">Code</a></p>{% endif %}
</div>
{% endfor %}

## Skills

- **Programming**: Python, C++, Java
- **Frameworks**: PyTorch, TensorFlow, JAX
- **Tools**: Git, Docker, Linux

## Contact

- **Email**: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- **GitHub**: [Vicent0205](https://github.com/Vicent0205)
- **Google Scholar**: [Junteng Liu](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- **X/Twitter**: [@junteng88716710](https://twitter.com/junteng88716710)
