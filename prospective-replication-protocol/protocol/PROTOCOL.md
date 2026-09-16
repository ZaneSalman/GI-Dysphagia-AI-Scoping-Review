# Artificial Intelligence Applications in Esophageal Dysphagia and Related Esophageal Disorders A Scoping Review Protocol for Replication and Re-analysis

## Protocol status

Protocol version: 1.0.1  
Status: Final prospective protocol awaiting public activation  
Review type: New from-scratch replication and re-analysis  
Protocol owner and guarantor: Zane Salman  
Corresponding author: Zane Salman, The University of Texas at Austin, Austin, Texas, USA; zgs277@eid.utexas.edu  

This protocol governs only a new replication and re-analysis that begins after its public release. It does not retrospectively govern or change the completed review. The operative copy will be the exact public Git commit recorded in `ACTIVATION_RECORD.md`.

## Structured abstract

**Objective:** To map artificial intelligence and comparable computational applications relevant to esophageal dysphagia, esophageal dysfunction, and related esophageal disorders, and to characterize validation and implementation maturity.

**Introduction:** Artificial intelligence is being evaluated across clinical data, manometry, endoscopy, imaging, molecular markers, histopathology, and physiologic sensors. A prospectively governed evidence map is needed because the literature spans heterogeneous disorders, methods, outcomes, and validation designs.

**Inclusion criteria:** Original full reports, preprints, and assessable conference abstracts will be eligible when they address an esophageal or swallowing population or sample, use an eligible artificial intelligence or comparable computational method, and pursue a clinically relevant esophageal application. Age and language will not determine eligibility.

**Methods:** Six bibliographic and registry sources will be searched from inception, followed by reference-list checking. Two reviewers will independently screen records and reports and resolve disagreements by consensus. One reviewer will chart all included reports and a second will verify every field using a frozen JBI-informed instrument. Evidence will be summarized descriptively at report and study levels; no meta-analysis or formal critical appraisal is planned.

**Keywords:** artificial intelligence; scoping review; esophageal dysphagia; esophageal motility; achalasia; gastroesophageal reflux disease; eosinophilic esophagitis; Barrett esophagus.

## Background and rationale

Artificial intelligence and related computational methods are increasingly being applied to swallowing and esophageal disorders using clinical records, videofluoroscopy, manometry, reflux monitoring, endoscopy, histopathology, molecular markers, imaging, and physiologic sensors. Existing evidence is heterogeneous with respect to clinical populations, data modalities, model families, intended applications, validation methods, and implementation maturity.

Several related evidence syntheses have recently been published. Da Silva et al. mapped artificial intelligence applications in dysphagia diagnosis and management across age groups and clinical contexts [5]. Their review included 61 studies and found that the literature was dominated by deep-learning applications, videofluoroscopic assessment, and neurologic populations. Its dysphagia-centered scope did not specifically map the broader esophageal diagnostic pathway or systematically distinguish reports from underlying studies. Sreedevi et al. subsequently focused on artificial intelligence tools for adult dysphagia assessment and management [6]. That review addressed clinically established dysphagia and emphasized swallowing screening, instrumental assessment, and therapeutic applications rather than the full spectrum of esophageal disorders and diagnostic modalities.

Aiolfi et al. reviewed artificial intelligence in benign esophageal disease, including achalasia, gastroesophageal reflux disease, Barrett esophagus, hiatus hernia, and Zenker diverticulum [7]. That review primarily examined diagnosis and surgical management, including surgical planning, intraoperative assistance, postoperative monitoring, and surgical education. Its search was restricted to English-language published articles, excluded conference abstracts, and did not include eosinophilic esophagitis as a defined disease domain. It therefore overlaps with, but does not replace, a broader review centered on the complete esophageal diagnostic pathway, nonsurgical computational applications, report-to-study relationships, dataset provenance, validation design, and implementation maturity.

A preliminary PubMed and web search conducted on 16 September 2026 identified these adjacent dysphagia-focused and surgically focused reviews but did not identify a current review matching the complete proposed scope: artificial intelligence and comparable computational applications across esophageal dysphagia, motility disorders, reflux disease, eosinophilic esophagitis, Barrett-related applications, and associated diagnostic modalities. A new prospectively governed replication is therefore warranted to integrate these domains, capture newly published and conference evidence, independently reproduce the selection and charting process, distinguish reports from underlying studies, and systematically characterize internal and external validation, dataset provenance, transparency, reproducibility, and readiness for clinical implementation. A scoping review is appropriate because the purpose is to map concepts, evidence characteristics, and gaps across a heterogeneous literature rather than estimate a single intervention effect.

## Objective

To map artificial intelligence and comparable computational applications relevant to esophageal dysphagia, esophageal dysfunction, and related esophageal disorders, and to characterize their validation and implementation maturity.

## Review questions

1. Which esophageal conditions and populations have been studied?
2. Which clinical data modalities and artificial intelligence or computational methods have been used?
3. Which diagnostic, classification, segmentation, quantitative-assessment, modeling, or decision-support objectives have been pursued?
4. How have models been validated and how mature is their implementation?
5. Which evidence, reporting, and implementation gaps remain?

## Methodological framework

The replication will be conducted using JBI methodological guidance for scoping reviews and will be reported according to PRISMA-ScR. Population, Concept, and Context will structure eligibility. PRISMA-P informs the completeness of this protocol without changing the scoping-review design.

## Review team and roles

The protocol authors, in order, are Zane Salman, Ryan Zeitouny, Daliah Refaei, Samer Salman, Rohan Phadke, Isha Tripuraneni, Anthony Shatby, Akhil Javvadi, Carol Gerges, Yara Abdullah, and Ajay Tripuraneni. Zane Salman, Ryan Zeitouny, and Daliah Refaei contributed equally and share first authorship. Zane Salman is the guarantor and repository custodian.

### Author affiliations and contact information

1. Zane Salman — The University of Texas at Austin, Austin, Texas, USA; zgs277@eid.utexas.edu
2. Ryan Zeitouny — Texas A&M University, College Station, Texas, USA
3. Daliah Refaei — Capital Schools of Austin, Austin, Texas, USA
4. Samer Salman — Baylor College of Medicine, Houston, Texas, USA
5. Rohan Phadke — Baylor College of Medicine, Houston, Texas, USA
6. Isha Tripuraneni — McGovern Medical School at UTHealth Houston, Houston, Texas, USA
7. Anthony Shatby — Texas A&M School of Engineering Medicine, Houston, Texas, USA
8. Akhil Javvadi — HelloAlfred.Ai, Austin, Texas, USA
9. Carol Gerges — A.T. Still University School of Osteopathic Medicine, Mesa, Arizona, USA
10. Yara Abdullah — Northeastern University, Boston, Massachusetts, USA; abdallah.y@northeastern.edu
11. Ajay Tripuraneni — Baylor College of Medicine, Houston, Texas, USA

### Contributions

Daliah Refaei and Zane Salman will independently screen records and reports. Daliah Refaei will chart included reports, and Zane Salman will verify all charted fields. Disagreements will be resolved by consensus using source evidence. Each author will confirm their CRediT roles and approve the final protocol before public release; final contributions to the completed review will be reported using the CRediT taxonomy.

## Eligibility criteria

| PCC element | Included scope | Excluded scope |
|---|---|---|
| Population | Esophageal dysphagia or dysfunction and related esophageal disorders or relevant clinical samples | No relevant esophageal or swallowing population, condition, or sample |
| Concept | Artificial intelligence, machine learning, deep learning, neural networks, natural-language processing, computer vision, segmentation, support-vector machines, tree-based learning, comparable data-driven computational modeling, or computational decision support | Conventional descriptive or inferential statistics alone; signal processing without an eligible computational model; no eligible AI or computational application |
| Context | Clinical detection, diagnosis, classification, interpretation, segmentation, phenotyping, quantitative assessment, physiologic assessment, or decision support | Administrative applications without a clinical esophageal objective; treatment delivery without an eligible diagnostic, assessment, prediction, or decision-support component |
| Evidence type | Full articles, preprints, and assessable conference abstracts reporting original results | Editorials, commentaries, narrative reviews, protocols, registry records without posted results, and reports without original eligible results |

Age will be charted but will not determine eligibility. Mixed-age and age-unspecified reports will not be excluded solely because adult results are inseparable. No language restriction will be applied. Reports that cannot be obtained will be classified as not retrieved rather than excluded.

## Information sources

The replication will search PubMed/MEDLINE, Embase, Scopus, Web of Science Core Collection, IEEE Xplore, and ClinicalTrials.gov. Searches will cover database inception through the execution date. Reference lists of included reports and relevant reviews will be checked for additional eligible reports. Newly identified companion reports will enter the same screening and eligibility process.

## Search strategy

The search will follow JBI's three-step approach. First, after protocol activation, a limited search of PubMed/MEDLINE and Embase will identify additional text words in titles and abstracts and relevant indexing terms. Any terms added to the source strategies will be documented before the comprehensive searches are executed. Second, the finalized text words and index headings will be translated and run across all six sources. Third, reference lists of included reports and relevant reviews will be examined for additional eligible evidence. Newly identified records will undergo the same screening process.

The planned source-specific strategies are stored in `search-strategies/`. They combine controlled vocabulary, where available, with free-text terms for esophageal dysphagia, motility disorders, reflux disease, eosinophilic esophagitis, Barrett esophagus, and artificial intelligence or comparable computational methods. No language or age filters will be applied. Non-substantive syntax corrections will be documented in the execution record; conceptual changes will be logged as amendments before the comprehensive searches proceed.

## Record management and independence from the previous review

All sources will be searched from inception through the new execution date. The replication will create a new record universe and new stable Record IDs. Records and reports assessed in the previous review will be evaluated again under this prospectively frozen protocol. Previous screening, eligibility, linkage, and charting decisions may be consulted only after the new independent decisions have been locked, and only for discrepancy analysis. They will not determine eligibility or extracted values in the replication.

Raw exports will be preserved unchanged in the private audit archive, with export counts, filenames, formats, and SHA-256 checksums. Deduplication will use DOI, PMID, trial number, normalized title, authorship, year, and bibliographic fields. Uncertain matches will receive manual review. A duplicate log will identify the retained record, removed record, and basis for each decision.

## Selection of sources of evidence

Daliah Refaei and Zane Salman will first apply the eligibility criteria independently to the same 25-record title-and-abstract calibration set. They will compare decisions, resolve interpretive differences, and repeat calibration with a new set if agreement is below 75%. Formal screening will begin only after at least 75% agreement is reached and the criteria are operationally clear. Calibration records will remain in the screening universe and will be screened again under the frozen interpretation.

The reviewers will then independently screen the same title-and-abstract record universe using the frozen criteria. Original independent decisions will be preserved. Disagreements will be resolved by consensus and the consensus decision will be recorded separately.

Before formal full-text assessment, both reviewers will independently apply the criteria to the same five retrieved reports selected to represent likely inclusions, exclusions, and borderline cases. They will resolve differences and document clarifications without changing the review question or scope. The five reports will then be reassessed under the frozen interpretation.

Both reviewers will independently assess retrieved reports at full text. Every excluded report will receive one primary exclusion reason from the hierarchy in `forms/FULL_TEXT_EXCLUSION_CODES.csv`. Reports that cannot be obtained will remain in the retrieval log and will not be counted as full-text exclusions. No unresolved eligibility decision will enter data charting.

## Retrieval and report identity

Reports will be sought through lawful institutional and public access routes, DOI and publisher pages, bibliographic databases, metadata or preview services, and companion-report sources. Retrieval activity will be recorded in `forms/REPORT_RETRIEVAL_LOG.csv`. Identity will be verified using title, authors, DOI or other identifier, and publication details. An incorrect or mismatched file will not be treated as the target report.

## Report and study linkage

Each publication or abstract will receive a Report ID and each underlying investigation a Study ID. Linkage will consider authorship, institution, recruitment period, sample size, dataset or cohort name, registration identifiers, diagnostic method, model description, and explicit cross-reference. Reports will be grouped only when the evidence supports a common investigation. Primary and companion reports will remain separate at report level while study-level summaries avoid double counting.

## Data charting

The charting dictionary and operational form in `forms/` will be calibrated on three included reports selected to represent different conditions, modalities, and report types. Daliah Refaei will chart the three reports and Zane Salman will verify every field. Definitions, permitted values, and source-location instructions may be clarified during calibration. The final form will then be versioned and frozen before complete charting begins. Calibration reports will be re-charted using the frozen form.

Daliah Refaei will chart every included report and Zane Salman will verify every field against the report or bibliographic record. Corrections will preserve the original value, corrected value, evidence location, extractor, verifier, and resolution. Missing-data codes will be `NR` for not reported, `NA` for not applicable, `Unclear` for information present but uninterpretable, and `Not assessed` for a field outside scope.

## Data items

Charted domains will include citation and setting, study design, population and condition, age and sex descriptors, sample size and unit of analysis, data modality and provenance, training, validation, and test datasets, model purpose and family, architecture and preprocessing, comparators and reference standards, performance metrics and uncertainty, clinician comparison, intended use and deployment, generalizability, transparency, limitations, funding, conflicts of interest, and source location.

Internal validation will mean evaluation using data originating from the same source population or development dataset, including resampling or held-out splits. External validation will require evaluation in an independently sourced population, institution, geography, or dataset not used for model development. Temporal validation will be recorded separately. Cross-validation alone will not be classified as external validation.

## Critical appraisal

No formal critical appraisal will be performed. The objective is to map the extent, characteristics, validation, implementation maturity, and gaps of the evidence rather than estimate a pooled effect or exclude evidence according to methodological quality. Reporting and validation limitations will nevertheless be charted descriptively.

## Analysis and presentation

Evidence will be summarized descriptively at report and study levels. Categorical fields will be counted at report level unless explicitly labeled otherwise. Multi-response modality and model-family totals may exceed the number of reports. Performance values will retain their reported units, denominators, thresholds, dataset roles, and validation contexts. Estimates will not be pooled and models will not be ranked across heterogeneous populations, thresholds, datasets, and validation designs.

Planned outputs are a PRISMA flow diagram, publication-year distribution, condition-by-modality matrix, model-family-by-application matrix, validation-maturity summary, report-to-study linkage table, and narrative synthesis of evidence, reporting, and implementation gaps. Counts will be reconciled using `reporting/PRISMA_ACCOUNTING.csv`.

## Stakeholder and public involvement

No formal stakeholder consultation or patient and public involvement is planned. The review will map published evidence and will not collect participant-level data.

## Amendments and deviations

After activation, any planned methodological change will be recorded in `AMENDMENT_LOG.md` before the affected work proceeds whenever feasible. An unplanned departure discovered after it occurs will be recorded in `DEVIATION_LOG.md`. The frozen protocol and original reviewer decisions will not be overwritten. The completed review will distinguish the original plan, amendments, and deviations.

## Data management and confidentiality

Raw database exports, locked independent screening files, consensus files, retrieval evidence, legally obtained full texts, charting audit files, and private correspondence will be preserved in a restricted audit archive. The public repository will contain the protocol, executed strategies, blank forms, reporting materials, and deidentified derived data that the authors have the right to share. Copyrighted reports, credentials, private correspondence, and personal information will not be released.

## Funding and competing interests

No external funding is planned. No funder or sponsor will influence the protocol, conduct, interpretation, or reporting. Each contributor will disclose relevant competing interests in the final report; none are declared in this protocol.

## Dissemination

The completed replication will be submitted for journal publication and reported according to PRISMA-ScR. The protocol, amendment and deviation logs, executed search strategies, PRISMA materials, and public data suitable for redistribution will remain available in the repository. The report will identify itself as a new replication and re-analysis and will compare its results with the previous review without presenting the earlier review as prospectively registered.

## References

1. Peters MDJ, Godfrey C, McInerney P, Munn Z, Tricco AC, Khalil H. Scoping Reviews. In: JBI Manual for Evidence Synthesis. JBI; 2024. https://doi.org/10.46658/JBIMES-24-09
2. Tricco AC, et al. PRISMA extension for Scoping Reviews (PRISMA-ScR): checklist and explanation. Ann Intern Med. 2018;169:467-473. https://doi.org/10.7326/M18-0850
3. Moher D, et al. Preferred reporting items for systematic review and meta-analysis protocols (PRISMA-P) 2015 statement. Syst Rev. 2015;4:1. https://doi.org/10.1186/2046-4053-4-1
4. Peters MDJ, Godfrey C, McInerney P, Khalil H, Larsen P, Marnie C, Pollock D, Tricco AC, Munn Z. Best practice guidance and reporting items for the development of scoping review protocols. JBI Evid Synth. 2022;20(4):953-968. https://doi.org/10.11124/JBIES-21-00242
5. da Silva RD, Almeida SB, Gonçalves FM, Zeigelboim BS, Stechman-Neto J, Schroder AGD, Nascimento WV, Santos RS, de Araujo CM. Artificial intelligence in the diagnosis and management of dysphagia: a scoping review. CoDAS. 2025;37(4):e20240305. https://doi.org/10.1590/2317-1782/e20240305en
6. Sreedevi EV, Iyer KS, Thankappan K, Janakiram C, Karuveettil V, Krishnan R, Guntha R, Roe J, Menon JR. Artificial intelligence tools for the assessment and management of dysphagia: a scoping review. BMJ Open. 2026;16:e119582. https://doi.org/10.1136/bmjopen-2026-119582
7. Aiolfi A, Wang Q, Mascagni P, Bona D, Leone N, Bonavina L. Artificial intelligence for surgical management of benign esophageal disease: scoping review and evidence mapping. Langenbecks Arch Surg. 2026;411(1):149. https://doi.org/10.1007/s00423-026-04050-1
