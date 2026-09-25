---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

Hi! I am Jiaqi Xiong (熊嘉琪). I am a Master student in [Social Data Science](https://www.oii.ox.ac.uk/people/profiles/jiaqi-xiong/) at the [Oxford Internet Institute](https://www.oii.ox.ac.uk/), University of Oxford, where I am fortunate to be supervised by [Prof. Xiaowen Dong](https://web.media.mit.edu/~xdong/) and [Prof. Michael Bronstein](https://www.cs.ox.ac.uk/people/michael.bronstein/), and to work closely with [Dr. Andy Huang](https://shenyanghuang.github.io/). Additionally, I work as a research assistant with [Prof. Enyan Dai](https://enyandai.github.io/) at the [Hong Kong University of Science and Technology (Guangzhou)](https://www.hkust-gz.edu.cn/). Before Oxford, I obtained my dual bachelor's degree in Artificial Intelligence from the University of Aberdeen (with first-class honours) and South China Normal University (SCNU) in 2025, where I completed my thesis under the supervision of [Dr. Chris Norval](http://cnorval.com/) and [Dr. Huan Yang](https://www.scholat.com/hyang8851.en). My research interests include <mark class="ox-mark" markdown="span">**self-evolving agents**</mark>, <mark class="ox-mark" markdown="span">**agentic scientific discovery**</mark>, and <mark class="ox-mark" markdown="span">**biological foundation models**</mark>.

{% include research-chips.html %}

{% include seeking-callout.html %}


# 🔥 News

{% capture news_content %}{% include news-timeline.html %}{% endcapture %}
{% include scroll-panel.html content=news_content kind="news" label="News" count=site.data.news.size unit="updates" %}


# 📖 Education

{% include education-cards.html %}


# 💼 Work & Research Experience

{% capture experience_content %}{% include experience-timeline.html %}{% endcapture %}
{% include scroll-panel.html content=experience_content kind="experience" label="Work and research experience" count=site.data.experience.size unit="experiences" %}


# 📝 Publications

{% capture publications_content %}{% include publications-list.html %}{% endcapture %}
{% include scroll-panel.html content=publications_content kind="publications" label="Publications" count=site.data.publications.publications.size unit="publications" %}


# 🎖 Honors and Awards

{% include honors-grid.html %}


# 🤝 Academic Service

- Reviewer, International Conference on Learning Representations (ICLR)
- Reviewer, [ICML 2026 Workshop on Graph Foundation Models: A New Era for Graph Machine Learning (GFM)](https://openreview.net/group?id=ICML.cc/2026/Workshop/GFM)


# 📬 Contact

<span class='anchor' id='-contact'></span>

Reach me at **[{{ site.author.email }}](mailto:{{ site.author.email }})**, or find me on [GitHub](https://github.com/{{ site.author.github }}) · [Google Scholar]({{ site.author.googlescholar }}) · [LinkedIn](https://www.linkedin.com/in/{{ site.author.linkedin }}).

Based in Oxford, UK. Open to research collaboration and chats.
