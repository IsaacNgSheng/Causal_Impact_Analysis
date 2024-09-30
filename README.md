# Causal Impact Analysis and Experimental Design in Marketing and Recommender Systems

## Overview
This project investigates multiple real-world data science problems, including causal impact analysis for marketing campaigns, A/B testing in recommendation algorithms, demand estimation for a ride-sharing service, and experimental design in e-commerce. The analysis applies statistical methods to evaluate the effectiveness of business strategies and experiments, with a focus on identifying causal relationships and providing actionable insights.

## Motivation
Understanding the causal impact of business strategies and marketing interventions is essential for optimizing decision-making. This project aims to refine techniques for measuring the true return on investment (ROI) in advertising, optimize recommendation algorithms, and provide strategic pricing recommendations. My approach focuses on leveraging statistical models and data science to drive business outcomes more effectively.

## Technologies Used
R for statistical analysis and simulations
ggplot2 for data visualization
Regression and A/B Testing techniques for causal inference
Instrumental Variables (IV) for addressing endogeneity in demand estimation
Custom t-tests and Permutation tests for statistical significance

## Project Structure
code/: Contains the R scripts for analysis, including A/B testing, demand estimation, and experimental design.
data/: Experimental datasets used for analysis, including customer data, ride-sharing data, and platform usage data.
results/: Output files, including tables and visualizations that summarize the findings.
README.md: This documentation.

## Methodology
This project is divided into four key sections, each analyzing a distinct business problem:

Causal Impact of KOL Advertising:
- Critique the current method of evaluating YouTuber ads using promotion codes.
- Propose a more robust method for determining the ROI of ads using regression analysis and causal inference.

A/A Testing in Tikkot’s Recommender System:
- Verify random assignment in the treatment and control groups.
- Estimate the average treatment effect (ATE) using various statistical methods, including t-tests and regression analysis.
- Investigate the role of gender, registration date, and operating system in influencing the treatment effect.

Demand Estimation for a Ride-Sharing Platform:
- Perform OLS regression to estimate demand.
- Address potential endogeneity with an Instrumental Variables (IV) approach.
- Provide optimal pricing recommendations based on weekend and location data.

Experimental Design in Ladaza E-commerce:
- Visualize gender-based distributions for key performance metrics.
- Calculate the sample size required for a statistically significant experiment.
- Run AA tests to critique a dynamic stopping rule for experiments.

## Key Results
KOL Advertising: Identified the potential for bias in using promotion codes and proposed a regression-based approach for better ROI estimation.
Tikkot Recommender System: Verified random assignment and provided statistically significant evidence that the new recommendation algorithm increases user engagement.
Demand Estimation for Grad: Developed an IV-based demand function and proposed optimal pricing strategies for different regions and times.
Ladaza Experiment Design: Highlighted flaws in the dynamic stopping approach, particularly the elevated false-positive rate in AA tests.

## Conclusion
This project showcases the application of advanced causal inference and experimental design techniques in solving real-world business problems. The results provide actionable insights into optimizing advertising strategies, improving recommender systems, and making data-driven pricing decisions.
