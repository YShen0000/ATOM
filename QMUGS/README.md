### Introducition
The first dataset for model training is QMUGS dataset(over 3000k rows). Specifically, the goal is to train regression models(RF, NN) with featurizers(graphconv, ECFP) to predict the HOMO_LUMO gap value of each compound baseds on features in the dataset.

General Process:
- data loading
- data curation
- EDA
- search for functional groups in each compound
  - split the dataset based on functional groups
- train models for each subdataset
- view results
