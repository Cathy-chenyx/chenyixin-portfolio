# Yixin Chen — Portfolio

[中文版本](README.md)

**Southern Medical University | Applied Statistics (Biostatistics) | Data-Driven Strategist**

![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Shiny](https://img.shields.io/badge/Shiny-0B7DBC?style=for-the-badge&logo=r&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SAS](https://img.shields.io/badge/SAS-FF0000?style=for-the-badge)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## Education

**B.Sc. in Applied Statistics (Biostatistics)** — Southern Medical University, Guangzhou  
*2022 – 2026*

- GPA: 3.53 / 5.0 | Rank: 12 / 39
- Key coursework: Evidence-Based Medicine (97), Data Management (98), Survival Analysis (96.5), Clinical Trial Design (95.7), R Programming (95), Statistical Modeling (94.9)

---

## Certifications & Honors

| Certification / Honor | Issuer | Date | Level |
|---|---|---|---|
| Junior Statistician (National) | MOHRSS & NBS | 2025.10 | Passed |
| SAS Base Programmer | SAS Institute | 2025.05 | Certified |
| CET-6 (English) | Ministry of Education | 2025.06 | 546 |
| National Math Modeling Contest | Guangdong Province | 2024.12 | Provincial 3rd Prize |
| National Computer Rank Exam (Level 2) | Ministry of Education | 2023.03 | Passed |

**Competition Highlights:**

- **SAS China Analytics Competition (2024)** — National 2nd Prize
- **China Undergraduate Mathematical Contest in Modeling (2024)** — Provincial 3rd Prize
- **MCM/ICM (2024)** — Successful Participant (S Award)
- **National Career Planning Competition**, SMU Campus Final — **Grand Prize (1st Place)**, Provincial Bronze Prize (2025.11)
- **SMU First-Class Scholarship** (2023–2024), Third-Class Scholarship (2024–2025)
- **SMU Outstanding Student** (2023–2024, 2024–2025)
- **School of Public Health "Top Ten Star" — Sports Star** (2025)

**Athletic Achievements (Aerobics):**
- National Collegiate Aerobics Championships — National Silver Medal (2023) & Bronze Medal (2024)
- Guangdong Provincial Aerobics Championships — 1st Place (Team Overall & Calisthenics, 2023 & 2024)
- Multiple top-4 finishes in Trio, Mixed Doubles, and Group Five at national and provincial levels

---

## Internship Experience

### Parexel International — RWD Strategy Intern  
*March 2026 – Present (~3 months) | Guangzhou*

As an intern in the Asia-Pacific RWD Strategy team at a top-tier global CRO, I contributed to the full lifecycle of multinational real-world evidence (RWE) projects for clients including **GSK, Grifols, AstraZeneca, Johnson & Johnson, and Astellas**.

**GSK Chronic Hepatitis B (CHB) — IAR/IAI Final Delivery & Cross-Regional Quotation Management**
- Finalized IAR/IAI deliverables across 10+ Asia-Pacific data sources (Korea SMC/SNUH/Severance, Taiwan NHIRD, Singapore NUHS, Australia REACH-B, Kingpoint, Lianren, etc.)
- Compiled country-level patient counts, total cost, and cost-per-patient summaries with CNY-to-GBP conversion
- Tracked data source quotations (Lianren: ¥3M+ → ¥4.5M+, Kingpoint: ¥15M inclusive of tax)
- Communicated findings directly to client (Jaime Smith) via English email

**Grifols 295372 — Cirrhosis Albumin RWE Feasibility Assessment**
- Authored the first draft of the Integrated Analysis Plan (IAP) and coordinated ICD-10/ATC coding with the Medical team
- Led alternative data source scouting after Inspur became unavailable (Kingpoint, Lianren, West China Hospital, Qinghai, etc.)
- Completed literature review on 15 cirrhosis + albumin studies; summarized RWE methodology expertise of Prof. Sun Xin's team at West China Hospital
- Supported project resume after 1-month hold (April 28 → May 28), participated in timeline revision

**AstraZeneca (AZ) Projects**
- **India Savotinib NSCLC**: Systematic PubMed search, extracted data sources from Indian real-world NSCLC registries with DOIs
- **Middle East Multiple Myeloma**: Identified UAE DRWD and Qatar databases; produced `MM_Mid_East.pptx` and `MiddleEast_MM_DataSources.xlsx`
- **GOLD 2026 & Personalized Management Workshop**: Authored COPD workshop content covering GOLD 2026 updates, RCT vs. RWE, MITOS EROS+CP studies

**J&J RWE Innovation Workshop**
- Co-prepared workshop content on machine learning validation case study (White Paper + Lianren collaboration) and GSK database application case
- Workshop successfully delivered on May 8, 2026 with positive client feedback

**Additional Project Support**
| Project | Contribution |
|---|---|
| Astellas | Consolidated two feasibility analysis proposals (AMD, GA); compiled Taiwan NHIRD (~$162K USD) and Korea HIRA (~$55K USD) quotations |
| Michel Chronic Osteomyelitis (313119) | Vendor outreach to Jiangbei and Lianren for descriptive analysis quotations |
| OM Project | Contract revision tracking (timeline refinement, indemnity clauses); Inspur signing status monitoring |
| China Commercial RWD Data Source Survey | Systematic mapping of China RWD commercial data sources (type, volume, origin, publications) |

**Professional Development**
- Mastered the full RWD project lifecycle: IAP → IAI → IAR → Protocol
- Studied Parexel RWD Management SOPs (WI02–WI33) covering validation specifications, data quality checks, CDM mapping, clinical coding (MedDRA/WHODrug), and aggregate data management
- Learned meta-analysis and network meta-analysis methods through internal workshops
- Produced 25+ bilingual meeting minutes; collaborated cross-functionally with Medical, Epi, SPL, RWR Delivery teams
- Gained proficiency in SharePoint, Monday.com, Salesforce, and Microsoft Teams

---

## Projects

### SampleSize_R — Interactive Clinical Trial Sample Size Calculator (Capstone Project)

**Description**: Independently developed an R Shiny application implementing **20 mainstream clinical study designs** for sample size calculation, spanning mean comparisons, proportion comparisons, equivalence/non-inferiority tests, survival analysis, correlation coefficients, regression, and categorical variable analysis. Features include three-dimensional filtering (data type → test type → design type), dynamic parameter panels, dropout rate adjustment, and power curve visualization.

**Tech Stack**: R-Shiny, `PowerTOST`, `gsDesign`, `npsurvSS`, dynamic UI generation, statistical modeling

**Key Outcomes**:
- Delivered a fully documented, extensible, and production-ready tool
- Modular function architecture with a `calculators_db.xlsx` registry for easy method extension
- Academic outputs include detailed statistical theory notes, user manual, and capstone proposal

**Links**: [Live Demo](https://cathy-chenyx.shinyapps.io/SampleSize_R/) | [GitHub](https://github.com/Cathy-Chenyx/SampleSize_R.Shiny)

---

### SSEA — Sample Size Estimation Assistant (Contributor)

**Description**: Contributed as a biostatistics student to the development of the SSEA clinical research calculation platform (Zhujiang Hospital research group), covering RCTs, observational studies, and diagnostic trials.

**Contributions**:
- Validated calculation accuracy (error rate < 0.1%)
- Co-authored the [SSEA User Guide series](https://mp.weixin.qq.com/s/t2dFiUKlmI-tuyuoxMN4wA) on WeChat Official Account
- Provided statistical consulting to ensure methodological appropriateness

**Link**: [SSEA Platform](https://smuonco.shinyapps.io/SSEA/)

---

### STEMI In-Hospital GI Bleeding Prediction Model — Statistical Modeling Competition Entry

![ROC Curves](https://gitee.com/Cathy_chenyx/my-wechat-images/raw/master/images/image-20260603151148773.png)

**Description**: Developed an interpretable gastrointestinal bleeding risk prediction model using real-world data from 4,489 STEMI patients at Guangdong Provincial People's Hospital (2010–2020, ~9% positive rate), aimed at supporting early risk stratification and personalized anti-thrombotic management.

**Tech Stack**: R, Python, multiple imputation (`mice`), Knockoff + Lasso dual variable selection (FDR control), adaptive linear regression, pattern submodels, ensemble learning (Stacking/Boosting), SHAP interpretability, decision curve analysis (DCA)

**Key Outcomes**:
- Built an end-to-end analysis pipeline: data cleaning → high-missingness variable removal (>80%) → multiple imputation → variable selection → model training & validation
- Systematically compared 4 variable sets × 12 models; the best-performing model (**Knockoff + Adaptive Linear Regression**) achieved test-set AUC of **0.7977**, significantly outperforming traditional bleeding scores (CRUSADE 0.659, HAS-BLED 0.612, HEMORRHAGES 0.688)
- Innovatively handled real-world missing data with adaptive linear regression and pattern submodels — no prior imputation required, avoiding imputation bias
- Identified 11 clinically interpretable predictors (in-hospital PPI use within 48h, serum creatinine, hemoglobin, direct bilirubin, uric acid, etc.), validated by SHAP analysis and DCA

**Link**: [GitHub Repository](https://github.com/Cathy-chenyx/STEMI_Predictive_model)

---

### ACS Stress Biomarker Prognostic Study — Multi-Cohort Data Analysis & Risk Prediction

**Description**: Using real-world data from >4,000 ACS inpatients at Guangdong Provincial People's Hospital (2010–2015), systematically evaluated the independent prognostic value of 7 admission stress biomarkers (HsCRP, BUN, CystatinC, NT-proBNP, Uric acid, WBC, Lactate) for short-term and long-term clinical outcomes (all-cause mortality, MACE), supporting evidence-based risk stratification.

**Tech Stack**: R, survival analysis (KM + Cox regression), multivariable logistic regression, ROC analysis, three-level diabetes stratification, missing pattern analysis

**Key Outcomes**:
- Completed full analysis pipeline (data cleaning → baseline comparison → univariate → multivariable → composite model → ROC) across three cohorts: ACS overall, STEMI, and UA+NSTEMI
- Lactate on STEMI long-term mortality: Cox HR = 1.21 (95% CI 1.11–1.31); high-lactate group KM curves significantly elevated at 30-day, 1-year, and 3-year follow-up
- HsCRP, BUN, CystatinC, and NT-proBNP demonstrated independent predictive value for Death/MACE in multivariable models; multiple stress biomarkers AUC > 0.6
- Established a reproducible analysis framework with 14 scripts and a modular R function library

**Link**: [GitHub Repository](https://github.com/Cathy-Chenyx/ACS_Analysis_Project)

---

### Asia-Pacific GI Cancer Burden — GBD Data Analysis

**Description**: Analyzed epidemiological trends and regional disparities in gastrointestinal cancer burden across the Asia-Pacific region using Global Burden of Disease (GBD) data.

**Tech Stack**: Joinpoint regression, APC analysis, ICD-10 coding standardization, data visualization

**Key Outcome**: Identified critical trend inflection points (APC = −0.8%, p < 0.05); produced 15+ visualizations to support decision-making

---

### Gaming User Churn Prediction — XGBoost Machine Learning Application

**Description**: Built and deployed a user churn prediction system addressing class imbalance with high-accuracy real-time predictions.

**Tech Stack**: XGBoost, SMOTE, SHAP interpretability, R-Shiny deployment

**Key Outcome**: Achieved 91.18% accuracy; awarded National 2nd Prize in the SAS China Analytics Competition

**Link**: [Live Demo](https://gameretainpredictlab.shinyapps.io/smu-XGboost/)

---

### Cardiometabolic Disease (CMD) Dynamic Prediction Model

**Description**: Developed a joint model coupling longitudinal data with survival outcomes to improve prediction performance for time-varying covariates.

**Tech Stack**: R, joint modeling, dynamic prediction, survival analysis

**Key Outcome**: Validation demonstrated significant improvement over the traditional Cox model

---

### Academic Course Reports (Selected)

- *Survival Analysis — Hypothesis Testing for Left-Truncated Data Based on Area Method*
- *Time Series Analysis — Comparative Study of RNN Architectures*
- *Statistical Simulation — Two-Stage Crossover Design Rate Comparison*
- *Genetic Statistics — Causal Structure Learning via BIMMER and MRSL*
- Plus 5 additional specialized reports

---

## International Experience

### Charles Sturt University (CSU) — Evidence-Based Medicine Joint Program  
*August 2025 | Australia*

- Selected for a 10-day immersive international EBM training program in collaboration with CSU
- Focused on systematic reviews, meta-analysis, and machine learning applications in medicine
- **Group project**: "Interventions for post-traumatic growth in breast cancer patients: a meta-analysis"
- Independently authored the Background, Objectives, Search Strategy, and PICOS sections; delivered English oral defense
- Completed PROSPERO registration for the systematic review protocol

**Evidence**: [PROSPERO Registration File](https://github.com/Cathy-Chenyx/chenyixin-portfolio/blob/main/03项目证明/循证医学项目_PROSPERO.pdf)

---

### Global Travel & Content Creation

**"Building understanding through travel, crystallizing insights through narrative."**

- Independently planned and executed deep travel across **12 countries, 57 cities**
- Published **6 detailed travelogues** (~48,000 words) on Mafengwo, including a ⭐ **Star-Rated Featured Article**
- Demonstrated end-to-end project management, resource integration, and cross-cultural adaptability

**Selected Travelogues**:
- [Hainan 11-Day Road Trip](https://www.mafengwo.cn/i/24805402.html) — ⭐ Star-Rated Featured Article, 5,000+ views
- [Singapore-Malaysia-Thailand 10-Day](https://www.mafengwo.cn/i/24801513.html)
- [Russia: Moscow & St. Petersburg](https://www.mafengwo.cn/i/24374668.html)
- [Japan: Hakuba Ski Week](https://www.mafengwo.cn/i/24644042.html)
- [Hong Kong: Camping & City Walk](https://www.mafengwo.cn/i/24514083.html)
- [Henan Cultural Heritage Tour](https://www.mafengwo.cn/i/24618237.html)

---

## Personal Brand & Content Creation

**WeChat Official Account: "嗨森的糖罐子" (Hisen's Candy Jar)**  
*September 2025 – January 2026*

- Published **20+ original articles** covering biostatistics course notes, post-graduate exam prep resources, and in-depth travel writing
- Top-performing article: *"26应统考研全过程分享"* — **4,759 reads**, 150+ shares
- Consistent follower growth driven by high-utility content; demonstrated content strategy, audience insight, and data-driven optimization

---

## Contact

- **Email**: 3227042017@i.smu.edu.cn
- **Phone**: +86 133-0291-1809
- **GitHub Portfolio**: [github.com/Cathy-Chenyx/chenyixin-portfolio](https://github.com/Cathy-Chenyx/chenyixin-portfolio)
*（内容由AI生成，仅供参考）*
