## Louis Yiven Zhu

[![Website](https://img.shields.io/badge/Website-4E8A7B?style=flat-square&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIj48Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSI5Ii8+PGVsbGlwc2UgY3g9IjEyIiBjeT0iMTIiIHJ4PSI0IiByeT0iOSIvPjxwYXRoIGQ9Ik0zIDEyaDE4TTQuNSA2LjVoMTVNNC41IDE3LjVoMTUiLz48L3N2Zz4=)](https://louisyzhu.github.io/)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=flat-square&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=XCeO1nIAAAAJ&hl=en)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0009-0001-5579-0340)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square)](https://www.linkedin.com/in/yiven-z/)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=white)](https://huggingface.co/louisyzhu)

Hi, I'm [Louis](https://louisyzhu.github.io/), an MSc student at the Oxford Internet Institute
working on the science of AI evaluation.

Benchmarks are the exams AI models sit. I study what those scores measure and when they predict
performance beyond the test, drawing on psychometrics (the statistics of human testing),
statistical modelling and economics. I am increasingly interested in what changes when the
system being evaluated uses tools or works with people.

The work sits under four questions.

1. Can the score be trusted?
2. What does the score measure?
3. What does the score predict outside the evaluation?
4. When should a decision rely on it?

Four manuscripts from this work are under review at NeurIPS 2026 workshops, where I also serve
as an invited reviewer. This GitHub holds the research code behind them, and benchprobe, the
library that re-derives their published numbers from pinned data. Each repository states its
reproduction tier, which quantities are recomputed from source and which are regenerated from
archived outputs.

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
| **[One Capability or Many?](https://github.com/louisyzhu/frontier-ai-economic-validity)**<br>Do frontier AI benchmarks measure one capability or several? Factor analysis and leave-one-benchmark-out prediction over a hash-pinned snapshot of 421 model configurations (103 in the economic-dense predictive subset). No distinct economic factor, yet modest but reliable incremental prediction, pooled ΔMSE 0.037 with a 95% interval of 0.019 to 0.055. Hypotheses pre-specified, analysis plan deposited retrospectively. | `Python` `EFA` `nested CV`<br>`pre-specified` |
| **[Three Ways CTT Misleads for LLM Judges](https://github.com/louisyzhu/llm-judge-reliability)**<br>Do the standard reliability statistics still answer the right question when the rater is a language model? A 210-item judge bank, reliability estimators, simulation studies and figure scripts. Quantities measured on the bank recompute exactly. Simulations are statistically reproduced from disclosed seeds. Figures regenerate from the archived grid. | `Python` `psychometrics`<br>`MIT` + `CC BY 4.0` |
| **[Frontier Safety Framework Corpus](https://github.com/louisyzhu/frontier-safety-framework-corpus)**<br>When a frontier AI developer revises its safety framework, how much of the change can a reader identify from the developer's own account of it? A versioned, hash-pinned corpus of 52 documents and 19 labelled version pairs, each with the provider's revision account, plus the coding behind the silent revision rate. The corpus verifies against its manifest by SHA-256. Statistics recompute from the released coding sheet, which is itself an archived output. | `Python` `content analysis`<br>`hash-pinned` `MIT` + `CC BY 4.0` |
| **[A Parliament Language Model](https://github.com/louisyzhu/hansard-char-lm)**<br>A 273k-parameter GRU implemented from scratch in PyTorch on 2.1M characters of Hansard, under a hard parameter budget and a no-attention rule, with controlled experiments on context length and capacity. A token-matched arm and a position-wise evaluation cut the headline context effect from 0.398 to 0.041. | `PyTorch` `deep learning`<br>`from scratch` |
| **[AI Risk and UK Wages](https://github.com/louisyzhu/ai-risk-uk-wage-panel)**<br>How real wages evolved in occupations scored as high automation risk after 2016. A descriptive occupation-year panel of ONS automation-risk scores and occupation-level ASHE wage data, 367 occupations, 2014 to 2023, with two-way fixed effects. | `Stata` `panel data`<br>`two-way FE` `descriptive` |
| **[benchprobe](https://github.com/louisyzhu/benchprobe)**<br>A Python psychometrics library for AI benchmark scores. Reliability and grader agreement, factor structure controlled for release date, leave-one-benchmark-out predictive validity, and item-response scaling with anchor linking, on any model × benchmark matrix. Every estimator is validated by reproducing the published numbers of three studies from hash-pinned data, with 44 acceptance tests and a per-number reproducibility ledger. Building it surfaced three corrections to my own published archives, all documented. v0.1.0, [DOI](https://doi.org/10.5281/zenodo.22705351). | `Python` `psychometrics`<br>`168 tests` `MIT` |

Also worth a look. [Agent-based labour market](https://github.com/louisyzhu/abm-labor-market-automation) ·
[double ML](https://github.com/louisyzhu/double-ml-causal-inference) ·
[ABM-ACE](https://github.com/louisyzhu/abm-ace) ·
[insurance demand](https://github.com/louisyzhu/term-life-insurance-demand) ·
[Marshall Investment Fund site](https://github.com/louisyzhu/MIF-Site)

### Writing

- **One Capability or Many?** Preprint, [arXiv 2608.29420](https://arxiv.org/abs/2608.29420). Under review, NeurIPS 2026 Trust-AI-Eval Workshop. [analysis plan, deposited retrospectively](https://doi.org/10.17605/OSF.IO/VD34J) · [code](https://github.com/louisyzhu/frontier-ai-economic-validity)
- **Three Ways Classical Test Theory Misleads for LLM Judges.** Under review, NeurIPS 2026 JUDGe Workshop. [code and data](https://github.com/louisyzhu/llm-judge-reliability)
- **The Price of Intelligence.** Preprint, [arXiv 2608.29843](https://arxiv.org/abs/2608.29843). Under review, NeurIPS 2026 EconML Workshop. [pre-registered validity audit](https://doi.org/10.17605/OSF.IO/5UQJ2) · [dataset](https://doi.org/10.5281/zenodo.22177190)
- **A Score Should Travel With Its Repair History.** Position paper, [SocArXiv preprint](https://doi.org/10.31235/osf.io/7bg8r_v1). Under review at two NeurIPS 2026 workshops, [AI for Meta-Science](https://ai4metascience.org/) and [AI & Science](https://aiscik.github.io/).
- **Silent Revision.** Measuring undisclosed change in the safety frameworks of frontier AI developers. Preprint, [arXiv 2609.08789](https://arxiv.org/abs/2609.08789). [corpus](https://doi.org/10.5281/zenodo.22670700) · [code and coding](https://github.com/louisyzhu/frontier-safety-framework-corpus)
- **From Advisor to Voting Teammate.** Workshop paper, [Workshop on Human-Agent Collaboration at CHI 2026](https://chi26workshop-human-agent-collaboration.hailab.io/assets/papers/36%20-%20From%20Advisor%20to%20Voting%20Teammate%20Institutional%20Authority%20and%20Information%20Structures%20of%20AI%20Agents%20in%20Bounded-Rational%20Human%20Groups.pdf). An agent-based simulation, co-authored.
- **When Should Neural Data Inform Welfare?** Minor revision invited, [UCL Journal of Economics](https://student-journals.ucl.ac.uk/UJE/). [arXiv](https://doi.org/10.48550/arXiv.2511.19548)
- **The Unassembled Validity Argument.** How harness-dependent instability in MMLU propagates into the leaderboards and capability claims built on it. BSc dissertation, STS Best Dissertation Prize. Manuscript in preparation.

### Service

Invited reviewer, NeurIPS 2026 [Trust-AI-Eval](https://tai-eval.github.io/), [EconML](https://econml26-workshop.github.io/) and [JUDGe](https://judge2026.github.io/) workshops.
Core contributor, [EvalEval Coalition](https://evalevalai.com) Science of Evaluations, on validity and evidentiary standards.
