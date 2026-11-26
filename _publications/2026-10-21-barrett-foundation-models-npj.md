---
title: 'Towards reliable morphological subtyping and cancer detection on Barrett’s esophagus pathology through ensembling foundation models'
collection: publications
category: manuscripts
date: 2026-10-21
venue: 'npj Digital Medicine'
paperurl: 'https://doi.org/10.1038/s41746-026-03329-3'
citation: 'Kazemi A, Saueressig C, Liu J, Li H, Shakhtour J, Grosser B, Stögbauer F, Horstmann J, Navab N, Eslami S, Quante M, Slotta-Huspenina J, Schüffler PJ. Towards reliable morphological subtyping and cancer detection on Barrett’s esophagus pathology through ensembling foundation models. npj Digital Medicine. 2026;9:811.'
doi: '10.1038/s41746-026-03329-3'
image: '/images/publications/clinical-benchmark-barrett.jpg'
image_alt: 'Figure 1: overview of the foundation-model benchmarking pipeline'
image_license: 'CC BY 4.0'
themes: [computational-pathology]
featured: true
---

The reliability of emergent histopathology foundation models (Histo-FMs) for real-world diagnostic tasks remains unproven. Given the complexity of diagnostic tasks and the challenges inherent in real-world data, we utilized Histo-FMs to investigate their utility for morphological subtyping of Barrett’s esophagus (BE) and detecting esophageal adenocarcinoma (EAC) across the BE progression spectrum. We benchmarked Histo-FMs on the BarrettNet cohort, spanning diagnostic categories ranging from normal to EAC (N2EAC). The dataset comprised 3528 hematoxylin and eosin (H&E)-stained whole-slide images (WSIs) from 790 patients. A multi-magnification, multi-backbone aggregation of the five most expert-consistent single-scale models yielded incremental performance gains (AUROC of 0.907, F1-score of 0.696, accuracy of 0.795, and κ of 0.651 for morphological subtyping; AUROC of 0.909, F1-score of 0.836, accuracy of 0.959, and κ of 0.673 for EAC detection), with non-uniform gains across single-model comparisons and limited benefit for dysplasia. The findings support the capability of Histo-FMs for BE morphological subtyping and EAC detection in a multicenter clinical cohort, while highlighting persistent challenges in dysplasia assessment and the need for external validation. This study provides a foundation for future clinical validation.
