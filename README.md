# Bioinfomatics-ml-predictions
### Comparison of various methods of machine learning algorithms for protein structure prediction


Input: protein sequence


| Dimensions  | Methodology | Performance Metrics | Input Data | Output Data |
|------------------|-------------|---------------------|------------|-------------|
|  1     | NN, Feed forward NN     |8% below the predicted limit of 88% -                   | Protein Primary Sequence | Amino Acid Features |
|  2     | NN, Recursive NN, Self-Organizing Maps, SVM| Average Precision and Recall around 50% | PPS, output 1 | Bio Contact Map |
|  3     | Content Cell | - | PPS, output 1, output 2 |  fold recognition, model generation , and model evaluation |
|  4     | Content Cell | - | PPS, output 1, output 2, output 3 | Relationship between 3d structure  |




## **Machine Learning Methods for Protein Structure Prediction**

In this project, we plan to compare the performance of several pre-existing machine learning models, including deep learning models such as convolutional neural networks (CNNs) and recurrent neural networks (RNNs), as well as traditional machine learning models. We will use publicly available datasets of protein sequences and their corresponding structures to train and evaluate these models. We will also compare the performance of these models with traditional methods such as homology modeling.

We will collect a suitable dataset of protein sequences and their corresponding structures from publicly available databases. We will then perform feature extraction on these sequences to convert them into a suitable representation that can be used as input. We can use that to train the pre-existing machine learning models and evaluate these models compared to each other and to traditional methods. The main metric we will use to evaluate each model would mainly rely on prediction accuracy compared to the real structure of the protein. We can use python to implement the project. 

To analyze the results, we will compare the performance of the pre-existing machine learning models with each other, and with traditional methods such as homology modeling. We will investigate the impact of different factors on prediction accuracy, such as the size of the protein sequence, the amount of training data available, or the use of additional information such as evolutionary conservation.



Technologies effieicny overview:

Main machine learning modules:
- Hidden Markov Models
- Neural Networks
- Support Vector Machines

1 Dimension:
* Input: Protein Primary Sequence
* Output: Predicted features of amino acids
* Goal: 
* Analysis: from past to present (50 % -> 78% - 80%) when using traditional correlation to neural networks
* Methodology: instead of using 

2 Dimension:
* Goal: Spatial Relationship between residue, Prediciton of protein contact maps:
* 
* 
    
3 Dimensions:
* Goal: Prediction of structural protein complexes 
* Methods: Non neural networks, Hidden Markov Models, SAM, viterbi algorithm
* Monte Carlo methods
* Fragment Assembly toll Rosetta -> Clustering techinique

4 Dimensions:
* Goal: Prediction of strucutral protein complexes comprised of several folded protein also known as protein docking
* Methods:
    * Rosetta Clock
    * Adap 3D - 4D problems
    * 4D grid Fourier transformation method to dock protein subunits together


Common bottlenecks:
- Size of conformation space
- Not yet develoepd for membrane protein becuase of not having enough data
- There are still optimization that can be done


