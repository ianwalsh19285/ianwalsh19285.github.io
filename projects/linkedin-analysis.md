---
layout: page
---

<div class="project-shell">

<div class="project-hero">
  <h1>Job Salary Prediction Model</h1>
  <p class="project-subtitle">Machine learning project</p>
</div>

<img class="project-image" src="/assets/img/projects/cohen_kappa_graph.png" alt="Bar chart comparing Cohen's kappa scores across machine learning models">

<div class="project-copy">
  <p>
    This project used LinkedIn job posting data to classify postings into lower-, middle-, and upper-salary bins using text features, job metadata, and location fields. My partner and I built the workflow as a machine learning final project, with an emphasis on feature engineering, model comparison, and practical interpretation of classification performance.
  </p>

  <h2>What I built</h2>
  <ul>
    <li>A cleaned modeling dataset based on 2023–2024 LinkedIn job posting data, including trimmed salary values and a three-bin target variable.</li>
    <li>A feature engineering workflow combining TF-IDF text features, one-hot encoded categorical variables, imputed numeric data, and PCA-based summary features.</li>
    <li>A comparative modeling pipeline testing Random Forest, Logistic Regression, Gaussian Naive Bayes, and a neural network on a holdout set.</li>
    <li>A final analysis summarizing model performance, feature choices, and limitations in the source data.</li>
  </ul>

  <h2>Key outcomes</h2>
  <ul>
    <li>Found that Random Forest performed best among the models tested on the salary-bin classification task, based on Cohen's kappa score as a comparison metric.</li>
    <li>Showed how messy posting data with mixed text, categorical, and numeric inputs can still support a useful end-to-end machine learning workflow.</li>
    <li>Demonstrated that PCA-derived features contributed meaningful predictive signal, with several principal components ranking among the Random Forest model’s most important features.</li>
  </ul>
</div>

<img class="project-image-secondary" src="/assets/img/projects/random_forest_confusion.png" alt="Random forest confusion matrix for salary bin classification">

</div>