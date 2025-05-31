### Multiple Default Model Comparisons
Comparing mutlipel models using default hyperparameters/settings we find.
#### Confusion Matrix
<a href="./analysis_results/module_17_01.step10.model_comparison.confusion_matrix.png" target="_blank"><img src="./analysis_results/module_17_01.step10.model_comparison.confusion_matrix.png"/></a>

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
      <td>Model Comparisons</td>
      <td>Logistic Regression</td>
      <td>accuracy</td>
      <td>0.906812</td>
      <td>0.908116</td>
      <td>0.097605</td>
      <td>0.097605</td>
      <td>{}</td>
    </tr>
    <tr>
      <td>Model Comparisons</td>
      <td>SVC</td>
      <td>accuracy</td>
      <td>0.929530</td>
      <td>0.905414</td>
      <td>5.053246</td>
      <td>5.053246</td>
      <td>{}</td>
    </tr>
    <tr>
      <td>Model Comparisons</td>
      <td>KNN</td>
      <td>accuracy</td>
      <td>0.916639</td>
      <td>0.890332</td>
      <td>0.008141</td>
      <td>0.008141</td>
      <td>{}</td>
    </tr>
    <tr>
      <td>Model Comparisons</td>
      <td>Decision Tree</td>
      <td>accuracy</td>
      <td>1.000000</td>
      <td>0.886148</td>
      <td>0.242597</td>
      <td>0.242597</td>
      <td>{}</td>
    </tr>
  </tbody>
</table>
</div>

#### Performance Metrics (Visualized)
<a href="./analysis_results/module_17_01.step10.model_comparison.model_comparison_graphs.png" target="_blank"><img src="./analysis_results/module_17_01.step10.model_comparison.model_comparison_graphs.png"/></a>

#### Analysis
- The best performing model is Logistic Regression with a score of 90.8116118908552% which is better than our baseline score of 88.61476767500653%.
- The worst performing model is Decision Tree with a score of 88.61476767500653% which is worse than our baseline score of 88.61476767500653%.
- The fastest performing model is KNN with a score of 89.03321419231105% which is better than our baseline score of 88.61476767500653%.
- The slowest performing model is SVC with a score of 90.5413651817627% which is better than our baseline score of 88.61476767500653%.

