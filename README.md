# Sensory predictors of treatment response
Preprint manuscript and data/code for McAllister et al., "Treatment Response Across Biofeedback Modalities May Be Mediated by Auditory and Somatosensory Acuity"

## Abstract

Purpose: This study examined whether individual differences in auditory-perceptual and oral somatosensory acuity moderate response to different treatment approaches for residual speech sound disorder (RSSD) affecting English /ɹ/. Drawing on a personalized learning framework, we tested whether treatment effectiveness depends on the match between learners’ sensory profiles and the sensory information emphasized by intervention.

Method: Participants were 100 children aged 9-15 years who completed a multisite randomized controlled trial comparing visual-acoustic biofeedback, ultrasound biofeedback, and traditional motor-based treatment (MBT). Baseline auditory-perceptual measures included identification, discrimination, and category goodness judgment tasks; somatosensory measures included oral stereognosis and articulatory awareness tasks. Linear regression models tested interactions between sensory acuity and treatment condition in predicting change in perceptually rated accuracy of untreated /ɹ/ words from pre- to post-treatment.

Results: Significant interactions were observed between treatment condition and one auditory measure (discrimination) and one somatosensory measure (oral stereognosis). In the auditory domain, visual-acoustic biofeedback was associated with greater improvement among children with weaker auditory discrimination, whereas ultrasound and MBT showed the opposite pattern. In the somatosensory domain, ultrasound biofeedback and MBT were associated with greater improvement among children with weaker somatosensory acuity, while for visual-acoustic biofeedback the association was reversed.
Conclusions: The observed interactions are consistent with the possibility that treatment effectiveness is influenced by the alignment between learners’ sensory needs and the sensory information highlighted by different interventions. Although replication in larger, balanced samples is needed, the findings provide preliminary support for a personalized approach to treatment planning for RSSD.

## Documents

The preprint manuscript with figures in text is Sensory predictors of treatment response_FigsInText.pdf.

The manuscript's supplementary materials include complete regression model results (Supplementary Table A) and pairwise correlations among sensory measures (Supplementary Table B).

## Data Files

**RSSD_normed_sensory.csv**

Contains the sensory measures used in the analyses, normalized relative to age-matched reference data. Measures include auditory identification, discrimination, category goodness judgment, oral stereognosis, and articulatory awareness.

**RCT_subjlevel_data.csv**

Contains subject-level data from the randomized controlled trial used in the treatment-response analyses. The primary regression models use change in perceptually rated /ɹ/ accuracy from pre- to post-treatment as the outcome variable. Contains no identifiers.

## Analysis Script

**CRESULTS_sensory_predictors.Rmd**

R Markdown script containing the analyses reported in the manuscript, including descriptive statistics, pairwise correlations among sensory measures, regression models examining auditory and somatosensory predictors of treatment response, and alternative models controlling for baseline accuracy.

## Reproducing the Analyses

Place the two CSV files and the R Markdown script in the same directory. Open `CRESULTS_sensory_predictors.Rmd` in RStudio and knit the document to reproduce the analyses.

