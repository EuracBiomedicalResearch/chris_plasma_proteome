# Mass spectrometry-based plasma proteome of the CHRIS study

This repository contains analysis (Rmd) files defining various analyses of the
ScanningSWATH mass spectromentry (MS)-based plasma proteome data of the CHRIS
population study. The data is available for about 3,500 participants of the
CHRIS baseline collection.

- [sex_age_bmi_associated_proteins.Rmd](sex_age_bmi_associated_proteins.Rmd):
  general overview of the data, multiple linear regression-based analysis to
  identify sex, age and BMI associated proteins. Identification of sex hormone
  treatment associated proteins and sensitivity analysis to evaluate impact of
  this treatment on general results.

- [HCU_associated_proteins_baseII.Rmd](HCU_associated_proteins_baseII.Rmd):
  analysis for association of proteins with hormonal contraceptive use (HCU) in
  the [serum proteome data of the BASE-II
  cohort](https://doi.org/10.1101/2024.06.22.24309293).

The mass spectrometry proteomics data for QC samples, the fasta file used for
spectral library annotation and peptide and protein quantities obtained from
DIA-NN have been deposited to the ProteomeXchange Consortium
(http://proteomecentral.proteomexchange.org) via the PRIDE partner
repository. The corresponding PRIDE identifiers for the study pools and
quality controls are PXD052861 and PXD052892 respectively.

Individual level data acquired as part of the CHRIS study data analyzed in here
can be requested for research purposes by submitting a dedicated request to the
CHRIS Access Committee. Please visit https://chrisportal.eurac.edu/ for more
information on the process. A similar principle is applied for the BASE-II
data. Please contact the scientific coordinator as outlined on
https://www.base2.mpg.de/contact.
