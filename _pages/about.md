---
permalink: /
title: "About"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div class="profile-home">
  <div class="profile-intro" markdown="1">
I'm a **Senior Research Engineer at Google DeepMind** in London, working on **Gemini pre-training and continual learning**.

My research spans language models, temporal graph learning, and the theoretical foundations of neural architectures. Recent work includes SkillSmith, which combines learned skills with textual knowledge, and research on the trade-off between information propagation speed and fidelity in computational graphs.
  </div>

  <nav class="profile-links" aria-label="Profile links">
    <a href="{{ '/cv/' | relative_url }}">CV <span aria-hidden="true">→</span></a>
    <a href="{{ site.author.googlescholar }}">Google Scholar <span aria-hidden="true">↗</span></a>
    <a href="mailto:{{ site.author.email }}">Email <span aria-hidden="true">↗</span></a>
  </nav>

  <section aria-labelledby="selected-publications">
    <h2 id="selected-publications">Selected publications</h2>
    {% assign selected_publications = site.publications | where_exp: "paper", "paper.selected_order != nil" | sort: "selected_order" %}
    {% for paper in selected_publications %}
      {% include publication-card.html paper=paper %}
    {% endfor %}
    <p class="all-publications"><a href="{{ '/publications/' | relative_url }}">View all publications <span aria-hidden="true">→</span></a></p>
  </section>

  <section class="profile-background" aria-labelledby="background" markdown="1">
## Background

I completed my MSc in Advanced Computer Science at the University of Oxford, where I worked with [Yarin Gal](https://www.cs.ox.ac.uk/people/yarin.gal/website/) in [OATML](https://oatml.cs.ox.ac.uk/) on language-model uncertainty and with [Michael Bronstein](https://www.cs.ox.ac.uk/people/michael.bronstein/) on temporal graph learning. Before that, I studied at the University of Cambridge, graduating **first in my cohort**. I've also held research appointments at Oxford, Cambridge, Mila, and EMBL-EBI, and previously worked in engineering at [XTX Markets](https://www.xtxmarkets.com/) and [Amazon Web Services](https://aws.amazon.com/).
  </section>
</div>
