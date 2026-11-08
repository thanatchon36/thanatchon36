### Hi, I'm Thanatchon 👋

Senior Data Scientist at the **Bank of Thailand**, where I build production generative AI and multi-agent systems. Before that I was a lead data scientist and a software engineer. MSc Data Science, University of Glasgow.

Off the clock I write pre-registered, reproducible research papers on central banking, financial risk and AI-agent safety, each shipped with its code, data and an archived DOI, and I build small, focused open-source tools for people who work with LLMs, coding agents and CI.

#### 📄 Research papers

**🏦 Central banking & financial risk**

| Project | Paper | Read |
|---|---|---|
| [**shadow-dollars**](https://github.com/thanatchon36/shadow-dollars) | *Shadow Dollars: Stablecoin Rails, Scam Finance and the Limits of Detection in Thailand*. Public on-chain, sanctions and macro data show USDT on Tron is a distinct retail dollar rail (47% of covered USDT supply) and that chain-wide event studies cannot evaluate national crackdowns; four account-level detectors, from difference-in-bunching at the 50,000-baht threshold to direction-aware graph exposure, are validated on simulated mule accounts with a pre-registered plan for PDPA data; dataset on Hugging Face. | [Web](https://thanatchon36.github.io/shadow-dollars/paper/) · [PDF](https://github.com/thanatchon36/shadow-dollars/raw/main/paper/paper.pdf) · [DOI](https://doi.org/10.5281/zenodo.24050717) |
| [**finality-research**](https://github.com/thanatchon36/finality-research) | *False Confidence in the Tail: Finality, Extreme-Value Uncertainty, and Contagion in Banking-Sector Cyber Risk*. From 30-year records, standard intervals miss the true 1-in-1,000-year loss about 40% of the time, always on the low side, while profile likelihood restores most of the coverage; finality explains 67% of the attacker payoff gap between a bank core and a cross-chain bridge; illustrative parameters, [interactive instrument](https://thanatchon36.github.io/finality-research/instrument/), dataset on Hugging Face. | [Web](https://thanatchon36.github.io/finality-research/paper/) · [PDF](https://github.com/thanatchon36/finality-research/raw/main/paper/paper.pdf) · [DOI](https://doi.org/10.5281/zenodo.24050729) |
| [**demonetsim-th**](https://github.com/thanatchon36/demonetsim-th) | *Can Demonetization Defeat Grey Capital? Evidence, a Calibrated Agent-Based Model, and a Research Agenda for Retiring Thailand's 1,000-Baht Note*. An agent-based model calibrated to India's 2016 shock by ABC: an India-style move destroys or seizes a median 7.7% of illicit cash with about one sixth of India's liquidity disruption, most of it borne by vulnerable holders; statistics are approximate and parameters assumed; Thai version and dataset on Hugging Face. | [Web](https://thanatchon36.github.io/demonetsim-th/paper/) · [PDF](https://github.com/thanatchon36/demonetsim-th/raw/main/paper/pdf/paper_en.pdf) · [DOI](https://doi.org/10.5281/zenodo.24050061) |
| [**beyond99-banknote-detection**](https://github.com/thanatchon36/beyond99-banknote-detection) | *Beyond 99%: Open-Set Evaluation Reveals Silent Failures of Counterfeit Banknote Detectors, and the Case for One-Class Screening*. Tree ensembles that score above 99% on random splits catch only 51–61% of counterfeit families they have never seen at a 1% genuine-rejection budget, while a one-class autoencoder trained on genuine notes alone catches 99.98%; UCI Banknote Authentication data, dataset on Hugging Face. | [Web](https://thanatchon36.github.io/beyond99-banknote-detection/paper/) · [PDF](https://github.com/thanatchon36/beyond99-banknote-detection/raw/main/paper/paper.pdf) · [DOI](https://doi.org/10.5281/zenodo.24049790) |
| [**lockdowns-as-partial-holidays**](https://github.com/thanatchon36/lockdowns-as-partial-holidays) | *Lockdowns as Partial Holidays: Identifying Work-Stoppage Elasticities from Recurring Holidays and Transferring Them to Forecast Thailand's Monthly Exports through the COVID-19 Shock*. A Holiday-Equivalent Stoppage Index that turns lockdowns into a dose of the holiday effect, so an unseen lockdown needs no new parameter; in a 30-replication Monte Carlo study the error on 2020–2021 exports falls from 26.0% to 7.8% MAPE; exports are simulated, while the holiday, stringency and mobility inputs are real; Thai version and dataset on Hugging Face. | [Web](https://thanatchon36.github.io/lockdowns-as-partial-holidays/paper/) · [PDF](https://github.com/thanatchon36/lockdowns-as-partial-holidays/raw/main/paper/paper.pdf) · [DOI](https://doi.org/10.5281/zenodo.24036955) |
| [**tbg-kit**](https://github.com/thanatchon36/tbg-kit) | *Mapping Thailand's Business Groups: Ownership, Control, and the Finance-Business Nexus*. An open pipeline that traces every subsidiary to its ultimate owner from SET, Form 56-1, DBD, Pillar 3 and GLEIF disclosures, measures pyramids and the control/cash-flow wedge, and links bank groups to business groups; the published demo uses synthetic data only, because real shareholder lists fall under the PDPA; [interactive explorer](https://thanatchon36.github.io/tbg-kit/explorer.html). | [Web](https://thanatchon36.github.io/tbg-kit/paper/) · [PDF](https://github.com/thanatchon36/tbg-kit/raw/main/docs/paper_demo.pdf) · [DOI](https://doi.org/10.5281/zenodo.24037021) |
| [**stablerun**](https://github.com/thanatchon36/stablerun) | *When Stablecoins Run: Fire-Sale Spillovers to the Treasury Bill Market. An Agent-Based Stress Test*. A working draft and calibrated agent-based model of a run on a payment stablecoin, fitted to the USDC (2023) and USDT (2022) episodes; at today's size a run moves three-month bill yields by roughly 20 bp through demand withdrawn at auction rather than fire sales; calibration inputs are still to be verified; simulation outputs on Hugging Face. | [Web](https://thanatchon36.github.io/stablerun/paper/) · [PDF](https://github.com/thanatchon36/stablerun/raw/main/paper.pdf) · [DOI](https://doi.org/10.5281/zenodo.23996044) |
| [**thainowcast**](https://github.com/thanatchon36/thainowcast) | *ThaiNowcast: Pseudo-Real-Time Nowcasting of Thai GDP and Inflation with Official and Alternative Data*. A working draft and open pipeline racing bridge, MIDAS, dynamic factor, elastic net and gradient-boosting models on official indicators and five alternative-data families; forecast results so far come from synthetic test data and validate the pipeline, not the Thai economy; dataset on Hugging Face. | [Web](https://thanatchon36.github.io/thainowcast/paper/) · [PDF](https://github.com/thanatchon36/thainowcast/raw/main/paper/paper.pdf) · [DOI](https://doi.org/10.5281/zenodo.23995547) |
| [**underwater-collateral**](https://github.com/thanatchon36/underwater-collateral) | *Underwater Collateral: Flood Risk in Official Land Values, Credit under Relief and Bank Capital*. A working draft with a public-data pilot on how flood risk reaches bank capital in Thailand, from flood maps through official land values to a reverse stress test; RQ1 pre-registration pending, open data on Hugging Face. | [Web](https://thanatchon36.github.io/underwater-collateral/paper/) · [PDF](https://github.com/thanatchon36/underwater-collateral/raw/main/paper/paper.pdf) · [DOI](https://doi.org/10.5281/zenodo.23949061) |
| [**llm-home-bias**](https://github.com/thanatchon36/llm-home-bias) | *Do Open-Source LLMs Have a Home Bias? Investment Advice from Chinese, American, European and Thai Models*. A pre-registered factorial experiment asking 12 local open-weight models to split an equity portfolio across eight markets; public dataset of replies on Hugging Face. | [Web](https://thanatchon36.github.io/llm-home-bias/) · [PDF](https://github.com/thanatchon36/llm-home-bias/raw/main/paper/paper.pdf) · [DOI](https://doi.org/10.5281/zenodo.23861180) |
| [**stablecoin-tbills-genius-act**](https://github.com/thanatchon36/stablecoin-tbills-genius-act) | *Stablecoin Flows and Treasury-Bill Yields after the GENIUS Act: A Pre-Registered Replication-in-Spirit*. Local projections on 11 fiat-backed USD stablecoins, extending Ahmed & Aldasoro (2025, BIS WP 1270) 15 months past enactment; open data on Hugging Face. | [Web](https://thanatchon36.github.io/stablecoin-tbills-genius-act/) · [PDF](https://github.com/thanatchon36/stablecoin-tbills-genius-act/raw/main/paper/paper.pdf) · [DOI](https://doi.org/10.5281/zenodo.23836447) |
| [**cpilens**](https://github.com/thanatchon36/cpilens) | *How Much Does Product Classification Cost in Basis Points? Multilingual Classification of Thai Product Text for Consumer Price Measurement* | [Web](https://thanatchon36.github.io/cpilens/paper/) · [PDF](https://github.com/thanatchon36/cpilens/raw/main/paper/main.pdf) · [DOI](https://doi.org/10.5281/zenodo.23686886) |
| [**cbtone**](https://github.com/thanatchon36/cbtone) | *Do Local-LLM Tone Scores of Central-Bank Communication Carry Policy Signal? Pre-registered Evidence from Seven Central Banks in Three Languages* | [Web](https://thanatchon36.github.io/cbtone/paper/) · [PDF](https://github.com/thanatchon36/cbtone/raw/main/paper/paper.pdf) · [DOI](https://doi.org/10.5281/zenodo.23371641) |
| [**fraud-synth-bench**](https://github.com/thanatchon36/fraud-synth-bench) | *Classic and Modern Fraud Detectors under Controlled Imbalance, Drift, Ring Fraud and Label Delay: A Reproducible Study on Synthetic Data* | [Web](https://thanatchon36.github.io/fraud-synth-bench/paper/) · [PDF](https://github.com/thanatchon36/fraud-synth-bench/raw/main/paper/paper.pdf) · [DOI](https://doi.org/10.5281/zenodo.23343483) |

**🏛️ AI governance & agent security**

| Project | Paper | Read |
|---|---|---|
| [**coauthored**](https://github.com/thanatchon36/coauthored) | *How Much of the Code That Trains the Models Declares AI Help? AI Co-Authorship Trailers in AI Infrastructure Repositories, 2023–2026*. A pre-registered count of AI-attributed commits across 2.85M commits in 96 open-source repositories; `pip install coauthored`. | [Web](https://thanatchon36.github.io/coauthored/paper/) · [PDF](https://github.com/thanatchon36/coauthored/raw/main/paper/coauthored.pdf) · [DOI](https://doi.org/10.5281/zenodo.23752989) |
| [**sandbank**](https://github.com/thanatchon36/sandbank) | *Under Pressure: Do LLM Agents Circumvent KYC/AML Controls to Hit Business Targets?* A pre-registered sandbox study of Claude agents in a synthetic bank. | [Web](https://thanatchon36.github.io/sandbank/paper/) · [PDF](https://github.com/thanatchon36/sandbank/raw/main/paper/main.pdf) · [DOI](https://doi.org/10.5281/zenodo.23732290) |
| [**airmkit**](https://github.com/thanatchon36/airmkit) | *Operationalising the MAS Guidelines on AI Risk Management for LLM and Agentic Systems: A Machine-Checkable Control Catalogue and Pre-registered Empirical Study*. Independent project, not affiliated with MAS. | [Web](https://thanatchon36.github.io/airmkit/paper/) · [PDF](https://github.com/thanatchon36/airmkit/raw/main/paper/paper.pdf) · [DOI](https://doi.org/10.5281/zenodo.23341671) |
| [**harnesswatch**](https://github.com/thanatchon36/harnesswatch) | *The Harness Is the Attack Surface: A Security Analysis of AI Coding-Agent Harnesses (2025–2026)* | [Web](https://thanatchon36.github.io/harnesswatch/paper/) · [PDF](https://github.com/thanatchon36/harnesswatch/raw/main/paper/main.pdf) · [DOI](https://doi.org/10.5281/zenodo.23407630) |
| [**rulewarden**](https://github.com/thanatchon36/rulewarden) | *rulewarden: Deterministic Runtime Assurance for AI Coding Agents* | [Web](https://thanatchon36.github.io/rulewarden/paper/) · [PDF](https://github.com/thanatchon36/rulewarden/raw/main/paper/paper.pdf) · [DOI](https://doi.org/10.5281/zenodo.23368991) |

**🔬 AI ecosystem & compute trends**

| Project | Paper | Read |
|---|---|---|
| [**open-model-phylogeny**](https://github.com/thanatchon36/open-model-phylogeny) | *Phylogenetics of Open Models: Structure, Hybridisation, Tempo and Speciation in the Hugging Face Lineage Graph*. A working draft that reads the declared `base_model` lineage of 965,292 Hub models as a phylogeny: the top 1% of roots hold 74.8% of connected models, and for heavily reused bases the median time to the first fine-tune fell from 35 days to 2.8; snapshot data on Hugging Face. | [Web](https://thanatchon36.github.io/open-model-phylogeny/paper/) · [PDF](https://github.com/thanatchon36/open-model-phylogeny/raw/main/paper/paper.pdf) · [DOI](https://doi.org/10.5281/zenodo.24029159) |
| [**chipledger**](https://github.com/thanatchon36/chipledger) | *Is Huang's Law Moore's Law? Decomposing a Decade of AI Accelerator Performance Growth, 2012–2026*. A pre-registered split of vendor-published peaks for 79 accelerators from 14 vendors into density, die area, clock, specialization and precision; open dataset with per-value provenance. | [Web](https://thanatchon36.github.io/chipledger/paper/) · [PDF](https://github.com/thanatchon36/chipledger/raw/main/paper/chipledger.pdf) · [DOI](https://doi.org/10.5281/zenodo.23763729) |

**🌾 Thai agriculture & tourism**

| Project | Paper | Read |
|---|---|---|
| [**isan-rice-yield-benchmark**](https://github.com/thanatchon36/isan-rice-yield-benchmark) | *Leakage-Safe, Explainable Multi-Source Machine Learning for District-Level Rice Yield Forecasting: A Ground-Truth Simulation Benchmark for Northeast Thailand*. A process-informed simulator of 200 Isan districts over 18 seasons that stores the true yield components, so both forecasts and SHAP explanations can be checked; random cross-validation understates error by 10–21%; synthetic data, dataset on Hugging Face. | [Web](https://thanatchon36.github.io/isan-rice-yield-benchmark/paper/) · [PDF](https://github.com/thanatchon36/isan-rice-yield-benchmark/raw/main/paper/paper.pdf) · [DOI](https://doi.org/10.5281/zenodo.24036675) |
| [**twelve-views-thai-tourism**](https://github.com/thanatchon36/twelve-views-thai-tourism) | *Twelve Views of Thai Tourism: A Data-Shape-Driven Framework for Visual Analysis, Evaluated by Planted-Structure Recovery*. Four research questions mapped to twelve coordinated views, from radial spirals and Sankey diagrams to a t-SNE map, each scored on whether it recovers structure planted in synthetic data; dataset on Hugging Face. | [Web](https://thanatchon36.github.io/twelve-views-thai-tourism/paper/) · [PDF](https://github.com/thanatchon36/twelve-views-thai-tourism/raw/main/paper/paper.pdf) · [DOI](https://doi.org/10.5281/zenodo.24035605) |

**⚛️ Quantum computing**

| Project | Paper | Read |
|---|---|---|
| [**bp-from-scratch**](https://github.com/thanatchon36/bp-from-scratch) | *Barren Plateaus from Scratch: A NumPy State-Vector Study of Trainability in Variational Quantum Circuits*. A roughly 500-line NumPy simulator with exact adjoint gradients, checked against PennyLane, that reproduces and extends the barren-plateau literature on 2–16 qubits; cached results on Hugging Face. | [Web](https://thanatchon36.github.io/bp-from-scratch/paper/) · [PDF](https://github.com/thanatchon36/bp-from-scratch/raw/main/paper/paper.pdf) · [DOI](https://doi.org/10.5281/zenodo.23995487) |

#### 🤖 LLM & agent tooling

| Project | What it does |
|---|---|
| [**upfront**](https://github.com/thanatchon36/upfront) | See how many tokens your MCP servers, skills and `AGENTS.md` cost a coding agent up front, and which tools break in which client. |
| [**tracecost**](https://github.com/thanatchon36/tracecost) | Recompute what your LLM traces cost, offline, from OTLP, Langfuse or Phoenix exports, with cache and reasoning tokens priced. |
| [**skills**](https://github.com/thanatchon36/skills) | Agent skills that take an open-source project from a one-page `MISSION.md` to a shipped public repo. |

#### 🛠️ CI & developer tools

| Project | What it does |
|---|---|
| [**lastgreen**](https://github.com/thanatchon36/lastgreen) | Compare a failing GitHub Actions job with its last green run: runner image, tool versions, new log lines. |
| [**verdrift**](https://github.com/thanatchon36/verdrift) | Find every place your repo pins a Node, Python or Go version, and see where they disagree. |
| [**layerdelta**](https://github.com/thanatchon36/layerdelta) | See why your container image got bigger: compare two images file by file, with a CI size budget. |

#### 📊 Experiments

| Project | What it does |
|---|---|
| [**gemini-candlestick**](https://github.com/thanatchon36/gemini-candlestick) | An AI-simulated board meeting of 10 legendary market technicians debating daily S&P 500 charts (Gemini + TA-Lib). |

#### 🧰 Stack

Python · PyTorch · scikit-learn · Spark · LLM APIs (Claude, Gemini, OpenAI) · RAG & agent frameworks · Docker · Kubernetes · GitHub Actions

#### 📫 Connect

[LinkedIn](https://www.linkedin.com/in/thanatchon/) · Issues and PRs on any of the repos above are welcome.

<sub>Views here are my own and do not represent the Bank of Thailand.</sub>
