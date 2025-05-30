# Photocatalytic-Micelles
Predicting performance of catalytic micelle system and extracting feature importance.

Photocatalytic system which forms micelles in water and catalyses the reduction of CO2 and H2O to CO and H2, respectively. The system is comprised of the following components:

- catalyst ('Cat')
- photosensitiser ('PS')
- surfactant ('Surf.')
- reductant ('Red.')
- buffer ('Buf')

The concentration of each component was varied and the turn over frequency (TOF) of CO ('TOFCO / min−1') was measured. Hence, the concentrations of each component can be modelled to predict the TOF of CO. This dataset was obtained from the following publication: https://doi.org/10.1021/jacs.4c01305

The model predicts the buffer concentration as the most important feature affecting TOF, whereby low buffer concentrations increase the TOF until ~550 mM, after which increasing the buffer concentrations negatively impacts the TOF. This can be rationalised by the micelles salting out at high buffer concentrations, which hinders catalysis.
