# Awesome-Model-Drift-Detection

## Top Model Drift Detection Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Data Drift, Concept Drift, Prediction Drift, Embedding Drift, Feature Distribution Monitoring & Production Model Stability*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Model Drift Detection**. These systems continuously compare production data and model behavior against reference distributions to detect data drift, concept drift, prediction drift, and related degradations—enabling timely alerts, investigation, and retraining.



**Examples** include Arize AI, WhyLabs, Fiddler AI, Evidently AI, Aporia, Arthur AI, Superwise, TruEra, Galileo, and Deepchecks (the category leaders).



**Open-source emphasis**: Drift detection has a rich open-source ecosystem. **Evidently**, **Deepchecks**, **whylogs**, **Alibi Detect**, and **NannyML** provide production-ready libraries and self-hosted capabilities for statistical and multivariate drift detection across tabular, text, and other data types. This section is heavily expanded with every major active project.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Arize AI](https://arize.com/)**  

  Leading ML and LLM observability platform with strong drift detection across features, predictions, and embeddings, plus root-cause analysis and large-scale production monitoring.



- **[Fiddler AI](https://www.fiddler.ai/)**  

  AI observability platform that combines drift detection, performance monitoring, and explainability—frequently chosen in regulated environments.



- **[WhyLabs](https://whylabs.ai/)**  

  AI observability solution centered on statistical data profiling for scalable, privacy-aware detection of distribution shifts and data quality issues.



- **[Evidently AI (Cloud)](https://www.evidentlyai.com/)**  

  Hosted platform built on the open-source Evidently framework, offering managed drift reports, tests, dashboards, and alerting for ML and LLM systems.



- **[Aporia, Arthur AI, Superwise, TruEra, Galileo, Deepchecks (Managed)](https://www.aporia.com/)**  

  Additional commercial platforms providing drift detection, model validation, continuous monitoring, and governance features for production AI.



- **[Other drift detection & ML observability platforms](https://arize.com/)**  

  Solutions focused on real-time or batch drift monitoring, embedding-space analysis, and enterprise observability.



## Open-Source GitHub Projects



- **[Evidently](https://github.com/evidentlyai/evidently)**  

  Leading open-source ML and LLM observability framework with extensive drift detection (data drift, prediction drift, target drift), 100+ metrics, test suites, and a self-hostable monitoring dashboard (Apache 2.0).



- **[Deepchecks](https://github.com/deepchecks/deepchecks)**  

  Open-source suite for AI & ML validation and monitoring. Includes built-in checks for data drift, model performance, and data integrity across tabular, NLP, and computer-vision data (core under AGPL).



- **[whylogs](https://github.com/whylabs/whylogs)**  

  Open-source library for generating statistical profiles (sketches) of datasets and model I/O. Enables efficient, privacy-preserving drift and quality monitoring by comparing profiles over time.



- **[Alibi Detect](https://github.com/SeldonIO/alibi-detect)**  

  Open-source Python library for outlier, adversarial, and drift detection (univariate and multivariate) on tabular, text, and image data. Integrates well with model-serving stacks.



- **[NannyML](https://github.com/NannyML/nannyml)**  

  Open-source library focused on multivariate drift detection and estimating model performance without ground truth—useful when labels arrive with significant delay.



- **[Other drift detection libraries](https://github.com/search?q=data+drift+OR+concept+drift+OR+model+drift)**  

  Community and research projects implementing statistical tests, domain classifiers, and custom drift detectors.



- **[LLM & embedding drift tools](https://github.com/search?q=embedding+drift+OR+LLM+drift+OR+text+drift)**  

  Emerging open projects for monitoring distribution shifts in embeddings and generative model outputs.



- **[General ML monitoring companions](https://github.com/search?q=model+monitoring+open+source)**  

  Broader open observability stacks that incorporate or extend drift detection capabilities.



### Additional Strong Open-Source Options



- **Evidently Reports & Test Suites**: Declarative drift tests that can run in CI/CD or batch jobs.

- **Deepchecks Suites**: Pre-built and custom checks for drift and data validation.

- **Profile comparison with whylogs**: Lightweight, high-throughput drift monitoring without raw data retention.

- **Alibi Detect detectors**: Domain-classifier and statistical methods for multivariate drift.

- **NannyML**: Performance estimation + drift when labels are delayed.

- Composable pipelines: Evidently or Deepchecks for metrics + Prometheus/Grafana or custom stores for alerting and historical tracking.



**Frameworks for building custom systems**:  

The strongest open-source foundations for drift detection are **Evidently** (most complete metrics + dashboard), **Deepchecks** (validation + monitoring checks), **whylogs** (scalable profiling), **Alibi Detect** (flexible detectors), and **NannyML** (performance-without-labels + multivariate drift).  

These can be assembled into robust self-hosted monitoring systems.  

Commercial platforms (Arize, Fiddler, WhyLabs, etc.) add enterprise-scale storage, advanced embedding/LLM drift analysis, collaboration, governance, and support.  

Many teams begin with Evidently or Deepchecks for core drift detection and later adopt a commercial observability platform for multi-model fleets or regulated environments. Fully open stacks are production-viable when teams can operate the supporting infrastructure.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Drift detection surfaces distributional changes but does not automatically diagnose root causes or trigger retraining. Alert thresholds, statistical significance, and business impact must be carefully calibrated to avoid alert fatigue.

- Open-source drift tools offer transparency and no vendor lock-in but require management of data pipelines, storage, security, and alerting. Ensure chosen statistical tests and reference windows match your data characteristics and risk tolerance before production use.



---



**Made for ML engineers, MLOps practitioners, data scientists, and AI platform teams detecting and responding to model and data drift in production.**  

Let's keep drift detection open, statistically sound, and actionable—through both excellent open-source libraries and complementary commercial observability platforms.
