# Mind the GAP: Improving Robustness to Subpopulation Shifts with Group-Aware Priors

This repository will contain the official implementation for

**_Mind the GAP: Improving Robustness to Subpopulation Shifts with Group-Aware Priors_**; Tim G. J. Rudner, Ya Shi Zhang, Andrew Gordon Wilson, Julia Kempe. **AISTATS 2024**.

**Abstract:** Machine learning models often perform poorly under subpopulation shifts in the data distribution. Developing methods that allow machine learning models to better generalize to such shifts is crucial for safe deployment in real-world settings. In this paper, we develop a family of group-aware prior (GAP) distributions over neural network parameters that explicitly favor models that generalize well under subpopulation shifts. We design a simple group-aware prior that only requires access to a small set of data with group information and demonstrate that training with this prior yields state-of-the-art performance—even when only retraining the final layer of a previously trained non-robust model. Group aware-priors are conceptually simple, complementary to existing approaches, such as attribute pseudo labeling and data reweighting, and open up promising new avenues for harnessing Bayesian inference to enable robustness to subpopulation shifts.

<p align="center">
  &#151; <a href="https://timrudner.com/gap"><b>View Paper</b></a> &#151;
</p>
