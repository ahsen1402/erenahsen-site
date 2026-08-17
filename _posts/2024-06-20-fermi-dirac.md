---
layout: single
author_profile: false
title: "A Quantum Leap in Binary Classification: Harnessing Fermi–Dirac Distributions"
date: 2024-06-20
categories: research
---

Binary classification stands as a cornerstone of machine learning, playing a critical role in a multitude of applications from medical diagnoses to spam filtering. However, a perennial challenge within this domain is obtaining a reliable probabilistic output indicating the likelihood of a classification being correct.

Our [paper](https://www.pnas.org) published in PNAS proposes an innovative approach: mapping the probability of correct classification to the probability of fermion occupation in a quantum system, specifically using the Fermi–Dirac distribution. This novel perspective facilitates calibrated probabilistic outputs and introduces new methodologies for optimizing classification thresholds and evaluating classifier performance.

## The Quantum Connection: Fermi–Dirac Distribution

At its core, the Fermi–Dirac distribution describes the statistical distribution of particles over energy states in systems obeying Fermi-Dirac statistics, typically applied to fermions that adhere to the Pauli exclusion principle. In this paper, we adapt the mathematical form of this distribution to model the probability of correct classification in binary classifiers.

By leveraging this quantum analogy, we establish a framework where:

* **Optimal Decision Threshold:** The threshold for class separation in binary classification is analogous to the chemical potential in a fermion system.
* **Calibrated Probabilistic Output:** The Fermi–Dirac distribution allows for a calibrated probability that reflects the likelihood of correct classification.
* **AUC and Temperature:** The area under the receiver operating characteristic curve (AUC) is related to the temperature of the analogous quantum system, providing insights into classifier performance variability.

The [paper can be found here](https://www.pnas.org).