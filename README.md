# Data Preprocessing in R (Multi-Source Integration & Tidy Workflow)

> A complete, reproducible preprocessing pipeline in R for merging, tidying, transforming, and quality-checking multi-source datasets.

## Project Overview
This project demonstrates a complete data preprocessing workflow in R, covering dataset integration, reshaping, transformation, and data quality management. It highlights proficiency with tidy data principles, type handling, and reproducible techniques to produce analysis-ready datasets.

## Data Sources
Open datasets (Creative Commons–compatible) were selected across domains such as Australian crime statistics, per‑capita income, and related socio‑economic indicators. Sources were chosen for transparency, shareability, and relevance to multi‑domain analysis.

## Scope and Methods
- **Merging & Integration:** Combined two or more datasets (e.g., crime and per‑capita income) to form a unified analysis table.  
- **Schema & Types:** Worked with numeric, character, and factor variables; implemented appropriate type conversions (character → factor/date, numeric → factor).  
- **Factors & Ordering:** Labeled and ordered factor variables to ensure clear, meaningful categories.  
- **Tidying Untidy Data:** Identified untidy structures, justified why they were untidy, and transformed them into tidy, analysis‑friendly formats.  
- **Feature Engineering:** Created derived variables (e.g., a savings metric from income and expenses) to enrich analytical value.  
- **Data Quality:** Systematically scanned for missing values, special values, and data errors; applied documented remediation strategies.  
- **Outliers:** Detected and treated outliers in numeric features using appropriate, well‑reasoned methods.  
- **Transformations:** Applied variable transformations to address scale, normalize distributions, or linearize relationships.  
- **Communication:** Summarized approach and outcomes in a 3–5 minute video presentation.

## Tooling
Implemented in R using **readr**, **dplyr**, **tidyr**, **ggplot2**, and custom helper functions. Emphasis on clear, reproducible code following tidyverse conventions.

## Learning Outcomes
- Confidently integrate heterogeneous datasets and manage data types.  
- Apply tidy data principles to restructure and enrich data.  
- Implement robust data quality checks and defensible treatments for missingness and outliers.  
- Produce transformation choices that support valid statistical analysis and modeling.

