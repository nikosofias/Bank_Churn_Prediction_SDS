# Bank_Churn_Prediction_SDS

1) RUN EDA.ipynb
2) RUN Modeling.ipynb

## Code Reproducibility

1) Load image of experiments: docker load < ds-project-nikos.tar
2) Run experiments with the names: 'Modeling_exp_v01.py', 'Modeling_exp_v02.py', 'Modeling_exp_v03.py'
3) Run the best model (LightGBM) with 2 possibilities: 1. Optimization (docker run ds-project-nikos python3 Modeling_final.py --optimization="True") and 2. Optimized version (docker run ds-project-nikos python3 Modeling_final.py --optimization="False")
