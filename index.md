---
layout: default
description: "Comparison of Genomic Data-Sharing Platforms against WHO Attributes and Principles of PGDSPs (2025)"
---

<style>
  .modal {
    display: flex;
    position: fixed;
    z-index: 1000;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.5);
    justify-content: center;
    align-items: center;
  }

  .modal-content {
    background-color: #fefefe;
    padding: 30px;
    border: 2px solid #4CAF50;
    border-radius: 8px;
    text-align: center;
    max-width: 500px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    animation: slideDown 0.3s ease-out;
  }

  @keyframes slideDown {
    from {
      transform: translateY(-50px);
      opacity: 0;
    }
    to {
      transform: translateY(0);
      opacity: 1;
    }
  }

  .modal-content h2 {
    color: #FF9800;
    margin-top: 0;
    font-size: 28px;
  }

  .modal-content p {
    color: #333;
    font-size: 16px;
    line-height: 1.6;
  }

  .close-btn {
    background-color: #4CAF50;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 16px;
    margin-top: 20px;
    transition: background-color 0.3s;
  }

  .close-btn:hover {
    background-color: #45a049;
  }
</style>

<div id="constructionModal" class="modal">
  <div class="modal-content">
    <h2>🚧 Under Construction</h2>
    <p>This site is currently under construction. The content and information may be subject to change.</p>
    <button class="close-btn" onclick="closeModal()">Got it!</button>
  </div>
</div>

<script>
  function closeModal() {
    document.getElementById('constructionModal').style.display = 'none';
  }
  
  // Optional: Auto-close after 10 seconds
  // setTimeout(closeModal, 10000);
</script>

# WHO PGDSP Operating Principles Review

## Comparison of Genomic Data-Sharing Platforms

### Alignment with <a href="./pdfs/9789240113831-eng.pdf" target="_blank" rel="noopener noreferrer">WHO "Attributes and Principles of PGDSPs" (2025)</a>

Platforms compared:

* **GISAID** — <a href="https://gisaid.org/" target="_blank" rel="noopener noreferrer">Global Initiative on Sharing All Influenza Data</a>
* **NCBI (INSDC)** — <a href="https://academic.oup.com/nar/advance-article-abstract/doi/10.1093/nar/gkae1058/7899524" target="_blank" rel="noopener noreferrer">International Nucleotide Sequence Database Collaboration</a>
* **Pathoplexus** — <a href="https://pathoplexus.org/" target="_blank" rel="noopener noreferrer">Pathoplexus.org</a>

Legend: 🟢 = meets | 🟡 = partly/conditional | 🔴 = not met / not documented

---

## 2.1 Governance

| Operating Principle                         | GISAID                                      | NCBI (INSDC)                                   | Pathoplexus                                      |
| ------------------------------------------- | ------------------------------------------- | ---------------------------------------------- | ------------------------------------------------ |
| 2.1.1 Governance structure described        | 🟢 Detailed governance page with Scientific Advisory Council, Database Technical Group, and Compliance Board structure. Operated by Freunde von GISAID e.V., a registered German non-profit with formal board (President, Treasurer, Secretary). <a href="https://gisaid.org/about-us/governance/" target="_blank" rel="noopener noreferrer">[39]</a> <a href="https://gisaid.org/about-us/imprint-privacy/" target="_blank" rel="noopener noreferrer">[40]</a> | 🟢 Clear organizational structure: Computational Biology Branch, Information Engineering Branch, Information Resources Branch. Board of Scientific Counselors meets twice yearly. Part of NIH/NLM federal framework. <a href="https://www.ncbi.nlm.nih.gov/home/about/structure/" target="_blank" rel="noopener noreferrer">[42]</a> <a href="https://www.ncbi.nlm.nih.gov/home/about/bosc/" target="_blank" rel="noopener noreferrer">[43]</a>   | 🟢 Statutes + Executive & Scientific Advisory Board pages. <a href="https://pathoplexus.org/about/governance/pathoplexus-statutes" target="_blank" rel="noopener noreferrer">[21]</a>         |
| 2.1.2 Scientific/ethical advisory mechanism | 🟢 Scientific Advisory Council with named members, Terms of Reference, plus Compliance Board. <a href="https://gisaid.org/about-us/governance/" target="_blank" rel="noopener noreferrer">[39]</a> | 🟢 Board of Scientific Counselors reviews programs & research activities twice yearly. NIH Intramural Research Program framework. <a href="https://www.ncbi.nlm.nih.gov/home/about/bosc/" target="_blank" rel="noopener noreferrer">[43]</a> <a href="https://www.ncbi.nlm.nih.gov/home/about/mission/" target="_blank" rel="noopener noreferrer">[44]</a> | 🟢 Scientific Advisory Board + published guidelines & minutes. <a href="https://pathoplexus.org/about/governance/minutes" target="_blank" rel="noopener noreferrer">[18]</a>            |
| 2.1.3 Conflicts of interest declared        | 🟢 Compliance Board established 2022 to prevent conflicts & ensure transparency; independent oversight. <a href="https://gisaid.org/about-us/governance/" target="_blank" rel="noopener noreferrer">[39]</a>                    | 🟢 Federal agency governance under NIH/HHS framework with established conflict of interest policies, FOIA compliance, and ethics oversight. <a href="https://www.ncbi.nlm.nih.gov/home/about/mission/" target="_blank" rel="noopener noreferrer">[44]</a>                           | 🟢 Board guidelines note governance; minutes list decisions; COI handling in statutes. <a href="https://pathoplexus.org/about/governance/pathoplexus-statutes" target="_blank" rel="noopener noreferrer">[21]</a>               |
| 2.1.4 Legal location & jurisdiction stated  | 🟢 German non-profit (Munich, Federal Republic of Germany); DAA specifies German law/arbitration. District Court Munich Association Register VR204844. <a href="https://gisaid.org/terms-of-use/" target="_blank" rel="noopener noreferrer">[2]</a> <a href="https://gisaid.org/about-us/imprint-privacy/" target="_blank" rel="noopener noreferrer">[40]</a>   | 🟢 US federal agency: National Library of Medicine, National Institutes of Health, 8600 Rockville Pike, Bethesda, MD 20894. Clear federal jurisdiction. <a href="https://www.ncbi.nlm.nih.gov/home/about/mission/" target="_blank" rel="noopener noreferrer">[44]</a>           | 🟢 Swiss non-profit; contact & banking jurisdiction; values/statutes public. <a href="https://pathoplexus.org/about/governance/pathoplexus-statutes" target="_blank" rel="noopener noreferrer">[21]</a> |

---

## 2.2 Transparency

| Operating Principle                                  | GISAID                        | NCBI (INSDC)                  | Pathoplexus                       |
| ---------------------------------------------------- | ----------------------------- | ----------------------------- | --------------------------------- |
| 2.2.1 Funding sources declared                             | 🟢 Comprehensive funding page lists major grants and donors (2007-2030): Singapore A*STAR $15M SGD (2025-2030), Rockefeller Foundation $5.2M (2021-2024), European Commission, APHL, Max-Planck, Swiss Federation, US HHS. <a href="https://gisaid.org/about-us/grants-and-donations/" target="_blank" rel="noopener noreferrer">[41]</a>                     | 🟢 Federal funding through NIH/NLM appropriations. Established by Congressional legislation (Claude Pepper, 1988). Clear federal agency funding structure. <a href="https://www.ncbi.nlm.nih.gov/home/about/mission/" target="_blank" rel="noopener noreferrer">[44]</a>       | 🟢 Funding page (donations, non-profit status). <a href="https://pathoplexus.org/about/funding" target="_blank" rel="noopener noreferrer">[23]</a> |
| 2.2.2 Governance team listed                               | 🟢 Scientific Advisory Council, Database Technical Group, and Compliance Board members all named with affiliations. <a href="https://gisaid.org/about-us/governance/" target="_blank" rel="noopener noreferrer">[39]</a>         | 🟢 Clear organizational leadership: Branch heads for CBB, IEB, IRB. Board of Scientific Counselors membership public. Research staff profiles available. <a href="https://www.ncbi.nlm.nih.gov/home/about/structure/" target="_blank" rel="noopener noreferrer">[42]</a> <a href="https://www.ncbi.nlm.nih.gov/home/about/bosc/" target="_blank" rel="noopener noreferrer">[43]</a>   | 🟢 Executive Board/SAB pages. <a href="https://pathoplexus.org/about/governance" target="_blank" rel="noopener noreferrer">[24]</a>   |
| 2.2.3 Meeting minutes public                               | 🔴 Governance structure detailed but meeting minutes not published. <a href="https://gisaid.org/about-us/governance/" target="_blank" rel="noopener noreferrer">[39]</a>               | 🟡 Board of Scientific Counselors meets twice yearly; meeting minutes not published publicly. Refer to Federal Register for meeting status. <a href="https://www.ncbi.nlm.nih.gov/home/about/bosc/" target="_blank" rel="noopener noreferrer">[43]</a>       | 🟢 Minutes published (General Assembly & Board). <a href="https://pathoplexus.org/about/governance/minutes" target="_blank" rel="noopener noreferrer">[18]</a>        |
| 2.2.4 Public data policy (scope, curation, AI use, access) | 🟢 DAA & FAQs detail access/redistribution rules. <a href="https://gisaid.org/terms-of-use/" target="_blank" rel="noopener noreferrer">[2]</a>                   | 🟢 Data/submit/help docs across INSDC. <a href="https://www.ncbi.nlm.nih.gov/home/submit/" target="_blank" rel="noopener noreferrer">[28]</a> | 🟢 Terms, submission/processing docs, API docs. <a href="https://pathoplexus.org/about/governance/data-submission" target="_blank" rel="noopener noreferrer">[19]</a>     |
| 2.2.5 Scientific advice public                             | 🟢 Scientific Advisory Council Terms of Reference published; members & expertise detailed. <a href="https://gisaid.org/about-us/governance/" target="_blank" rel="noopener noreferrer">[39]</a>               | 🟡 Refer to Federal Register for meeting status. <a href="https://www.ncbi.nlm.nih.gov/home/about/bosc/" target="_blank" rel="noopener noreferrer">[43]</a>       | 🟢 SAB guidelines & minutes. <a href="https://pathoplexus.org/about/governance/minutes" target="_blank" rel="noopener noreferrer">[18]</a>     |
| 2.2.6 Full description of data/metadata scope              | 🟢 Platform pages & help describe databases (EpiFlu/EpiCoV/EpiRSV/EpiPox). <a href="https://gisaid.org/" target="_blank" rel="noopener noreferrer">[1]</a> | 🟢 Comprehensive scope: GenBank DNA sequences, OMIM, MMDB protein structures, Gene Maps, Taxonomy, CGAP. Multiple databases with detailed documentation. <a href="https://www.ncbi.nlm.nih.gov/home/about/programs/" target="_blank" rel="noopener noreferrer">[45]</a>     | 🟢 Metadata fields & organisms listed. <a href="https://pathoplexus.org/api-documentation" target="_blank" rel="noopener noreferrer">[17]</a>             |
| 2.2.7 Auditable change trail                               | 🟡 Accession history exists; public change logs not emphasized. <a href="https://gisaid.org/" target="_blank" rel="noopener noreferrer">[1]</a>   | 🟢 Accession/versioning standard across INSDC; sequence updates tracked. <a href="https://www.ncbi.nlm.nih.gov/books/NBK49541/#NucProtFAQ.7_if_a_sequence_has_been_upda" target="_blank" rel="noopener noreferrer">[46]</a>        | 🟢 SeqSets/DOIs + metadata fields include data-use terms & embargo until. <a href="https://pathoplexus.org/api-documentation" target="_blank" rel="noopener noreferrer">[17]</a>                |
| 2.2.8 Processing code public                               | 🔴 Proprietary platform; code not open. <a href="https://gisaid.org/" target="_blank" rel="noopener noreferrer">[1]</a>                 | 🟢 Many tools open (e.g., SRA-tools). <a href="https://github.com/ncbi/sra-tools" target="_blank" rel="noopener noreferrer">[29]</a>      | 🟢 Open API; stack and docs link to GitHub; open standards (Keycloak, LAPIS). <a href="https://github.com/pathoplexus" target="_blank" rel="noopener noreferrer">[47]</a>               |
| 2.2.9 Usage statistics published                           | 🟡 News updates; usage metrics not routinely posted. <a href="https://weekly.chinacdc.cn/en/article/doi/10.46234/ccdcw2021.255" target="_blank" rel="noopener noreferrer">[6]</a>                | 🟡 Some stats in partner papers/dashboards. <a href="https://www.ncbi.nlm.nih.gov/home/submit/" target="_blank" rel="noopener noreferrer">[28]</a>             | 🟡 Public status page; usage metrics not routine. <a href="https://pathoplexus.org/" target="_blank" rel="noopener noreferrer">[25]</a>        |
| 2.2.10 Contact info available                               | 🟢 Help & support pages. <a href="https://gisaid.org/" target="_blank" rel="noopener noreferrer">[1]</a>               | 🟢 Numerous help desks (SRA, Pathogens). <a href="https://submit.ncbi.nlm.nih.gov/about/sra/" target="_blank" rel="noopener noreferrer">[30]</a>                   | 🟢 Contact page & emails. <a href="https://pathoplexus.org/" target="_blank" rel="noopener noreferrer">[25]</a>              |

---

## 2.3 Infrastructure & Security

| Principle                 | GISAID         | NCBI (INSDC)                     | Pathoplexus                            |
| ------------------------- | -------------- | -------------------------------- | -------------------------------------- |
| 2.3.1 Infrastructure documented | 🟡 Not detailed publicly. <a href="https://gisaid.org/" target="_blank" rel="noopener noreferrer">[1]</a> | 🟢 Cloud availability & mirroring across nodes documented. <a href="https://www.ncbi.nlm.nih.gov/nucleotide/" target="_blank" rel="noopener noreferrer">[12]</a> | 🟡 Status + components (Keycloak, LAPIS) noted; infra details limited. <a href="https://pathoplexus.org/" target="_blank" rel="noopener noreferrer">[25]</a>                    |
| 2.3.2 Cybersecurity policy      | 🟡 Implicit via access/DAA; policy not posted. <a href="https://gisaid.org/terms-of-use/" target="_blank" rel="noopener noreferrer">[2]</a>     | 🟢 NIH/NCBI info-sec governance; not always on resource page. <a href="https://www.ncbi.nlm.nih.gov/nucleotide/" target="_blank" rel="noopener noreferrer">[12]</a>     | 🟡 Not a formal policy page; authentication stack described. <a href="https://pathoplexus.org/api-documentation" target="_blank" rel="noopener noreferrer">[17]</a> |
| 2.3.3 Resilience arrangements   | 🟡 Not public. <a href="https://gisaid.org/" target="_blank" rel="noopener noreferrer">[1]</a>   | 🟢 Global mirroring (INSDC) improves availability. <a href="https://www.ncbi.nlm.nih.gov/nucleotide/" target="_blank" rel="noopener noreferrer">[12]</a>   | 🟡 Public status; redundancies not detailed. <a href="https://pathoplexus.org/" target="_blank" rel="noopener noreferrer">[25]</a>                  |

---

## 2.4 Data Scope

| Principle                         | GISAID                     | NCBI (INSDC)            | Pathoplexus                   |
| --------------------------------- | -------------------------- | ----------------------- | ----------------------------- |
| 2.4.1 Pathogen scope flexible           | 🟢 Influenza, SARS-CoV-2, RSV, mpox; expands to priority threats. <a href="https://gisaid.org/" target="_blank" rel="noopener noreferrer">[1]</a>           | 🟢 Broad, organism-agnostic (all pathogens). <a href="https://www.ncbi.nlm.nih.gov/home/submit/" target="_blank" rel="noopener noreferrer">[28]</a>             | 🟢 Focused set (CCHFV, Ebola, RSV, mpox, etc.); can expand. <a href="https://pathoplexus.org/" target="_blank" rel="noopener noreferrer">[25]</a> |
| 2.4.2 Consensus genomes + methods       | 🟢 EpiFlu/EpiCoV accept assemblies; method notes in metadata. <a href="https://theiagenepi.zendesk.com/hc/en-us/articles/29490901886491-Download-data-and-upload-it-into-the-GISAID-data-repository" target="_blank" rel="noopener noreferrer">[31]</a>                 | 🟢 GenBank/NCBI Virus metadata; BioSample fields. <a href="https://ncbi.xyz" target="_blank" rel="noopener noreferrer">[32]</a>              | 🟢 Consensus sequences + metadata template per organism. <a href="https://pathoplexus.org/api-documentation" target="_blank" rel="noopener noreferrer">[17]</a>                    |
| 2.4.3 Raw reads possible                | 🟡 Generally not (steers to consensus); raw reads not primary here. <a href="https://gisaid.org/" target="_blank" rel="noopener noreferrer">[1]</a>                  | 🟢 SRA accepts raw reads. <a href="https://submit.ncbi.nlm.nih.gov/about/sra/" target="_blank" rel="noopener noreferrer">[30]</a> | 🟡 Consensus only; raw reads via INSDC linked. <a href="https://pathoplexus.org/about/governance/data-submission" target="_blank" rel="noopener noreferrer">[19]</a>              |
| 2.4.4 Metagenomes accepted              | 🟡 Limited; scope more targeted. <a href="https://gisaid.org/" target="_blank" rel="noopener noreferrer">[1]</a>                  | 🟢 SRA/GenBank handle metagenomic submissions. <a href="https://submit.ncbi.nlm.nih.gov/about/sra/" target="_blank" rel="noopener noreferrer">[30]</a>                   | 🟡 Focus on pathogen consensus; not metagenomes. <a href="https://pathoplexus.org/about/faq" target="_blank" rel="noopener noreferrer">[26]</a>                     |
| 2.4.5 Minimum metadata defined          | 🟢 Templates & submission help. <a href="https://theiagenepi.zendesk.com/hc/en-us/articles/29490901886491-Download-data-and-upload-it-into-the-GISAID-data-repository" target="_blank" rel="noopener noreferrer">[31]</a>                      | 🟢 BioSample templates & packages. <a href="https://ncbi.xyz" target="_blank" rel="noopener noreferrer">[32]</a>                   | 🟢 Required TSV schema per organism. <a href="https://pathoplexus.org/api-documentation" target="_blank" rel="noopener noreferrer">[17]</a>                         |
| 2.4.6 Optional rich metadata            | 🟢 Extended fields (e.g., epi/clinical) commonly used. <a href="https://theiagenepi.zendesk.com/hc/en-us/articles/29490901886491-Download-data-and-upload-it-into-the-GISAID-data-repository" target="_blank" rel="noopener noreferrer">[31]</a> | 🟢 Extensive optional fields via BioSample. <a href="https://ncbi.xyz" target="_blank" rel="noopener noreferrer">[32]</a>       | 🟢 Additional optional fields documented. <a href="https://pathoplexus.org/api-documentation" target="_blank" rel="noopener noreferrer">[17]</a>             |
| 2.4.7 Legal/ethical compliance          | 🟢 Access-controlled, non-public redistribution. <a href="https://gisaid.org/terms-of-use/" target="_blank" rel="noopener noreferrer">[2]</a>        | 🟢 HRRT & dbGaP policies for sensitive data. <a href="https://ncbiinsights.ncbi.nlm.nih.gov/2023/02/02/scrubbing-human-sequences-sra-submissions/" target="_blank" rel="noopener noreferrer">[16]</a>           | 🟢 Terms flag non-sensitive metadata; no PHI; embargo option. <a href="https://pathoplexus.org/about/terms-of-use/data-use-terms" target="_blank" rel="noopener noreferrer">[22]</a>    |
| 2.4.8 Analytic/biologic metadata linked | 🟢 Variant/lineage tools & EPI_SET. <a href="https://gisaid.org/" target="_blank" rel="noopener noreferrer">[1]</a>          | 🟢 NCBI Virus filters/dashboards + links. <a href="https://www.ncbi.nlm.nih.gov/home/submit/" target="_blank" rel="noopener noreferrer">[28]</a>  | 🟢 LAPIS query engines & SeqSets/DOIs. <a href="https://pathoplexus.org/api-documentation" target="_blank" rel="noopener noreferrer">[17]</a>        |

---

## 2.5 Data Submission

| Principle                  | GISAID       | NCBI (INSDC)             | Pathoplexus           |
| -------------------------- | ------------ | ------------------------ | --------------------- |
| 2.5.1 Manual & automated uploads | 🟢 Batch GUI; some scripted clients exist for users. <a href="https://theiagenepi.zendesk.com/hc/en-us/articles/29490901886491-Download-data-and-upload-it-into-the-GISAID-data-repository" target="_blank" rel="noopener noreferrer">[31]</a>        | 🟢 Web forms, spreadsheets, fully automated XML; multiple transfer protocols. <a href="https://www.ncbi.nlm.nih.gov/home/submit/" target="_blank" rel="noopener noreferrer">[28]</a>       | 🟢 Web GUI + authenticated API; demo instance. <a href="https://pathoplexus.org/api-documentation" target="_blank" rel="noopener noreferrer">[17]</a>           |
| 2.5.2 Interfaces documented      | 🟢 Submission walkthroughs exist. <a href="https://theiagenepi.zendesk.com/hc/en-us/articles/29490901886491-Download-data-and-upload-it-into-the-GISAID-data-repository" target="_blank" rel="noopener noreferrer">[31]</a>  | 🟢 Detailed portal & help docs. <a href="https://submit.ncbi.nlm.nih.gov/about/sra/" target="_blank" rel="noopener noreferrer">[30]</a>       | 🟢 Step-by-step docs & Swagger. <a href="https://pathoplexus.org/api-documentation" target="_blank" rel="noopener noreferrer">[17]</a>    |
| 2.5.3 Submission training        | 🟢 Help/FAQ & community docs. <a href="https://theiagenepi.zendesk.com/hc/en-us/articles/29490901886491-Download-data-and-upload-it-into-the-GISAID-data-repository" target="_blank" rel="noopener noreferrer">[31]</a>       | 🟢 Extensive tutorials & help. <a href="https://submit.ncbi.nlm.nih.gov/about/sra/" target="_blank" rel="noopener noreferrer">[30]</a>              | 🟢 How-to docs. <a href="https://pathoplexus.org/about/faq" target="_blank" rel="noopener noreferrer">[26]</a>       |
| 2.5.4 Turnaround time published  | 🟡 Curation occurs; timelines not routinely posted. <a href="https://gisaid.org/" target="_blank" rel="noopener noreferrer">[1]</a> | 🟢 Immediate on release (or per embargo), varies by repo; policies documented. <a href="https://ena-docs.readthedocs.io/" target="_blank" rel="noopener noreferrer">[33]</a> | 🟢 Immediate post-approval; INSDC onward submission described. <a href="https://pathoplexus.org/about/governance/data-submission" target="_blank" rel="noopener noreferrer">[19]</a> |

---

## 2.6 Data Curation

| Principle                 | GISAID               | NCBI (INSDC) | Pathoplexus                |
| ------------------------- | -------------------- | ------------ | -------------------------- |
| 2.6.1 Public curation policy    | 🟡 Quality checks noted during submission; policy not centralized. <a href="https://theiagenepi.zendesk.com/hc/en-us/articles/29490901886491-Download-data-and-upload-it-into-the-GISAID-data-repository" target="_blank" rel="noopener noreferrer">[31]</a>            | 🟢 Extensive QC & processing docs per resource. <a href="https://www.ncbi.nlm.nih.gov/home/submit/" target="_blank" rel="noopener noreferrer">[28]</a>   | 🟢 "Data Submission & Processing" page. <a href="https://pathoplexus.org/about/governance/data-submission" target="_blank" rel="noopener noreferrer">[19]</a>                |
| 2.6.2 Verify host-read removal  | 🟡 Raw reads generally not hosted. <a href="https://gisaid.org/" target="_blank" rel="noopener noreferrer">[1]</a>                | 🟢 HRRT tooling/service for SRA. <a href="https://ncbiinsights.ncbi.nlm.nih.gov/2023/02/02/scrubbing-human-sequences-sra-submissions/" target="_blank" rel="noopener noreferrer">[16]</a>  | 🟡 Consensus only; advises linking raw reads via INSDC. <a href="https://pathoplexus.org/about/governance/data-submission" target="_blank" rel="noopener noreferrer">[19]</a>           |
| 2.6.3 Low-quality data handling | 🟡 Curators may flag/correct; limited public detail. <a href="https://gisaid.org/" target="_blank" rel="noopener noreferrer">[1]</a> | 🟢 QC flags & filtering vary by resource. <a href="https://www.ncbi.nlm.nih.gov/home/submit/" target="_blank" rel="noopener noreferrer">[28]</a>   | 🟢 Pipeline adds flags; submitter approval step before release. <a href="https://pathoplexus.org/about/governance/data-submission" target="_blank" rel="noopener noreferrer">[19]</a> |

---

## 2.7 Data Provenance

| Principle                     | GISAID                        | NCBI (INSDC)                 | Pathoplexus                   |
| ----------------------------- | ----------------------------- | ---------------------------- | ----------------------------- |
| 2.7.1 Accepts primary/imported data | 🟢 Primary submissions; does not mirror INSDC; unique repository. <a href="https://gisaid.org/" target="_blank" rel="noopener noreferrer">[1]</a>                | 🟢 Mirrors between INSDC nodes. <a href="https://www.ncbi.nlm.nih.gov/nucleotide/" target="_blank" rel="noopener noreferrer">[12]</a>              | 🟢 Accepts direct submissions; also pushes to INSDC. <a href="https://pathoplexus.org/about/governance/data-submission" target="_blank" rel="noopener noreferrer">[19]</a> |
| 2.7.2 Full attribution chain        | 🟢 Originating/Submitting lab attribution required. <a href="https://gisaid.org/" target="_blank" rel="noopener noreferrer">[1]</a> | 🟢 BioSample/BioProject linkage + accessions. <a href="https://www.ncbi.nlm.nih.gov/home/submit/" target="_blank" rel="noopener noreferrer">[28]</a> | 🟢 Metadata fields + SeqSets & DOIs for citation. <a href="https://pathoplexus.org/api-documentation" target="_blank" rel="noopener noreferrer">[17]</a>   |
| 2.7.3 Cross-references IDs          | 🟡 EPI ISL IDs; cross-links limited outside GISAID. <a href="https://gisaid.org/" target="_blank" rel="noopener noreferrer">[1]</a>             | 🟢 Cross-references via accessions across nodes/tools. <a href="https://www.ncbi.nlm.nih.gov/nucleotide/" target="_blank" rel="noopener noreferrer">[12]</a>           | 🟢 INSDC accessions included; onward submission policy. <a href="https://pathoplexus.org/about/governance/data-submission" target="_blank" rel="noopener noreferrer">[19]</a>         |

---

## 2.8 Access

| Principle                  | GISAID                      | NCBI (INSDC)   | Pathoplexus                  |
| -------------------------- | --------------------------- | -------------- | ---------------------------- |
| 2.8.1 Free & open access         | 🟡 Free but governed by DAA; no redistribution to non-users; collaboration/acknowledgement clauses. <a href="https://gisaid.org/terms-of-use/" target="_blank" rel="noopener noreferrer">[2]</a> | 🟢 Free, open, unrestricted reuse per INSDC policy. <a href="https://datascience.codata.org/articles/10.5334/dsj-2024-029/" target="_blank" rel="noopener noreferrer">[34]</a>  | 🟢 Free access; Open vs Restricted-Use clearly documented (embargo ≤1 yr). <a href="https://pathoplexus.org/about/terms-of-use/data-use-terms" target="_blank" rel="noopener noreferrer">[22]</a> |
| 2.8.2 GUI & API                  | 🟡 GUI; programmatic access limited/third-party wrappers for credentialed users. <a href="https://rdrr.io/github/Wytamma/GISAIDR/f/README.md" target="_blank" rel="noopener noreferrer">[35]</a>                  | 🟢 GUI & robust APIs (E-utilities; programmatic). <a href="https://www.ncbi.nlm.nih.gov/home/submit/" target="_blank" rel="noopener noreferrer">[28]</a>  | 🟢 Web + documented APIs (LAPIS & backend). <a href="https://pathoplexus.org/api-documentation" target="_blank" rel="noopener noreferrer">[17]</a>            |
| 2.8.3 Account approval timelines | 🟡 Registration vetting; no SLA posted; suspensions described. <a href="https://gisaid.org/terms-of-use/" target="_blank" rel="noopener noreferrer">[2]</a>             | 🟢 Not applicable (open). <a href="https://datascience.codata.org/articles/10.5334/dsj-2024-029/" target="_blank" rel="noopener noreferrer">[34]</a> | 🟢 Data view is open; submit/upload requires account; no long vetting delays described. <a href="https://pathoplexus.org/" target="_blank" rel="noopener noreferrer">[25]</a>         |

---

## 2.9 Interoperability

| Principle                 | GISAID         | NCBI (INSDC)          | Pathoplexus            |
| ------------------------- | -------------- | --------------------- | ---------------------- |
| 2.9.1 Interoperable with others | 🟡 Access limited to authorized users; onward sharing constrained. <a href="https://gisaid.org/terms-of-use/" target="_blank" rel="noopener noreferrer">[2]</a>   | 🟢 High (open IDs/APIs; mirrored). <a href="https://www.ncbi.nlm.nih.gov/nucleotide/" target="_blank" rel="noopener noreferrer">[12]</a> | 🟢 High (open APIs; auto-forwarding to INSDC). <a href="https://pathoplexus.org/about/governance/data-submission" target="_blank" rel="noopener noreferrer">[19]</a>         |
| 2.9.2 API documented            | 🟡 No public general API; credentialed tools exist. <a href="https://rdrr.io/github/Wytamma/GISAIDR/f/README.md" target="_blank" rel="noopener noreferrer">[35]</a> | 🟢 E-utilities & resource-specific APIs. <a href="https://www.ncbi.nlm.nih.gov/home/submit/" target="_blank" rel="noopener noreferrer">[28]</a>         | 🟢 API documentation + Swagger UI. <a href="https://pathoplexus.org/api-documentation" target="_blank" rel="noopener noreferrer">[17]</a>         |
| 2.9.3 Standards in place        | 🟡 Internal; FAIR page describes approach; not open schemas. <a href="https://gisaid.org/help/fair-principles/" target="_blank" rel="noopener noreferrer">[3]</a>  | 🟢 INSDC schemas & standards. <a href="https://www.ncbi.nlm.nih.gov/nucleotide/" target="_blank" rel="noopener noreferrer">[12]</a>       | 🟢 LAPIS/JSON/NDJSON; machine-readable data-use fields. <a href="https://pathoplexus.org/api-documentation" target="_blank" rel="noopener noreferrer">[17]</a> |

---

## 2.10 Data Use & Benefit Sharing

| Principle                 | GISAID                    | NCBI (INSDC)           | Pathoplexus                        |
| ------------------------- | ------------------------- | ---------------------- | ---------------------------------- |
| 2.10.1 User code of practice     | 🟢 DAA governs use; suspensions described. <a href="https://gisaid.org/terms-of-use/" target="_blank" rel="noopener noreferrer">[2]</a>                     | 🟢 Open use; general terms under agency policies. <a href="https://datascience.codata.org/articles/10.5334/dsj-2024-029/" target="_blank" rel="noopener noreferrer">[34]</a>      | 🟢 Data Use Terms + governance processes. <a href="https://pathoplexus.org/about/terms-of-use/data-use-terms" target="_blank" rel="noopener noreferrer">[22]</a>                   |
| 2.10.2 Explicit licence          | 🟢 DAA with explicit restrictions (no redistribution to non-users; acknowledge; collaborate). <a href="https://gisaid.org/terms-of-use/" target="_blank" rel="noopener noreferrer">[2]</a>        | 🟢 Effectively public-domain/CC0-like for most archives (no use restrictions). <a href="https://datascience.codata.org/articles/10.5334/dsj-2024-029/" target="_blank" rel="noopener noreferrer">[34]</a>        | 🟢 Open vs Restricted-Use terms; embargo then becomes Open; SeqSet DOIs. <a href="https://pathoplexus.org/about/terms-of-use/data-use-terms" target="_blank" rel="noopener noreferrer">[22]</a>         |
| 2.10.3 Compliance mechanisms     | 🟡 User vetting & compliance team; machine-readable licences not advertised. <a href="https://gisaid.org/terms-of-use/" target="_blank" rel="noopener noreferrer">[2]</a>        | 🟢 Accessions & open licences enable automated reuse. <a href="https://datascience.codata.org/articles/10.5334/dsj-2024-029/" target="_blank" rel="noopener noreferrer">[34]</a> | 🟢 Metadata columns include dataUseTerms, dataUseTermsRestrictedUntil, dataUseTermsUrl. <a href="https://pathoplexus.org/about/terms-of-use/data-use-terms" target="_blank" rel="noopener noreferrer">[22]</a>          |
| 2.10.4 Benefit-sharing framework | 🟢 Strong acknowledgement/collab expectations. <a href="https://gisaid.org/terms-of-use/" target="_blank" rel="noopener noreferrer">[2]</a> | 🟡 Benefits flow via open science; no formal reciprocity terms. <a href="https://datascience.codata.org/articles/10.5334/dsj-2024-029/" target="_blank" rel="noopener noreferrer">[34]</a>      | 🟢 Explicit authorship/acknowledgement rules for Restricted-Use; pushes to INSDC for openness. <a href="https://pathoplexus.org/about/terms-of-use/data-use-terms" target="_blank" rel="noopener noreferrer">[22]</a> |

---

## 2.11 Analytical & Reporting Capabilities

| Principle                        | GISAID                      | NCBI (INSDC)            | Pathoplexus           |
| -------------------------------- | --------------------------- | ----------------------- | --------------------- |
| 2.11.1 Integrated search/filter         | 🟢 EpiCoV/EpiPox search, EPI_SET, lineage/variant views. <a href="https://gisaid.org/" target="_blank" rel="noopener noreferrer">[1]</a> | 🟢 NCBI Virus & Pathogen Detection browsers with rich filters. <a href="https://www.ncbi.nlm.nih.gov/home/submit/" target="_blank" rel="noopener noreferrer">[28]</a> | 🟢 LAPIS search engines & organism browsers. <a href="https://pathoplexus.org/api-documentation" target="_blank" rel="noopener noreferrer">[17]</a>        |
| 2.11.2 Summaries (geographic, temporal) | 🟢 Regular dashboards/visualizations. <a href="https://datascience.codata.org/articles/10.5334/dsj-2024-029/" target="_blank" rel="noopener noreferrer">[36]</a>                | 🟢 Dashboards & visual filters in NCBI Virus. <a href="https://www.ncbi.nlm.nih.gov/home/submit/" target="_blank" rel="noopener noreferrer">[28]</a>      | 🟢 On-site summaries per pathogen; status/news. <a href="https://pathoplexus.org/" target="_blank" rel="noopener noreferrer">[25]</a>  |
| 2.11.3 Analysis tools documented & version-controlled         | 🟡 Tools are platform-embedded; versioning not publicly tracked. <a href="https://gisaid.org/" target="_blank" rel="noopener noreferrer">[1]</a>                | 🟢 Docs for browsers/tools maintained. <a href="https://www.ncbi.nlm.nih.gov/home/submit/" target="_blank" rel="noopener noreferrer">[28]</a>            | 🟢 API & backend docs; explicit "under continuous development." <a href="https://pathoplexus.org/api-documentation" target="_blank" rel="noopener noreferrer">[17]</a> |

---

## 2.12 Sustainability

| Principle               | GISAID                    | NCBI (INSDC)              | Pathoplexus                      |
| ----------------------- | ------------------------- | ------------------------- | -------------------------------- |
| 2.12.1 Clear value proposition | 🟢 Long-standing mission (influenza → broader pathogens). <a href="https://weekly.chinacdc.cn/en/article/doi/10.46234/ccdcw2021.255" target="_blank" rel="noopener noreferrer">[37]</a> | 🟢 Foundational public infrastructure for NSD. <a href="https://datascience.codata.org/articles/10.5334/dsj-2024-029/" target="_blank" rel="noopener noreferrer">[34]</a>        | 🟢 Values/statutes outline mission. <a href="https://pathoplexus.org/about/governance/values" target="_blank" rel="noopener noreferrer">[20]</a>  |
| 2.12.2 Business/funding model  | 🟡 Donor-supported non-profit; details limited publicly. <a href="https://gisaid.org/" target="_blank" rel="noopener noreferrer">[1]</a>         | 🟢 Public funding across three nodes. <a href="https://datascience.codata.org/articles/10.5334/dsj-2024-029/" target="_blank" rel="noopener noreferrer">[34]</a>       | 🟢 Donation-supported; seeking institutional partnerships. <a href="https://pathoplexus.org/about/funding" target="_blank" rel="noopener noreferrer">[23]</a>         |
| 2.12.3 Scalability plan        | 🟡 Not detailed publicly. <a href="https://gisaid.org/" target="_blank" rel="noopener noreferrer">[1]</a>              | 🟢 Decades-scale archives; global mirroring. <a href="https://www.ncbi.nlm.nih.gov/nucleotide/" target="_blank" rel="noopener noreferrer">[12]</a> | 🟡 Early-stage; infrastructure components public, plan evolving. <a href="https://pathoplexus.org/about/governance" target="_blank" rel="noopener noreferrer">[24]</a>                     |
| 2.12.4 Data lifecycle policy   | 🟡 Not centrally published. <a href="https://gisaid.org/" target="_blank" rel="noopener noreferrer">[1]</a>           | 🟢 Standard archival lifecycle across INSDC. <a href="https://ena-docs.readthedocs.io/" target="_blank" rel="noopener noreferrer">[33]</a>            | 🟢 Terms include onward INSDC deposit and embargo expiry. <a href="https://pathoplexus.org/about/terms-of-use/data-use-terms" target="_blank" rel="noopener noreferrer">[22]</a> |
| 2.12.5 Collaboration plan      | 🟢 Collaborates with GISRS & WHO activities. <a href="https://www.who.int/initiatives/pandemic-preparedness-and-response-accord" target="_blank" rel="noopener noreferrer">[38]</a>       | 🟢 Multilateral collaboration at scale. <a href="https://www.ncbi.nlm.nih.gov/nucleotide/" target="_blank" rel="noopener noreferrer">[12]</a>   | 🟢 Member-run governance; open minutes. <a href="https://pathoplexus.org/about/governance" target="_blank" rel="noopener noreferrer">[24]</a>       |
| 2.12.6 Environmental plan      | 🔴 Not published. <a href="https://gisaid.org/" target="_blank" rel="noopener noreferrer">[1]</a>             | 🟡 Not typically published per resource. <a href="https://www.ncbi.nlm.nih.gov/home/submit/" target="_blank" rel="noopener noreferrer">[28]</a>                 | 🔴 Not published. <a href="https://pathoplexus.org/" target="_blank" rel="noopener noreferrer">[25]</a>                    |

---

# Summary Highlights

* **GISAID**: excels at **equitable benefit sharing** with significantly **improved governance transparency** (2022-2024), including detailed advisory council structure and compliance oversight, but **limited open interoperability**.
* **NCBI (INSDC)**: best satisfies **open access, standardization, and data integrity** requirements.
* **Pathoplexus**: most transparent, **open governance with minutes**, **machine-readable licences**, and bridges openness with early data protection.

---

# Citations

### GISAID

* <a href="https://gisaid.org/register/" target="_blank" rel="noopener noreferrer">GISAID – Register (DAA)</a>
* <a href="https://gisaid.org/terms-of-use/" target="_blank" rel="noopener noreferrer">Terms of Use / DAA</a>
* <a href="https://gisaid.org/help/fair-principles/" target="_blank" rel="noopener noreferrer">FAIR Principles</a>
* <a href="https://gisaid.org/" target="_blank" rel="noopener noreferrer">Homepage</a>
* <a href="https://gisaid.org/mpox-variants-dashboard/" target="_blank" rel="noopener noreferrer">Mpox Variants Dashboard</a>
* <a href="https://weekly.chinacdc.cn/en/article/doi/10.46234/ccdcw2021.255" target="_blank" rel="noopener noreferrer">China CDC Weekly on GISAID</a>
* <a href="https://datascience.codata.org/articles/10.5334/dsj-2024-029/" target="_blank" rel="noopener noreferrer">Data Science Journal (2024)</a>
* <a href="https://rdrr.io/github/Wytamma/GISAIDR/f/README.md" target="_blank" rel="noopener noreferrer">GISAIDR Client</a>
* <a href="https://theiagenepi.zendesk.com/hc/en-us/articles/29490901886491-Download-data-and-upload-it-into-the-GISAID-data-repository" target="_blank" rel="noopener noreferrer">TheiaGenEpi Guide</a>
* <a href="https://www.ecdc.europa.eu/en/publications-data/gisaid-acknowledgements" target="_blank" rel="noopener noreferrer">ECDC Acknowledgements</a>
* <a href="https://www.ecdc.europa.eu/en/publications-data/data-virus-variants-covid-19-eueea" target="_blank" rel="noopener noreferrer">ECDC Dataset (Variants)</a>
* <a href="https://gisaid.org/about-us/governance/" target="_blank" rel="noopener noreferrer">Governance Structure</a>
* <a href="https://gisaid.org/about-us/imprint-privacy/" target="_blank" rel="noopener noreferrer">Imprint & Legal Information</a>
* <a href="https://gisaid.org/about-us/grants-and-donations/" target="_blank" rel="noopener noreferrer">Grants and Donations</a>

### NCBI / INSDC

* <a href="https://academic.oup.com/nar/advance-article-abstract/doi/10.1093/nar/gkae1058/7899524" target="_blank" rel="noopener noreferrer">INSDC Overview (Nucleic Acids Research 2024)</a>
* <a href="https://www.ncbi.nlm.nih.gov/nucleotide/" target="_blank" rel="noopener noreferrer">NCBI Nucleotide Database</a>
* <a href="https://www.ncbi.nlm.nih.gov/books/NBK49541/#NucProtFAQ.7_if_a_sequence_has_been_upda" target="_blank" rel="noopener noreferrer">Nucleotide Sequence Updates & Versioning</a>
* <a href="https://www.ncbi.nlm.nih.gov/home/develop/api/" target="_blank" rel="noopener noreferrer">NCBI APIs (E-utilities)</a>
* <a href="https://www.ncbi.nlm.nih.gov/books/NBK25497/" target="_blank" rel="noopener noreferrer">E-utilities Guide</a>
* <a href="https://eutilities.github.io/site/Quick_Start/eu_quick/" target="_blank" rel="noopener noreferrer">E-utilities Quick Start</a>
* <a href="https://ncbiinsights.ncbi.nlm.nih.gov/2023/02/02/scrubbing-human-sequences-sra-submissions/" target="_blank" rel="noopener noreferrer">HRRT Overview</a>
* <a href="https://academic.oup.com/nar/article/51/D1/D121/6777773" target="_blank" rel="noopener noreferrer">ENA (Nucleic Acids Research 2023)</a>
* <a href="https://www.ncbi.nlm.nih.gov/home/submit/" target="_blank" rel="noopener noreferrer">NCBI Submit</a>
* <a href="https://github.com/ncbi/sra-tools" target="_blank" rel="noopener noreferrer">SRA Tools GitHub</a>
* <a href="https://submit.ncbi.nlm.nih.gov/about/sra/" target="_blank" rel="noopener noreferrer">SRA Submit</a>
* <a href="https://ncbi.xyz" target="_blank" rel="noopener noreferrer">NCBI XYZ</a>
* <a href="https://ncbi.xyz" target="_blank" rel="noopener noreferrer">ncbi.xyz</a>
* <a href="https://www.ncbi.nlm.nih.gov/home/about/structure/" target="_blank" rel="noopener noreferrer">NCBI Organizational Structure</a>
* <a href="https://www.ncbi.nlm.nih.gov/home/about/bosc/" target="_blank" rel="noopener noreferrer">Board of Scientific Counselors</a>
* <a href="https://www.ncbi.nlm.nih.gov/home/about/mission/" target="_blank" rel="noopener noreferrer">NCBI Mission</a>
* <a href="https://www.ncbi.nlm.nih.gov/home/about/programs/" target="_blank" rel="noopener noreferrer">NCBI Programs & Activities</a>
* <a href="https://ena-docs.readthedocs.io/" target="_blank" rel="noopener noreferrer">ENA Documentation</a>
* <a href="https://datascience.codata.org/articles/10.5334/dsj-2024-029/" target="_blank" rel="noopener noreferrer">Data Science Journal INSDC (2024)</a>
* <a href="https://rdrr.io/github/Wytamma/GISAIDR/f/README.md" target="_blank" rel="noopener noreferrer">GISAIDR R Package</a>

### Pathoplexus

* <a href="https://pathoplexus.org/api-documentation" target="_blank" rel="noopener noreferrer">API Documentation</a>
* <a href="https://pathoplexus.org/about/governance/minutes" target="_blank" rel="noopener noreferrer">Meeting Minutes</a>
* <a href="https://pathoplexus.org/about/governance/data-submission" target="_blank" rel="noopener noreferrer">Data Submission & Processing</a>
* <a href="https://pathoplexus.org/about/governance/values" target="_blank" rel="noopener noreferrer">Values</a>
* <a href="https://pathoplexus.org/about/governance/pathoplexus-statutes" target="_blank" rel="noopener noreferrer">Statutes</a>
* <a href="https://pathoplexus.org/about/terms-of-use/data-use-terms" target="_blank" rel="noopener noreferrer">Data Use Terms</a>
* <a href="https://pathoplexus.org/about/funding" target="_blank" rel="noopener noreferrer">Funding Page</a>
* <a href="https://pathoplexus.org/about/governance" target="_blank" rel="noopener noreferrer">Governance Hub</a>
* <a href="https://pathoplexus.org/" target="_blank" rel="noopener noreferrer">Home Page</a>
* <a href="https://pathoplexus.org/about/faq" target="_blank" rel="noopener noreferrer">FAQ</a>
* <a href="https://github.com/pathoplexus" target="_blank" rel="noopener noreferrer">GitHub Repository</a>

### Additional References

* <a href="https://datascience.codata.org/articles/10.5334/dsj-2024-029/" target="_blank" rel="noopener noreferrer">Data Science Journal Open Science (2024)</a>
* <a href="https://weekly.chinacdc.cn/en/article/doi/10.46234/ccdcw2021.255" target="_blank" rel="noopener noreferrer">WHO China CDC Weekly</a>
* <a href="https://www.who.int/initiatives/pandemic-preparedness-and-response-accord" target="_blank" rel="noopener noreferrer">WHO Pandemic Accord</a>
* <a href="https://www.ncbi.nlm.nih.gov/books/NBK49541/#NucProtFAQ.7_if_a_sequence_has_been_upda" target="_blank" rel="noopener noreferrer">Nucleotide Sequence Updates & Versioning</a>
* <a href="https://github.com/pathoplexus" target="_blank" rel="noopener noreferrer">Pathoplexus GitHub Repository</a>

---
