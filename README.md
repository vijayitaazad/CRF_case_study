# CRF_case_study

# Ingredient and Unit Classification Model

This repository contains a machine learning model designed to classify ingredients, units, and quantities from a given dataset. The model is trained using **Conditional Random Fields (CRF)** and performs Named Entity Recognition (NER) on a food-related dataset, identifying and categorizing tokens such as ingredients, quantities, and units.

## Features

- **Named Entity Recognition (NER):** Classifies food-related tokens into categories such as `ingredient`, `unit`, and `quantity`.
- **CRF-based Model:** Uses Conditional Random Fields (CRF) with feature extraction to identify food-related entities.
- **Error Analysis and Insights:** Provides detailed misclassification analysis for validation datasets, helping improve model performance.
- **Class Weight Adjustment:** Adjusts class weights to penalize misclassifications of less frequent labels.
- **Evaluation Metrics:** Includes flat classification reports, confusion matrices, and label-wise accuracy analysis.

