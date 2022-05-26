[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 

<img src="https://raw.githubusercontent.com/DataDisca/django_api1/master/DataDisca-Logo.svg_d400.png" width="75" height="25" />

# Clustering Algorithms

We study frequently used clustering algorithms in this exercise.  

## Objectives

To study:
1. Python [openml](https://docs.openml.org/Python-examples/)
1. Data preparation
3. Clustering algorithms 
4. Performance measures
5. Hyper-parameter tuning
6. [joblib](https://joblib.readthedocs.io/en/latest/) library
7. Data visualisation

## Branch
 Make sure you know your branch of this module.  
 We continue to improve the modules based on your feedbacks and submitted outputs. 
 Therefore, we create a branch for you when we assign the module.  
 Go through the `README.md` of your branch.
 
 ARE YOU READING THE RIGHT BRANCH?
 
 If there is any doubt contact DataDisca.

This code is hosted in a private repository to regulate access.
After completing the module, you can host your work in an open repository under MIT license. 

Please help us by reporting all type of errors. 

## License
This code is hosted in a private repository to regulate access. 
You can share your data & code under MIT license.
  
## Datasets:
| Dataset | Instances | Classes | Missing Values| URL |
| --- | --- | --- | --- | --- |
|[iris](https://www.openml.org/d/61) | 150 | 3 | 0 | https://www.openml.org/d/61 |
|[wine](https://www.openml.org/d/187) | 178 | 3 | 0 | https://www.openml.org/d/187|
|[glass](https://www.openml.org/d/41)| 214 | 6 | 0 | https://www.openml.org/d/41 |
|[haberman](https://www.openml.org/d/43)| 306 | 2 | 0 | https://www.openml.org/d/43 |
|[libras_move](https://www.openml.org/d/299) | 360 | 15 | 0 | https://www.openml.org/d/299 |
|[satellite_image](https://www.openml.org/d/294)| 6435 | 6 | 0 | https://www.openml.org/d/294 |
|[isolet](https://www.openml.org/d/300)| 7797| 26 | 0 | https://www.openml.org/d/300|
|[nursery](https://www.openml.org/d/26) | 12960 | 5 | 0 | https://www.openml.org/d/26 |
|[gas-drift-different-concentrations](https://www.openml.org/d/1477)| 13910 | 6 | 0 | https://www.openml.org/d/1477 |
|[MagicTelescope](https://www.openml.org/d/1120)|19020| 2| 0 | https://www.openml.org/d/1120 |
|[letter](https://www.openml.org/d/6) | 20000 | 26 | 0 | https://www.openml.org/d/6 |
|[covertype](https://www.openml.org/d/150)| 581012|7|0 | https://www.openml.org/d/150 |
      
### Instructions
Follow the steps given below.

#### Step 1
 
 Study the following algorithms.       
 
1.  K-Means
1.  Agglomerative 
1.  DBScan
1.  Optics
1.  Gaussian mixtures
1.  Affinity propagation 
1.  Mean-shift 
1.  Spectral  
1.  Ward hierarchical 
1.  Birch
1.  Self organising maps
    
At the end of the excercise, you should be able to answer the following questions.
1. What are the important parameters in each algorithm? 
1. How and why those parameters affect the results of respective algorithms?

#### Step 2

Follow the steps given below to write your code.
1. In your code, download a dataset  using Python `openml` package
1. Prepare data
    1. Identify the data types: boolean/categorical, ordinal, numeric in this case. But there can be many other types as well.
    1. Transform categorical variable to numeric as necessary     
    1. Min-max normalise
1. Write a [joblib](https://joblib.readthedocs.io/en/latest/) code  to walk through the parameter grid
1. Record `f1_score`, `adjusted_rand_score` , `silhouette_score` and execution time 
against each parameter combination identified in Step 1.
1. Save the results to CSV files.  

#### Step 3

1. Execute your code over all the algorithms and all the datasets.
1. Save your results to CSV files.

#### Step 4

1. Create Tableau Dashboards or Plotly visualisations to analyse your results.
1. With visualisations:
    1. for each dataset compare and contrast results produced by each algorithm under optimal parameter settings
    1. for each given algorithm, how `f1_score`, `adjusted_rand_score` and `silhouette_score`  vary with the different parameter values
    1. Discuss the execution times of algorithms and their parameter settings? 
1. What are the most important parameters in each algorithm
1. Create a presentation or a pdf document or a Jupyter Notebook explaining the theory and applications of `f1_score`, `adjusted_rand_score` and `silhouette_score`.    

## Quality Standard of Your Work
1. Code should follow PEP8 Standard
1. Host your code on your GitHub in a public or private repository as you prefer. 
- If it is a public repository, send the link for us to evaluate.
- If it is a private repository, share (view only) with our GitHub usernames. Please contact us for them.

    Send us a notification to start the evaluation.
    We evaluate your code for your technical progress.

## Sponsor
DataDisca Pty Ltd, Melbourne, Australia

[https://www.datadisca.com](https://www.datadisca.com)


![very interting](https://user-images.githubusercontent.com/71443389/170477030-33e6ea00-9be8-4382-ae41-6ea49690b374.jpg)
