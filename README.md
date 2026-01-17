# Scalable-Edge-AI-Frameworks-for-Forest-Health-Prediction

A scalable simulation framework for predicting forest health using Edge AI principles. This project integrates real-time environmental data from NASA and World Bank APIs, employs random forest ensembles for efficient predictions, and prepares models for edge deployment. Focused on sustainable environments, it's ideal for deforestation monitoring— with potential extensions for Sri Lanka's tropical forests like Sinharaja.
Inspired by trends in Edge AI for sustainability, this repo demonstrates algorithmic innovations without hardware dependencies.

## Features

**1. API Data Fusion:** Parallel fetches from World Bank (temperature/rainfall) and NASA POWER (soil moisture) for global country-level data.

**2. Scalable Modeling:** Random Forest Regressor optimized for edge (shallow depth, parallel training) to predict forest health scores.

**3. Reproducibility:** Full centroids dictionary for ~200 countries; handles NaNs and exports models via Joblib.

**4. Sustainability Focus**: Low-compute params for energy-efficient inference; feature importances for interpretable insights (e.g., temperature's role in deforestation).

**5. Extensibility:** Placeholder for biodiversity index—ready for real API integrations (e.g., GBIF).

## Data Sources

* Deforestation CSV: GitHub Repo
* Climate Data: World Bank Climate Knowledge Portal API
* Soil Moisture: NASA POWER API (GWETROOT parameter)
* Centroids: Compiled from public sources (UN/Google datasets)
