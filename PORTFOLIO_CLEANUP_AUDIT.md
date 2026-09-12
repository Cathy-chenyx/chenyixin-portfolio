# Portfolio Cleanup Audit — Public / Private Evidence

> Step 5B classification only. No evidence files are deleted or renamed in this step.
>
> Classification is based on public portfolio value, likely privacy exposure, duplication risk, and maintainability. Binary/LFS files were not content-inspected here, so anything marked **REDACT & REPLACE** or **REVIEW DUPLICATE** should be visually checked before Step 5C execution.

## Classification legend

- **KEEP PUBLIC** — useful, low-risk evidence that can remain public as-is if content review confirms no sensitive information.
- **REDACT & REPLACE** — valuable evidence, but the public copy should remove student IDs, candidate numbers, certificate/verification IDs, QR codes, DOB, signatures, phone/address, or other unnecessary identifiers.
- **REMOVE FROM PUBLIC** — keep in private archive / Notion / local storage, but not in the public evidence repository.
- **REVIEW DUPLICATE** — likely duplicate/alternative format/overlapping evidence; compare before keeping one canonical version.

---

## 01专业能力

| File | Classification | Rationale / Step 5C action |
|---|---|---|
| `1.1南方医科大学_成绩单.pdf` | REMOVE FROM PUBLIC | Full transcript is unnecessary public exposure; keep private and show GPA/course summary in README/CV. |
| `1.2_SAS_base证书.pdf` | REDACT & REPLACE | High-value professional credential; publish only a sanitized copy if credential/candidate IDs are present. |
| `1.3计算机二级证书.pdf` | REMOVE FROM PUBLIC | Low marginal portfolio value relative to privacy/maintenance cost; retain privately. |
| `1.4_CET4_634.pdf` | REMOVE FROM PUBLIC | Score can be stated in CV/portfolio; raw exam document need not be public. |
| `1.5_CET6_546.pdf` | REMOVE FROM PUBLIC | Score can be stated publicly; raw exam proof belongs in private archive. |
| `1.6初级统计师证书.pdf` | REDACT & REPLACE | Relevant credential; keep a sanitized public proof if useful for applications. |
| `IELTS_JP22324507833-22-02-2025-ETRF.pdf` | REMOVE FROM PUBLIC | ETRF filename itself exposes a test-report identifier; official report commonly contains multiple personal identifiers. |
| `SMU_Enrollment.pdf` | REMOVE FROM PUBLIC | Enrollment/student-status documentation is identity/administrative evidence, not portfolio content. |
| `SMU_Transcript.pdf` | REVIEW DUPLICATE | Likely overlaps with `1.1南方医科大学_成绩单.pdf`; compare, keep neither publicly unless a sanitized excerpt is later needed. |
| `绩点说明（本科生）.pdf` | REMOVE FROM PUBLIC | Administrative explanatory document; unnecessary public exposure. |
| `英文英语六级证明（本科生）.pdf` | REVIEW DUPLICATE | Likely overlaps with CET-6 proof; retain only in private archive if needed for applications. |

**Recommended public outcome for this folder:** keep only sanitized copies of the SAS Base and Junior Statistician credentials; move all transcript/enrollment/language-score originals to private storage.

---

## 02荣誉奖项 / 2.1学术竞赛

| File | Classification | Rationale / Step 5C action |
|---|---|---|
| `SAS大赛获奖证书.jpg` | REVIEW DUPLICATE | Same award also has PDF; prefer one canonical format. |
| `SAS大赛获奖证书.pdf` | REDACT & REPLACE | High-signal national award; keep one sanitized canonical proof, preferably PDF. |
| `中国大学生数学建模广东省三等奖.pdf` | REDACT & REPLACE | Strong academic evidence; sanitize IDs/QR codes if present. |
| `美国大学生数学建模S奖.pdf` | REDACT & REPLACE | Useful supporting achievement; sanitize team/control numbers if present. |

## 02荣誉奖项 / 2.2个人荣誉

| File | Classification | Rationale / Step 5C action |
|---|---|---|
| `校内荣誉.pdf` | REMOVE FROM PUBLIC | Bundled campus honors are lower-signal than headline achievements; keep private and summarize publicly. |
| `职业规划大赛证书.jpg` | REVIEW DUPLICATE | Same award also exists as PDF; keep one canonical proof only. |
| `职业规划大赛证书.pdf` | REDACT & REPLACE | Strong personal-brand achievement; sanitized PDF can remain public. |

## 02荣誉奖项 / 2.3体育竞技

| File | Classification | Rationale / Step 5C action |
|---|---|---|
| `2023年中国大学生健美操锦标赛_亚军.pdf` | REDACT & REPLACE | Flagship national medal; keep one sanitized public proof. |
| `2023年广东省大学生健美操锦标赛_三人操_第四名.pdf` | REMOVE FROM PUBLIC | Supporting result; not needed as raw public evidence once headline athletics story is established. |
| `2023广东省大学生健美操_徒手操_冠军.pdf` | REDACT & REPLACE | Flagship provincial championship; sanitized public proof is reasonable. |
| `2024年广东省大学生健美操锦标赛_三人操_亚军.pdf` | REMOVE FROM PUBLIC | Good achievement but redundant in a public evidence hub with stronger flagship medals. |
| `2024年广东省大学生健美操锦标赛_团体总分_第一名.pdf.pdf` | REVIEW DUPLICATE | High-value result but filename is malformed; verify whether it adds unique evidence before renaming/keeping. |
| `2024年广东省大学生健美操锦标赛_有氧踏板_第五名.pdf.pdf` | REMOVE FROM PUBLIC | Lower-priority result and malformed filename; private archive only. |
| `三人第四名.pdf` | REVIEW DUPLICATE | Ambiguous filename; likely overlaps another trio fourth-place certificate. Compare before any rename. |
| `广东省第十二届大学生运动会健美操_三人操_第四名.jpg.pdf` | REMOVE FROM PUBLIC | Supporting result; malformed extension and low need for raw public proof. |
| `第18届中国大学生健美操锦标赛_五人操_第四名.pdf` | REMOVE FROM PUBLIC | Supporting national result, but not necessary as raw evidence once stronger medals are shown. |
| `第18届中国大学生健美操锦标赛_有氧踏板_第三名.pdf` | REDACT & REPLACE | Flagship national medal; good candidate for sanitized public proof. |
| `第18届中国大学生健美操锦标赛_混合双人操_第四名.pdf` | REMOVE FROM PUBLIC | Supporting result; summarize in portfolio rather than expose every certificate. |

**Recommended public outcome for athletics:** retain only 3–4 representative sanitized certificates (national silver, national bronze, provincial champion, optionally team overall first) instead of every placement.

---

## 03项目证明

| File | Classification | Rationale / Step 5C action |
|---|---|---|
| `GBD.pdf` | REVIEW DUPLICATE | Likely overlaps `统计建模_GBD疾病负担分析.pdf`; compare and retain one canonical final report. |
| `Meta-analysis-report.pdf` | KEEP PUBLIC | Method/research work is appropriate portfolio evidence if cover page contains no student ID or private collaborator details; otherwise sanitize first. |
| `R语言_基于 Cox 回归的动态预测模型.pdf` | KEEP PUBLIC | Relevant biostatistics-method evidence; retain if it represents original/allowed academic work and has no sensitive cover-page data. |
| `循证医学项目_PROSPERO.pdf` | KEEP PUBLIC | Relevant evidence-synthesis artifact; retain if no unpublished/confidential protocol details or unnecessary personal IDs. |
| `时间序列分析_循环神经网络模型的应用比较研究.pdf` | KEEP PUBLIC | Demonstrates methods breadth; acceptable as secondary evidence. |
| `游戏用户留存度预测分析.pdf` | KEEP PUBLIC | Directly supports SAS competition achievement; good public project evidence. |
| `生存分析_左截断数据基于面积法的假设检验方法.pdf` | KEEP PUBLIC | Strong methodology evidence aligned with biostatistics identity. |
| `统计建模_GBD疾病负担分析.pdf` | REVIEW DUPLICATE | Candidate canonical GBD report; compare against `GBD.pdf`. |
| `统计建模_旅客出行交通方式选择.pdf` | KEEP PUBLIC | Acceptable supporting modeling project, though not Featured; keep as archive evidence if original work is clear. |
| `统计模拟_两阶段交叉设计率比较检验方法的模拟研究.pdf` | KEEP PUBLIC | Strong statistical-method evidence; aligned with clinical-trial/statistical computing profile. |
| `遗传统计学_遗传变异的因果结构学习——基于双向介导MR（BIMMER)与结合图论和MVMR的因果网络修剪方法（MRSL）.pdf` | KEEP PUBLIC | High technical signal; keep if it is your own course/research output and contains no restricted data/material. |

**Important content check before Step 5C:** project PDFs should be visually reviewed for student IDs, teammate contact information, instructor signatures, unpublished data, hospital/patient data, or copyrighted source material before remaining public.

---

## 04补充材料

| File | Classification | Rationale / Step 5C action |
|---|---|---|
| `南方医科大学凤翔杯乒乓球比赛第四名.pdf` | REMOVE FROM PUBLIC | Low portfolio signal; summarize activity privately/publicly without raw proof. |
| `南方医科大学凤翔杯篮球比赛亚军/凤翔杯.pic.jpg` | REMOVE FROM PUBLIC | Personal/team photo evidence is unnecessary in GitHub evidence repository. |
| `南方医科大学凤翔杯篮球比赛亚军/篮球比赛.pdf` | REMOVE FROM PUBLIC | Campus-level sports proof; private archive only. |
| `南方医科大学大满贯篮球赛冠军/大满灌篮球赛获奖人员证明.pdf` | REMOVE FROM PUBLIC | Campus sports proof; private archive only. |
| `南方医科大学大满贯篮球赛冠军/大满贯.pic.jpg` | REMOVE FROM PUBLIC | Personal/team photo evidence should not live in technical evidence hub. |
| `南方医科大学校运会跳远第五名.jpg` | REMOVE FROM PUBLIC | Low-signal campus evidence. |
| `南方医科大学跳绳比赛第五名.jpg` | REMOVE FROM PUBLIC | Low-signal campus evidence. |
| `大创立项.png` | REDACT & REPLACE | Potentially relevant research evidence; keep only if it supports a meaningful project and redact student/contact IDs. |
| `大数据挑战赛.jpg` | REMOVE FROM PUBLIC | Unless tied to a Featured/Selected achievement, low incremental value. |
| `循证医学项目.jpg` | REVIEW DUPLICATE | May duplicate PROSPERO/project evidence in `03项目证明`; compare and retain the stronger artifact only. |

---

## Repository-level files

| File | Classification | Rationale / Step 5C action |
|---|---|---|
| `README.md` | KEEP PUBLIC | Primary storefront; already rewritten in Step 4. |
| `README_EN.md` | KEEP PUBLIC | English storefront; synchronized in Step 5A. |
| `.gitignore` | KEEP PUBLIC | Standard repository configuration. |
| `.gitattributes` | KEEP PUBLIC | Required for current Git LFS setup; review IELTS exception after private removal. |
| `PORTFOLIO_CLEANUP_AUDIT.md` | KEEP PUBLIC | Temporary cleanup decision log; can later move to private/maintenance docs if desired. |

---

## Step 5C proposed execution order

1. **Privacy first:** remove raw transcript, enrollment, IELTS, CET, and low-value official originals from the public branch after confirming private backups exist.
2. **Duplicate review:** compare transcript variants, SAS JPG/PDF, career-planning JPG/PDF, GBD reports, trio-fourth-place files, and PROSPERO/evidence image overlap.
3. **Create sanitized public proofs:** SAS Base, Junior Statistician, selected academic awards, career-planning award, and 3–4 flagship athletics certificates.
4. **Reduce public sports evidence:** move remaining athletics/campus proof to private archive.
5. **Project-PDF privacy review:** inspect cover pages and content for student IDs, teammate information, signatures, restricted data, or copyrighted material.
6. **Normalize filenames:** fix `.pdf.pdf`, `.jpg.pdf`, ambiguous names, and choose a consistent naming convention.
7. **Repair links:** update README relative links after moves/renames and remove the IELTS-specific `.gitattributes` exception if no longer needed.
8. **Git-history decision:** separately decide whether sensitive files need history rewriting; deleting from `main` alone does not purge old commits/LFS history.

## Target public repository philosophy

The public repository should prove **capability**, not expose every original document.

A good end state is:

- 2–3 sanitized professional credentials
- 3–5 representative awards
- 3–4 representative athletics proofs at most
- selected project reports / evidence
- concise README storefronts
- no raw transcript, enrollment record, IELTS/CET report, or low-signal campus proof
