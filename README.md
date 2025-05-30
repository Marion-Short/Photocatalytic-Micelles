# Photocatalytic-Micelles
Predicting performance of catalytic micelle system and extracting feature importance.

Photocatalytic system which forms micelles in water and catalyses the reduction of CO2 and H2O to CO and H2, respectively. The system is comprised of the following components:

- catalyst ('Cat')
- photosensitiser ('PS')
- surfactant ('Surf.')
- reductant ('Red.')
- buffer ('Buf')

The concentration of each component was varied and the turn over frequency (TOF) of CO ('TOFCO / min−1') was measured. The features and target variables are continuous, hence this dataset can be modelled using supervised regression machine learning models to predict the TOF of CO. This dataset was obtained from the following publication: https://doi.org/10.1021/jacs.4c01305

The photocatalytic micelle dataset can be modelled with tree-based stochastic gradient boosting regression which clearly illustrates the threshold behaviour of the buffer concentration (indentified as the most important feature by SHAP analysis) on the catalytic system.
