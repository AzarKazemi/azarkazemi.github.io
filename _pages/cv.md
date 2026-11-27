---
layout: archive
title: "CV"
banner_subtitle: "Education, experience and professional activities"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="cv" markdown="1">

## Profile

Medical informatics researcher working at the intersection of artificial intelligence, computational pathology and clinical diagnostics. My research focuses on developing and validating AI approaches for histopathology, with particular emphasis on reliable model performance, expert-guided evaluation and clinically meaningful interpretation of whole-slide images. I have worked across multidisciplinary pathology projects involving cancer detection, morphological characterization, biomarker assessment and emerging AI tools. My broader interest is the translation of computational pathology from experimental models toward robust decision-support tools that complement pathologists in clinical practice.

## Research experience

### Guest Researcher, Computational Pathology
Technical University of Munich · Munich, Germany · 02.2026 – present
{: .cv-meta}

- Contribute to the organization of the MICCAI REG² Pathologist Reasoning-Guided Report Generation Challenge within an international multidisciplinary team.
- Contribute to pathology data curation, quality control, LLM-based pathology report generation and the development of reasoning-oriented evaluation metrics for whole-slide images and pathology reports.

### Guest Doctoral Researcher
Technical University of Munich · Munich, Germany · 03.2022 – 01.2026
{: .cv-meta}

- Developed a computational pathology framework for morphological subtyping and cancer detection using large-scale whole-slide histopathology images.
- Designed and implemented an end-to-end, FAIR-aligned pathology data pipeline supporting reproducible data curation, quality control and machine-learning-ready whole-slide image analysis.
- Developed and systematically evaluated weakly supervised learning approaches leveraging multiple pathology foundation models, and investigated model-fusion strategies.
- Evaluated model interpretability through attention-based heatmaps, including systematic pathologist assessment of the clinical relevance of model-identified regions.
- Led an immuno-oncology project on histopathology-based biomarker quantification, developing active-learning and expert-in-the-loop annotation workflows and evaluating pathology foundation models for lymphocyte identification and quantification.
- Validated the reliability of a histopathology foundation model and MambaVision for quantifying and identifying lymphocyte regions.
- Assessed inter-observer agreement in tumor-infiltrating lymphocyte and tumor–stroma ratio quantification in colorectal cancer and analyzed annotation variability.

### Research Assistant, Digital and Computational Pathology
Technical University of Munich · Munich, Germany · 09.2022 – 08.2024
{: .cv-meta}

- Contributed to digital pathology workflow implementation, whole-slide imaging quality assurance and validation of digital diagnostics, evaluating concordance between digital and conventional assessment.
- Contributed to pathology foundation model-based classification of glioma subtypes on H&E-stained whole-slide images.
- Contributed to virtual staining research in breast cancer histopathology, using structure-aware diffusion-based approaches to generate immunohistochemistry representations from H&E images.

### Doctoral Researcher in Medical Informatics
Mashhad University of Medical Sciences · Mashhad, Iran · 09.2018 – 02.2022
{: .cv-meta}

- Conducted medical data science research involving clinical data curation, survival analysis, outcome prediction, feature engineering and machine-learning-based risk stratification.
- Developed reproducible analytical workflows incorporating missing-data handling, biostatistical validation and graphical analysis in collaboration with clinicians.

### Research Assistant
Shiraz Transplant Research Center · Shiraz, Iran · 01.2017 – 09.2018
{: .cv-meta}

- Designed and implemented a structured SQL-based pathology reporting database aligned with pathology reporting standards, including CAP-based requirements.
- Conducted clinical data analysis on factors associated with medication adherence in liver transplant recipients and contributed to multidisciplinary research and grant development.

## Education

### PhD in Medical Informatics
Mashhad University of Medical Sciences, Iran
{: .cv-meta}

### MSc in Medical Informatics
Shiraz University of Medical Sciences, Iran
{: .cv-meta}

### BSc in Software Engineering
Eshragh Higher Education Institute, Iran
{: .cv-meta}

## Teaching & mentoring

### Adjunct Lecturer
Shiraz University of Medical Sciences · Shiraz, Iran · 2014 – 2018
{: .cv-meta}

- Taught Data Structures and C Programming, and Information Technology in Medicine and Paramedicine to medical, nursing and dentistry students ([courses](/teaching/)).
- Developed lectures, course materials, assignments and examinations for students from computing and healthcare backgrounds.

### Supervision and mentoring
Technical University of Munich · Munich, Germany · 03.2022 – 01.2026
{: .cv-meta}

- Co-supervised a master's thesis in computational pathology: project design, methodology, analysis and scientific interpretation.
- Mentored master's students in seminar courses and scientific presentations on computational pathology.

## Professional activities

</div>

{% include activities-list.html %}

<div class="cv" markdown="1">

## Selected publications

- **Kazemi, A.**, Saueressig, C., Liu, J., et al. & Schüffler, P. J. (2026). Towards reliable morphological subtyping and cancer detection on Barrett's esophagus pathology through ensembling foundation models. *npj Digital Medicine*, 9, 811.
- Li, H., Liu, J., Ura, A., Hou, J., Xu, Z., **Kazemi, A.**, et al. & Schüffler, P. (2026). Paired uterine whole-slide images and pathology reports for multimodal computational pathology. *arXiv:2607.04020*.
- Liu, J., Deng, X., Li, H., **Kazemi, A.**, Grashei, C., Wilkens, G., et al. & Schüffler, P. J. (2025). From pixels to pathology: Restoration diffusion for diagnostic-consistent virtual IHC. *Computers in Biology and Medicine*, 198, 111264.
- Saueressig, C., Delbridge, C., Scholz, D., **Kazemi, A.**, Khan, M. Z., Metz, M., et al. & Wiestler, B. (2025). From histology to diagnosis: Leveraging pathology foundation models for glioma classification. *Computers in Biology and Medicine*, 197, 110988.
- Iwuajoku, V., Ekici, K., Haas, A., Khan, M. Z., **Kazemi, A.**, Kasajima, A., et al. & Schüffler, P. J. (2025). An equivalency and efficiency study for one year digital pathology for clinical routine diagnostics in an accredited tertiary academic center. *Virchows Archiv*, 487(1), 3–12.
- **Kazemi, A.**, Rasouli-Saravani, A., Gharib, M., Albuquerque, T., Eslami, S. & Schüffler, P. J. (2024). A systematic review of machine learning-based tumor-infiltrating lymphocytes analysis in colorectal cancer: Overview of techniques, performance metrics, and clinical outcomes. *Computers in Biology and Medicine*, 173, 108306.
- **Kazemi, A.**, Gharib, M., Mohamadian Roshan, N., Taraz Jamshidi, S., Stögbauer, F., Eslami, S. & Schüffler, P. J. (2023). Assessment of the tumor–stroma ratio and tumor-infiltrating lymphocytes in colorectal cancer: Inter-observer agreement evaluation. *Diagnostics*, 13(14), 2339.

All publications with abstracts: [Publications](/publications/) · [Google Scholar](https://scholar.google.com/citations?hl=en&user=a-VjYwQAAAAJ)

## Talks & conference presentations

- **Keynote:** Beyond Accuracy: From Foundation Models to Clinically Trustworthy Computational Pathology. 2nd MedAI Summit, October 2026, online. ([talk page](/talks/2026-10-28-talk-1))
- N2EAC: A Reliable Multi-Backbone Ensemble Framework for Improved Histopathological Esophageal Morphological Subtyping. 22nd European Congress on Digital Pathology (ECDP 2026), June 2026, Graz, Austria.
- Annotation-Efficient and Reliable Tumor-Infiltrating Region Density Stratification in Colorectal Cancer Histopathology Images: Pathologist-in-the-loop Approach. ECDP 2026, June 2026, Graz, Austria.
- Weakly Supervised Subtyping of Barrett's Esophagus Using Histopathological Images: From Normal to Adenocarcinoma. 108th Annual Meeting of the German Society of Pathology (DGP), June 2025, Leipzig, Germany.
- Weakly Supervised Subtyping of Barrett's Esophagus Using Histopathological Images: From Normal to Adenocarcinoma. 21st European Congress on Digital Pathology (ECDP 2025), Barcelona, Spain.
- Deep Learning-based Early Detection of Esophageal Adenocarcinoma in Histopathological Images. 36th European Congress of Pathology (ECP), September 2024, Florence, Italy.
- Machine Learning-Based Tumor-Infiltrating Lymphocytes Analysis in Colorectal Cancer: Techniques, Performance Metrics, and Clinical Outcomes. 20th European Congress on Digital Pathology (ECDP 2024), June 2024, Vilnius, Lithuania.
- Automatic Detection of Esophageal Cancer in Whole Slide Images. Next Generation Pathology, 107th Annual Meeting of the German Society of Pathology, May 2024, Munich, Germany.

</div>
