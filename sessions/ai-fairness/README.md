# Evaluating Fairness of AI Models in Radiology

Session by: Paul Yi, [Jeremias Sulam](https://sites.google.com/view/jsulam), [Beepul Bharti](https://beepulbharti.github.io/), and [Jacopo Teneggi](https://jacopoteneggi.github.io/).


## Objective 1: Evaluating Fairness

### Motivation

As the use of machine learning models in real world high-stakes decision settings continues to grow, it is highly important that we are able to audit and control for any potential fairness violations these models may exhibit towards certain groups.

Common notions of fairness consider the different error rates of a model across different groups: males and females, white and non-white, etc. For example, the equal opportunity criterion requires the true positive rate (TPR) be equal across both groups, while equalized odds requires both TPR and false positive rate (FPR) to be the same across groups. 

These notions of fairness allow us to identify which groups the model could be negatively impacting and in turn allow us to formulate methods to help the unfairly treated group.

### Agenda

In this session, we will explore model fairness for ICH detection in head CT. 

In particular, we will use a model trained on the RSNA 2019 Intracranial Hemorrhage Detection Challenge. 

We will evaluate the model's fairness with respect to biological sex and learn of a simple method to correct for fairness violations.

## Objective 2: Explaining Model Predictions

### Motivation

As machine learning models become more and more complex, their predictions become less and less intelligible to the humans interacting with them.

Recently, *post-hoc* explanation methods have been proposed to produce saliency maps that highlight the most important features in an input for with respect to a given model prediction.

Explanation methods can be used to verify that a model is not relying on spurious correlations in the data, to identify potential biases, and to enhance trust in the model.

### Agenda

In this session, we will explore explainability for ICH detection in head CT. 

In particular, we will use a model trained on the RSNA 2019 Intracranial Hemorrhage Detection Challenge. 

We will evaluate model's performance on an external hold-out test set: the CT-ICH dataset, and we will use h-Shap to explain models predictions.

## References

- [RSNA 2019 Intracranial Hemorrhage Detection Challenge](https://www.kaggle.com/c/rsna-intracranial-hemorrhage-detection)
- [CT-ICH dataset](https://physionet.org/content/ct-ich/1.3.1/)
- h-Shap: [Teneggi, Jacopo, Alexandre Luster, and Jeremias Sulam. "Fast hierarchical games for image explanations." IEEE Transactions on Pattern Analysis and Machine Intelligence 45.4 (2022): 4494-4503.](https://www.computer.org/csdl/journal/tp/2023/04/09826424/1EVdAz76rC0)
- EOD with Missing Sensitive Attributes: [Bharti, Beepul, Paul Yi, and Jeremias Sulam. "Estimating and Controlling for Equalized Odds via Sensitive Attribute Predictors." Neural Information Processing Systems (2023)](https://openreview.net/pdf?id=e2aCgjtjMR)
