---
layout: default
description: "Comparison of Genomic Data-Sharing Platforms against WHO Attributes and Principles of PGDSPs (2025)"
---

# WHO PGDSP Operating Principles Review

## Comparison of Genomic Data-Sharing Platforms

### Alignment with [WHO "Attributes and Principles of PGDSPs" (2025)](./pdfs/9789240113831-eng.pdf)

Platforms compared:

* **GISAID** — [Global Initiative on Sharing All Influenza Data](https://gisaid.org/)
* **NCBI (INSDC)** — [International Nucleotide Sequence Database Collaboration](https://academic.oup.com/nar/advance-article-abstract/doi/10.1093/nar/gkae1058/7899524)
* **Pathoplexus** — [Pathoplexus.org](https://pathoplexus.org/)

Legend: 🟢 = meets | 🟡 = partly/conditional | 🔴 = not met / not documented

---

## 2.1 Governance

| Operating Principle                         | GISAID                                      | NCBI (INSDC)                                   | Pathoplexus                                      |
| ------------------------------------------- | ------------------------------------------- | ---------------------------------------------- | ------------------------------------------------ |
| 2.1.1 Governance structure described        | 🟡 Public terms & general org info; detailed org charts sparse. [[1]](https://gisaid.org/) | 🟢 INSDC collaboration & partner roles publicly described across nodes. [[12]](https://www.australianbiocommons.org.au/insdc)   | 🟢 Statutes + Executive & Scientific Advisory Board pages. [[21]](https://pathoplexus.org/about/governance/pathoplexus-statutes)         |
| 2.1.2 Scientific/ethical advisory mechanism | 🟡 Advisory roles implied via collaborations, not centrally documented. [[1]](https://gisaid.org/) | 🟢 Multiple formal advisory programs across NCBI/NIH; INSDC partner governance. [[12]](https://www.australianbiocommons.org.au/insdc) | 🟢 Scientific Advisory Board + published guidelines & minutes. [[18]](https://pathoplexus.org/about/governance/minutes)            |
| 2.1.3 Conflicts of interest declared        | 🟡 Not routinely published site-wide. [[1]](https://gisaid.org/)                    | 🟢 NIH/NCBI policies; conflicts handled under federal policy; not per-dataset. [[12]](https://www.australianbiocommons.org.au/insdc)                           | 🟢 Board guidelines note governance; minutes list decisions; COI handling in statutes. [[21]](https://pathoplexus.org/about/governance/pathoplexus-statutes)               |
| 2.1.4 Legal location & jurisdiction stated  | 🟢 German non-profit; DAA specifies German law/arbitration. [[2]](https://gisaid.org/terms-of-use/)   | 🟢 US federal hosting; INSDC includes US/EU/JP nodes. [[12]](https://www.australianbiocommons.org.au/insdc)           | 🟢 Swiss non-profit; contact & banking jurisdiction; values/statutes public. [[21]](https://pathoplexus.org/about/governance/pathoplexus-statutes) |

---

## 2.2 Transparency

| Operating Principle                                  | GISAID                        | NCBI (INSDC)                  | Pathoplexus                       |
| ---------------------------------------------------- | ----------------------------- | ----------------------------- | --------------------------------- |
| 2.2.1 Funding sources declared                             | 🟡 Organization identified; funding details limited. [[1]](https://gisaid.org/)                     | 🟢 Agency & grant funding widely documented in partner pubs (e.g., ENA). [[27]](https://academic.oup.com/nar/article/51/D1/D121/6777773)       | 🟢 Funding page (donations, non-profit status). [[23]](https://pathoplexus.org/about/funding) |
| 2.2.2 Governance team listed                               | 🟡 Limited public detail. [[1]](https://gisaid.org/)         | 🟢 Partner institutes visible; program pages list contacts. [[12]](https://www.australianbiocommons.org.au/insdc)   | 🟢 Executive Board/SAB pages. [[24]](https://pathoplexus.org/about/governance)   |
| 2.2.3 Meeting minutes public                               | 🔴 Not published. [[1]](https://gisaid.org/)               | 🟡 Some governance changes communicated via docs/blogs; minutes not centralized. [[12]](https://www.australianbiocommons.org.au/insdc)       | 🟢 Minutes published (General Assembly & Board). [[18]](https://pathoplexus.org/about/governance/minutes)        |
| 2.2.4 Public data policy (scope, curation, AI use, access) | 🟢 DAA & FAQs detail access/redistribution rules. [[2]](https://gisaid.org/terms-of-use/)                   | 🟢 Data/submit/help docs across INSDC. [[28]](https://www.ncbi.nlm.nih.gov/home/submit/) | 🟢 Terms, submission/processing docs, API docs. [[19]](https://pathoplexus.org/about/governance/data-submission)     |
| 2.2.5 Scientific advice public                             | 🔴 Not published. [[1]](https://gisaid.org/)               | 🟡 Mixed by node/program. [[12]](https://www.australianbiocommons.org.au/insdc)                     | 🟢 SAB guidelines & minutes. [[18]](https://pathoplexus.org/about/governance/minutes)     |
| 2.2.6 Full description of data/metadata scope              | 🟢 Platform pages & help describe databases (EpiFlu/EpiCoV/EpiRSV/EpiPox). [[1]](https://gisaid.org/) | 🟢 INSDC/NCBI resource docs list scope. [[28]](https://www.ncbi.nlm.nih.gov/home/submit/)     | 🟢 Metadata fields & organisms listed. [[17]](https://pathoplexus.org/api-documentation)             |
| 2.2.7 Auditable change trail                               | 🟡 Accession history exists; public change logs not emphasized. [[1]](https://gisaid.org/)   | 🟢 Accession/versioning standard across INSDC. [[12]](https://www.australianbiocommons.org.au/insdc)        | 🟢 SeqSets/DOIs + metadata fields include data-use terms & embargo until. [[17]](https://pathoplexus.org/api-documentation)                |
| 2.2.8 Processing code public                               | 🔴 Proprietary platform; code not open. [[1]](https://gisaid.org/)                 | 🟢 Many tools open (e.g., SRA-tools). [[29]](https://github.com/ncbi/sra-tools)      | 🟢 Open API; stack and docs link to GitHub; open standards (Keycloak, LAPIS). [[17]](https://pathoplexus.org/api-documentation)               |
| 2.2.9 Usage statistics published                           | 🟡 News updates; usage metrics not routinely posted. [[6]](https://weekly.chinacdc.cn/en/article/doi/10.46234/ccdcw2021.255)                | 🟡 Some stats in partner papers/dashboards. [[28]](https://www.ncbi.nlm.nih.gov/home/submit/)             | 🟡 Public status page; usage metrics not routine. [[25]](https://pathoplexus.org/)        |
| 2.2.10 Contact info available                               | 🟢 Help & support pages. [[1]](https://gisaid.org/)               | 🟢 Numerous help desks (SRA, Pathogens). [[30]](https://submit.ncbi.nlm.nih.gov/about/sra/)                   | 🟢 Contact page & emails. [[25]](https://pathoplexus.org/)              |

---

## 2.3 Infrastructure & Security

| Principle                 | GISAID         | NCBI (INSDC)                     | Pathoplexus                            |
| ------------------------- | -------------- | -------------------------------- | -------------------------------------- |
| 2.3.1 Infrastructure documented | 🟡 Not detailed publicly. [[1]](https://gisaid.org/) | 🟢 Cloud availability & mirroring across nodes documented. [[12]](https://www.australianbiocommons.org.au/insdc) | 🟡 Status + components (Keycloak, LAPIS) noted; infra details limited. [[25]](https://pathoplexus.org/)                    |
| 2.3.2 Cybersecurity policy      | 🟡 Implicit via access/DAA; policy not posted. [[2]](https://gisaid.org/terms-of-use/)     | 🟢 NIH/NCBI info-sec governance; not always on resource page. [[12]](https://www.australianbiocommons.org.au/insdc)     | 🟡 Not a formal policy page; authentication stack described. [[17]](https://pathoplexus.org/api-documentation) |
| 2.3.3 Resilience arrangements   | 🟡 Not public. [[1]](https://gisaid.org/)   | 🟢 Global mirroring (INSDC) improves availability. [[12]](https://www.australianbiocommons.org.au/insdc)   | 🟡 Public status; redundancies not detailed. [[25]](https://pathoplexus.org/)                  |

---

## 2.4 Data Scope

| Principle                         | GISAID                     | NCBI (INSDC)            | Pathoplexus                   |
| --------------------------------- | -------------------------- | ----------------------- | ----------------------------- |
| 2.4.1 Pathogen scope flexible           | 🟢 Influenza, SARS-CoV-2, RSV, mpox; expands to priority threats. [[1]](https://gisaid.org/)           | 🟢 Broad, organism-agnostic (all pathogens). [[28]](https://www.ncbi.nlm.nih.gov/home/submit/)             | 🟢 Focused set (CCHFV, Ebola, RSV, mpox, etc.); can expand. [[25]](https://pathoplexus.org/) |
| 2.4.2 Consensus genomes + methods       | 🟢 EpiFlu/EpiCoV accept assemblies; method notes in metadata. [[31]](https://theiagenepi.zendesk.com/hc/en-us/articles/29490901886491-Download-data-and-upload-it-into-the-GISAID-data-repository)                 | 🟢 GenBank/NCBI Virus metadata; BioSample fields. [[32]](https://ncbi.xyz)              | 🟢 Consensus sequences + metadata template per organism. [[17]](https://pathoplexus.org/api-documentation)                    |
| 2.4.3 Raw reads possible                | 🟡 Generally not (steers to consensus); raw reads not primary here. [[1]](https://gisaid.org/)                  | 🟢 SRA accepts raw reads. [[30]](https://submit.ncbi.nlm.nih.gov/about/sra/) | 🟡 Consensus only; raw reads via INSDC linked. [[19]](https://pathoplexus.org/about/governance/data-submission)              |
| 2.4.4 Metagenomes accepted              | 🟡 Limited; scope more targeted. [[1]](https://gisaid.org/)                  | 🟢 SRA/GenBank handle metagenomic submissions. [[30]](https://submit.ncbi.nlm.nih.gov/about/sra/)                   | 🟡 Focus on pathogen consensus; not metagenomes. [[26]](https://pathoplexus.org/about/faq)                     |
| 2.4.5 Minimum metadata defined          | 🟢 Templates & submission help. [[31]](https://theiagenepi.zendesk.com/hc/en-us/articles/29490901886491-Download-data-and-upload-it-into-the-GISAID-data-repository)                      | 🟢 BioSample templates & packages. [[32]](https://ncbi.xyz)                   | 🟢 Required TSV schema per organism. [[17]](https://pathoplexus.org/api-documentation)                         |
| 2.4.6 Optional rich metadata            | 🟢 Extended fields (e.g., epi/clinical) commonly used. [[31]](https://theiagenepi.zendesk.com/hc/en-us/articles/29490901886491-Download-data-and-upload-it-into-the-GISAID-data-repository) | 🟢 Extensive optional fields via BioSample. [[32]](https://ncbi.xyz)       | 🟢 Additional optional fields documented. [[17]](https://pathoplexus.org/api-documentation)             |
| 2.4.7 Legal/ethical compliance          | 🟢 Access-controlled, non-public redistribution. [[2]](https://gisaid.org/terms-of-use/)        | 🟢 HRRT & dbGaP policies for sensitive data. [[16]](https://ncbiinsights.ncbi.nlm.nih.gov/2023/02/02/scrubbing-human-sequences-sra-submissions/)           | 🟢 Terms flag non-sensitive metadata; no PHI; embargo option. [[22]](https://pathoplexus.org/about/terms-of-use/data-use-terms)    |
| 2.4.8 Analytic/biologic metadata linked | 🟢 Variant/lineage tools & EPI_SET. [[1]](https://gisaid.org/)          | 🟢 NCBI Virus filters/dashboards + links. [[28]](https://www.ncbi.nlm.nih.gov/home/submit/)  | 🟢 LAPIS query engines & SeqSets/DOIs. [[17]](https://pathoplexus.org/api-documentation)        |

---

## 2.5 Data Submission

| Principle                  | GISAID       | NCBI (INSDC)             | Pathoplexus           |
| -------------------------- | ------------ | ------------------------ | --------------------- |
| 2.5.1 Manual & automated uploads | 🟢 Batch GUI; some scripted clients exist for users. [[31]](https://theiagenepi.zendesk.com/hc/en-us/articles/29490901886491-Download-data-and-upload-it-into-the-GISAID-data-repository)        | 🟢 Web forms, spreadsheets, fully automated XML; multiple transfer protocols. [[28]](https://www.ncbi.nlm.nih.gov/home/submit/)       | 🟢 Web GUI + authenticated API; demo instance. [[17]](https://pathoplexus.org/api-documentation)           |
| 2.5.2 Interfaces documented      | 🟢 Submission walkthroughs exist. [[31]](https://theiagenepi.zendesk.com/hc/en-us/articles/29490901886491-Download-data-and-upload-it-into-the-GISAID-data-repository)  | 🟢 Detailed portal & help docs. [[30]](https://submit.ncbi.nlm.nih.gov/about/sra/)       | 🟢 Step-by-step docs & Swagger. [[17]](https://pathoplexus.org/api-documentation)    |
| 2.5.3 Submission training        | 🟢 Help/FAQ & community docs. [[31]](https://theiagenepi.zendesk.com/hc/en-us/articles/29490901886491-Download-data-and-upload-it-into-the-GISAID-data-repository)       | 🟢 Extensive tutorials & help. [[30]](https://submit.ncbi.nlm.nih.gov/about/sra/)              | 🟢 How-to docs. [[26]](https://pathoplexus.org/about/faq)       |
| 2.5.4 Turnaround time published  | 🟡 Curation occurs; timelines not routinely posted. [[1]](https://gisaid.org/) | 🟢 Immediate on release (or per embargo), varies by repo; policies documented. [[33]](https://ena-docs.readthedocs.io/) | 🟢 Immediate post-approval; INSDC onward submission described. [[19]](https://pathoplexus.org/about/governance/data-submission) |

---

## 2.6 Data Curation

| Principle                 | GISAID               | NCBI (INSDC) | Pathoplexus                |
| ------------------------- | -------------------- | ------------ | -------------------------- |
| 2.6.1 Public curation policy    | 🟡 Quality checks noted during submission; policy not centralized. [[31]](https://theiagenepi.zendesk.com/hc/en-us/articles/29490901886491-Download-data-and-upload-it-into-the-GISAID-data-repository)            | 🟢 Extensive QC & processing docs per resource. [[28]](https://www.ncbi.nlm.nih.gov/home/submit/)   | 🟢 "Data Submission & Processing" page. [[19]](https://pathoplexus.org/about/governance/data-submission)                |
| 2.6.2 Verify host-read removal  | 🟡 Raw reads generally not hosted. [[1]](https://gisaid.org/)                | 🟢 HRRT tooling/service for SRA. [[16]](https://ncbiinsights.ncbi.nlm.nih.gov/2023/02/02/scrubbing-human-sequences-sra-submissions/)  | 🟡 Consensus only; advises linking raw reads via INSDC. [[19]](https://pathoplexus.org/about/governance/data-submission)           |
| 2.6.3 Low-quality data handling | 🟡 Curators may flag/correct; limited public detail. [[1]](https://gisaid.org/) | 🟢 QC flags & filtering vary by resource. [[28]](https://www.ncbi.nlm.nih.gov/home/submit/)   | 🟢 Pipeline adds flags; submitter approval step before release. [[19]](https://pathoplexus.org/about/governance/data-submission) |

---

## 2.7 Data Provenance

| Principle                     | GISAID                        | NCBI (INSDC)                 | Pathoplexus                   |
| ----------------------------- | ----------------------------- | ---------------------------- | ----------------------------- |
| 2.7.1 Accepts primary/imported data | 🟢 Primary submissions; does not mirror INSDC; unique repository. [[1]](https://gisaid.org/)                | 🟢 Mirrors between INSDC nodes. [[12]](https://www.australianbiocommons.org.au/insdc)              | 🟢 Accepts direct submissions; also pushes to INSDC. [[19]](https://pathoplexus.org/about/governance/data-submission) |
| 2.7.2 Full attribution chain        | 🟢 Originating/Submitting lab attribution required. [[1]](https://gisaid.org/) | 🟢 BioSample/BioProject linkage + accessions. [[28]](https://www.ncbi.nlm.nih.gov/home/submit/) | 🟢 Metadata fields + SeqSets & DOIs for citation. [[17]](https://pathoplexus.org/api-documentation)   |
| 2.7.3 Cross-references IDs          | 🟡 EPI ISL IDs; cross-links limited outside GISAID. [[1]](https://gisaid.org/)             | 🟢 Cross-references via accessions across nodes/tools. [[12]](https://www.australianbiocommons.org.au/insdc)           | 🟢 INSDC accessions included; onward submission policy. [[19]](https://pathoplexus.org/about/governance/data-submission)         |

---

## 2.8 Access

| Principle                  | GISAID                      | NCBI (INSDC)   | Pathoplexus                  |
| -------------------------- | --------------------------- | -------------- | ---------------------------- |
| 2.8.1 Free & open access         | 🟡 Free but governed by DAA; no redistribution to non-users; collaboration/acknowledgement clauses. [[2]](https://gisaid.org/terms-of-use/) | 🟢 Free, open, unrestricted reuse per INSDC policy. [[34]](https://datascience.codata.org/articles/10.5334/dsj-2024-029/)  | 🟢 Free access; Open vs Restricted-Use clearly documented (embargo ≤1 yr). [[22]](https://pathoplexus.org/about/terms-of-use/data-use-terms) |
| 2.8.2 GUI & API                  | 🟡 GUI; programmatic access limited/third-party wrappers for credentialed users. [[35]](https://rdrr.io/github/Wytamma/GISAIDR/f/README.md)                  | 🟢 GUI & robust APIs (E-utilities; programmatic). [[28]](https://www.ncbi.nlm.nih.gov/home/submit/)  | 🟢 Web + documented APIs (LAPIS & backend). [[17]](https://pathoplexus.org/api-documentation)            |
| 2.8.3 Account approval timelines | 🟡 Registration vetting; no SLA posted; suspensions described. [[2]](https://gisaid.org/terms-of-use/)             | 🟢 Not applicable (open). [[34]](https://datascience.codata.org/articles/10.5334/dsj-2024-029/) | 🟢 Data view is open; submit/upload requires account; no long vetting delays described. [[25]](https://pathoplexus.org/)         |

---

## 2.9 Interoperability

| Principle                 | GISAID         | NCBI (INSDC)          | Pathoplexus            |
| ------------------------- | -------------- | --------------------- | ---------------------- |
| 2.9.1 Interoperable with others | 🟡 Access limited to authorized users; onward sharing constrained. [[2]](https://gisaid.org/terms-of-use/)   | 🟢 High (open IDs/APIs; mirrored). [[12]](https://www.australianbiocommons.org.au/insdc) | 🟢 High (open APIs; auto-forwarding to INSDC). [[19]](https://pathoplexus.org/about/governance/data-submission)         |
| 2.9.2 API documented            | 🟡 No public general API; credentialed tools exist. [[35]](https://rdrr.io/github/Wytamma/GISAIDR/f/README.md) | 🟢 E-utilities & resource-specific APIs. [[28]](https://www.ncbi.nlm.nih.gov/home/submit/)         | 🟢 API documentation + Swagger UI. [[17]](https://pathoplexus.org/api-documentation)         |
| 2.9.3 Standards in place        | 🟡 Internal; FAIR page describes approach; not open schemas. [[3]](https://gisaid.org/help/fair-principles/)  | 🟢 INSDC schemas & standards. [[12]](https://www.australianbiocommons.org.au/insdc)       | 🟢 LAPIS/JSON/NDJSON; machine-readable data-use fields. [[17]](https://pathoplexus.org/api-documentation) |

---

## 2.10 Data Use & Benefit Sharing

| Principle                 | GISAID                    | NCBI (INSDC)           | Pathoplexus                        |
| ------------------------- | ------------------------- | ---------------------- | ---------------------------------- |
| 2.10.1 User code of practice     | 🟢 DAA governs use; suspensions described. [[2]](https://gisaid.org/terms-of-use/)                     | 🟢 Open use; general terms under agency policies. [[34]](https://datascience.codata.org/articles/10.5334/dsj-2024-029/)      | 🟢 Data Use Terms + governance processes. [[22]](https://pathoplexus.org/about/terms-of-use/data-use-terms)                   |
| 2.10.2 Explicit licence          | 🟢 DAA with explicit restrictions (no redistribution to non-users; acknowledge; collaborate). [[2]](https://gisaid.org/terms-of-use/)        | 🟢 Effectively public-domain/CC0-like for most archives (no use restrictions). [[34]](https://datascience.codata.org/articles/10.5334/dsj-2024-029/)        | 🟢 Open vs Restricted-Use terms; embargo then becomes Open; SeqSet DOIs. [[22]](https://pathoplexus.org/about/terms-of-use/data-use-terms)         |
| 2.10.3 Compliance mechanisms     | 🟡 User vetting & compliance team; machine-readable licences not advertised. [[2]](https://gisaid.org/terms-of-use/)        | 🟢 Accessions & open licences enable automated reuse. [[34]](https://datascience.codata.org/articles/10.5334/dsj-2024-029/) | 🟢 Metadata columns include dataUseTerms, dataUseTermsRestrictedUntil, dataUseTermsUrl. [[22]](https://pathoplexus.org/about/terms-of-use/data-use-terms)          |
| 2.10.4 Benefit-sharing framework | 🟢 Strong acknowledgement/collab expectations. [[2]](https://gisaid.org/terms-of-use/) | 🟡 Benefits flow via open science; no formal reciprocity terms. [[34]](https://datascience.codata.org/articles/10.5334/dsj-2024-029/)      | 🟢 Explicit authorship/acknowledgement rules for Restricted-Use; pushes to INSDC for openness. [[22]](https://pathoplexus.org/about/terms-of-use/data-use-terms) |

---

## 2.11 Analytical & Reporting Capabilities

| Principle                        | GISAID                      | NCBI (INSDC)            | Pathoplexus           |
| -------------------------------- | --------------------------- | ----------------------- | --------------------- |
| 2.11.1 Integrated search/filter         | 🟢 EpiCoV/EpiPox search, EPI_SET, lineage/variant views. [[1]](https://gisaid.org/) | 🟢 NCBI Virus & Pathogen Detection browsers with rich filters. [[28]](https://www.ncbi.nlm.nih.gov/home/submit/) | 🟢 LAPIS search engines & organism browsers. [[17]](https://pathoplexus.org/api-documentation)        |
| 2.11.2 Summaries (geographic, temporal) | 🟢 Regular dashboards/visualizations. [[36]](https://datascience.codata.org/articles/10.5334/dsj-2024-029/)                | 🟢 Dashboards & visual filters in NCBI Virus. [[28]](https://www.ncbi.nlm.nih.gov/home/submit/)      | 🟢 On-site summaries per pathogen; status/news. [[25]](https://pathoplexus.org/)  |
| 2.11.3 Analysis tools documented & version-controlled         | 🟡 Tools are platform-embedded; versioning not publicly tracked. [[1]](https://gisaid.org/)                | 🟢 Docs for browsers/tools maintained. [[28]](https://www.ncbi.nlm.nih.gov/home/submit/)            | 🟢 API & backend docs; explicit "under continuous development." [[17]](https://pathoplexus.org/api-documentation) |

---

## 2.12 Sustainability

| Principle               | GISAID                    | NCBI (INSDC)              | Pathoplexus                      |
| ----------------------- | ------------------------- | ------------------------- | -------------------------------- |
| 2.12.1 Clear value proposition | 🟢 Long-standing mission (influenza → broader pathogens). [[37]](https://weekly.chinacdc.cn/en/article/doi/10.46234/ccdcw2021.255) | 🟢 Foundational public infrastructure for NSD. [[34]](https://datascience.codata.org/articles/10.5334/dsj-2024-029/)        | 🟢 Values/statutes outline mission. [[20]](https://pathoplexus.org/about/governance/values)  |
| 2.12.2 Business/funding model  | 🟡 Donor-supported non-profit; details limited publicly. [[1]](https://gisaid.org/)         | 🟢 Public funding across three nodes. [[34]](https://datascience.codata.org/articles/10.5334/dsj-2024-029/)       | 🟢 Donation-supported; seeking institutional partnerships. [[23]](https://pathoplexus.org/about/funding)         |
| 2.12.3 Scalability plan        | 🟡 Not detailed publicly. [[1]](https://gisaid.org/)              | 🟢 Decades-scale archives; global mirroring. [[12]](https://www.australianbiocommons.org.au/insdc) | 🟡 Early-stage; infrastructure components public, plan evolving. [[24]](https://pathoplexus.org/about/governance)                     |
| 2.12.4 Data lifecycle policy   | 🟡 Not centrally published. [[1]](https://gisaid.org/)           | 🟢 Standard archival lifecycle across INSDC. [[33]](https://ena-docs.readthedocs.io/)            | 🟢 Terms include onward INSDC deposit and embargo expiry. [[22]](https://pathoplexus.org/about/terms-of-use/data-use-terms) |
| 2.12.5 Collaboration plan      | 🟢 Collaborates with GISRS & WHO activities. [[38]](https://www.who.int/initiatives/pandemic-preparedness-and-response-accord)       | 🟢 Multilateral collaboration at scale. [[12]](https://www.australianbiocommons.org.au/insdc)   | 🟢 Member-run governance; open minutes. [[24]](https://pathoplexus.org/about/governance)       |
| 2.12.6 Environmental plan      | 🔴 Not published. [[1]](https://gisaid.org/)             | 🟡 Not typically published per resource. [[28]](https://www.ncbi.nlm.nih.gov/home/submit/)                 | 🔴 Not published. [[25]](https://pathoplexus.org/)                    |

---

# Summary Highlights

* **GISAID**: excels at **equitable benefit sharing** but **lacks full transparency and open interoperability**.
* **NCBI (INSDC)**: best satisfies **open access, standardization, and data integrity** requirements.
* **Pathoplexus**: most transparent, **open governance with minutes**, **machine-readable licences**, and bridges openness with early data protection.

---

# Citations

### GISAID

* [GISAID – Register (DAA)](https://gisaid.org/register/)
* [Terms of Use / DAA](https://gisaid.org/terms-of-use/)
* [FAIR Principles](https://gisaid.org/help/fair-principles/)
* [Homepage](https://gisaid.org/)
* [Mpox Variants Dashboard](https://gisaid.org/mpox-variants-dashboard/)
* [China CDC Weekly on GISAID](https://weekly.chinacdc.cn/en/article/doi/10.46234/ccdcw2021.255)
* [Data Science Journal (2024)](https://datascience.codata.org/articles/10.5334/dsj-2024-029/)
* [GISAIDR Client](https://rdrr.io/github/Wytamma/GISAIDR/f/README.md)
* [TheiaGenEpi Guide](https://theiagenepi.zendesk.com/hc/en-us/articles/29490901886491-Download-data-and-upload-it-into-the-GISAID-data-repository)
* [ECDC Acknowledgements](https://www.ecdc.europa.eu/en/publications-data/gisaid-acknowledgements)
* [ECDC Dataset (Variants)](https://www.ecdc.europa.eu/en/publications-data/data-virus-variants-covid-19-eueea)

### NCBI / INSDC

* [Australian BioCommons INSDC](https://www.australianbiocommons.org.au/insdc)
* [INSDC Overview (Nucleic Acids Research 2024)](https://academic.oup.com/nar/advance-article-abstract/doi/10.1093/nar/gkae1058/7899524)
* [NCBI APIs (E-utilities)](https://www.ncbi.nlm.nih.gov/home/develop/api/)
* [E-utilities Guide](https://www.ncbi.nlm.nih.gov/books/NBK25497/)
* [E-utilities Quick Start](https://eutilities.github.io/site/Quick_Start/eu_quick/)
* [HRRT Overview](https://ncbiinsights.ncbi.nlm.nih.gov/2023/02/02/scrubbing-human-sequences-sra-submissions/)
* [ENA (Nucleic Acids Research 2023)](https://academic.oup.com/nar/article/51/D1/D121/6777773)
* [NCBI Submit](https://www.ncbi.nlm.nih.gov/home/submit/)
* [SRA Tools GitHub](https://github.com/ncbi/sra-tools)
* [SRA Submit](https://submit.ncbi.nlm.nih.gov/about/sra/)
* [NCBI XYZ](https://ncbi.xyz)
* [ncbi.xyz](https://ncbi.xyz)
* [ENA Documentation](https://ena-docs.readthedocs.io/)
* [Data Science Journal INSDC (2024)](https://datascience.codata.org/articles/10.5334/dsj-2024-029/)
* [GISAIDR R Package](https://rdrr.io/github/Wytamma/GISAIDR/f/README.md)

### Pathoplexus

* [API Documentation](https://pathoplexus.org/api-documentation)
* [Meeting Minutes](https://pathoplexus.org/about/governance/minutes)
* [Data Submission & Processing](https://pathoplexus.org/about/governance/data-submission)
* [Values](https://pathoplexus.org/about/governance/values)
* [Statutes](https://pathoplexus.org/about/governance/pathoplexus-statutes)
* [Data Use Terms](https://pathoplexus.org/about/terms-of-use/data-use-terms)
* [Funding Page](https://pathoplexus.org/about/funding)
* [Governance Hub](https://pathoplexus.org/about/governance)
* [Home Page](https://pathoplexus.org/)
* [FAQ](https://pathoplexus.org/about/faq)

### Additional References

* [Data Science Journal Open Science (2024)](https://datascience.codata.org/articles/10.5334/dsj-2024-029/)
* [WHO China CDC Weekly](https://weekly.chinacdc.cn/en/article/doi/10.46234/ccdcw2021.255)
* [WHO Pandemic Accord](https://www.who.int/initiatives/pandemic-preparedness-and-response-accord)

---
