## CRISP DM: Modeling
- We will use the accuracy of the test score to evaluate the models against each other and select best model during Grid Search.
- However if the bank had an opinon for example one of the ones below we would adjust the scoring type.
  - Recall: If we wanted to make sure we didn't miss any customers that may sign up we would optimize for recall.
  - Precision: If we wanted to make sure we only spend time contacting customers that are likely sign up we would optimize for precision.
### Baseline Model
#### Confusion Matrix
<a href="./analysis_results/module_17_01.step07.baseline_model.confusion_matrix.png" target="_blank"><img src="./analysis_results/module_17_01.step07.baseline_model.confusion_matrix.png"/></a>

#### Performance Metrics (Tables)
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>experiment</th>
      <th>model</th>
      <th>scoring_type</th>
      <th>train score</th>
      <th>test score</th>
      <th>average fit time</th>
      <th>grid_search_train_wall_time</th>
      <th>best_params</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Baseline</td>
      <td>Baseline (DummyClassifier)</td>
      <td>accuracy</td>
      <td>0.889736</td>
      <td>0.886148</td>
      <td>0.00706</td>
      <td>0.00706</td>
      <td>{}</td>
    </tr>
  </tbody>
</table>
</div>

#### Analysis
The Baseline (DummyClassifier) has an accuracy test score of 88.61476767500653%
