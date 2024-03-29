---
layout: cv
title: Zeping Li
email:
  text: lzp632697@gmail.com
homepage:
  text: https://github.com/RL-LBAM/MyProjects (project report repository)
---

# Zeping **Li**

<!--
include contact information from the front matter
Supported arguments:
    - homepage: url, text
    - phone
    - email
-->

{% include cv-contact.html %}

## Education

### **University of Edinburgh** `09/2022–11/2023`

```
Edinburgh, UK
```

*MSc in Artificial Intelligence*



Relevant Courses: Machine Learning and Pattern Recognition; Machine Learning Practical; Probabilistic Modelling and Reasoning; Natural Language Understanding, Generation and Machine Translation

### **University of Warwick** `10/2020–10/2021`

```
Coventry, UK
```

*MSc in Behavioural and Economic Science* 80/100 (ranked first)



Relevant Courses: Principles of Cognition; Neuroeconomics; Behavioural Microeconomics; Psychological Models of Choice; Bayesian Approaches in Behavioural Science

### **Zhejiang University** `09/2016–07/2020`

```
Zhejiang, China
```

*BSc in Psychology* 86/100  
Relevant Courses: Calculus; Linear Algebra; Probability and Mathematical Statistics; Stochastic Processes; Sampling Theory; Mathematical Physics

## Research Experiences

### **Modelling Object Co-Occurences in Images** `02/2023–09/2023`
*Supervisor: Professor Chris Williams*  
Modelled high-dimensional object count data from COCO dataset using VAE, mixture, discrete flow and discrete diffusion models. 

Proposed a sequence-to-set variational autoencoding transformer modeling the sparse counts as sets. 

Compared the models using the test set likelihood and sample quality (introducing a discriminator network).

Found the sequence-to-set model achieved the highest test set likelihood, while the discrete diffusion model generated samples closest to the empirical data.

### **Deep Bayesian Active Learning with Hybrid Query Strategies** `01/2023–05/2023` 
*Team Work*

Proposed 2 computationally efficient metrics to measure the distance between a data point and a collection of data points.

Developed 54 hybrid query strategies by considering 3 uncertainty metrics, 3 diversity metrics, and 6 combination methods.

Compared the hybrid and pure query strategies in 2 image classifiacation tasks using deep Bayesian active learning (implemented through MC dropout).

Found the hybrid query strategies performed better in the difficult task. Their advantage decreased but still existed with more queried data points.

### **Human Probability Judgments: A Bayesian Sequential Sampler Account** `02/2021–09/2021`
*Supervisors: Professor Adam Sanborn & Professor Nick Chater*  
Extended a sampling-based model to explain human probability judgments as Bayesian inference. 

Collected data through an online experiment. 

Fitted the model using moment matching between the simulated and empirical data. 

Compared its variants with different stopping rules using the Wasserstein distance between the simulated and empirical distributions.

Found task condition (accuracy emphasized/speed emphasized/ambiguous stimuli) could change the choice of stopping rule and the underlying cognitive processes.

### **A Model Comparison Study for Human Choices in Two-Armed Bandit Problems: Reinforcement Learning and Win-Stay-Loss-Shift Heuristics** `09/2019–07/2020`  
*Supervisor: Associate Professor Junyi Dai*  
Modelled human choices in two-armed bandit problems using the temporal difference reinforcement learning and the win-stay-loss-shift heuristics. 

Fitted the models using maximum likelihood. 

Compared their variants with different learning rules on one-step-ahead (BIC and test set likelihood) and long term predictive abilities (MSE between the simulated and empirical choice sequences).

Found the heuristics model explained the human choices better.

## Projects
### **Machine Translation Systems with Transformers Using Lexical Models** `2023`
### **A Review of Dirichlet Process Mixture Models for Clustering and Density Estimation** `2022`
### **A Review of Sequential Sampling Models in Computational Cognitive Neuroscience** `2021`
### **A Comparison of Different Generalized Cognitive Hierarchy Models for Matrix Games** `2020`


## Work Experience
### **Shokz** `05/2022–09/2022`
```
Shenzhen, China
```
*Data Analyst*   
Developed and maintained the sales data dashboard. 

Utilized time-series models to forecast the sales data during promotional periods..

### **Openverse** `09/2023–Now`
```
Hangzhou, China
```
*Multimodal Research Engineer* 

Clustered blackhole images based on painting styles using the BLIP model, incorporating prompting techniques. 

Finetuned the stable diffusion model using LoRA to generate blackhole images in various styles. 

Incorporated astronomical knowledge into the model to ensure the generation of scientific images.

## Computational Skills
**Programming:** MATLAB, Python(Numpy, Pytorch), R(Tidyverse), SQL  
**Statistics:** Stan, JASP, SPSS, PowerBI
## Research Interests
I used to be a fan of cognitive modeling, which views the mind as a computing machine that can generalize from few labeled data. Now I focus more on probabilistic (mainly Bayesian) machine learning, no matter for the traditional part (e.g., Bayesian nonparametrics), or the modern deep learning part (e.g., deep generative models). I am recently interested in using neural networks to estimate parameters of intractable models (e.g., training a neural network to recover the parameters from synthetic data generated by the target model), and enhancing traditional statistical learning with neural networks like how VAE enchances factor analysis.


<!-- ### Footer

-->
