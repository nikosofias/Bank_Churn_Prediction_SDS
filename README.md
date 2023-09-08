# Bank_Churn_Prediction_SDS

1) Inspect EDA.ipynb for visualizations
2) Inspect Modeling.ipynb (all experiments in one file) 

## Code Reproducibility

1) Load image of experiments: docker load < ds-project-nikos.tar
2) Run experiments with the names: 'Modeling_exp_v01.py', 'Modeling_exp_v02.py', 'Modeling_exp_v03.py'
3) Run the best model (LightGBM) with 2 possibilities: 1. Optimization (docker run ds-project-nikos python3 Modeling_v04.py --optimization="True") and 2. Optimized version (docker run ds-project-nikos python3 Modeling_final.py --optimization="False")
4) See the results for the best model: docker run ds-project-nikos python3 Modeling_final.py
