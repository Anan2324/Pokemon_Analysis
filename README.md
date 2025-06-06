# Pokemon_Analysis

## 📥 Dataset Source

The dataset used in this project was sourced from **Kaggle**:  
🔗 [Pokemon with stats – by abcsds on Kaggle](https://www.kaggle.com/datasets/abcsds/pokemon)

This project explores what makes a Pokémon *legendary* using data analysis and machine learning techniques in R. With guidance from the legendary Professor Oak, we dive into a Pokédex of 801 Pokémon to identify key traits that separate legendary Pokémon from the rest.

## Project Objectives

- Import and clean Pokédex data
- Visualize Pokémon by height and weight
- Compare fighter stats across legendary and non-legendary Pokémon
- Build machine learning models to predict legendary status

## Tools & Libraries

- **R** & **R Markdown**
- **tidyverse** for data manipulation and visualization
- **ggplot2** for plotting
- **rpart** for decision trees
- **randomForest** for ensemble modeling
- **ROCR** for model evaluation via ROC curves

## 🔍 Key Insights

- Only **8.7%** of Pokémon are legendary.
- Legendary Pokémon often have higher **fighter stats** (attack, defense, speed, etc.).
- Height and weight also show patterns among legendary Pokémon.
- A **random forest** model achieves ~93% accuracy, outperforming the decision tree baseline.

## 📁 Files

- `Pokemon_Analysis.Rmd` – the full analysis in R Markdown
- `datasets/pokedex.csv` – the Pokédex dataset
- `README.md` – project overview

## Getting Started

1. Clone the repository.
2. Open the `.Rmd` file in RStudio.
3. Run all chunks to see the full analysis and model outputs.
4. Make sure the `pokedex.csv` is placed in the correct `datasets/` directory.

## Example Outputs
- 📍 ROC curve comparing Decision Tree vs Random Forest
- 📦 Boxplots of fighter stats by legendary status
- 🧬 Decision tree explaining classification criteria



