---
date: "2021-03-08"
external_link: ""
image:
  caption: Measurement Noise Models
  focal_point: Smart
#links:
#- icon: shiny.svg
#  icon_pack: /assets/media/icon-pack/
#  name: Shiny App
#  url: https://rshiny.jax.org/measurement_noise/
summary: Measurement noise is frequently ignored in mediation analysis. Inferences are made under the assumption that the data represents the underlying causal relationship when in reality the observed data is just a shadow of the true causal variables. In this analysis, we address the impact of applying a standard mediation analysis to data as if it is measured without error and identify ways to diagnose inconsistent results.
tags:
- Mediation Analysis
- Measurement Noise
title: Uncovering the effect of measurement noise on mediation analysis
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

Mediation analysis focuses on inferring the relationship between an exogenous variable (X), target (Y), and candidate mediator (M). When X, M, and Y are all correlated, there are a few plausible relationships between them. In the Causal model, the effect of X on Y is mediated entirely through M. In the Independent model, there is no causal relationship between Y and M because X effects them independently. In the Reactive model, the proposed mediator is downstream of the proposed target and is thus reacting to changes in Y. Lastly, in the Complex model X effects Y both directly and indirectly through M. 

Most analyses ignore measurement noise and assume that as the sample size approaches infinity, inferences made from the observed data accurately reflect the underlying structural model (*ie.* results are consistent). This is an unrealistic assumption with a profound impact on the results of mediation analysis. We define a measurement noise model that describes the observed data in terms of the underlying structural model and the measurement noise in each variable. This model is equivalent to a simpler latent variable model, which we use to show that the underlying structural model is unidentifiable without additional information. It is also used to explain how data can be observed given any of the structural models to identify configurations that are realistic given prior knowledge about the relative amount of measurement noise in X, M, and Y. 

Through simulations of the measurement noise model, we show that each of the structural models can generate any observable data correlation under varying combinations of the strength of the structural model and the amount of measurement noise. We identify regions of the parameter space for the latent variable model in which inferences will be consistent and those in which it will be inconsistent (*ie.* as the sample size increases so does the evidence for an incorrect inference). With examples in data from human cell lines and model organisms, we demonstrate cases where the inferred relationship disagrees with biological evidence of the underlying relationship and offer an explanation for each case. 
