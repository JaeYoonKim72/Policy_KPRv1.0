# Korean Pangenome Reference (KPR) Data Access Policy

*Version 1.0 — Effective 26 November 2026*

## Data Access Committee

**Name:** KRIBB Genomic Medicine Research Center Data Access Committee  
**EGA accession:** [EGAC50000001142](https://ega-archive.org/dacs/EGAC50000001142)  
**Institution:** Genomic Medicine Research Center, Korea Research Institute of Bioscience and Biotechnology (KRIBB), 125 Gwahak-ro, Yuseong-gu, Daejeon 34141, Republic of Korea  
**Contact:** Jae-Yoon Kim (jaeyoonkim@kribb.re.kr)

## Scope

This policy governs access to the controlled-access genomic resources generated for the Korean Pangenome Reference (KPR):

1. **Raw sequencing data** — long-read whole-genome sequencing on the PacBio Revio and Oxford Nanopore PromethION platforms, together with Hi-C data, from 19 Korean individuals (EGA study [EGAS50000002074](https://ega-archive.org/studies/EGAS50000002074); dataset [EGAD50000002977](https://ega-archive.org/datasets/EGAD50000002977)).
2. **Genome assemblies** — polished genome assemblies from all 22 Korean individuals, including the three individuals sequenced using PacBio Sequel II in our previous study, being deposited under the same EGA study (EGAS50000002074; dataset accession pending). The 28 haplotype assemblies from 14 individuals retained after quality control were used to construct KPR.
3. **Pangenome graph files** — the KPR and HPRC+KPR graphs in GFA format, distributed through the [Korean Genome Research (KGR) project site](https://kgr.appex.kr/resource/data-download/). These graphs contain individual-level haplotype sequences and are therefore governed by the same access terms as the KOR genome assemblies from which they were constructed. The graphs can be reconstructed from the deposited KOR assemblies and the corresponding reference resources using the [publicly released construction pipeline](https://github.com/JaeYoonKim72/KPR-pipeline).

Participants gave written informed consent, and the work was approved by the Institutional Review Boards of Chungnam National University Hospital (CNUH 2019-06-034, including the previously sequenced three individuals), the Korea Research Institute of Bioscience and Biotechnology (KRIBB P01-202503-02-002), and Chungbuk National University Hospital (CBNUH 2025-07-011).

The earlier PacBio Sequel II raw-read dataset EGAD50000000552 (EGAS50000000375) remains subject to its own EGA access policy. Access to deposits at K-BDS follows the conditions applicable to those deposits.

## Research uses that will be approved

Access is granted for any research purpose, consistent with Data Use Ontology code DUO:0000042 (general research use), within the scope of the participants' informed consent and applicable ethical and regulatory requirements, provided the application satisfies all of the following:

- the work is non-commercial and conducted by a not-for-profit research institution (DUO:0000018);
- the applicant's institution holds ethics approval covering the proposed work (DUO:0000021);
- the proposed use is described as a specific project with defined aims and duration (DUO:0000027);
- the application identifies the researchers who will access the data and their institutional affiliations;
- the proposed storage and analysis environment satisfies the security requirements of this policy;
- the applicant's institution and named users sign the KPR Data Access Agreement (DAA).

Research areas expressly within scope include, but are not limited to: population and evolutionary genomics, including studies of ancestry and population history; construction and extension of pangenome and variant resources; development, benchmarking and validation of methods for assembly, graph construction, read mapping, variant calling and imputation; and health-related or biomedical research in which genomic variation is analysed.

Incorporation of these data into broader pangenome or variant resources is permitted within the scope of the approved project. Distribution of resulting resources containing individual-level KOR genomic data requires DAC approval and must be governed by access terms equivalent to this policy.

**Applications are not evaluated on scientific merit, novelty, research expertise, or whether the proposed work overlaps with that of the data producers.** The DAC assesses eligibility against the criteria above and nothing else.

## Research uses that will not be approved

- commercial or for-profit use of any kind;
- any attempt to identify individual research participants or their relatives;
- forensic, law-enforcement, insurance, employment or marketing use;
- redistribution of the data to any party not named in the approved application, except where separately approved by the DAC under equivalent access terms;
- use beyond the scope of the approved project without further DAC approval.

## How to apply

Applications are submitted through the EGA data-access request system from the relevant dataset page. The Data Access Agreement ([Word](KPR_Data_Access_Agreement.docx), [PDF](KPR_Data_Access_Agreement.pdf)) and [application checklist](KPR_Application_Checklist.md) are published in this repository. Supporting documents are submitted privately to the DAC contact by email.

An application must include a detailed research proposal describing the project, its aims and duration, the requested resources, the named individuals who will access the data and their institutional affiliations, the institution's ethics approval, and the secure environment in which the data will be held and analysed.

Each individual requesting access to data through EGA must have an individual EGA account and submit an access request. The applicant's institution and named users must sign the KPR Data Access Agreement before access is granted. No second research proposal is required for graph delivery following approval covering the KOR assemblies.

## Review mechanism and timeline

The DAC comprises five members of the Genomic Medicine Research Center at KRIBB. Applications are reviewed against the eligibility criteria above; a decision requires the agreement of at least three of the five members. Members with a conflict of interest must recuse themselves. If fewer than three non-conflicted members are available, the DAC must arrange a qualified replacement or alternative review in accordance with institutional rules before issuing a decision, and notify the applicant of any resulting delay.

| Step | Target |
| --- | --- |
| Acknowledgement of receipt | 5 working days |
| Decision on a complete application | 10 working days |
| Access provisioned after approval and receipt of the signed agreement | 5 working days |
| Download link for pangenome graph files following verification of existing approval | 2 working days |

Working days are working days in the Republic of Korea. A complete application includes all documents and information specified in the checklist, including a signed DAA. If further information is required, the applicant is notified within the acknowledgement period, and the decision period restarts when the requested information is received. The DAC informs the applicant of any exceptional delay and the expected decision date.

The decision is communicated in writing. If an application is refused, the DAC provides reasons with reference to the eligibility criteria. Following approval and receipt of the signed DAA, access permissions for the approved EGA datasets are granted through the EGA DAC Portal.

Approved access is granted for one year. Access may be renewed for further one-year periods on request; renewal requires only written confirmation that the approved project, named users, ethics approval and secure environment remain unchanged and valid, and is handled within the same timeline. A material change requires a new application or DAC-approved amendment before the change takes effect.

Upon expiration of the approved period, unless renewed, access permissions are withdrawn; retention or deletion of downloaded data is governed by the DAA.

An applicant may request reconsideration of a refusal by writing to the DAC contact within 30 days. The DAC will reconsider the application in light of additional information or clarification provided by the applicant.

## Access to pangenome graph files

Approved applicants whose current DAC approval covers the KOR genome assemblies may obtain the KPR and HPRC+KPR GFA files from the [KGR data download page](https://kgr.appex.kr/resource/data-download/). This procedure will apply once the assembly dataset and revised KGR download workflow are available.

The applicant submits a short form giving their name, institutional affiliation, the email address associated with their EGA account and DAC approval, and the requested graph file. A DAC approval reference may optionally be provided, if available. No separate EGA-generated approval number is required. Following verification of the applicant's current access permissions, a download link is sent to the approved email address within two working days.

**This step is an identity and access-permission check, not a second review.** It confirms that the requester is named in a current approval covering the KOR assemblies. No additional application, justification or assessment of the proposed research is carried out, and a valid request from an approved applicant is not refused. Graph use remains within the approved project and DAA.

The download link is valid for up to seven days, or until DAC approval expires or is revoked, whichever occurs earlier. Applicants may request a new download link while their approval remains valid. Downloading the genome assembly files from EGA is not a prerequisite for obtaining the graph files. Information submitted through the form is used solely to verify and fulfil the request. Technical issues may be directed to durud103@kribb.re.kr; access-policy enquiries should be directed to jaeyoonkim@kribb.re.kr.

Applicants who prefer not to use the project site may reconstruct the graphs from the deposited KOR assemblies and corresponding reference resources using the publicly released construction pipeline.

## Conditions of use

Data accessed under this policy must be held and analysed in a secure environment restricted to named, approved users. The applicant institution must maintain individual user accounts, appropriate authentication and access controls, secure transfer and storage, and procedures to prevent unauthorized access, disclosure or loss. Controlled files and derivatives containing individual-level data must not be placed in public repositories or shared with parties not named in the approved application unless separately authorized by the DAC.

Data must not be used to identify individual research participants or their relatives, nor for forensic, law-enforcement, insurance, employment or marketing purposes. Any use beyond the approved project requires further DAC approval. Users must promptly notify the DAC of unauthorized access, loss, disclosure or other security incidents and cooperate in their resolution.

Aggregate research results that do not disclose identifiable individual-level genomic information may be published or shared within the approved project scope and applicable ethical requirements, subject to the publication provisions below.

## Publication moratorium and acknowledgement

The publication moratorium ends upon the first publication of the primary KPR study or 12 months after the original KPR data were first made available, whichever occurs earlier. Subsequent deposits under this policy do not restart the moratorium. Prior to the end of this period, manuscripts based on these data may be submitted for publication with written consent from KRIBB.

**Following the end of the moratorium, no further publication embargo or publication-related approval from KRIBB or the DAC is required for research conducted within the scope of the approved project.** Results derived from these data must acknowledge the source study and cite the EGA study and relevant dataset accession numbers.

The DAC will remove the publication moratorium designation (DUO:0000024) from the corresponding EGA policy and update its text when the moratorium ends. The remaining conditions, including participant privacy protection and restrictions on individual-level data redistribution, continue to apply.

## Openly available resources

The following are available without application to the DAC:

- the [analysis pipelines and methods documentation](https://github.com/JaeYoonKim72/KPR-pipeline), under the MIT License;
- the supplementary tables published with the primary study, including the gene annotation and copy-number results, the catalogue of AMY structural haplotypes, pangenome graph statistics, non-reference sequence summaries, and variant-calling benchmarks.

Individual-level data — raw reads, genome assemblies, and pangenome graph files carrying per-sample haplotype paths — remain under controlled access because they contain sequence from which individual research participants could be identified.

## Data Use Ontology (DUO) codes

| Code | Term |
| --- | --- |
| DUO:0000042 | general research use (GRU) |
| DUO:0000018 | not for profit, non commercial use only (NPUNCU) |
| DUO:0000021 | ethics approval required (IRB) |
| DUO:0000027 | project specific restriction (PS) |
| DUO:0000024 | publication moratorium (MOR; applicable only until the moratorium ends) |

Following the end of the moratorium, DUO:0000024 will no longer apply.

## Related documents

- KPR Data Access Agreement — controlled-access genomic resources: [Word](KPR_Data_Access_Agreement.docx), [PDF](KPR_Data_Access_Agreement.pdf), [Markdown](KPR_Data_Access_Agreement.md)
- [Policy PDF (stable filename)](KPR_DAC_Policy_1.pdf)
- [KPR application checklist](KPR_Application_Checklist.md)
- [KPR analysis pipeline](https://github.com/JaeYoonKim72/KPR-pipeline)
- [EGA policy documentation](https://ega-archive.org/access/data-access-committee/policy-documentation/)
