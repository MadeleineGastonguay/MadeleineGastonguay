+++
title = "Predicting Imminent Conversion to Exudative Age-Related Macular Degeneration Using Multimodal Data and Ensemble Machine Learning"
date = "2025-01-01"
doi = "https://doi.org/10.1016/j.xops.2025.100785"
authors = ["T. Y. Alvin Liu", "Yuxuan Liu", "Madeleine S. Gastonguay", "Dan Midgett", "Nathanael Kuo", "Yujie Zhao", "Kareef Ullah", "Gwyneth Alexander", "Todd Hartman", "Neslihan D. Koseoglu", "Craig Jones"]
publication_types = ["2"]
publication = "Ophthalmology Science, (5), 5, _pp. 100785_"
publication_short = "Ophthalmology Science, (5), 5, _pp. 100785_"
abstract = "Objective\nExudative age-related macular degeneration (eAMD) is a major cause of central vision loss. Identifying patients at high risk of imminent eAMD could enable timely treatment and improve outcomes. Our goal was to develop and compare classical machine learning (ML) and deep learning (DL) models to predict imminent eAMD conversion within 6 months and integrate OCT with clinical data into a single predictive model.
Design\nRetrospective cohort study.\nParticipants\nPatients seen at the Wilmer Eye Institute between 2013 and 2021 with eAMD in ≥1 eye.\nMethods\nSpectral domain OCT volumes prior to conversion and the corresponding clinical data (age, best-corrected visual acuity, sex, and fellow-eye status) were collected and used for model training or testing. ResNet-50 and classical ML (Random Forest and XGBoost) models were trained to predict imminent conversion to eAMD within 6 months on an eye level. For the multilayer perceptron (MLP) framework, the trained ResNet-50 model was used as the feature encoder, and a downsampled feature vector concatenated with corresponding clinical tabular data was passed through the MLP (prediction head). Data were partitioned at the patient level (75\% training, 15\% validation, and 10\% testing). Model performance was evaluated using the area under the operating characteristic curve (AUC) and 95\% confidence interval (CI) for the model AUC was calculated using the percentile method after bootstrapping the test set 10 000 times. Model comparisons were made using modified paired t test. P {\textless} 0.05 was considered statistically significant.\nMain Outcome Measures\nArea under the operating characteristic curve.\nResults\nThirty-three thousand one hundred eighty-nine OCT volumes from 2084 patients (63\% female; 89.1\% White, 4.8\% Black, and 2.3\% Asian) were included. The mean age at the time of first-eye conversion was 78.9 (± 9.3) years. Our best-performing models, “MLP multimodal” (trained with both OCT and clinical data; AUC: 0.76, 95\% CI: 0.71–0.80) and “CNN OCT” (trained with only OCT data; AUC: 0.75, 95\% CI: 0.70–0.79), had a DL (ResNet-50) architecture; “MLP multimodal” outperformed “CNN OCT” in predicting both all-eye (P {\textless} 0.05) and first-eye conversion (P {\textless} 0.001).\nConclusions\nThe 3-dimensional DL models, trained with OCT volumes, are capable of predicting both first-eye and fellow-eye imminent conversion to eAMD. The addition of clinical data further improved the model performance. These models, if validated prospectively, could serve as screening tools and allow retinal specialists to prioritize patients with more acute retinal issues.\nFinancial Disclosure(s)\nProprietary or commercial disclosure may be found in the Footnotes and Disclosures at the end of this article."
abstract_short = ""
image_preview = ""
selected = false
projects = []
tags = []
url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""
math = true
highlight = true
[header]
image = ""
caption = ""
+++
