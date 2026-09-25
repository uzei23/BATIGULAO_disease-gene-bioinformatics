# BATIGULAO_SCN5A_disease-gene-bioinformatics

Name: Batigulao, Jehiah Bless T.

Date Completed: September 25, 2026

Assigned Gene: SCN5A

PART A. Create Your GitHub Activity Record
GitHub Repository Link: https://github.com/uzei23/BATIGULAO_disease-gene-bioinformatics

PART B. Locate Your Gene in the UCSC Genome Browser

| Item |  |
|---|---|
| **a. Official gene symbol** | **SCN5A** |
| **b. Full gene name** | **Sodium voltage-gated channel alpha subunit 5** |
| **c. Chromosome** | **Chromosome 3 (chr3)** |
| **d. Genome assembly used** | **GRCh38/hg38** |
| **e. Genomic coordinates shown in UCSC** | **chr3:38,548,062–38,649,687** |
| **f. DNA strand** | **Minus (-) strand** |
| **g. Approximate gene size or length** | **101,626 bp (approximately 101.6 kb)** |

### Screenshot 1. Gene Location

<img width="1902" height="927" alt="Screenshot 2026-09-25 095119" src="https://github.com/user-attachments/assets/bcccce02-ec41-4b93-9c1c-332bd9a6da24" />

The UCSC Genome Browser was used to locate the **SCN5A** gene on the human GRCh38/hg38 genome assembly. The gene is located on chromosome 3 and spans approximately 101.6 kb.

PART C. Understand the Gene Structure: Exons, Introns, and Transcripts

**Selected transcript:** SCN5A transcript variant 2, RefSeq **NM_000335.5** / GENCODE **ENST00000423572.7**

**a. Number of exons:**
The selected SCN5A transcript contains **28 total exons**, including **27 coding exons**.

**b. Multiple transcripts/isoforms:**
Yes. Multiple SCN5A transcript models/isoforms are visible in the UCSC Genome Browser. These transcripts can differ in their exon usage or exon boundaries because of alternative splicing.

**c. Difference between an exon and an intron:**
Exons are regions of a gene that remain in the mature RNA after splicing. They may contain protein-coding sequences or untranslated regions (UTRs). Introns are intervening regions between exons that are removed from the RNA during RNA splicing.

**d. Introns compared with exons:**
The introns of SCN5A generally appear longer than the exons. In the genome browser, the exon boxes are relatively short and are separated by longer connecting lines representing introns.

### Screenshot 2. SCN5A gene model

<img width="1841" height="812" alt="image" src="https://github.com/user-attachments/assets/e01cc478-82ac-428c-bbb7-3912c8e62901" />

PART D. Turn On and Examine Genome Browser Tracks

a. Which gene annotation track did you use?
I used the GENCODE V50 track as the primary gene annotation track. The NCBI RefSeq and MANE Select Plus Clinical tracks were also visible and provided additional SCN5A transcript models.

b. Were ClinVar-related variant marks visible within or near SCN5A?
Yes. ClinVar-related marks were visible in the SCN5A region. The screenshot shows the ClinVar Short Nucleotide Variants <50bp track, the ClinVar Copy Number Variants >=50bp track, and the ClinVar SNVs submitted interpretations and evidence track. The interpretation track contains colored marks, including pathogenic/likely pathogenic, uncertain-significance, benign/likely benign, and other interpretation categories as represented by the track legend. These marks show that clinically submitted variant interpretations are present in or near the displayed SCN5A region.

c. Were some regions more conserved than others?
Yes. The 100 vertebrates Basewise Conservation by PhyloP track shows variable conservation across the displayed region. Some positions have stronger positive conservation peaks, whereas other positions have weaker signals near the baseline or lower conservation values.

d. Did conserved regions correspond mainly to exons, introns, both, or another region?
The stronger conservation signals often occur in or near the annotated exon blocks, particularly around several larger exon regions. However, conserved signals are also present in some intronic or other non-coding intervals. Therefore, the most accurate conclusion is that conservation occurs in both exons and introns/non-coding regions, with stronger peaks appearing frequently near exons.

e. Why can strong conservation suggest biological importance?
Strong conservation across different species suggests that a DNA region has been maintained over evolutionary time because changes in that region may affect an important biological function. Therefore, highly conserved regions may have functional or structural importance, although conservation alone does not prove that a variant causes disease.

### Screenshot 3. Gene with at least one additional track 

<img width="1047" height="912" alt="image" src="https://github.com/user-attachments/assets/40cc692d-91be-454f-8cbc-cee496dc946c" />

PART E. Select One Variant in NCBI ClinVar

| Item                               |                                                                                                          |
| ---------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| **a. Gene**                        | `SCN5A`                                                                                                        |
| **b. Variant HGVS**                | `NM_000335.5(SCN5A):c.4296+1G>A`                                                                               |
| **c. rsID / ClinVar Variation ID** | `ClinVar Variation ID: 1739478`  /  **rs2061175467**                                                           |
| **d. Chromosome and position**     | `chr3:38557230 (GRCh38/hg38)`                                                                                  |
| **e. Condition**                   | `Brugada syndrome 1`                                                                                           |
| **f. Clinical significance**       | `Likely pathogenic`                                                                                            |
| **g. Review status**               | `Criteria provided, multiple submitters, no conflicts` / **4 out of 4 stars**                                  |
| **h. ClinVar URL**                 | (https://www.ncbi.nlm.nih.gov/clinvar/variation/1739478/?term=%22c.4296%2B1G%3EA%22%5BVARNAME%5D+AND+%22SCN5A%22%5BGENE%5D) |


### Screenshot 4. ClinVar variant record

<img width="1890" height="925" alt="image" src="https://github.com/user-attachments/assets/7879581b-56dd-41a5-9993-cd5e55848145" />

PART F. Find Your Selected Variant Back in UCSC

| Item                                       |                                                                                                                                                                                                                                                                                                                                                                                                                 |
| ------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **a. Location relative to the gene**       | The variant is located **within the SCN5A gene**, at **chr3:38,557,230 (GRCh38)**. It is in the intronic region immediately following a coding exon.                                                                                                                                                                                                                                                                  |
| **b. Exon, intron, UTR, splice, or other** | **Splice site / intron**. ClinVar identifies `c.4296+1G>A` as a **splice donor variant** affecting **intron 24** of SCN5A. ([NCBI][1])                                                                                                                                                                                                                                                                                |
| **c. Coding or non-coding**                | **Non-coding / intronic**, because the `+1` position is located in the intron immediately after the coding position `c.4296`. However, it affects an important splice site needed for proper processing of the RNA.                                                                                                                                                                                                   |
| **d. Brief mechanism**                     | The **G>A substitution** occurs at the canonical donor splice site. This can disrupt normal pre-mRNA splicing, potentially causing abnormal RNA processing, loss of correctly produced SCN5A protein, or degradation of the abnormal transcript through nonsense-mediated decay. ClinVar submitter evidence specifically describes the expected disruption of RNA splicing and possible loss of function. ([NCBI][1]) |
| **e. Additional evidence needed**          | Additional **RNA/splicing studies**, functional studies, segregation or case data, and other clinical evidence would help confirm the exact effect of the variant on SCN5A function and its relationship to Brugada syndrome.                                                                                                                                                                                         |
### Screenshot 5. Selected variant in UCSC relative to gene structure

<img width="1707" height="892" alt="image" src="https://github.com/user-attachments/assets/780d4186-ccaf-4ece-87dc-3f9124a7add0" />

PART G. Short Reflection

**1. What did you learn about how gene variants can affect human health?**
I learned that even a single nucleotide change can affect human health, especially when it occurs in an important region of a gene. In the SCN5A variant I studied, the mutation affects a splice donor site, which can interfere with the normal processing of the RNA and may affect the production of the sodium channel protein.

**2. Why is it useful to combine genome browsers with clinical databases?**
Combining UCSC Genome Browser with NCBI ClinVar makes it easier to understand a variant from both genomic and clinical perspectives. UCSC helps locate the variant and determine whether it is in an exon, intron, or splice site, while ClinVar provides information about its reported clinical significance and associated conditions.

**3. What part of the activity was most challenging or most interesting?**
The most challenging part was locating the exact variant in UCSC and understanding how its genomic position relates to the transcript and gene structure. It was also interesting to see how a small DNA change can potentially affect RNA splicing and contribute to a human disease.

References

VCV001739478.5 - ClinVar - NCBI. (2026). Nih.Gov. https://www.ncbi.nlm.nih.gov/clinvar/variation/1739478/?term=%22c.4296%2B1G%3EA%22%5BVARNAME%5D+AND+%22SCN5A%22%5BGENE%5D

University of California, Santa Cruz. (n.d.). UCSC Genome Browser: Human (GRCh38/hg38), SCN5A. UCSC Genome Browser. https://genome.ucsc.edu/cgi-bin/hgTracks?db=hg38&position=chr3%3A38548062%2D38649687

## Submission

* **GitHub repository URL:** [https://github.com/uzei23/BATIGULAO_disease-gene-bioinformatics]
* **Assigned gene:** SCN5A
* **Selected ClinVar variant:** NM_000335.5(SCN5A):c.4296+1G>A — Variation ID 1739478, **Likely Pathogenic**
* **Human disease / phenotype:** Brugada syndrome 1
* **Variant type:** Splice donor variant
* **Date completed:** September 25, 2026
