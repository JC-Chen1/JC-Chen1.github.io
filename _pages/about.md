---
permalink: /
title: ""
# excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently an undergrad in School of Computer Science and Technology, South China University of Technology. I am honored to be advised by [Prof. Yue-Jiao Gong](https://scholar.google.com/citations?user=Mi0Zu3IAAAAJ), and fortunate to work closely with [Zeyuan Ma](https://scholar.google.com/citations?user=Jcy8wPgAAAAJ&hl=en) and Hongshu Guo. We co-founded [GMC-DRL](https://gmc-drl.github.io/) research team aiming to make further exploration in Meta-Black-Box optimization.

I was an [SURF](https://www.sfp.caltech.edu/undergraduate-research/programs/surf) fellow in [Computing + Mathematical Sciences (CMS)](https://www.cms.caltech.edu/) Department at Caltech, where I am honored to be advised by [Prof. Yisong Yue](http://www.yisongyue.com/) and [Dr. Kaiyu Yang](https://yangky11.github.io/) and work on AI4Math research project.

My research interest includes two main directions.
- **Meta-Black-Box optimization** (Decision making process under uncertainty). Traditional black box optimization methods replies on intensive labour tuning to achieve required performance especially when applying to new tasks. Meta-Black-Box optimization is generally to mitigates the labour-intensive development in traditional black-box optimization algorithms through meta-learning. (e.g. leverage learning-based methods to automatically deside the most suitable configuration of some black-box optimization algorithms.) The decision making process in Meta-Black-Box optimization is under uncertainty due to the intrinsic randomness in black-box optimization.
- **Formal Theorem Proving** (Decision making process under certainty). Compared to informal one, formal theorem proving usually use proof assistants such as Coq, Isabelle, and Lean. The correctness of formal proofs can be conveniently verified by these proof assitants. Thereforce, decision making process in formal theorem proving allows no mistakes to reach the goal.


# 🔥 News
- *2024.09*: &nbsp;🎉🎉 Hello World!
- *2024.05*: &nbsp;🎉🎉 SYMBOL will be presented in ICLR 2024 as a poster!
- *2023.12*: &nbsp;🎉🎉 MetaBox will be presented in Neurips 2023 as the oral presentation!

# 📝 Publications 

<!-- MetaBox -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/overview-metabox.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MetaBox: A Benchmark Platform for Meta-Black-Box Optimization with Reinforcement Learning](https://neurips.cc/virtual/2023/poster/73497)

Zeyuan Ma, Hongshu Guo, **Jiacheng Chen**, Zhenrui Li, Guojun Peng, Yue-Jiao Gong, Yining Ma, and Zhiguang Cao.



[**Project**](https://github.com/GMC-DRL/MetaBox) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We released a benchmark platform for Meta-Black-Box Optimization named MetaBox. We integrate three different testsuits, about 20 baselines including traditional black-box methods and Meta-Black-Box methods, and new evaluation metrics tailored for Meta-Black-Box optimization. The codebase can be found here. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024</div><img src='images/overview-symbol.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SYMBOL: Generating Flexible Black-Box Optimizers through Symbolic Equation Learning](https://iclr.cc/virtual/2024/poster/17539)

**Jiacheng Chen**\*, Zeyuan Ma\*, Hongshu Guo, Yining Ma, Jie Zhang, Yue-Jiao Gong.

[**Project**](https://github.com/GMC-DRL/Symbol) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Unlike previous methods incrementally auto-configuring some existing black-box algortithms, SYMBOL directly generate stepwise update rule in the form of symbolic eqution to achieve more flexible and interpretable optimization behaviour.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">GECCO 2024</div><img src='images/overview-gleet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Auto-configuring Exploration-Exploitation Tradeoff in Evolutionary Computation via Deep Reinforcement Learning](https://arxiv.org/abs/2404.08239)

Zeyuan Ma\*, **Jiacheng Chen**\*, Hongshu Guo, Yining Ma, Yue-Jiao Gong.

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- We explore about how to make a trade-off between exploration and exploitation in Black-Box optimization through learn-based method. In this work, we carefully designed a framework which is based on transfromer-based model and leverage exploration-exploitation related feature tailored for black-box optimization scenario to resolve this problem.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/overview-neurela.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Neural Exploratory Landscape Analysis](https://www.arxiv.org/abs/2408.10672)

Zeyuan Ma, **Jiacheng Chen**, Hongshu Guo, Yue-Jiao Gong.

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- We developed an Neural-Network based lanscape analyser to replace the feature-extracting parts in Meta-Black-Box works which is usually manually designed. To ensure the generalization ability of the NeurELA, we let it operate in Multi-task setting and use neuroevolution to train it.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/overview-llamoco.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LLaMoCo: Instruction Tuning of Large Language Models for Optimization Code Generation](https://arxiv.org/abs/2403.01131)

Zeyuan Ma, Hongshu Guo, **Jiacheng Chen**, Guojun Peng, Zhiguang Cao, Yining Ma, Yue-Jiao Gong.

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- We propose to fine-tune language model to generate executable code that can be used for optimization tasks. We proposed a dataset that containing diversed optimization problems and corresponding algorithm in this paper, also leverage some tricks during training process and finally provided a fine-tuned LM for optimization tasks.

</div>
</div>

- [Deep Reinforcement Learning for Dynamic Algorithm Selection: A Proof-of-Principle Study on Differential Evolution](https://arxiv.org/abs/2403.02131), Hongshu Guo, Yining Ma, Zeyuan Ma, **Jiacheng Chen**, Xinglin Zhang, Zhiguang Cao, Jun Zhang, Yue-Jiao Gong, **GECCO 2024**

# 🎖 Honors and Awards
- *2024*, Caltech SURF Award.
- *2021 - 2022*, China National Scholarship. 

# 📖 Educations
- *2021.09 - now*, School of Computer Science and Technology, South China University of Technology.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Research Experience
- *2024.06 - 2024.08*, SURF, Caltech.
- *2022-03 - 2023.03*, SRP, SCUT.