---
date: "2023-11-27"
external_link: ""
image:
  caption: 
  focal_point: Smart
links:
  - icon: github
  icon_pack: fab
  name: View Code
  url: https://github.com/MadeleineGastonguay/KSHV_math
- name: Poster PDF
  url: /project/KSHV/MIDAS_poster_gastonguay
#- icon: shiny.svg
#  icon_pack: /assets/media/icon-pack/
#  name: Shiny App
#  url: https://rshiny.jax.org/measurement_noise/
summary: In collaboration with the Kaye lab at Brigham and Women's Hospital, we are quantifying the dynamics of latent Kaposi's sarcoma-associated herpesvirus (KSHV) persistence. We developed a mathematical model and a statistical inference framework to infer viral dynamics from fluorescence microscopy images of cells in culture. Forward simulations were used to understand decades-long viral persistence and evaluate latent KSHV replication as a potential therapeutic target to disrupt KSHV-dependent tumor growth. 
tags:
- Viral Dynamics
- Bayesian Inference
- Stochastic simulation
- Mathematical modeling
title: Quantifying the dynamics of Kaposi's sarcoma-associated herpesvirus persistence
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

Kaposi’s sarcoma-associated herpesvirus (KSHV) is a causative agent of several 
lymphoproliferative diseases, particularly in immunocompromised individuals. 
These malignancies often originate from latently infected B cells, where KSHV persists as extrachromosomal, 
circularized episomes. While the viral protein LANA is essential for viral maintenance during latency, 
the mechanisms enabling lifelong persistence remain unclear.

To quantify episome dynamics, we developed a mathematical model of latent KSHV 
replication and segregation during cell division, and a statistical framework to 
infer viral dynamics from fluorescent microscopy images of cells in culture. First, 
we built a Gibbs sampler to extract episome counts from imperfectly resolved images 
of pre- and post-division cells. Using these counts, we jointly estimate the efficiency 
of episome replication and segregation, propagating imaging uncertainty into our parameter estimates.

Our framework, which was validated using synthetic data, provided similar estimates of 
replication efficiency (78%, 95% CI [53%, 90%]) and segregation efficiency (91%, 95% CI [78%, 100%]) 
when applied to fixed and live images of cells transfected with either full-length KSHV or 
a minimal plasmid capable of episome maintenance but incapable of lytic replication. 
Forward simulations of viral persistence in a population of dividing cells indicated that 
imperfect replication and segregation alone preclude decades-long persistence without the 
assistance of additional mechanisms such as cell-survival benefits to infection or occasional lytic replication. 

In addition, we modeled KSHV-dependent malignancies to evaluate reduction of replication 
or segregation as potential growth disruption strategies. Simulations of exponentially growing 
tumors demonstrated that reducing replication, but not segregation, could effectively disrupt tumor growth, 
and the requisite reduction depends on cell division kinetics.

These results suggest that KSHV persists by employing an active partitioning mechanism, 
as opposed to random segregation, but that both replication and segregation are imperfect. 
Furthermore, therapeutic strategies targeting episome replication may effectively 
reduce tumor burden for KSHV-associated malignancies. 

Co-authors: Jeffery Gerold, Franceline Juillard, Agnieszka Szymula, Alison L Hill, and Kenneth Kaye
Featured figure created in BioRender. Gastonguay, M. (2025) https://BioRender.com/e42n725