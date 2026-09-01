## Louis Yiven Zhu

[![Website](https://img.shields.io/badge/Website-4E8A7B?style=flat-square&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIj48Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSI5Ii8+PGVsbGlwc2UgY3g9IjEyIiBjeT0iMTIiIHJ4PSI0IiByeT0iOSIvPjxwYXRoIGQ9Ik0zIDEyaDE4TTQuNSA2LjVoMTVNNC41IDE3LjVoMTUiLz48L3N2Zz4=)](https://louisyzhu.github.io/)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=flat-square&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=XCeO1nIAAAAJ&hl=en)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0009-0001-5579-0340)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square)](https://www.linkedin.com/in/yiven-z/)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/datasets/louisyzhu/price-of-intelligence)

Hi, I'm [Louis](https://louisyzhu.github.io/), an MSc candidate at the Oxford Internet Institute
working on the science of AI evaluation.

Benchmarks are the exams AI models sit, and an exam is only useful if it is fair, consistent,
and testing the right thing. My research asks what a benchmark score is really evidence of,
applying the statistics of human testing (item response theory, factor analysis, argument-based
validity) to the exams we set for machines. Then it follows the scores downstream into what
they decide, which is prices, wages and rules.

Four papers from this work are under review at NeurIPS 2026 workshops, where I also serve as an
invited reviewer. Everything ships with its data. Hash-pinned snapshots, pre-registered analysis
plans, and reproduction bundles that regenerate every number and figure in the paper.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![Stata](https://img.shields.io/badge/Stata-1A5F7A?style=flat-square)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square)

### Featured

| Project | Stack |
|---|---|
| **[Three Ways CTT Misleads for LLM Judges](https://github.com/louisyzhu/llm-judge-reliability)**<br>Do the standard reliability statistics still mean what they seem to when the rater is a language model? A full reproduction bundle with a 210-item judge bank, estimators, sweeps and figures. Measured quantities reproduce bit-for-bit. | `Python` `psychometrics`<br>`MIT` + `CC BY 4.0` |
| **[One Capability or Many?](https://github.com/louisyzhu/frontier-ai-economic-validity)**<br>Do frontier AI benchmarks measure one capability or several? Pre-registered factor analysis over a hash-pinned snapshot of 421 model configurations, with leave-one-benchmark-out prediction. | `Python` `EFA` `nested CV`<br>`pre-registered` |
| **[A Parliament Language Model](https://github.com/louisyzhu/hansard-char-lm)**<br>A 273k-parameter GRU built from scratch on 2.1M characters of Hansard, under a hard budget and a no-attention rule. The perplexity is not the point. The controls are, cutting the headline effect from 0.398 to 0.041. | `PyTorch` `deep learning`<br>`from scratch` |
| **[AI Risk and UK Wages](https://github.com/louisyzhu/ai-risk-uk-wage-panel)**<br>Did occupations more exposed to automation see pay diverge after 2016? An occupation-year panel built from ONS automation-risk scores and ASHE microdata, 367 occupations, 2014 to 2023. | `Stata` `panel data`<br>`two-way FE` |

Also worth a look. [Agent-based labour market](https://github.com/louisyzhu/abm-labor-market-automation) ·
[double ML](https://github.com/louisyzhu/double-ml-causal-inference) ·
[ABM-ACE](https://github.com/louisyzhu/abm-ace) ·
[insurance demand](https://github.com/louisyzhu/term-life-insurance-demand) ·
[Marshall Investment Fund site](https://github.com/louisyzhu/MIF-Site)

`benchprobe`, a PyTorch package for psychometric analysis of benchmark score matrices, is planned for October 2026.

### Writing

- **One Capability or Many?** Under review, NeurIPS 2026 TAE Workshop. [arXiv](https://arxiv.org/abs/2608.29420) · [analysis plan](https://doi.org/10.17605/OSF.IO/VD34J) · [code](https://github.com/louisyzhu/frontier-ai-economic-validity)
- **Three Ways Classical Test Theory Misleads for LLM Judges.** Under review, NeurIPS 2026 JUDGe Workshop. [code and data](https://github.com/louisyzhu/llm-judge-reliability)
- **The Price of Intelligence.** Under review, NeurIPS 2026 EconML Workshop. [arXiv](https://arxiv.org/abs/2608.29843) · [pre-registration](https://doi.org/10.17605/OSF.IO/5UQJ2) · [dataset](https://doi.org/10.5281/zenodo.22177190)
- **A Score Should Travel With Its Repair History.** Under review at two NeurIPS 2026 workshops, [AI for Meta-Science](https://ai4metascience.org/) and [AI & Science](https://aiscik.github.io/). [preprint](https://doi.org/10.31235/osf.io/7bg8r_v1)
- **From Advisor to Voting Teammate.** [Workshop on Human-Agent Collaboration, ACM CHI 2026](https://chi26workshop-human-agent-collaboration.hailab.io/assets/papers/36%20-%20From%20Advisor%20to%20Voting%20Teammate%20Institutional%20Authority%20and%20Information%20Structures%20of%20AI%20Agents%20in%20Bounded-Rational%20Human%20Groups.pdf), co-author.
- **When Should Neural Data Inform Welfare?** Under review at the [UCL Journal of Economics](https://student-journals.ucl.ac.uk/UJE/) after an invited minor revision. [arXiv](https://doi.org/10.48550/arXiv.2511.19548)
- **The Unassembled Validity Argument.** BSc dissertation, STS Best Dissertation Prize.

### Service

Invited Reviewer, NeurIPS 2026, for [Trust-AI-Eval](https://tai-eval.github.io/) and [EconML](https://econml26-workshop.github.io/).
Core contributor, [EvalEval Coalition](https://evalevalai.com) (Hugging Face · Edinburgh · EleutherAI).
