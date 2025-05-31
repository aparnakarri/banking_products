### Grid Search - Only Bank Client Data
Experiment using bank client data features including duration
#### Confusion Matrix
<a href="./analysis_results/module_17_01.step11.improving_model.experiment1.confusion_matrix.png" target="_blank"><img src="./analysis_results/module_17_01.step11.improving_model.experiment1.confusion_matrix.png"/></a>

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
      <td>Improving Model - Grid Search</td>
      <td>Decision Tree</td>
      <td>accuracy</td>
      <td>0.907858</td>
      <td>0.902101</td>
      <td>0.029547</td>
      <td>4.833368</td>
      <td>{"criterion": "gini", "max_depth": 6}</td>
    </tr>
    <tr>
      <td>Improving Model - Grid Search</td>
      <td>Logistic Regression</td>
      <td>accuracy</td>
      <td>0.900534</td>
      <td>0.900445</td>
      <td>0.015970</td>
      <td>1.858696</td>
      <td>{"C": 0.6, "penalty": "l2"}</td>
    </tr>
    <tr>
      <td>Improving Model - Grid Search</td>
      <td>SVC</td>
      <td>accuracy</td>
      <td>0.913911</td>
      <td>0.899050</td>
      <td>4.022144</td>
      <td>981.196614</td>
      <td>{"C": 1.0, "kernel": "rbf"}</td>
    </tr>
    <tr>
      <td>Improving Model - Grid Search</td>
      <td>KNN</td>
      <td>accuracy</td>
      <td>0.999963</td>
      <td>0.889024</td>
      <td>0.008453</td>
      <td>116.650805</td>
      <td>{"n_neighbors": 52, "weights": "distance"}</td>
    </tr>
  </tbody>
</table>
</div>

#### Performance Metrics (Visualized)
<a href="./analysis_results/module_17_01.step11.improving_model.experiment1.model_comparison_graphs.png" target="_blank"><img src="./analysis_results/module_17_01.step11.improving_model.experiment1.model_comparison_graphs.png"/></a>

#### Analysis
- The best performing model is Decision Tree with a score of 90.21009502222998% which is better than our baseline score of 88.61476767500653%.
- The worst performing model is KNN with a score of 88.90244965565338% which is better than our baseline score of 88.61476767500653%.
- The fastest performing model is KNN with a score of 88.90244965565338% which is better than our baseline score of 88.61476767500653%.
- The slowest performing model is SVC with a score of 89.90497777002876% which is better than our baseline score of 88.61476767500653%.

### Grid Search - Bank Client Data + Other
Experiment using bank client data features, other features including duration
#### Confusion Matrix
<a href="./analysis_results/module_17_01.step11.improving_model.experiment2.confusion_matrix.png" target="_blank"><img src="./analysis_results/module_17_01.step11.improving_model.experiment2.confusion_matrix.png"/></a>

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
      <td>Improving Model - Grid Search</td>
      <td>Logistic Regression</td>
      <td>accuracy</td>
      <td>0.901693</td>
      <td>0.902711</td>
      <td>0.023279</td>
      <td>2.625720</td>
      <td>{"C": 0.5, "penalty": "l2"}</td>
    </tr>
    <tr>
      <td>Improving Model - Grid Search</td>
      <td>Decision Tree</td>
      <td>accuracy</td>
      <td>0.915219</td>
      <td>0.902537</td>
      <td>0.033482</td>
      <td>5.520002</td>
      <td>{"criterion": "entropy", "max_depth": 8}</td>
    </tr>
    <tr>
      <td>Improving Model - Grid Search</td>
      <td>SVC</td>
      <td>accuracy</td>
      <td>0.920599</td>
      <td>0.901229</td>
      <td>4.007379</td>
      <td>980.030772</td>
      <td>{"C": 1.0, "kernel": "rbf"}</td>
    </tr>
    <tr>
      <td>Improving Model - Grid Search</td>
      <td>KNN</td>
      <td>accuracy</td>
      <td>1.000000</td>
      <td>0.888763</td>
      <td>0.009101</td>
      <td>120.654340</td>
      <td>{"n_neighbors": 12, "weights": "distance"}</td>
    </tr>
  </tbody>
</table>
</div>

#### Performance Metrics (Visualized)
<a href="./analysis_results/module_17_01.step11.improving_model.experiment2.model_comparison_graphs.png" target="_blank"><img src="./analysis_results/module_17_01.step11.improving_model.experiment2.model_comparison_graphs.png"/></a>

#### Analysis
- The best performing model is Logistic Regression with a score of 90.27111847267021% which is better than our baseline score of 88.61476767500653%.
- The worst performing model is KNN with a score of 88.87629674832186% which is better than our baseline score of 88.61476767500653%.
- The fastest performing model is KNN with a score of 88.87629674832186% which is better than our baseline score of 88.61476767500653%.
- The slowest performing model is SVC with a score of 90.1229186644582% which is better than our baseline score of 88.61476767500653%.

### Grid Search - Bank Client Data + Other + Social and Economic
Experiment using bank client data features, other features, social and economic features including duration
#### Confusion Matrix
<a href="./analysis_results/module_17_01.step11.improving_model.experiment3.confusion_matrix.png" target="_blank"><img src="./analysis_results/module_17_01.step11.improving_model.experiment3.confusion_matrix.png"/></a>

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
      <td>Improving Model - Grid Search</td>
      <td>Decision Tree</td>
      <td>accuracy</td>
      <td>0.915219</td>
      <td>0.913957</td>
      <td>0.040089</td>
      <td>6.514614</td>
      <td>{"criterion": "gini", "max_depth": 5}</td>
    </tr>
    <tr>
      <td>Improving Model - Grid Search</td>
      <td>Logistic Regression</td>
      <td>accuracy</td>
      <td>0.906737</td>
      <td>0.908203</td>
      <td>0.037394</td>
      <td>4.146136</td>
      <td>{"C": 0.7000000000000001, "penalty": "l2"}</td>
    </tr>
    <tr>
      <td>Improving Model - Grid Search</td>
      <td>SVC</td>
      <td>accuracy</td>
      <td>0.929530</td>
      <td>0.905414</td>
      <td>3.898248</td>
      <td>960.763582</td>
      <td>{"C": 1.0, "kernel": "rbf"}</td>
    </tr>
    <tr>
      <td>Improving Model - Grid Search</td>
      <td>KNN</td>
      <td>accuracy</td>
      <td>1.000000</td>
      <td>0.890245</td>
      <td>0.009783</td>
      <td>133.428291</td>
      <td>{"n_neighbors": 32, "weights": "distance"}</td>
    </tr>
  </tbody>
</table>
</div>

#### Performance Metrics (Visualized)
<a href="./analysis_results/module_17_01.step11.improving_model.experiment3.model_comparison_graphs.png" target="_blank"><img src="./analysis_results/module_17_01.step11.improving_model.experiment3.model_comparison_graphs.png"/></a>

#### Analysis
- The best performing model is Decision Tree with a score of 91.39569348792608% which is better than our baseline score of 88.61476767500653%.
- The worst performing model is KNN with a score of 89.02449655653388% which is better than our baseline score of 88.61476767500653%.
- The fastest performing model is KNN with a score of 89.02449655653388% which is better than our baseline score of 88.61476767500653%.
- The slowest performing model is SVC with a score of 90.5413651817627% which is better than our baseline score of 88.61476767500653%.

### Grid Search - Bank Client Data + Other + Social and Economic without Duraton
Experiment using all features except duration.
As part of the data description above we are told:
```
duration: last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target (e.g., if duration=0 then y="no"). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model
```

#### Confusion Matrix
<a href="./analysis_results/module_17_01.step11.improving_model.experiment4.confusion_matrix.png" target="_blank"><img src="./analysis_results/module_17_01.step11.improving_model.experiment4.confusion_matrix.png"/></a>

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
      <td>Improving Model - Grid Search</td>
      <td>Decision Tree</td>
      <td>accuracy</td>
      <td>0.896723</td>
      <td>0.893035</td>
      <td>0.033771</td>
      <td>5.484499</td>
      <td>{"criterion": "entropy", "max_depth": 4}</td>
    </tr>
    <tr>
      <td>Improving Model - Grid Search</td>
      <td>SVC</td>
      <td>accuracy</td>
      <td>0.911594</td>
      <td>0.892512</td>
      <td>38.301795</td>
      <td>7901.851101</td>
      <td>{"C": 1.0, "kernel": "rbf"}</td>
    </tr>
    <tr>
      <td>Improving Model - Grid Search</td>
      <td>Logistic Regression</td>
      <td>accuracy</td>
      <td>0.894892</td>
      <td>0.890768</td>
      <td>0.037005</td>
      <td>4.059869</td>
      <td>{"C": 0.7000000000000001, "penalty": "l2"}</td>
    </tr>
    <tr>
      <td>Improving Model - Grid Search</td>
      <td>KNN</td>
      <td>accuracy</td>
      <td>0.894145</td>
      <td>0.886845</td>
      <td>0.009532</td>
      <td>130.961234</td>
      <td>{"n_neighbors": 36, "weights": "uniform"}</td>
    </tr>
  </tbody>
</table>
</div>

#### Performance Metrics (Visualized)
<a href="./analysis_results/module_17_01.step11.improving_model.experiment4.model_comparison_graphs.png" target="_blank"><img src="./analysis_results/module_17_01.step11.improving_model.experiment4.model_comparison_graphs.png"/></a>

#### Analysis
- The best performing model is Decision Tree with a score of 89.30346090140354% which is better than our baseline score of 88.61476767500653%.
- The worst performing model is KNN with a score of 88.68450876122395% which is better than our baseline score of 88.61476767500653%.
- The fastest performing model is KNN with a score of 88.68450876122395% which is better than our baseline score of 88.61476767500653%.
- The slowest performing model is SVC with a score of 89.25115508674047% which is better than our baseline score of 88.61476767500653%.

