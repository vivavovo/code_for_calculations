# All the Code Related to Calculations in Our Work
This repository contains all the necessary code for calculations discussed in our manuscript. The code implements key mathematical models, including Poisson distribution calculations, event probabilities, Kullback-Leibler (KL) divergence, and relevance calculations. These are central to the analysis and experiments presented in the paper.  
  
### The code implements the following key features:  
**Poisson Distribution:** Computes probabilities for events in both narrow and wide domains.  
**Prior and Posterior Probabilities:** Calculates probabilities for different event scenarios, including the effect of domain expansion.  
**KL Divergence:** Measures the intensity of belief update after domain expansion.  
**Relevance Calculation:** Computes the relevance of events, showing how the widening of the domain (e.g., using "any") impacts the probability of encountering counterexamples and belief updates.  
  
### Dependencies:
To run the code, you need the following Python packages:  
**NumPy:** For general-purpose numerical operations.  
**SciPy:** For statistical functions, particularly Poisson distribution calculations.  
**mpmath:** For mathematical operations, such as logarithms used in KL divergence.  
**sentence-transformers:** For calculating sentence embeddings and cosine similarity.  

### Running the Code:
Since this code involves downloading Python packages and running specific calculations, you can choose to run it on a platform that supports Python packages, such as Google Colab. This platform allows you to run Python code in a notebook without needing to install anything locally.

#### 1. Google Colab
Open [Google Colab](https://colab.research.google.com/)  
Upload the notebook or copy the code into a new Python 3 notebook.  
Run the code in the Colab environment and see the results immediately.
#### 2.Local Environment:
If you prefer running the code locally, ensure Python 3.9 and the required packages are installed.  
Clone this repository or download the notebook script.  
Run the script in your Python environment.
 
