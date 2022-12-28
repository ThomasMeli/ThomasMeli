![](https://www.thomasmeli.tech/wp-content/uploads/2020/12/Screen-Shot-2020-12-15-at-1.56.10-PM.png)

In 2016, when AlphaGo beat Lee Sedol in Go, my world was shaken.  I had been playing Go since I was 15, and never thought a computer would beat a professional human.  I now believe the most important breakthroughs that will happen in the next 20 years will probably occur due to improving our computational intelligence and resources.   

My gifts are explaining complicated concepts in a clear and intuitive way and making intriguing connections across disciplines that tell a bigger story.  My mission involves disrupting traditional education with technology so that the mystery of being alive in an ecological, social, and cultural web is kept vibrant throughout life -- and thus a fundamental respect and gratitude towards all beings remains in tact.

---

Skills: Python | JS / TS | Svelte | TDD-ish | D3 | R |  Rust | TF / Keras | Scikit-Learn | SQL | Explorable Explainers | Compassionate Communication | 

I really enjoy the aesthetics and power of beautiful and intelligent code.  I'm interested in education disruption, model building for clarity, statistical analysis, and visual interactive explainers.

---

[<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg' alt='linkedin' height='40'>](https://www.linkedin.com/in/thomasmeli/)  

---
## Curated Lists of Free High-Quality Resources
* **Interpretable Machine Learning Resources** - https://github.com/ThomasMeli/Interpretable_ML_Resources
* **Free Online Data Science Books** - https://github.com/ThomasMeli/Data_Free_Books
* **Interactive Learning and Explorables** - Simply the best way to learn anything. - https://github.com/ThomasMeli/Data_Interactive_Learning


## Previous Data Science Work 

### Dengue Fever Analysis


Dengue Fever is a mosquito-borne disease that often occurs in the tropics.  There are nearly half a billion cases of Dengue in Latin America alone.  In this competition, I made use of satellite and weather data to do the following:

* Used vegetation indices and other weather variables to find strong correlations with mosquito incidence.
* Did a time series analysis to break down the time series into its unobserved components.
* Interpolated missing data with a linear approximation due to the continuous nature of the variables.
* Used sequence sensitive deep learning models (LSTM, GRU, etc.)
* Ensemble these techniques with tree based regression classifies (XGBoost, Extratrees).

Achieved the top 8% in the world out of all participants.
https://github.com/ThomasMeli/DengueAI2/blob/main/dengue_eda.ipynb

### Walmart Sales - SARIMA Prediction


Most sales data is represented as a time series and has seasonality associated with it.  In interpreting data over long periods of time, it is important to separate out the seasonal components from the long-term trends from the noise in the data.   After doing this, one can combine this seasonal information and long-term trend information to make more accurate predictions based on other external variables.  

* I used a SARIMA model (Seasonal autoregressive model) to successfully predict ~30 time steps ahead.
* I created a visual guide that led to the notebook to be highly upvoted by the Kaggle community.

https://www.kaggle.com/tpmeli/visual-guide-3-m5-baselines-eda-sarima

### Cell Mechanism of Action - Exploratory Data Analysis

With the advent of cell and gene array techniques, many drugs can be used on various cell and gene lines simultaneously.  Making sense of the huge data that is generated represents a major difficulty.  Challenges in this competition involved noisy data as well as standardization that left the original gene and cell expressions unclear.  In this notebook, I perform a visual guide to the project and a preliminary data analysis for other data scientists to use.



https://www.kaggle.com/tpmeli/visual-guide-to-moa-eda-nn-walkthrough

### Predictions Analyzer Package


Different models are good at different things.  However, the sheer number of models and permutations of those models can make it time-consuming to analyze which models are good at predicting which samples.  Predictions Analyzer is an open-source project designed to find out which samples are the hardest to predict, which are the easiest to predict, and which models are the most accurate on those hard-to-predict samples.

It also seeks to automate much of the model selection pipeline so data scientists can focus on thinking through problems and interpreting their results in a statistically sound manner.  

https://github.com/ThomasMeli/predictions_analyzer

### Data Science Bowl 2019

This project was designed to take data from an educaational game to develop insights about how children learn.  It was the first time that I used the skills I was learning on a real dataset for an extended period.  I learned an enormous amount about code conciseness, modularity, and how to explore models.

https://www.kaggle.com/tpmeli/dsb-2019-finalizing

### Rare Species Classification

Ecological ID - Mel Spectrograms | Convolutional Neural Nets | Data Augmentation | GPU Learning | Tensorflow | Keras

Conserving rare species is both very important and represents a difficult data challenge  Because these species are rare, we have less information about them…

* Preprocessing audio for high signal to noise ratio samples.
* Dealing with class imabalance.
* Converting sound to spectrograms for visual analysis.
* Data augmentation for out of sample learning.
* Creatively using false positives to increase classifier accuracy.
* Used functional Keras API for multiple model inputs.


### Missingness Analysis 

If missing data is not missing at random, then the fact that data is missing can itself be important information.  In this missing data analysis, I show ‘fancy’ data imputation methods perform sub-optimally compared to a simple mean imputer.  

Conclusion: "The null hypothesis here is that the means are equal within the missing data and the non-missing data. If this was true, it may mean that the missing values (even if they are missing-not-at-random), may not have a significant impact on the mean of the data.  The mean of the missing values is more negative here. The p-values are extremely small meaning that, if we assume the means are the same, the likelihood of getting our actual means is extremely unlikely. This allows us to reject the null hypothesis that the means are the same, providing more evidence for missing-not-at-random."

https://www.kaggle.com/tpmeli/missing-data-exploration-mean-iterative-more

### Data Cleaning - Kaggle 

A small project where very messy and inconvenient data was cleaned to make data analysis much easier for participants.

* Cleaning: https://www.kaggle.com/tpmeli/kaggle-questionere-csv-cleaning
* Barplots: https://www.kaggle.com/tpmeli/barplots-of-all-questions-exploratory

### Cassava Disease Identification - R and Python in one RMarkdown script

In this project, I was learning the powerful R package reticulate.  It allows one to code in both Python and R, allowing the data scientist to get the best of both worlds.  I also did the project in RMarkdown instead of a Jupyter Notebook, which allowed for a very clearn tabular style that made for easier reading.

* RMarkdown Doc: https://www.kaggle.com/tpmeli/cassava-r-and-python-eda

--
