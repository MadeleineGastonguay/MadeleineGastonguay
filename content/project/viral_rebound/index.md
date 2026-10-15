---
date: "2024-03-01"
external_link: ""
image:
  caption: 
  focal_point: Smart
links:
- name: Poster PDF
  url: /project/viral_rebound/gastonguay_ACOP_poster.pdf
summary: In collaboration with Mélanie Prague at the University of Bordeaux, we developed a mathematical model of within-host HIV dynamics and used nonlinear mixed-effects modeling implemented in Monolix to investigate the mechanism of action of several immunotherapies.
tags:
- Viral Dynamics
- Nonlinear mixed-effect modeling
- Mathematical modeling
title: Viral rebound kinetics following single and combination immunotherapy for HIV/SIV
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

Antiretroviral therapy (ART) can treat but not cure HIV. Viral rebound occurs within 
weeks of ART interruption due to latent reservoir reactivation and weak immune control, 
motivating the development of  immunotherapy for durable remission. Three such therapies - 
a TLR7 agonist, a therapeutic vaccine, and the broadly neutralizing antibody (bNAb) PGT121 - 
were evaluated in nonhuman primate (NHP) models of HIV [1-4]. Animals received ART 
with or without single/combination immunotherapy, and rebound was monitored after therapy 
washout. Treated animals exhibited altered rebound kinetics, and some maintained viral 
control after therapy cleared. Our objectives are to characterize how these therapies 
affect the latent reservoir and antiviral immunity, to identify drug synergies, 
and to make informed predictions about their efficacy in humans.

We analyzed NHP rebound data after immunotherapy using the basic viral dynamics 
model extended to include latent cell reactivation and immune response. We assessed 
structural and practical identifiability and fixed non-identifiable parameters using 
literature or profile likelihood. Using mixed-effects modeling, we estimated parameter 
distributions for latent reactivation, immune effector activation/expansion, 
target cell availability, and viral infectivity. To identify which processes were
modulated by each therapy, we explored candidate treatment effects on parameters 
based on biological hypotheses and covariate model building with overfitting safeguards. 
We simulated human trials by fitting the model to HIV rebound data in the absence 
of therapy, sampling parameters from the posterior, and applying NHP-derived treatment effects.

Our analysis suggests that in NHP, therapeutic vaccination reduces latent reactivation 
5-fold and enhances effector activation 33-fold. The bNAb reduces viral infectivity 
5-fold, enhances effector activation 7-fold, and has no significant effect on the latent 
reservoir. The effects of the TLR7 agonist are context-dependent: with late ART initiation, 
it reduces reactivation and increases target cell availability; with early ART, 
it increases immune memory and, in one cohort, synergizes with vaccination to boost 
effector activation. Clinical trial simulations show that combination therapy, 
especially TLR7 with bNAb, may achieve durable viral control for HIV patients. 
Furthermore, patients may rebound before establishing control, complicating clinical 
trial design as patients typically restart ART following detectable virus.

We used mixed-effects modeling to characterize how novel HIV immunotherapies alter 
viral rebound kinetics by affecting viral and immune dynamics. We found evidence of 
a vaccinal effect of the bNAb, though precise mechanisms of this immune activation 
remain unclear. While we did not find evidence of synergy between the bNAb and TLR7 
agonist in reducing the latent reservoir (“kick and kill”), virtual clinical trials 
showed that their combination could establish durable viral control in HIV patients 
via immune effects. Finally, we show that clinical trials evaluating cures may require 
longer ART interruption windows or altered restart criteria to capture remission.

Co-authors: Mélanie Prague, Jeffrey M Gerold, Irene Balelli, Chloé Pasin, Jonathan Z Li, Dan H Barouch, James B Whitney, and Alison L Hill

