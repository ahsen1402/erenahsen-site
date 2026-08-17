---
layout: single
author_profile: false
title: "A Fresh Look at Combination Therapy: Correlated Drug Action Models"
date: 2024-06-20
categories: research
---

Combination therapy, the principle of treating patients with multiple drugs either simultaneously or sequentially, has long been a cornerstone in the battle against complex diseases like cancer and HIV/AIDS. The rationale is straightforward: cancer cells, for instance, might develop resistance to one drug, but the likelihood of evading multiple drugs with different mechanisms is considerably lower. This strategy, pioneered by Frei and Freirich, has become an integral part of modern oncology.

However, the challenge lies in efficiently quantifying the effects of these combinations, given the vast number of possible combinations and the resources required. Our recent [research](https://www.sciencedirect.com) introduces a novel framework—Correlated Drug Action (CDA)—to address this challenge.

## The Essence of Combination Therapy Models

Combination therapies can be studied at two levels: *in vitro* on cells and *in vivo* on living organisms. In vitro research focuses on dose response at a fixed time post-drug administration (dose-space models), while in vivo research focuses on survival time at fixed doses (temporal models).

Traditionally, null models have established a baseline for expected drug combination effects. These models are essential for determining if a combination is more effective than expected.

## Introducing Correlated Drug Action (CDA)

Building on the principle of Independent Drug Action (IDA), which posits that each drug in a combination acts as if the other drug were absent, we introduce the temporal Correlated Drug Action (tCDA) model. Unlike previous models with time-varying correlation coefficients, tCDA employs a non-time-varying coefficient, offering a fast and scalable solution.

The tCDA model describes the effect of a combination based on individual monotherapies and a population-specific correlation coefficient. This model is valid for generic joint distributions of survival times characterized by their Spearman correlation.

## Validating tCDA with Clinical Data

We applied the tCDA model to public oncology clinical trial data involving 18 different combinations. The model effectively explained the effect of clinical combination therapies and identified combinations that could not be explained by tCDA alone. When the survival distribution of a combination is explained by tCDA, the estimated correlation parameter can reveal sub-populations that may benefit more from one monotherapy or the combination.

## Extending CDA to Cell Cultures: Dose-Space CDA (dCDA)

To address the limitations of translating preclinical cell line results to clinical outcomes, we adapted IDA’s temporal-space ideas to dose-space, resulting in the dose-space CDA (dCDA) model. This model describes the effect of combinations in cell cultures in terms of the dosages required for each monotherapy to kill cells after treatment.

The dCDA model estimates the correlation between joint distribution dosages, similar to the tCDA and ORR models in patient cohorts. Using MCF7 breast cancer cell line experiments, we demonstrated dCDA’s effectiveness in assessing potential drug synergy. We introduced the Excess Over CDA (EOCDA) metric to evaluate possible synergy, allowing for non-zero correlations.

[Read the full paper](https://www.sciencedirect.com).