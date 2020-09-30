## Day 1
Started 100 days!
I realized that I already put in time coding and now I just need to organize it.
One of my goals currently is to put together a Kaggle notebook on the [Titanic DB](https://www.kaggle.com/c/titanic/data).

A notebook that has the highest score is by **startupsci** at [Titanic Data Science Solutions](https://www.kaggle.com/startupsci/titanic-data-science-solutions). this notebook has an excellent explanation of parts for a report. The following are notes from this Python/notebook.

### Workflow (goals) stages -  7 stages

1. Question or problem definition.
    - Provide background info.
    - Pose question to tackle initially.
2. Acquire training and testing data.
    - We may want to classify or categorize our samples.
3. Wrangle, mung, prepare, cleanse the data, NA, missing values, structure,...
4. Analyze, identify patterns, and explore the data, EDA.
    - Which features within the dataset contribute significantly to our solution goal? Statistically speaking is there a correlation among a feature and solution goal?
5. Model, predict and solve the problem.
    - For modeling stage, depending on the choice of model algorithm one may require features to be converted to numerical equivalent values.
    - Can we create new features based on an existing feature or a set of features, such that the new feature follows the correlation, conversion, completeness goals.
7. Visualize, report, and present the problem solving steps and final solution.
    - Viz may be moved up to work with EDA
    - Select the right visualization, (hard?)
8. Submit the results in report format
	
### Practical Stages

1. Load data & libraries
2. Preliminary data analysis, str(), summary(), head(), tail(), 
    - Which columns are factors or features
4. Check for missing values, errors; Is Imputation needed?
5. boxplot(), hist() or scatter plot(), tables of survival or not...
6. Is data normal? poisson, distribution, skew, outliers?
7. Is data nominal, cat, muerical, discrete or continous?
8. Correlation plots
9. Near-zero variance or zero variance data deleted?
10. Model data using caret(?)
    - Titanic data is modeled against Logit, KNN, SVM, NB, DT, RF, ANN
    - Provide hyperparameters (tuning) and confidence intervals(?)
    - Cross validation
11. Model evaluation; accuracy, ROC,...

[mrisdal](https://www.kaggle.com/mrisdal/exploring-survival-on-the-titanic) provided an **.rmd** format.

1. **Introduction**; Load and check data
2. **Feature Engineering**; What’s in a name? Do families sink or swim together? Treat a few more variables, PCA, LDA…
3. **Missingness**; Sensible value imputation, Predictive imputation, Feature Engineering: Round 2
4. **Prediction**; Split into training & test sets, Building the model, Variable importance, Prediction!
5. **Conclusion**

See Also: [cheatsheet-70-ggplot-charts](https://www.kaggle.com/raenish/cheatsheet-70-ggplot-charts)
