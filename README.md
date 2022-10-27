### credit-risk-modelling based on Probabilistic graphical models

Formulate Bayesian Network Models ( Include deep probabilistic learning Models too) for modelling credit risk on FNMA Multifamily loan performance data. 

Compare the model performance against classical Machine learning models and deep neural network Model.

- Data Exploration

- Data Pre-processing and cleaning

- Data Visulization

- Fearure Transformation

- Data Preparation

- Model Building & Evaluation

1) Bayessian Network Model (with Deep Probabilistic Model)
    Defining Prior & Posterior distribution of weights.
    BNN Model Creation, Compilation & training
    Loss Curve, ROC curve, confusion matrix
    
2) Machine Learning Model
    Construct decision tree model
    Loss Curve, ROC curve, confusion matrix
    importance feature selection
    
3) Deep Neural Network Model
    3 hidden layer is used
    Early stopping
    Loss Curve, ROC curve, confusion matrix
  
- Analyzing the parameter relationship & Creating bayesian network model

    Model Baysian Network
    Trying to understand & validate the impact of parameter on identified target class (SDQ Indicator)
    Inferencing with Bayesian Network
    Structural Learning based on HillClimbSearch & BDeuScore
   
- Result
    Since we have trained a BNN model (epistemic) , the model produces a different output each time we call it with the same input, since each time a new set of weights are sampled from the distributions to construct the network and produce an output. The less certain the mode weights are, the more variability (wider range) we will see in the outputs of the same inputs. The same has been observed in the loss curve for BNN network

Also based on our training data, we found that all model is performing well for credit risk with deep learning giving the best result.
