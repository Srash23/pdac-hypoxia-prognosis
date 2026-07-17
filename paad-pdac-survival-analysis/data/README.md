# Data

`paad_tcga_pan_can_atlas_2018_clinical_data.tsv` is the patient-level clinical data
export for the **TCGA-PAAD (Pancreatic Adenocarcinoma), PanCancer Atlas (2018)** study,
downloaded from [cBioPortal](https://www.cbioportal.org/study/summary?id=paad_tcga_pan_can_atlas_2018).

184 patients, including AJCC stage, overall/disease-specific/progression-free survival,
tumor mutation burden, fraction of genome altered, aneuploidy score, three hypoxia
gene-expression signatures (Buffa, Ragnum, Winter), MSIsensor score, and mutation count.

TCGA data is open access and freely redistributable for research and educational use.
If you'd rather pull a fresh copy: go to the study page above, open the **Clinical
Data** tab, and use the download button. This repo commits the file directly (it's
small, ~180KB) so the analysis is reproducible without a separate download step.

**Citation:** Cancer Genome Atlas Research Network. Integrated genomic characterization
of pancreatic ductal adenocarcinoma. *Cancer Cell* 32.2 (2017): 185-203.
