## Louis Yiven Zhu

[![Website](https://img.shields.io/badge/Website-4E8A7B?style=flat-square&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIj48Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSI5Ii8+PGVsbGlwc2UgY3g9IjEyIiBjeT0iMTIiIHJ4PSI0IiByeT0iOSIvPjxwYXRoIGQ9Ik0zIDEyaDE4TTQuNSA2LjVoMTVNNC41IDE3LjVoMTUiLz48L3N2Zz4=)](https://louisyzhu.github.io/)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=flat-square&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=XCeO1nIAAAAJ&hl=en)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0009-0001-5579-0340)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square)](https://www.linkedin.com/in/yiven-z/)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=white)](https://huggingface.co/louisyzhu)

Hi, I'm [Louis](https://louisyzhu.github.io/), an MSc candidate at the Oxford Internet Institute
working on the science of AI evaluation.

Benchmarks are the exams AI models sit. I study what those scores measure and when they justify
predictions about performance beyond the test, drawing on psychometrics (the statistics of human
testing), statistical modelling and economics. The next question is whether evaluation results
predict how systems perform once deployed, particularly in interactive and agentic settings,
ahead of doctoral study from 2027.

The work puts four questions to any evaluation.

1. Can the score be trusted?
2. What does the score measure?
3. What does the score predict outside the evaluation?
4. When should a decision rely on it?

Five manuscripts from this work are under review at NeurIPS 2026 workshops, where I also serve as
an invited reviewer, and the flagship paper is under review at ICLR 2027. This GitHub holds the
research code behind them, and benchprobe, the library that re-derives their published numbers
from pinned data. Each repository states its reproduction tier, which quantities are recomputed
from source and which are regenerated from archived outputs.

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
| **[One Capability or Many?](https://github.com/louisyzhu/frontier-ai-economic-validity)**<br>Structural and predictive tests of benchmark validity disagree about economic benchmarks for frontier AI. Factor analysis and leave-one-benchmark-out prediction over a hash-pinned snapshot of 421 model configurations (103 in the economic-dense predictive subset). No distinct economic factor, yet modest but reliable incremental prediction, pooled ΔMSE 0.037 with a 95% interval of 0.019 to 0.055. Hypotheses pre-specified, analysis plan deposited retrospectively. Under review at ICLR 2027. | `Python` `EFA` `nested CV`<br>`pre-specified` |
| **[Three Ways CTT Misleads for LLM Judges](https://github.com/louisyzhu/llm-judge-reliability)**<br>Do the standard reliability statistics still answer the right question when the rater is a language model? A 210-item judge bank, reliability estimators, simulation studies and figure scripts. Quantities measured on the bank recompute exactly. Simulations are statistically reproduced from disclosed seeds. Figures regenerate from the archived grid. | `Python` `psychometrics`<br>`MIT` + `CC BY 4.0` |
| **[Frontier Safety Framework Corpus](https://github.com/louisyzhu/frontier-safety-framework-corpus)**<br>When a frontier AI developer revises its safety framework, how much of the change can a reader identify from the developer's own account of it? A versioned, hash-pinned corpus of 52 documents and 19 labelled version pairs, each with the provider's revision account, plus the coding behind the silent revision rate. The corpus verifies against its manifest by SHA-256. Statistics recompute from the released coding sheet, which is itself an archived output. | `Python` `content analysis`<br>`hash-pinned` `MIT` + `CC BY 4.0` |
| **[A Parliament Language Model](https://github.com/louisyzhu/hansard-char-lm)**<br>A 273k-parameter GRU implemented from scratch in PyTorch on 2.1M characters of Hansard, under a hard parameter budget and a no-attention rule, with controlled experiments on context length and capacity. A token-matched arm and a position-wise evaluation cut the headline context effect from 0.398 to 0.041. | `PyTorch` `deep learning`<br>`from scratch` |
| **[Automation Exposure and the UK Labour Market](https://github.com/louisyzhu/ai-risk-uk-wage-panel)**<br>How employment, pay and hours moved in more automatable occupations after 2016. An occupation-year panel joining ONS automation-risk scores to seven ASHE releases on a single SOC 2010 classification, 366 four-digit occupations, 2014 to 2020, with two-way fixed effects. Replication materials for the revised working paper, which withdraws the earlier reading and lists every withdrawn claim. The December 2025 panel is kept at a tag so the rebuild is checkable cell for cell. | `Stata` `panel data`<br>`two-way FE` `descriptive` |
| **[benchprobe](https://github.com/louisyzhu/benchprobe)**<br>A Python psychometrics library for AI benchmark scores. Reliability and grader agreement, factor structure controlled for release date, leave-one-benchmark-out predictive validity, and item-response scaling with anchor linking, on any model × benchmark matrix. Every estimator is validated by reproducing the published numbers of three studies from hash-pinned data, with 44 acceptance tests and a per-number reproducibility ledger. Building it surfaced three corrections to my own published archives, all documented. v0.1.0, [DOI](https://doi.org/10.5281/zenodo.22705351). | `Python` `psychometrics`<br>`168 tests` `MIT` |

Also worth a look. [Agent-based labour market](https://github.com/louisyzhu/abm-labor-market-automation) ·
[double ML](https://github.com/louisyzhu/double-ml-causal-inference) ·
[ABM-ACE](https://github.com/louisyzhu/abm-ace) ·
[insurance demand](https://github.com/louisyzhu/term-life-insurance-demand) ·
[Marshall Investment Fund site](https://github.com/louisyzhu/MIF-Site)

### Writing

**Published and accepted**

- **Neural Evidence and Behavioural Welfare Economics.** When can neuroeconomics inform policy? UCL Journal of Economics, accepted and in production. [doi 10.14324/111.444.2755-0877.2257](https://doi.org/10.14324/111.444.2755-0877.2257), where the revised article is forthcoming.
- **From Advisor to Voting Teammate.** Workshop paper, [Workshop on Human-Agent Collaboration at CHI 2026](https://chi26workshop-human-agent-collaboration.hailab.io/assets/papers/36%20-%20From%20Advisor%20to%20Voting%20Teammate%20Institutional%20Authority%20and%20Information%20Structures%20of%20AI%20Agents%20in%20Bounded-Rational%20Human%20Groups.pdf). An agent-based simulation, co-authored.

**Preprints and submitted manuscripts**

- **One Capability or Many? Structural and Predictive Tests of Benchmark Validity Disagree About Economic Benchmarks for Frontier AI.** Preprint, [arXiv 2608.29420](https://arxiv.org/abs/2608.29420), v2 forthcoming. Under review at ICLR 2027, and the workshop version at the NeurIPS 2026 Trust-AI-Eval Workshop. [analysis plan, deposited retrospectively](https://doi.org/10.17605/OSF.IO/VD34J) · [code](https://github.com/louisyzhu/frontier-ai-economic-validity)
- **Three Ways Classical Test Theory Misleads for LLM Judges.** Under review, NeurIPS 2026 JUDGe Workshop. Full version in preparation for NeurIPS 2027 Evaluations and Datasets. [paper](https://drive.google.com/file/d/1yRjvbQC1EorzLK95utH4GoHfASW6_1i2/view?usp=sharing) · [code and data](https://github.com/louisyzhu/llm-judge-reliability)
- **The Price of Intelligence.** A quality-adjusted price index for AI services. Preprint, [arXiv 2608.29843](https://arxiv.org/abs/2608.29843). Under review, NeurIPS 2026 EconML Workshop. Full version in preparation for FAccT 2027. [pre-registered validity audit](https://doi.org/10.17605/OSF.IO/5UQJ2) · [dataset](https://doi.org/10.5281/zenodo.22177190)
- **A Score Should Travel With Its Repair History.** Position paper, [SocArXiv preprint](https://doi.org/10.31235/osf.io/7bg8r_v1). Under review at two NeurIPS 2026 workshops, [AI for Meta-Science](https://ai4metascience.org/) and [AI & Science](https://aiscik.github.io/). Full version in preparation for the ICML 2027 Position Paper Track.
- **Silent Revision.** Measuring undisclosed change in the safety frameworks of frontier AI developers. Preprint, [arXiv 2609.08789](https://arxiv.org/abs/2609.08789). Under review, NeurIPS 2026 AISciK Workshop. In preparation for FAccT 2027. [corpus](https://doi.org/10.5281/zenodo.22670700) · [code and coding](https://github.com/louisyzhu/frontier-safety-framework-corpus)
- **Automation Exposure and the UK Labour Market.** Employment, pay and the wage floor, 2014 to 2020. SSRN working paper, v2, [doi 10.2139/ssrn.5736503](https://doi.org/10.2139/ssrn.5736503). [code](https://github.com/louisyzhu/ai-risk-uk-wage-panel)

**In progress**

- **The Science of Evaluations.** EvalEval Coalition, core contributor on validity and evidentiary standards. In preparation for TMLR.
- **Who Makes the Future of Work? Measurement, Hidden Labour and the Evidence on AI.** With Joanna Octavia. Review article funded by the UCL MAPS Summer Research Internship scheme. First draft complete, for submission to the International Labour Review.
- **The Unassembled Validity Argument.** How harness-dependent instability in MMLU propagates into the leaderboards and capability claims built on it. BSc dissertation, STS Best Dissertation Prize. Manuscript in preparation. Invited talk, UCL Centre for Responsible Innovation.

### Service and collaborations

Invited reviewer, NeurIPS 2026 [Trust-AI-Eval](https://tai-eval.github.io/), [EconML](https://econml26-workshop.github.io/) and [JUDGe](https://judge2026.github.io/) workshops.

Core contributor, [EvalEval Coalition](https://evalevalai.com). The Science of Evaluations paper, on validity and evidentiary standards, and Every Agent Ever, the coalition's shared schema for reporting, storing and analysing agent evaluation runs, extending the Every Eval Ever reporting standard.

Research contributor, [ETH Zurich Center for Law & Economics](https://lawecon.ethz.ch/).
