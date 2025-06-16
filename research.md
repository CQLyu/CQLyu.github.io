---
layout: page
permalink: /research/index.html
title: Research
---

# Research

**My research delves into the intricate connections among stellar mass growth history, star formation quenching history, halo assembly history, and chemical evolution history. Utilizing sky survey data alongside semi-analytical models and simulations, I aim to uncover the underlying mechanisms shaping the landscape of galaxy formation and evolution.**

## Coplanar Inflows in Driving Disk Evolution

**In Lyu et al. (2025), we investigated the radial gradients of gas-phase metallicity (∇log (O/H)) and their relationship with other galaxy properties utilizing MaNGA sample, providing indirect observational evidence for the dominant role of coplanar gas inflows in disk evolution.** 

The formation and evolution of galaxy disks are central issues in the study of galaxies. In star-forming galaxies, the gas disk requires a continuous supply of gas to sustain star formation. However, there has long been a lack of direct observational evidence for how gas is accreted onto the disk and flows within the galaxy. Based on numerical simulations and theoretical models, astronomers have proposed two main modes of disk formation: one involves continuous gas inflows along the disk plane, while the other suggests that different parts of the disk evolve independently, with gas flows, star formation, and metal enrichment occurring independently within each region. The dominance of either mode has been a matter of debate.

The study found that, at a given stellar mass, disks with lower gas-phase metallicity exhibit steeper negative gradients (i.e., metallicity decreases rapidly from the center to the outskirts). This trend aligns well with the coplanar inflow scenario, where gas flowing inward along the disk plane is progressively enriched by in situ star formation. In contrast, if different regions of the disk evolved independently, the metallicity gradient would be strongly correlated with the gradient of stellar mass surface density, which was not observed in the study.

Additionally, the study revealed a close correlation between the gas turbulence parameter (represented by σgas/Re) and the metallicity gradient. Turbulence weakens the gradient through gas mixing. Using a Random Forest machine learning model, the study quantified the impact of different physical parameters on the gradient. The results showed that metallicity excess (Δlog(O/H)) and the gas turbulence parameter (σgas/Re) are the most critical factors in predicting the gradient, far outweighing traditional parameters such as stellar mass or galaxy size. This highlights the combined role of turbulence and coplanar inflows in shaping the metallicity gradient.



<img src="https://cqlyu.github.io/images/Lyu25-1.png" class="floatpic" width="1000">



## The impact of halo assembly history on galaxy evolution

**In Lyu et al. (2023), we investigate the impact of halo assembly history on galaxy stellar mass growth history and quenching history for central galaxies.** It has been established in previous decades that the growth of galaxy stellar mass is tightly related to the assembly of their host dark matter halos from both observational and theoretical perspectives (Wechsler et al. 2018). However, the secondary effect of the galaxy-halo connections still remains elusive in observation. 

Using stellar mass growth history derived from SDSS-MaNGA, we show that at a given present-day stellar mass, passive galaxies assembled half of their final stellar mass ∼ 2 Gyr earlier than star-forming counterparts, which agrees well with simulation results. We also look into the state-of-the-art semi-analytic model of galaxy formation, L-GALAXIES, and find that at a given present stellar mass, the passive central galaxies reside in, on average, more massive halos with a higher halo accretion rate across cosmic time. Consequently, passive central galaxies are assembled faster and also quenched earlier than their star-forming counterparts. 

Different halo assembly history also produces a very different final stellar mass of the central galaxy within, and the difference in the present stellar mass can be as large as ∼ 1 dex. At the same present halo mass, halos assembled earlier tend to host more massive centrals with a higher averaged quenched fraction, in particular around 10 12 M ⊙ . **Our study presents the quantitative connection between the growth of galaxy stellar mass and the assembly of their halo, and calls attention back to the dark matter halo as an important driver of galaxy evolution.**



<img src="https://cqlyu.github.io/images/Lyu23-1.png" class="floatpic" width="600">

## Tracing star formation quenching by metallicity

In Lyu et al. (2023), we investigate the stellar mass growth history and the chemical enrichment history of central galaxies measured from the SDSS-MaNGA survey. We find that at a given epoch, the derived stellar metallicity of central passive galaxies is always higher than that of the star-forming ones. This stellar metallicity enhancement becomes larger for low-mass galaxies (at a given epoch) and for an earlier epoch (at a given stellar mass). **We find strangulation is the primary mechanism for star formation quenching in central galaxies not only in the local Universe (Peng et al. 2015), but very likely also at higher redshifts up to z ∼ 3.



<br><img src="https://cqlyu.github.io/images/Lyu23-2.png" class="floatpic" width="600"><br>

## Estimate the halo assembly history for SDSS galaxy groups

In Lyu et al. (2024), **we establish new regression models using observable quantities of galaxies and group properties to estimate unobservable halo assembly history. Applied the trained models to the SDSS group catalog, we derive the halo assembly time of each individual central galaxy.** The properties of the central galaxy are tightly connected to their host dark matter halo mass and halo assembly history. For instance, as found in Work I, at the same present-day halo mass, different halo assembly histories can produce significantly different final stellar mass of the central galaxy within. However, accurate measurement of the halo assembly history in observation is very challenging but is of great importance to the understanding of galaxy formation and evolution. The stellar-to-halo mass ratio (Mstar/M_h) for the centrals has often been used to indicate the halo assembly time t_h,50 of the group, where t_h,50 indicates the lookback time at which a halo has assembled 50% of its present-day virial mass. 

Using mock data from the semi-analytic model L-GALAXIES, we find that Mstar/M_h shows a significant scatter with t_h,50, with a strong systematic difference between the group with a star-forming central (blue group) and passive central (red group). To improve the accuracy, we develop machine-learning regression models to estimate t_h,50 for galaxy groups at 0.01<z<0.20, using only observable quantities in the mocks. Since star-formation quenching will decouple the co-growth of the dark matter and baryon for the central galaxies, we train our models separately for blue and red groups. We show our models have successfully recovered the t_h,50, within an accuracy of ~0.99 Gyr for the blue groups, and ~1.03 Gyr for the red groups. Nevertheless, our models do not perform well for red groups assembled relatively recently (with t_h,50 < 5 Gyr, less than 5% of all mock samples), and even including non- or difficult-observable properties can barely improve the model performance for this small population, probably due to the recent merger of the halos in a random fashion. 

With careful calibrations of individual observable quantities in the mocks with SDSS observations, we apply these trained models to the SDSS groups (Yang et al. 2007, 2009) and accurately derive the t_h,50 for each group for the first time. We show the derived SDSS t_h50 distribution functions are in reasonable agreement with that in the mocks, in particular for blue groups, which hence strongly supports our methods. **The derived halo assembly time, together with the halo masses, make an important step forward in studying the halo-galaxy connections.**

<img src="https://cqlyu.github.io/images/Lyu24-1.png" class="floatpic" width="1000">



## Star Formation Quenching

- TBD



## Chemical Models

- TBD

