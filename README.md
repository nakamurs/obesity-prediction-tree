# Obesity Prediction using Classification Trees

This project aims to build a **classification tree** to predict whether or not an individual is *obese* based on their eating habits and physical condition.

It follows these steps:
1. **Load the Dataset**
2. **Identify Missing Data**
3. **Format the Data for Decision Trees**
4. **Build a Preliminary Classification Tree**
5. **Apply Cost Complexity Pruning**
6. **Perform Cross Validation**
7. **Build and Interpret the Final Classification Tree**
  
## Structure

- [`obesity_prediction_tree.ipynb`](obesity_prediction_tree.ipynb): Main Jupyter notebook with code, results, and observations.
- [`obesity_prediction_tree.pdf`](obesity_prediction_tree.pdf): PDF version of the notebook, formatted for readability.
- [`ObesityDataSet_raw_and_data_sinthetic.csv`](ObesityDataSet_raw_and_data_sinthetic.csv): Dataset derived from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition).

## Libraries
- `pandas`: Data handling
- `NumPy`: Numerical operations
- `Matplotlib`: Plotting
- `scikit-learn`: Decision tree and model evaluation
  
## Source
StatQuest with Josh Starmer. (2020, June 6). Classification Trees in Python from Start to Finish [Video]. YouTube. https://youtu.be/q90UDEgYqeI
