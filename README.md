# Bayesian Network Implementation for Fraud Detection

## Introduction:
This code implements a Bayesian network for fraud detection. It models the dependencies between various factors such as travel, foreign purchases, owning a device, and online purchases to predict the likelihood of fraud.

## Requirements:
To run this code, you need to have the following packages installed:
- pomegranate==0.14.9
- matplotlib
- pandas
- networkx
- seaborn

You can install the required packages using pip:
```
pip install pomegranate==0.14.9 matplotlib pandas networkx seaborn
```

## Usage:
1. Install the required packages.
2. Run the code in a Python environment.
3. Ensure that the necessary data structures and functions are loaded.

## Code Explanation:

### Bayesian Network Construction:
- Nodes and their conditional probability tables (CPTs) are defined for each variable: travel, foreign purchase, owns device, online purchase, and fraud.
- A Bayesian network is created, and nodes are added with their respective dependencies.

### Visualization:
- A directed graph representing the Bayesian network is plotted using NetworkX and matplotlib.
  
  ![Bayesian Network Structure](https://github.com/Abhrajyoti00/AI_Assignments/blob/main/BN_Structure.png)

### Inference:
- Gibbs Sampling is performed to predict fraud under different scenarios.
- Variable Elimination is used to find probabilities under different evidences.

### Metropolis-Hastings Algorithm:
- Metropolis-Hastings algorithm is implemented to generate samples from a given target distribution.

## Results:
- Probability of fraud under different evidences is computed.
- Histograms and Markov chains are plotted for samples generated using the Metropolis-Hastings algorithm with different sigma values.

## Conclusion:
This code demonstrates the construction and inference of a Bayesian network for fraud detection, along with the implementation of the Metropolis-Hastings algorithm for sampling.

---

Ensure that the link to the image is accessible and replace it with the correct URL if needed.
