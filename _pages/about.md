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

# Jiacheng Chen

Welcome!

I am an PhD student at the CSE department in The Chinese University of Hong Kong, where I am fortunate to be advised by [Prof. Weiyang Liu](https://wyliu.com/) and [Prof. Yu Cheng](https://ych133.github.io/). I also work closely with [Dr. Ganqu Cui](https://cgq15.github.io/) and [Prof. Ning Ding](https://www.stingning.cn/). I received barchelor degree from South China University of Technology, where I was fortunate to be advised by [Prof. Yue-Jiao Gong](https://scholar.google.com/citations?user=Mi0Zu3IAAAAJ). I was a visiting researcher at Caltech, where I was honored to be advised by [Prof. Yisong Yue](http://www.yisongyue.com/) and [Dr. Kaiyu Yang](https://yangky11.github.io/).

<!-- I was an [SURF](https://www.sfp.caltech.edu/undergraduate-research/programs/surf) fellow in [Computing + Mathematical Sciences (CMS)](https://www.cms.caltech.edu/) Department at Caltech, where I am honored to be advised by [Prof. Yisong Yue](http://www.yisongyue.com/) and [Dr. Kaiyu Yang](https://yangky11.github.io/) and work on AI4Math research project. -->

My research interests include，
- **Reasoning in NLP** 
- **Reinforcement Learning**


# 🔥 News
- *2025.05*: &nbsp;🎉🎉 Our paper [Entropy Mechanism of Reinforcement Learning for Large Language Model Reasoning](https://arxiv.org/pdf/2505.22617) has released!
- *2024.05*: &nbsp;🎉🎉 [SYMBOL](https://iclr.cc/virtual/2024/poster/17539) will be presented in ICLR 2024 as a poster!
- *2023.12*: &nbsp;🎉🎉 [MetaBox](https://neurips.cc/virtual/2023/poster/73497) will be presented in Neurips 2023 as the oral presentation!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/entropy-overview.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[The Entropy Mechanism of Reinforcement Learning for Reasoning Language Models](https://arxiv.org/pdf/2505.22617)

Ganqu Cui\*, Yuchen Zhang\*, **Jiacheng Chen***, Lifan Yuan, Zhi Wang, Yuxin Zuo, Haozhan Li, Yuchen Fan, Huayu Chen, Weize Chen, Zhiyuan Liu, Hao Peng, Lei Bai, Wanli Ouyang, Yu Cheng, Bowen Zhou, Ning Ding.

- We conducted empirical and theoretical analysis at “entropy collapse” phenomena, and proposed new way of entropy control.

</div>
</div>

<!-- RiR -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024 Workshop MATH-AI</div><img src='images/overview-rir.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reasoning in Reasoning: A Hierarchical Framework for Neural Theorem Proving](https://openreview.net/pdf?id=H5hePMXKht) (NeurIPS 2024 Workshop MATH-AI)

Ziyu Ye, **Jiacheng Chen**, Jonathan Light, Yifei Wang, Jiankai Sun, Mac Schwager, Philip Torr, Guohao Li, Yuxin Chen, Kaiyu Yang, Yisong Yue, Ziniu Hu.


</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024</div><img src='images/overview-symbol.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SYMBOL: Generating Flexible Black-Box Optimizers through Symbolic Equation Learning](https://iclr.cc/virtual/2024/poster/17539) (ICLR 2024)

**Jiacheng Chen**\*, Zeyuan Ma\*, Hongshu Guo, Yining Ma, Jie Zhang, Yue-Jiao Gong.

[**Project**](https://github.com/GMC-DRL/Symbol) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Unlike previous methods incrementally auto-configuring some existing black-box algortithms, SYMBOL directly generate stepwise update rule in the form of symbolic eqution to achieve more flexible and interpretable optimization behaviour.

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

<!-- MetaBox -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/overview-metabox.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MetaBox: A Benchmark Platform for Meta-Black-Box Optimization with Reinforcement Learning](https://neurips.cc/virtual/2023/poster/73497) (Neurips 2023 Oral)

Zeyuan Ma, Hongshu Guo, **Jiacheng Chen**, Zhenrui Li, Guojun Peng, Yue-Jiao Gong, Yining Ma, Zhiguang Cao.



[**Project**](https://github.com/GMC-DRL/MetaBox) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We released a benchmark platform for Meta-Black-Box Optimization named MetaBox. We integrate three different testsuits, about 20 baselines including traditional black-box methods and Meta-Black-Box methods, and new evaluation metrics tailored for Meta-Black-Box optimization. The codebase can be found here. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/overview-neurela.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Neural Exploratory Landscape Analysis](https://www.arxiv.org/abs/2408.10672) (ICLR 2025)

Zeyuan Ma, **Jiacheng Chen**, Hongshu Guo, Yue-Jiao Gong.

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- We developed an Neural-Network based lanscape analyser to replace the feature-extracting parts in Meta-Black-Box works which is usually manually designed. To ensure the generalization ability of the NeurELA, we let it operate in Multi-task setting and use neuroevolution to train it.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">GECCO 2024</div><img src='images/overview-gleet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Auto-configuring Exploration-Exploitation Tradeoff in Evolutionary Computation via Deep Reinforcement Learning](https://arxiv.org/abs/2404.08239) (GECCO 2024)

Zeyuan Ma\*, **Jiacheng Chen**\*, Hongshu Guo, Yining Ma, Yue-Jiao Gong.

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- We explore about how to make a trade-off between exploration and exploitation in Black-Box optimization through learn-based method. In this work, we carefully designed a framework which is based on transfromer-based model and leverage exploration-exploitation related feature tailored for black-box optimization scenario to resolve this problem.

</div>
</div>

- [ConfigX: Modular Configuration for Evolutionary Algorithms via Multitask Reinforcement Learning](https://arxiv.org/pdf/2412.07507), Hongshu Guo\*, Zeyuan Ma\*, **Jiacheng Chen**, Yining Ma,Zhiguang Cao, Xinglin Zhang, Yue-Jiao Gong, **AAAI 2025** (Oral)
- [Deep Reinforcement Learning for Dynamic Algorithm Selection: A Proof-of-Principle Study on Differential Evolution](https://arxiv.org/abs/2403.02131), Hongshu Guo, Yining Ma, Zeyuan Ma, **Jiacheng Chen**, Xinglin Zhang, Zhiguang Cao, Jun Zhang, Yue-Jiao Gong, **GECCO 2024**

# 🎖 Honors and Awards
- *2024*, Caltech Summer Undergraduate Research Fellowship (SURF).


# 📖 Educations
<!-- - *2021.09 - present*, School of Computer Science and Technology, South China University of Technology. -->

<div class='school-box'> 
<div class='school-box-text' markdown="1">
- *2025.10 - present*, PhD, Department of Computer Science and Engineering, The Chinese University of Hong Kong.
</div>
<div class='school-box-image'><div><img src='images/cuhk.jpg' alt="sym" width="100%"></div></div>
</div>

<div class='school-box'> 
<div class='school-box-text' markdown="1">
- *2021.09 - 2025.06*, B.E., School of Computer Science and Technology, South China University of Technology.
</div>
<div class='school-box-image'><div><img src='images/scut.jpg' alt="sym" width="100%"></div></div>
</div>
<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Research Experience

<div class='school-box'> 
<div class='school-box-text' markdown="1">
- *2024.06 - 2024.08*, SURF, Caltech.
  - *Thesis: AI for Math.*
  - *Advisor: [Prof. Yisong Yue](http://www.yisongyue.com/) and [Dr. Kaiyu Yang](https://yangky11.github.io/).*
</div>
<div class='school-box-image'><div><img src='images/caltech.png' alt="sym" width="100%"></div></div>
</div>

<div class='school-box'> 
<div class='school-box-text' markdown="1">
- *2022-03 - 2023.03*, SRP, SCUT.
  - *Thesis: Meta Black Box Optimization.*
  - *Advisor: [Prof. Yue-Jiao Gong](https://scholar.google.com/citations?user=Mi0Zu3IAAAAJ)*
</div>
<div class='school-box-image'><div><img src='images/scut.jpg' alt="sym" width="100%"></div></div>
</div>
