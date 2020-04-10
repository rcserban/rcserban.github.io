## This can be your internal website page / project page

**Project description:** Predict/provide accurate forecasts for the number of COVID-19 deaths for each of the countries present in the input data set.

### 1. Perform exploratory data analysis and provide meta-data characterization and descriptive statistics.

Load and explore the input data set. Perform descriptive data statistics.

```javascript
train = load('input/train.csv');
provide data statistics for `train` data set;
test = load('input/test.csv');
provide data statistics for `test` data set;
```

### 2. Formulate hypotheses about relevant features/indicators for predicting number of deaths

Calculate lagged data features. Suggest relevant features that could be used to enrich the data set (e.g. total population, population density, virulence/attack ratio, average temperature/humidity/air quality, number of hospital beds).

```javascript
for i in 1..n {
  generate lagged(i) value for the train data set;
  generate lagged(i) value for the test data set;
}
```

### 3. Generate enriched analytical data record to be used for building/training the model.

Generate enriched analytical data record to be used for building/training the model. Perform any necessary feature transformation and model tuning.
Determine baseline model and model performance metric.

### 4. Generate predictions from the built model for the test data set.

Generate predictions from the built model for the test data set.
