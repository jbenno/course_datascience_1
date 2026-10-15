# Data Science in the Wild
Cornell Tech CS 5304 / INFO 5304

Data in the wild are unruly. They might be collected for very different purposes, metrics are contested, and models end up in processes that affect people. This course teaches the statistics and machine learning needed to work with such data, with New York City open data examples throughout. Students frame a problem before touching the data, estimate before computing, and learn regression, evaluation, resampling and testing through the problems each technique claims to fix. Later modules cover causal inference, gradient boosting, neural networks, and text, sensor, network and genomic data, including the re-engineering of an image-recognition pipeline. Privacy, fairness and the politics of code are treated as part of the method. A team project on real data runs through the term.

## Schedule

### Module A. Framing projects, getting data, ca. 3 weeks
Decide what success for a data project will mean before opening the data. Treat data as the product of a collection process with its own biases.
* Statistics and data science, competing aims, inference against prediction
* The politics/ethics of design choices
* Problem framing, metrics and naive baselines
* Fermi estimation, orders of magnitude, logarithms
* Descriptive statistics
* Code review (Python, SQL, GitHub, scraping, APIs)
* Metadata, licences, provenance
* Missing populations
* Joins and data fusion, small curated data calibrating large messy data
* Covariance, correlation, spurious correlation, Simpson's paradox, ecological fallacy

### Module B. Regression, next 3 weeks
Regression as quick approximation to a response surface. Its residual holds the complexity that is set aside. It should beat a heuristic baseline before it is trusted.
* Time series and seasonality
* MLE, closed form solutions, stochastic gradient descent
* Log/ log-log transformations, heteroskedasticity, residual plots, robust standard errors
* Generalised linear models, logistic regression, Poisson/negative binomial regression
* Preprocessing, recoding, normalization, regularization, featurization

### Module C. Evaluation, uncertainty, probably. After midterm, 2-3 weeks
Evaluation must match the decision. Significance at large samples says little about effect size.
* Prediction against inference, over-fitting, train and test splits, grouped and temporal splits, leakage, cross-validation
* Bayes rule and base rates, binary metrics, unbalanced classes, threshold choice, ROC and AUC
* Probabilities rather than class labels
* Expected loss, asymmetric errors, fairness criteria and their conflict, dirty data in predictive policing
* Bootstrap and permutation, binomial and geometric distributions, polling and margins of error
* Hypothesis tests on regression tables, effect size against p-value, joint and marginal probability
* Simulation of null distributions, multiple testing, forking paths, the replication crisis
* Agent-based models as data-generating processes, including feedback loops

### D. Causal inference. One week
Predicting an outcome is not the same as knowing what an intervention would change.
* Potential outcomes, DAGs, confounders, colliders, selection bias
* A/B experiments and their limits
* Difference-in-differences, interrupted time series, regression discontinuity, synthetic control
* Parallel trends and placebo checks, applied to NYC congestion pricing

### E. Data in the wild. Last 4 weeks
A model within the process: labels, users, losses/risks and people affected. Audit, re-engineer and document the process, not only the model.
* Trees, random forests, gradient boosting, calibration
* Natural language processing
* Naive Bayes, neural networks, embeddings, transfer learning
* Re-engineering an image-recognition pipeline, annotation labour, label errors, error rates by group, human review
* Sensor and event data, change-point and anomaly detection, streaming
* Networks, clustering, collaborative filtering, matrix factorisation, SVD
* Genomic data
* Privacy and surveillance, re-identification attacks, k-anonymity, differential privacy, datasheets and model cards
* A/B tests in deployment, visualisation, storytelling, alternative readings as critique, building functional alternatives
* Final-project
