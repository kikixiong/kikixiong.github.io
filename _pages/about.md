---
permalink: /
title: ""
excerpt: ""
redirect_from:
  - /about/
  - /about.html
---

<div class="ox-intro-layout" id="about-me">
  <aside class="ox-intro-layout__profile" aria-label="Profile">
    {% include author-profile.html %}
  </aside>
  <div class="ox-intro-layout__body">
    <section class="ox-intro" aria-labelledby="about-heading">
      <h1 class="ox-intro__title" id="about-heading">About me</h1>
      <p>I am a master's student in <a href="https://www.oii.ox.ac.uk/people/profiles/jiaqi-xiong/">Social Data Science</a> at the <a href="https://www.oii.ox.ac.uk/">Oxford Internet Institute</a>, University of Oxford. I am supervised by <a href="https://web.media.mit.edu/~xdong/">Prof. Xiaowen Dong</a> and <a href="https://www.cs.ox.ac.uk/people/michael.bronstein/">Prof. Michael Bronstein</a>, and work closely with <a href="https://shenyanghuang.github.io/">Dr. Andy Huang</a>. I also work as a research assistant with <a href="https://enyandai.github.io/">Prof. Enyan Dai</a> at the <a href="https://www.hkust-gz.edu.cn/">Hong Kong University of Science and Technology (Guangzhou)</a>.</p>
      <p>Before Oxford, I earned a dual bachelor's degree in Artificial Intelligence from the University of Aberdeen (with first-class honours) and South China Normal University in 2025. I completed my thesis under the supervision of <a href="http://cnorval.com/">Dr. Chris Norval</a> and <a href="https://www.scholat.com/hyang8851.en">Dr. Huan Yang</a>.</p>
      <p class="ox-intro__interests"><strong>Research interests:</strong> self-evolving agents, agentic scientific discovery, and biological foundation models.</p>
    </section>

    {% include seeking-callout.html %}
  </div>
</div>


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


# ✍️ Blogs
{: #blogs }

I write about machine learning foundations and research notes on my [blog](https://kikixiong.github.io/blogs/). Recent posts:

- [Transformer 编码器与解码器：一张结构图读懂信息流](https://kikixiong.github.io/blogs/2026/10/04/transformer/)
- [BERT：双向编码器、预训练与微调](https://kikixiong.github.io/blogs/2026/10/04/bert/)
- [图学习入门：从消息传递到 GCN 与 GAT](https://kikixiong.github.io/blogs/2026/10/04/graph-learning/)


# 📬 Contact

<span class='anchor' id='-contact'></span>

Reach me at **[{{ site.author.email }}](mailto:{{ site.author.email }})**, or find me on [GitHub](https://github.com/{{ site.author.github }}) · [Google Scholar]({{ site.author.googlescholar }}) · [LinkedIn](https://www.linkedin.com/in/{{ site.author.linkedin }}).

Based in Oxford, UK. Open to research collaboration and chats.
