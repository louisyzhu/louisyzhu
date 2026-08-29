## Louis Yiven Zhu

Measurement and validity in AI evaluation. MSc candidate at the **Oxford Internet Institute**,
University of Oxford (St Antony's College).

Hi, I'm [Louis](https://looloo-dot.github.io/). Evaluation results shape how AI systems are
priced, deployed and regulated — my research asks what licenses the inference from *score* to
*claim*. I apply psychometric methods, from item response theory to argument-based validity, to
test whether benchmarks and LLM-judge pipelines actually function as measurement instruments.
I also follow the numbers downstream, tracing how scores gain credibility in model reports and
governance documents, and using econometric methods to ask what measured capability is worth.

Mostly Python (PyTorch, scikit-learn, HuggingFace) and R, with Stata for panel work.

### Selected work

| Project | What it asks | Approach |
|---|---|---|
| **[One Capability or Many?](https://github.com/Looloo-dot/frontier-ai-economic-validity)** | Do frontier AI benchmarks measure one capability or many — and do "economic" benchmarks add anything over general model progress? | Pre-registered latent-variable study over a hash-pinned snapshot of 421 model configurations across twelve benchmarks. Exploratory factor analysis plus a leave-one-benchmark-out predictive test: a single factor explains 74.5% of common variance and is strongly associated with release date (R² = 0.505), and economic benchmarks carry only limited incremental validity over a general-capability index (pooled ΔMSE = 0.037). |
| **[A Parliament Language Model](https://github.com/Looloo-dot/hansard-char-lm)** | Where do you spend a fixed parameter budget when context and capacity compete for it? | A 273,939-parameter GRU written from scratch in PyTorch on 2.1M characters of Hansard, under a 500k-parameter cap and a no-attention rule. Perplexity 4.0 against a bigram's 11.5 — but the point is the controls: a token-matched arm and a position-wise evaluation take the headline effect from 0.398 to 0.041. |
| **[AI Risk and UK Wages](https://github.com/Looloo-dot/ai-risk-uk-wage-panel)** | Did occupations more exposed to automation see their pay diverge after 2016? | UK occupation-year panel, 2014–2023, 367 occupations, built from ONS automation-risk scores and ASHE microdata. Two-way fixed effects clustered by occupation. The risk-by-post-2016 interaction comes out positive and precise, which is the opposite of the naive prior and wants explaining. |
| **[Automation Workforce Simulation](https://github.com/Looloo-dot/abm-labor-market-automation)** | How do employment, wages and skill composition co-evolve under an automation shock? | Agent-based model in R: 2,000 heterogeneous workers, configurable shock and retraining dynamics. Fully seeded and reproducible. |
| **[Double Machine Learning](https://github.com/Looloo-dot/double-ml-causal-inference)** | Can ML nuisance estimators support causal inference without inheriting regularisation bias? | DML-PLIV with cross-fitting and the R-learner on simulated data with known ground truth, plus a policy-targeting evaluation. |
| **[ABM-ACE](https://github.com/Looloo-dot/abm-ace)** | How do adaptive agents, climate shocks and inequality interact under different policy regimes? | An agent-based research sandbox with a fully parameterised CLI, so every run is reproducible and auditable. |
| **[Term Life Insurance Demand](https://github.com/Looloo-dot/term-life-insurance-demand)** | Which household characteristics predict life-insurance coverage, and does regularisation beat transparent OLS? | Two-margin design on 2004 SCF data; Ridge and Lasso against an interpretable benchmark over 30 repeated splits. |
| **[Marshall Investment Fund](https://github.com/Looloo-dot/MIF-Site)** | — | Site for a student-managed long-only equity fund, [live on GitHub Pages](https://looloo-dot.github.io/MIF-Site/). Static HTML/CSS/JS, no build step. |

`benchprobe`, a PyTorch package for psychometric analysis of benchmark score matrices, is
planned for release in October 2026.

### Selected writing

- **Three Ways Classical Test Theory Misleads for LLM Judges** — under review, NeurIPS 2026 Workshop on Reliable Evaluation for Language Models (JUDGe).
- **The Unassembled Validity Argument: Constructing, Repairing and Circulating MMLU, 2020–2026** — BSc dissertation (STS Best Dissertation Prize). Six years of MMLU's construction, repair and circulation, and how harness-dependent score instability propagates into the capability claims and risk thresholds built on it.
- **A Score Should Travel With Its Repair History** — position paper, under review, NeurIPS 2026 Workshop on AI for Meta-Science.
- **The Price of Intelligence: A Quality-Adjusted Price Index for AI Inference** — under review, NeurIPS 2026 EconML Workshop. 87% of the price decline is invisible to matched-model methods.
- **From Advisor to Voting Teammate** — Workshop on Human-Agent Collaboration, [ACM CHI 2026](https://chi26workshop-human-agent-collaboration.hailab.io/assets/papers/36%20-%20From%20Advisor%20to%20Voting%20Teammate%20Institutional%20Authority%20and%20Information%20Structures%20of%20AI%20Agents%20in%20Bounded-Rational%20Human%20Groups.pdf) (co-author).
- **Automation Risk and Wage Dynamics in the United Kingdom** — SSRN working paper, [10.2139/ssrn.5736503](https://doi.org/10.2139/ssrn.5736503).
- **When Should Neural Data Inform Welfare?** — working paper, [arXiv:2511.19548](https://doi.org/10.48550/arXiv.2511.19548).

### Service

Invited Reviewer, [NeurIPS 2026 Trust-AI-Eval (TAE) Workshop](https://tai-eval.github.io/) —
*Can We Trust AI Evaluation?*

Core contributor to the [EvalEval Coalition](https://evalevalai.com) (Hugging Face · Edinburgh ·
EleutherAI), owning the validity sections of the coalition's *Science of Evaluations* paper.

### Currently

Frontier model evaluation at the Oxford Internet Institute, with a focus on whether capability
measurements hold up as economic indicators. Preparing for doctoral study from 2027.

### Elsewhere

[Website](https://looloo-dot.github.io/) ·
[Google Scholar](https://scholar.google.com/citations?user=XCeO1nIAAAAJ&hl=en) ·
[ORCID](https://orcid.org/0009-0001-5579-0340) ·
[LinkedIn](https://www.linkedin.com/in/yiven-z/)
