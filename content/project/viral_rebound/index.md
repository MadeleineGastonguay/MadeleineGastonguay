---
date: "2023-11-27"
external_link: ""
image:
  caption: 
  focal_point: Smart
#links:
#- icon: shiny.svg
#  icon_pack: /assets/media/icon-pack/
#  name: Shiny App
#  url: https://rshiny.jax.org/measurement_noise/
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

Combination antiretroviral therapy (ART) can treat but not cure HIV, motivating the 
development of therapies that stimulate the immune system to control or eliminate infection. 
Two such immunotherapies- a TLR7 agonist and a therapeutic vaccine - 
were previously tested in SIV-infected rhesus macaques. Animals received ART alone
or with concurrent single or combination immunotherapy, and viral rebound was monitored 
after treatment interruption. Many treated animals exhibited altered rebound kinetics, 
and a subset achieved either complete viral suppression or immune control after an initial rebound. 
However, the mechanisms driving these effects are unknown: do these therapies deplete the 
latent reservoir or enhance antiviral immunity, and do they act synergistically?

To investigate the effects of immunotherapy, we built a mathematical model of viral 
dynamics incorporating latent cell reactivation and a generalized immune response. 
We confirmed the model could reproduce the range of rebound trajectories seen in the data, 
and examined whether parameters could be reliably estimated from the available data 
by assessing structural and practical identifiability. Using nonlinear mixed-effects modeling, 
we quantified inter-individual variability and identified significant differences in model parameters between treatment groups. 
We fond that commonly used deterministc stepwise model selection methods using
arbitrarily small difference in goodness of fit criteria were sensitive to changes 
in initial parameter guesses, and the biological meaning of the selected model was
often difficult to interpret. Thus, we implemented a threshold of model fit improvement
that must be met to include a treatment effect, and developed an approach to systematically 
evaluate alternatives to the best fit model at each step of the selection process. 
These adjustments provided more robust results to the model fitting procedure.

Our results indicate that the vaccine alone reduces latent virus reactivation and 
enhances immune response avidity. The TLR7 agonist, when administered after late ART initiation, 
increases target cell availability and reduces the latent reservoir. We found that regardless of ART initiation,
the two therapies act synergistically to further enhance immune response avidity. 
Immune avidity appeared to increase with later ART initiation, although whether 
this effect is specific to TLR7 treatment is unclear. Our model provides mechanistic 
insight into immunotherapeutic control of viral rebound and can be adapted to predict 
their impact in controlling HIV, guiding future therapeutic design and clinical trials.

Co-authors: Mélanie Prague, Jeffrey M Gerold, Irene Balelli, Chloé Pasin, Jonathan Z Li, Dan H Barouch, James B Whitney, and Alison L Hill1

