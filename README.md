# Awesome-Pharmacovigilance

## Top Pharmacovigilance Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Pharmacovigilance, Drug Safety, ICSR Case Processing, Safety Reporting, Signal Detection, Risk Management & Safety Intelligence*  

**Last updated: August 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Pharmacovigilance (PV) and Drug Safety**. These systems help pharmaceutical, biotechnology, CRO, and healthcare organizations collect, process, assess, analyze, and report adverse events and Individual Case Safety Reports (ICSRs), while supporting regulatory submissions, signal detection, aggregate reporting, literature surveillance, and safety analytics.



**Examples** include Oracle Argus Safety, ArisGlobal LifeSphere Safety, Veeva Vault Safety, Ennov Vigilance, SafetyEasy PV, SARUS PV, AB Cube, Celegence, EXTEDO, Pharmapod, Sarjen PV, IQVIA Vigilance Platform, Sparta Safety, and Drug Safety Solutions. Enterprise PV systems commonly cover case intake, data entry, MedDRA coding, medical review, regulatory reporting, signal management, and safety analytics. :contentReference[oaicite:0]{index=0}



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



- **[Oracle Argus Safety](https://www.oracle.com/life-sciences/safety/)**  

  Enterprise pharmacovigilance platform for safety case management, intake, regulatory reporting, analytics, and global drug-safety workflows. Oracle's current Safety One Argus offering combines case management and intake with cloud-based automation and analytics. :contentReference[oaicite:1]{index=1}



- **[ArisGlobal LifeSphere Safety](https://www.arisglobal.com/lifesphere/safety/)**  

  Cloud-native end-to-end pharmacovigilance platform covering case management, intake and triage, literature intelligence, reporting, signal management, analytics, and AI-powered safety automation. :contentReference[oaicite:2]{index=2}



- **[Veeva Vault Safety](https://www.veeva.com/products/vault-safety/)**  

  Cloud pharmacovigilance platform supporting adverse-event case processing, regulatory submissions, safety reporting, and integration with the broader Veeva Vault ecosystem.



- **[Ennov Vigilance](https://www.ennov.com/solutions/pharmacovigilance/)**  

  Pharmacovigilance platform supporting safety case processing, reporting, workflow management, compliance, and drug-safety operations.



- **[Ennov PV-Works](https://www.ennov.com/)**  

  Pharmacovigilance software supporting individual case safety reports, workflow, regulatory reporting, and safety-data management.



- **[SafetyEasy PV](https://www.safetyeasy.com/)**  

  Pharmacovigilance solution focused on safety case management, regulatory reporting, workflow, and compliance.



- **[AB Cube](https://www.abcube.com/)**  

  Life-sciences software provider associated with SafetyEasy and pharmacovigilance solutions for safety case management and regulatory processes.



- **[EXTEDO](https://www.extedo.com/)**  

  Regulatory and pharmacovigilance software provider offering solutions for safety reporting, regulatory information management, submissions, and compliance.



- **[Pharmapod](https://www.pharmapodhq.com/)**  

  Medication-safety and pharmacovigilance-oriented platform focused on incident reporting, medication safety, analysis, and risk reduction.



- **[Sarjen PV](https://www.sarjen.com/)**  

  Pharmacovigilance software portfolio supporting safety case processing, reporting, compliance, and drug-safety workflows.



- **[PvEdge](https://www.sarjen.com/)**  

  Sarjen's pharmacovigilance platform, formerly associated with PvNET, providing safety case management and pharmacovigilance workflows.



- **[IQVIA Vigilance Platform](https://www.iqvia.com/solutions/technologies/safety-and-regulatory)**  

  Safety technology ecosystem supporting pharmacovigilance case processing, safety analytics, regulatory reporting, signal management, and related services.



- **[Sparta Systems](https://www.spartasystems.com/)**  

  Life-sciences quality and safety technology provider with solutions and services supporting regulated safety and compliance processes.



- **[Drug Safety Solutions](https://www.drugsafetysolutions.com/)**  

  Drug-safety and pharmacovigilance technology/services provider supporting safety operations and regulated pharmacovigilance processes.



- **[RxLogix PV Suite](https://www.rxlogix.com/)**  

  Pharmacovigilance and drug-safety platform covering signal management, aggregate reporting, benefit-risk management, case processing, and safety analytics.



- **[Clinevo Safety](https://www.clinevo.com/)**  

  Pharmacovigilance software and services provider supporting safety case processing, reporting, and drug-safety operations.



- **[Flex Databases](https://www.flexdatabases.com/)**  

  Life-sciences software platform providing configurable systems for clinical research, pharmacovigilance, and related regulated workflows.



- **[PVWorks](https://www.ennov.com/)**  

  Ennov's pharmacovigilance solution supporting safety case processing, reporting, workflow, and regulatory compliance.



- **[Oracle Life Sciences Empirica](https://www.oracle.com/life-sciences/pharmacovigilance/)**  

  Safety signal-management and data-mining solution for detecting and investigating potential safety signals across large safety datasets. :contentReference[oaicite:3]{index=3}



- **[ArisGlobal LifeSphere Advanced Intake](https://www.arisglobal.com/lifesphere/safety/)**  

  Automated safety-data intake and triage capabilities designed to accelerate collection and processing of adverse-event information from diverse sources. :contentReference[oaicite:4]{index=4}



- **[ArisGlobal LifeSphere Advanced Signals](https://www.arisglobal.com/lifesphere/safety/)**  

  Signal and risk-management capabilities for identifying, assessing, and investigating potential safety signals using analytics and automation. :contentReference[oaicite:5]{index=5}



- **[ArisGlobal LifeSphere Literature Intelligence](https://www.arisglobal.com/lifesphere/safety/)**  

  Automated literature-monitoring and assessment capabilities designed to streamline pharmacovigilance literature surveillance. :contentReference[oaicite:6]{index=6}



## Open-Source GitHub Projects



- **[BioDEX](https://github.com/KarelDO/BioDEX)**  

  Open biomedical adverse-drug-event extraction resource containing tens of thousands of biomedical publications and hundreds of thousands of associated drug-safety reports. It provides data and models useful for pharmacovigilance NLP research. :contentReference[oaicite:7]{index=7}



- **[OnSIDES](https://github.com/tatonetti-lab/onsides)**  

  Open-source database of drug adverse events extracted from structured drug-product labels. The project provides millions of drug-ADE pairs and is particularly useful for adverse-event research, safety signal analysis, and pharmacovigilance NLP. :contentReference[oaicite:8]{index=8}



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



The open-source ecosystem is currently much stronger around **data, NLP, observational research, and signal-detection research** than around a complete validated replacement for enterprise safety databases. BioDEX, for example, is specifically designed as a biomedical adverse-drug-event extraction resource, while OnSIDES provides a large adverse-drug-event knowledge base extracted from product labels. :contentReference[oaicite:9]{index=9}



Enterprise systems remain substantially more comprehensive for regulated end-to-end PV operations. Current platforms such as Oracle Safety One Argus and ArisGlobal LifeSphere Safety integrate case management, intake, reporting, analytics, signal management, automation, and regulatory workflows. :contentReference[oaicite:10]{index=10}



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
