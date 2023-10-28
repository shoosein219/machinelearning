# machinelearning examples
Model architecture: (1) Random Forest (2) Neural Networks

## 1. Random forest regressor: training model.py ##
 USING Parallel/Bootstrap Aggregation (Bagging) method: creates training subset from sample data

data used: https://www.kaggle.com/datasets/usharengaraju/indian-women-in-defense

RNA-seq data from the human airway smooth muscle (HASM) transcriptome  
Data collected to understand treatment of drugs on asmatic patients
testing the effect of glucocorticosteroidal use in combination with more the common Albuterol treatment

[Exploratory_ML ipynb_script](/Ex_MLwithGeneExpData.ipynb)

GRAPHS
- Histogram
  ![Histogram](/figure_1.png)
- actual vs. predicted values

## 2. Boosting algorithms via neural network models ##

[PyTorch_ipynb script](/PyTorchExample.ipynb)

1. Split and Pre-process data
2. Define model of neural network
3. Define loss and optimizer
4. Train and evaluate model

   
VIZ_1: Model integrity - line graphs (1) Training Loss: epochs vs loss (2) Testing Accuracy: epoch vs accuracy
![Model_integrity](/Model_integrity.png)

VIZ_2: Model-Layer2 integrity - heatmap (1) heatmap/matrixviz of layer 2
![Model-Layer2 integrity](/Model-layer2_integrity.png)

VIZ_3: Feature Importance - barchart (1)
 ![feature importance](/Barchart_RFC_featureimportance.png)

## Part 3: Tensorflow (deep learning method for AI product development)
[Tensorflow ipynb_script](/TensorFlowTraining.ipynb)
1. Data pre-processing
2. Data splitting
3. Model Architecture
4. Model Compilation
5. Training
6. Evaluation
