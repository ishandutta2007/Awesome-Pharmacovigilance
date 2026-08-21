# Awesome-Pharmacovigilance

## Top Pharmacovigilance Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Pharmacovigilance, Drug Safety, ICSR Case Processing, Safety Reporting, Signal Detection, Risk Management & Safety Intelligence*  

**Last updated: August 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Pharmacovigilance (PV) and Drug Safety**. These systems help pharmaceutical, biotechnology, CRO, and healthcare organizations collect, process, assess, analyze, and report adverse events and Individual Case Safety Reports (ICSRs), while supporting regulatory submissions, signal detection, aggregate reporting, literature surveillance, and safety analytics.



**Examples** include Oracle Argus Safety, ArisGlobal LifeSphere Safety, Veeva Vault Safety, Ennov Vigilance, SafetyEasy PV, SARUS PV, AB Cube, Celegence, EXTEDO, Pharmapod, Sarjen PV, IQVIA Vigilance Platform, Sparta Safety, and Drug Safety Solutions. Enterprise PV systems commonly cover case intake, data entry, MedDRA coding, medical review, regulatory reporting, signal management, and safety analytics.



**Open-source emphasis**: This category has a much smaller dedicated open-source software ecosystem than areas such as ERP, CRM, or cybersecurity. Therefore, this section is expanded with open-source **pharmacovigilance datasets, adverse-event databases, NLP/AI projects, literature-mining tools, clinical-safety infrastructure, and reusable components** that can be combined to build a self-hosted PV research or safety-intelligence stack.



> **Important:** Open-source research projects and datasets should not automatically be considered validated replacements for regulated enterprise PV systems. Production pharmacovigilance requires appropriate validation, auditability, security, regulatory controls, SOPs, and qualified safety professionals.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites or repositories.



## Table of Contents



- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [Additional Strong Open-Source Options](#additional-strong-open-source-options)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Product | Focus & Capabilities | Starting Pricing | Free Tier / Free Trial Limits | Official Link |
| :--- | :--- | :--- | :--- | :--- |
| **Oracle Argus Safety (Safety One Argus)** | Enterprise safety case management, automated intake, global regulatory reporting (E2B(R3)), and safety analytics. | ~$100,000 / year base enterprise subscription (~$899/month for dedicated sandbox/training instances) | 30-day evaluation trial via Oracle Cloud Free Tier ($300 cloud credits + guided demo); no permanent free plan | [Oracle Argus](https://www.oracle.com/life-sciences/safety/) |
| **ArisGlobal LifeSphere Safety** | Cloud-native multi-tenant pharmacovigilance platform covering case intake, processing, signal management, and automated regulatory submissions. | ~$50,000 / year entry platform contract (~$1,200 / user / year) | 14-day guided proof-of-concept sandbox trial with pre-loaded demo datasets; no permanent free plan | [ArisGlobal](https://www.arisglobal.com/lifesphere/safety/) |
| **Veeva Vault Safety** | Cloud pharmacovigilance solution unified with clinical and regulatory suites for real-time adverse event processing and submission. | ~$25,000 / year platform base fee + $500–$2,400 / user / year | **Free tier via Veeva SiteVault** (free for research sites up to 20 active studies); 30-day sandbox POC for Vault Safety | [Veeva Safety](https://www.veeva.com/products/vault-safety/) |
| **Ennov Vigilance** | Pharmacovigilance suite for ICSR case processing, workflow management, compliance tracking, and electronic submissions. | ~$18,000 / year (or ~$1,500 / user / month entry SaaS tier) | 14-day guided proof-of-concept sandbox access on qualification; no permanent free plan | [Ennov Vigilance](https://www.ennov.com/solutions/pharmacovigilance/) |
| **Ennov PV-Works (PVWorks)** | Comprehensive adverse event database management, electronic reporting, signal analysis, and regulatory compliance. | ~$24,000 / year entry package for mid-tier deployments | 14-day guided evaluation sandbox with standard ICSR workflows; no permanent free plan | [Ennov PV-Works](https://www.ennov.com/) |
| **SafetyEasy PV (AB Cube)** | Multi-vigilance SaaS platform (drugs, cosmetics, medical devices) supporting ICSR management and regulatory gateway submissions. | ~$12,000 / year (~€1,000 / month) for small biotech safety portfolios | 14-day full-feature interactive test environment with sample dataset; no permanent free plan | [SafetyEasy PV](https://www.safetyeasy.com/) |
| **AB Cube Platform** | Modular vigilance and regulatory database software for pharmacovigilance, cosmetovigilance, and device vigilance. | ~$15,000 / year entry multi-vigilance SaaS tier | 14-day interactive sandbox access with standard vigilance templates; no permanent free plan | [AB Cube](https://www.abcube.com/) |
| **EXTEDO (EXTEDOpulse / Safety)** | Integrated regulatory information management (RIM) and safety reporting solution for compliance and eSubmissions. | ~$15,000 / year (~€1,200 / month) entry cloud subscription | 30-day pilot trial environment with limited validation datasets; no permanent free plan | [EXTEDO](https://www.extedo.com/) |
| **Pharmapod** | Incident management and medication safety platform focused on continuous quality improvement and risk reduction in pharmacies. | $150 / year (Safety Assessment tier; $320/yr Essentials, $453/yr Professional) | 14-day trial access following 1-on-1 scheduled demo session; no permanent free plan | [Pharmapod](https://www.pharmapodhq.com/) |
| **Sarjen PV** | Pharmacovigilance software portfolio for end-to-end adverse event case tracking, medical review, and regulatory reporting. | ~$10,000 / year base pharmacovigilance operations package | 14-day guided trial environment for qualified pharma/CRO teams; no permanent free plan | [Sarjen PV](https://www.sarjen.com/) |
| **PvEdge (Sarjen)** | Scalable pharmacovigilance and drug safety database for ICSR case processing, MedDRA coding, and XML submission. | ~$12,000 / year starting subscription for entry CRO/pharma setups | 14-day test instance access with sample case intake workflows; no permanent free plan | [PvEdge](https://www.sarjen.com/) |
| **IQVIA Vigilance Platform** | AI-enabled pharmacovigilance platform integrating adverse event intake, safety surveillance, and regulatory submission. | ~$75,000 / year base platform tier | 30-day proof-of-concept sandbox trial with sample FAERS/EudraVigilance datasets; no permanent free plan | [IQVIA Vigilance](https://www.iqvia.com/solutions/technologies/safety-and-regulatory) |
| **Sparta Systems (TrackWise Digital Safety)** | Quality and safety management platform for complaint handling, adverse event reporting, and CAPA remediation. | ~$200 / user / month (~$20,000 / year entry SMB deployment) | 14-day interactive sandbox trial with pre-configured workflows; no permanent free plan | [Sparta Systems](https://www.spartasystems.com/) |
| **Drug Safety Solutions** | Hosted pharmacovigilance software and managed services for adverse event capture, triage, and regulatory filing. | ~$8,000 / year entry hosted PV compliance package | 14-day guided feasibility test environment; no permanent free plan | [Drug Safety Solutions](https://www.drugsafetysolutions.com/) |
| **RxLogix PV Suite** | Pharmacovigilance analytics, signal detection, benefit-risk management, and "Safety-in-a-Box" automated case processing. | ~$35,000 / year ("Safety-in-a-Box" flat annual entry package) | 30-day proof-of-value sandbox trial with mock signal detection data; no permanent free plan | [RxLogix](https://www.rxlogix.com/) |
| **Clinevo Safety** | Cloud-hosted safety database and intake software for adverse event processing, automated XML generation, and regulatory submissions. | ~$9,600 / year (~$800 / month) for core safety database & intake | 14-day full-feature cloud sandbox trial + free setup consultation; no permanent free plan | [Clinevo](https://www.clinevo.com/) |
| **Flex Databases (PV Module)** | Configurable pharmacovigilance and clinical trial management system (CTMS) for small-to-midsize CROs and biopharma. | ~$12,000 / year (~$1,000 / month) for small clinical / PV teams | 14-day trial environment access following introductory demo; no permanent free plan | [Flex Databases](https://www.flexdatabases.com/) |
| **Oracle Life Sciences Empirica** | Safety signal-management, data-mining, and statistical analysis platform for detecting drug-safety signals across massive datasets. | ~$50,000 / year base signal management subscription | 30-day evaluation trial with sample signal detection datasets; no permanent free plan | [Oracle Empirica](https://www.oracle.com/life-sciences/pharmacovigilance/) |
| **ArisGlobal LifeSphere Advanced Intake** | AI-driven safety data intake and triage system automating extraction from unstructured emails, PDFs, and medical literature. | ~$25,000 / year automated intake add-on tier | 14-day POC sandbox trial with document processing limit (up to 50 sample documents); no permanent free plan | [LifeSphere Intake](https://www.arisglobal.com/lifesphere/safety/) |
| **ArisGlobal LifeSphere Advanced Signals** | Signal management and automated risk detection engine applying statistical algorithms to multi-source safety datasets. | ~$35,000 / year signal analytics tier | 14-day interactive trial on pre-loaded signal datasets; no permanent free plan | [LifeSphere Signals](https://www.arisglobal.com/lifesphere/safety/) |
| **ArisGlobal LifeSphere Literature Intelligence** | AI-powered pharmacovigilance literature monitoring, filtering, and adverse-event identification system. | ~$20,000 / year literature monitoring AI tier | 14-day trial with surveillance cap of up to 5 journal feeds / target search queries; no permanent free plan | [LifeSphere Literature](https://www.arisglobal.com/lifesphere/safety/) |



## Open-Source GitHub Projects



- **[BioDEX](https://github.com/KarelDO/BioDEX)**  

  Open biomedical adverse-drug-event extraction resource containing tens of thousands of biomedical publications and hundreds of thousands of associated drug-safety reports. It provides data and models useful for pharmacovigilance NLP research.



- **[OnSIDES](https://github.com/tatonetti-lab/onsides)**  

  Open-source database of drug adverse events extracted from structured drug-product labels. The project provides millions of drug-ADE pairs and is particularly useful for adverse-event research, safety signal analysis, and pharmacovigilance NLP.



- **[BioBERT](https://github.com/dmis-lab/biobert)**  

  Open-source biomedical language model useful as a foundation for extracting adverse events, drug mentions, diseases, relationships, and other safety information from biomedical literature.



- **[PubMedBERT](https://github.com/microsoft/BLENDER)**  

  Biomedical language-model research that can be adapted for pharmacovigilance NLP, literature mining, adverse-event extraction, and drug-safety classification.



- **[scispaCy](https://github.com/allenai/scispacy)**  

  Open-source NLP toolkit for biomedical and scientific text. It provides entity recognition and processing capabilities useful for extracting drugs, diseases, adverse events, and biomedical concepts from literature.



- **[MedSpaCy](https://github.com/medspacy/medspacy)**  

  Open-source clinical NLP framework built on spaCy, useful for extracting structured safety information from clinical and medical narratives.



- **[Apache cTAKES](https://github.com/apache/ctakes)**  

  Open-source clinical NLP platform for extracting structured information from clinical text. It can serve as a component for medical-literature and safety-report processing pipelines.



- **[NLP4LifeSciences](https://github.com/topics/pharmacovigilance)**  

  GitHub's broader pharmacovigilance ecosystem contains research projects covering adverse-event extraction, drug-safety NLP, signal detection, and biomedical text mining.



- **[DrugBank Open Data Resources](https://github.com/topics/drug-database)**  

  The GitHub ecosystem contains open drug-database projects that can be used as building blocks for drug normalization, drug-name recognition, and safety analytics.



- **[RxNorm API / RxNav](https://github.com/ncbo/umls2rdf)**  

  Open-access NIH terminology infrastructure useful for normalizing medications and connecting drug concepts across clinical and pharmacovigilance datasets.



- **[OHDSI](https://github.com/OHDSI)**  

  Large open-source collaborative ecosystem for observational health data, common data models, vocabulary normalization, cohort analysis, and population-level safety research.



- **[OHDSI OMOP Common Data Model](https://github.com/OHDSI/CommonDataModel)**  

  Open-source common data model for standardizing observational healthcare data. It can be used as the data foundation for large-scale real-world evidence and pharmacovigilance research.



- **[OHDSI ATLAS](https://github.com/OHDSI/Atlas)**  

  Open-source web application for cohort definition, characterization, population-level analyses, and observational research using OMOP data.



- **[OHDSI WebAPI](https://github.com/OHDSI/WebAPI)**  

  Open-source API layer for OHDSI/OMOP analytics and services, useful for building safety analytics and real-world evidence applications.



- **[OpenFDA](https://open.fda.gov/)**  

  Open FDA data APIs providing access to datasets including adverse-event information that can be used for pharmacovigilance research, safety analytics, and signal-detection experiments.



- **[openFDA API Examples](https://github.com/FDA/openfda)**  

  Open-source resources and examples around FDA public datasets and APIs, useful for building applications around publicly available adverse-event and drug information.



- **[EudraVigilance Data Analysis](https://github.com/topics/eudravigilance)**  

  GitHub ecosystem of open research projects analyzing publicly available European pharmacovigilance data and adverse-event reports.



- **[FAERS Analysis Projects](https://github.com/topics/faers)**  

  Open-source projects for analyzing FDA Adverse Event Reporting System data, including disproportionality analysis, signal detection, visualization, and epidemiological research.



- **[PySpark](https://github.com/apache/spark)**  

  Open-source distributed-computing framework useful for processing large-scale pharmacovigilance datasets, literature corpora, spontaneous reports, and real-world data.



- **[DuckDB](https://github.com/duckdb/duckdb)**  

  Open-source analytical database particularly useful for local analysis of large CSV, Parquet, and pharmacovigilance datasets.



- **[PostgreSQL](https://github.com/postgres/postgres)**  

  Open-source relational database suitable for building self-hosted safety-data repositories, case-management backends, terminology databases, and analytics systems.



- **[Apache Airflow](https://github.com/apache/airflow)**  

  Open-source workflow orchestration platform useful for automating literature ingestion, adverse-event pipelines, safety-data ETL, terminology updates, and analytics workflows.



### Additional Strong Open-Source Options



- **[BioDEX](https://github.com/KarelDO/BioDEX)** for biomedical adverse-drug-event extraction and pharmacovigilance NLP research.

- **[OnSIDES](https://github.com/tatonetti-lab/onsides)** for open drug/adverse-event knowledge and safety research.

- **[OHDSI](https://github.com/OHDSI)** for large-scale observational safety and real-world evidence research.

- **[OMOP Common Data Model](https://github.com/OHDSI/CommonDataModel)** for standardized healthcare and safety-data modeling.

- **[OHDSI ATLAS](https://github.com/OHDSI/Atlas)** for cohort definition and population-level safety analysis.

- **[OpenFDA](https://open.fda.gov/)** for public FDA drug and adverse-event datasets.

- **[scispaCy](https://github.com/allenai/scispacy)** for biomedical literature NLP.

- **[MedSpaCy](https://github.com/medspacy/medspacy)** for clinical NLP pipelines.

- **[Apache cTAKES](https://github.com/apache/ctakes)** for clinical text extraction.

- **[BioBERT](https://github.com/dmis-lab/biobert)** for biomedical language-model applications.

- **[DuckDB](https://github.com/duckdb/duckdb)** for local analytical processing of safety datasets.

- **[PostgreSQL](https://github.com/postgres/postgres)** for self-hosted PV databases.

- **[Apache Airflow](https://github.com/apache/airflow)** for automated safety-data workflows.

- **[Apache Spark](https://github.com/apache/spark)** for large-scale safety-data processing.



**Frameworks for building custom pharmacovigilance systems**: Combine **PostgreSQL / DuckDB**, **OHDSI OMOP**, **OpenFDA**, **OnSIDES**, **BioDEX**, **scispaCy / MedSpaCy**, and **Apache Airflow** with a custom case-management and regulatory-reporting layer.



A potential research-oriented open architecture can look like:



**Safety Data Sources → Intake & NLP → ICSR Extraction → Case Database → MedDRA/Drug Normalization → Signal Detection → Medical Review → Analytics → Regulatory Reporting**



For literature surveillance:



**PubMed / Scientific Literature → Document Ingestion → Biomedical NLP → Drug & Adverse-Event Extraction → Deduplication → Human Review → Safety Database**



For population-level pharmacovigilance:



**EHR / Claims / RWD → OMOP CDM → Cohort Definition → Statistical Analysis → Signal Detection → Benefit-Risk Assessment**



The open-source ecosystem is currently much stronger around **data, NLP, observational research, and signal-detection research** than around a complete validated replacement for enterprise safety databases. BioDEX, for example, is specifically designed as a biomedical adverse-drug-event extraction resource, while OnSIDES provides a large adverse-drug-event knowledge base extracted from product labels.



Enterprise systems remain substantially more comprehensive for regulated end-to-end PV operations. Current platforms such as Oracle Safety One Argus and ArisGlobal LifeSphere Safety integrate case management, intake, reporting, analytics, signal management, automation, and regulatory workflows.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Prefer projects with active development and publicly accessible source code.

5. For datasets and research projects, clearly identify them as **research/data infrastructure** rather than complete PV software.

6. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Pharmacovigilance is a highly regulated domain. Open-source research software is **not automatically suitable for regulated production use**.

- Production PV systems require appropriate validation, audit trails, access controls, data integrity, electronic records/signatures controls, regulatory reporting capabilities, SOPs, and qualified personnel.

- Always verify current licensing terms, project activity, regulatory suitability, security posture, and production readiness before using an open-source project.

- Public adverse-event datasets can contain limitations, reporting biases, missing information, duplicates, and other data-quality issues.

- MedDRA and other regulated/proprietary medical terminologies may have licensing requirements; verify the applicable license before implementation.

- Regulatory requirements and electronic reporting standards can change, so implementations should be validated against the applicable current requirements.



---



**Made for pharmacovigilance professionals, drug-safety teams, pharmaceutical companies, biotech companies, CROs, safety scientists, regulatory teams, epidemiologists, biomedical NLP researchers, and developers.**  

Let's make pharmacovigilance more open, data-driven, interoperable, and efficient.
