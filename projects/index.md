---
title: Projects
---

During CAMS, each group works on a project proposal towards producing some
research product: a publication, a software package for distribution, an openly
accessible tool, *etc*.

For 2015, the projects are:

 - **Agent-Based Model of Clinically Immune Malaria Carriers** (TJH):
 People exposed multiple times to the malaria parasite can develop *clinical immunity*, where they no longer exhibit symptoms but can still transmit the pathogen to mosquitos.  This complicates malaria control, since part of the control relies on treatment to clear infectious people, and clinically immune individuals do not seek treatment.

    Workshop project work entails creating a flexible network-based transmission model that includes such carriers.  Longer term work could extend to fitting that model to data or testing intervention schemes to attempt to identify these asymptomatic carriers.

 - **Automated Bayesian Computation via Partial Least Squares** (NR, EL, MKD):
 ABC-SMC is a parameter estimation and sensitivity analysis library written in C++.  It can be run on a personal computer or distributed across thousands of processors on a supercomputer.

   Option 1: Although ABC-SMC is implemented in C++, it does not require any knowledge of C++ to use.  We would like to make it easier for people to use the library by writing wrappers in one or more other languages.  This will allow people with stochastic simulations written in other languages to use the library to fit their models.

   Option 2: In order to determine whether a particular parameter combination is "good," we compare the model outcomes (called metrics) to empirical data, but this comparison cannot be made directly.  Model parameters and metrics may be redundant or correlated, and metrics can also vary in magnitude in ways that do not reflect their importance.  We use partial least squares to find a set of orthogonal, latent factors, but some of the factors tend to just describe noise in the data.  Eliminating these is important in estimating the explained variance in the data, and can be done in a number of ways.  This project is to investigate what the best approach is in choosing the number of factors to use.

   Option 3: ABC-SMC is an iterative fitting procedure where you run a simulation N times, update priors for the parameters, run it N more times, update the priors, and so on, until it converges.  How big should N be, and how should convergence be assessed?

 - **Analysis of Non-Linear Plant Parasite Development Under Oscillating Environmental Conditions** (MKD):
 Microbial plant parasites are critical to understand if we wish to maximize agricultural production.  Based on constant environment experiments, these parasites have non-linear growth responses to temperature and humidity.  However, real production entails daily environmental oscillations, and current forecasting work for the spread of these parasites typically makes linearizing assumptions.

    Workshop project work entails preparing an analytical pipeline to characterize parasite growth data with non-constant experimental conditions, and to estimate forecast errors for different scenarios.  Longer term work would include applying this framework to particular datasets, and could also include additional growth curve models.

 - **Geospatial, Temporal Visualization of Infectious Disease Data** (NR):
 We have a dengue visualization website for a region in Mexico.  Gather disease incidence time series data for Ghana or another West African country, and create a visualization tool.  Ideally, this would be done for multiple diseases, and users could explore correlations in dynamics.  You are welcome to use our dengue website as a starting point.

 - **Infectious Disease Transmission Visualization with EpiFire** (TJH):
 EpiFire is a C++/Qt software package for simulating the spread of infectious diseases on finite contact networks (== graphs).  Currently it has the ability to visualize how individuals change in state over time, but the particular contact (edge) along which transmission occurred is not shown.  Extend the current functionality of EpiFire so that transmission routes are shown in the visualization.

 - **ODE Model Library of Ebola Transmission** (CABP):
 The West African Ebola Outbreak surprised, and nearly overwhelmed the public health systems in those areas and the international communities capacity to provide aid.  The differences in transmission that lead to a major outbreak in West Africa, while areas like Congo continue to see mild case counts, are not known and would benefit from modeling work.

     Workshop project work entails preparing a library of ODE models for transmission as an R package.  Longer term work would involve deploying these models in fitting and model comparison analyses, on data from the West African Ebola Outbreak.

 - **ODE Model Library of Resistant TB Transmission** (CABP):
 TB, and particularly drug resistant TB, is a critical public health concern.  There is evidence of some previously unconsidered dynamic processes, particularly to do with chronic TB.  Estimating the strength of these processes, however, is confounded by a variety of other processes (such as clustering of high risk groups, and HIV co-infections).

    Workshop project work entails preparing a library of ODE models for transmission as an R package.  Longer term work would involve deploying these models in fitting and model comparison analyses, on data from various African countries, particularly Swaziland.

 - **Dengue Vaccination Campaign Modeling for Thailand** (TJH):
 We have an agent-based dengue model which we have been using to study disease dynamics in Mexico.  This project is to modify the model as necessary to apply it to a region in Thailand, where dengue is an even larger problem.

 - **Teaching Tutorials for Meaningful Modeling of Epidemiological Data** (CABP):
 AIMS South Africa regularly hosts a workshop on modeling epidemiological data.  The group that runs that workshop has prepared a variety of tutorials and demonstrations in R.  However, that work has haphazardly accumulated over the many years of their workshop.

     Workshop project work entails organizing these disparate scripts into an R package, as well as preparing tests for the assorted simulations and refining their implementation.  Longer term work could include continued polishing, and extension of the package to include additional pedagogical tutorials.

 - **Visualization of Simple HIV Transmission + Models** (CABP):
 HIV is a global scourge, with a particularly heavy burden in African nations.  The UNAIDS program currently uses an Excel spreadsheet model for assorted analyses, but this model is difficult to verify and extend.

    Workshop project work entails starting re-implementation this model in the Rshiny framework, an interactive GUI framework for R, to enable future extension, improve verifiability of the model, and to end dependence on obsolete Excel versions.  Longer term work would fall into those veins.

 - **Data Mining for Pharmaceutical Discovery**: MKD
 - **De-noising High-Throughput Sequencing Data**: Maybe EL, Maybe NR
 - **Bayesian Analysis of Haemaglutenation-Inhibition Results**: EL
 - Sofiat's Graph Theory One: NR, EL
 - **Zero-inflated Poisson Model**: No NR, Maybe EL