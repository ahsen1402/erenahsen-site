---
layout: default
title: Software
permalink: /software/
---

# Software

Below are some of the software codes we have generated/generating with my collaborators. Please note that some of these are still in development but feel free to reach me if you need a beta version of the code.

## R-SUMMA

Recently, we have developed, in collaboration with my colleagues [Robert Vogel](https://github.com/robert-vogel) and Gustavo Stolovitzky, the SUMMA algorithm which is an unsupervised ensemble algorithm that tries to estimate performances of a set of base classifiers and uses this estimate in order to form a more robust ensemble ranker/classifier. More details about SUMMA can be found in our pre-print on [arXiv](https://arxiv.org). The R-SUMMA package is an R-implementation of the SUMMA algorithm developed.

## PY-SUMMA

This is python implementation of the SUMMA algorithm.

## DM-Diagnostic

Recently, we have organized a crowdsourced data competition, the [DREAM Digital Mammography Challenge](https://www.synapse.org), which attempts to improve the predictive accuracy of digital mammography for the early detection of breast cancer. During the challenge, methods developed by participants were trained and evaluated in the cloud on a collection of 634,929 de-identified digital mammography images, corresponding to 144,231 exams of 85,580 women.

Part of the organizing team, I developed an ensemble classifier that ensembles predictions of AI algorithms with that of the radiologists which improved the overall classification performance. To make the DM Challenge widely available, we prepared a docker container containing the code to run the ensemble method. The method requires as input a single image and/or radiologists prediction and outputs a confidence score of being cancer. (In collaboration with Bruce Hoff and Thomas Schaffter)

## Lonestar

Lonestar is an algorithm that automatically performs feature selection as well as sample classification. We applied Lonestar to predict lymph node metastasis in endometrial cancer, which is published in [BMC Genomics](https://bmcgenomics.biomedcentral.com/). This is a Matlab implementation of Lonestar, please contact me for further details and the code.

## PHIXER

PHIXER is a network inference algorithm that infers a directed network from a given perturbation matrix. We successfully applied PHIXER to reverse-engineer genetic interaction networks. In collaboration with my colleague Nitin we have developed a Matlab implementation of PHIXER.
