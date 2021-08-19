### [Home](README.md) | [Projects](Projects.md) | [Resume](docs/Adam_R_Rohde_Resume.pdf)


---

Find my latest projects below! More to come! See my resume for brief descriptions of my work at Charles River Associates. 


### Internal Validiy and Sample Selection Bias (In Progress)
with Chad Hazlett

Goal is to argue that internal causal quantities (causal quantities for the selected sample only) are of interest in many settings, that sample selection poses a threat to internal validity and hence that sample selection should be included in all causal models, and to present a formal criterion for determining recoverability from sample selection for internal causal quantities as well as lessons and examples for applied researchers. 

---
### Sensitivity Analysis for Internal Sample Selection Bias (In Progress)
with Chad Hazlett

Goal is to build a sensitivity analysis framework for internal sample selection bias by showing how certain types of internal sample selection bias can be viewed as omitted variable or common cause confounder bias. Focus is on how regression coefficients change when relevant variables are omitted and the user considers relationships of varying strengths between the treatment and confounder and outcome and confounder. Difficulties in interpretability of sensitivity parameters arise do to the nature of how sample selection of this sort manifests as confounding (i.e., via conditioning on a collider). 

---
### Big Data Big Problems (In Progress)
with Chad Hazlett and Carlos Cinelli

Building off of Cinelli and Hazlett (2020), we use sensitivity analysis in linear regression models to highlight a simple fact: large samples make it more likely that weak (or spurious) relationships will be statistically significant, which can mislead practitioners. Discussion of effect importance ought to incorporate uncertainty from identification as well as estimation. The focus of this paper is to demonstrate that this becomes increasingly more important as sample size increases.

---
### ATP Tennis Match Data Analysis (In Progress)

I explore and analyze ATP match level data from 1968 to 2020. The goal is to have some fun exploring historical match data and to see what interesting trends we can uncover. The code and discussion of results are all in Jupyter notebooks at this point (see repository). The work I've done so far and hope to do includes:

* Explore the data.
* Cleaning the data and building a database.
* Calculating Elo Ratings.
* Performing simple analyses that I found interesting. There will surely be more of these to come. 
    * Are older players doing better?  
    * How many matches are typically in a player's career and how many years does a typical career last?
    * How many players have been ranked number 1 and how can we visualize which players dominated during different periods of time?
    * How do the results for best-of-three versus best-of-five set matches differ? (In Progress)
    * How does handedness effect matchups? (In Progress)
* Build models for predicting match winner incorporating match and player information, head-to-head statistics, as well as Elo ratings. (In Progress but there is some initial work on this.)
* Build a web app that provides player profiles, match up predictions, match up histories, Elo ratings, other fun things.  (In Progress)

[Repository](https://github.com/Adam-Rohde/ATP-Tennis)

![](images/EloRatingsByAge.png)

---
### Modern Model-Based Bayesian Causal Inference for Randomized Experiments with Hamiltonian Monte Carlo in Stan

We explore the components of modern model-based Bayesian causal inferenece with a focus on randomized experiments. We discuss the potential outcomes framework, the Bayesian approach to causal inference, the MCMC sampling method Hamiltonian Monte Carlo, and the Stan probabilistic programming language. We also work through a simple example to illustrate how these components come together.

[Paper](docs/Bayesian-Causal-Inference-for-Randomized-Experiments-with-HMC.pdf)

[Repository](https://github.com/Adam-Rohde/Bayesian-Causal-Inference-for-Randomized-Experiments-with-HMC)

![](images/PosteriorDistributions.PNG)

---
### Political Extremism and Election System: A Study of Confounding of the Results of Single Round versus Runoff Elections under Plurality Rule
with Xuan Huynh, Andrew Shapiro, and Brandon Thoma

The conclusions of Bordignon, Nannicini, and Tabellini (2016) with respect to the effects of runoff elections on political participation and policy volatility provide informative results that positively add to the discussion of the benefits of different electoral systems on societal political behavior and economic stability. The sensitivity of the authors’ results survive the most common robustness challenges under a Regression Discontinuity Design, yet unobserved confounding ultimately remains possible but unable to be fully explored due to lack of Italian-specific knowledge. Additional studies are ultimately necessary to validate the results for a more recent Italian electorate, and to study the ability to generalize such results to countries outside of Italy.

[Paper](docs/Political-Extremism-and-Election-System.pdf)

[Slides](docs/Political-Extremism-and-Election-System-Slides.pdf)

[Repository](https://github.com/Adam-Rohde/Political-Extremism-and-Election-System)

![](images/lowess_sep.png)


---
### Cooking Up Recipes: A Recipe Recommender Based on Text Similarity
with Ashley Chiu and Ritvik Kharkar

In this project we use a range natural language processing techniques (bag of words, Doc2vec, recurrent neural networks-based LSTM models, and pre-trained language model BERT) to learn vector space embeddings for cooking recipes. We use these embeddings to determine similarity between recipes and recommend such similar recipes, based on user input to a web demo app. We assess the quality of recommendations and embeddings by human review, PCA, and cluster analysis, finding that our models produced mixed results. Generally, simpler models seem to perform best.

[Paper](docs/Cooking-Up-Recipes-A-Recipe-Recommender-Based-on-Text-Similarity.pdf)

[Repository](https://github.com/Adam-Rohde/nlp-recipe-project)

![](images/principal_comps.png)

---
### SVD-Based Watermarking Schemes
with Ian McGovern and Annie Zhang

This paper surveys techniques for digital image watermarking that employ singular value decomposition as a method for embedding watermarks imperceptibly in images. Multiple desirable qualities of digital watermarks are explained and their balance discussed. Three foundational papers are discussed in detail, implemented in Python, and experiments on these methods are conducted. We find that simpler methods tend to have better performance but at the cost of higher computational intensity. We discuss extensions to these schemes as well as practical applications in areas from medicine to copyright protection.

[Paper](docs/McGovern-Rohde-Zhang-SVD-Based-Watermarking-Schemes.pdf)

[Repository](https://github.com/Adam-Rohde/SVD-Based-Watermarking-Schemes)

![](images/LiuTan2002_watermarking_process.jpg)

---
### Screening AlexNet Hyperparameters with MNIST
with Ashley Chiu

We deploy an experimental approach to hyperparameter tuning in the context of AlexNet. We investigate AlexNet’s innovations, amongst other hyperparameters known to influence accuracy, to screen for the most important hyperparameters in an AlexNet-type CNN.


[Paper](docs/screening-alexnet-hyperparameters-with-mnist.pdf)

[Repository](https://github.com/Adam-Rohde/Screening-AlexNet-Hyperparameters-with-MNIST)

![](images/MNIST_Hyperparameters.PNG)

---
### Rational Bias in Inflation Expectations
with Robert Murphy

Using generalized method of moments, estimated a structural model of the economy to directly test hypotheses about whether inflation expectations respond rationally to food and energy price movements.

Murphy, R., Rohde, A. Rational Bias in Inflation Expectations. Eastern Econ J44, 153–171 (2018) doi:10.1057/eej.2015.50

[Paper](https://link.springer.com/article/10.1057%2Feej.2015.50)

[Final Working Version](docs/Rational-Bias-in-Inflation-Expectations-Working.pdf)

![](images/Rational_Bias_Chart.PNG)
