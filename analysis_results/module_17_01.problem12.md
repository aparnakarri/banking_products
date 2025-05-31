## CRISP DM: Evaluation
Using a "voting" approach where each time a feature is deemed important by a model it increments the vote. Coefficents are including to evaluate direction and magnitude as well.
### Only Bank Client Data
#### Feature Importance

Important features using voting approach:

['duration', 'month', 'contact', 'job', 'age']

The specific values of these important features are:
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
      <th>feature</th>
      <th>votes</th>
      <th>sum_coefficients</th>
      <th>coefficients</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>duration</td>
      <td>2</td>
      <td>1.082065</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": 1.0820652259919126}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>month_oct</td>
      <td>2</td>
      <td>0.259732</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": 0.25973186710045026}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>month_mar</td>
      <td>2</td>
      <td>0.246786</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": 0.2467861039284352}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>month_sep</td>
      <td>2</td>
      <td>0.208582</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": 0.2085821156741267}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>contact_telephone</td>
      <td>2</td>
      <td>-0.654124</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": -0.6541237717780517}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>month_jun</td>
      <td>1</td>
      <td>0.254270</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": 0.25427013376943686}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>job_retired</td>
      <td>1</td>
      <td>0.161437</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": 0.16143658338602945}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>job_student</td>
      <td>1</td>
      <td>0.128621</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": 0.12862113830729735}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>month_apr</td>
      <td>1</td>
      <td>0.124941</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": 0.12494066982232567}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>age</td>
      <td>1</td>
      <td>0.000000</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": null}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>month_may</td>
      <td>1</td>
      <td>-0.137883</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": -0.13788304045488461}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>month_jul</td>
      <td>1</td>
      <td>-0.209583</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": -0.2095832463104147}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
  </tbody>
</table>
</div>

#### Decision Tree
The descision tree is more easily interpretable/explainable to help with the understanding how the model works and can help the bank make decisions about optimizing the campaign.
<a href="./analysis_results/module_17_01.step12.final_analysis..decision_tree_final.png" target="_blank"><img src="./analysis_results/module_17_01.step12.final_analysis..decision_tree_final.png"/></a>
### Bank Client Data + Other
#### Feature Importance

Important features using voting approach:

['duration', 'previous', 'month', 'contact', 'job', 'age', 'campaign']

The specific values of these important features are:
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
      <th>feature</th>
      <th>votes</th>
      <th>sum_coefficients</th>
      <th>coefficients</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>duration</td>
      <td>2</td>
      <td>1.104149</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": 1.1041493266570828}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>previous</td>
      <td>2</td>
      <td>0.336996</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": 0.3369958059719511}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>month_mar</td>
      <td>2</td>
      <td>0.245418</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": 0.24541817165555524}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>month_jun</td>
      <td>2</td>
      <td>0.234438</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": 0.23443848089531738}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>month_oct</td>
      <td>2</td>
      <td>0.224402</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": 0.22440249901602916}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>month_may</td>
      <td>2</td>
      <td>-0.174344</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": -0.17434373655325844}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>contact_telephone</td>
      <td>2</td>
      <td>-0.520233</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": -0.5202334991847558}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>month_sep</td>
      <td>1</td>
      <td>0.168518</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": 0.1685180647782279}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>job_retired</td>
      <td>1</td>
      <td>0.156343</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": 0.15634272303250796}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>age</td>
      <td>1</td>
      <td>0.000000</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": null}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>month_jul</td>
      <td>1</td>
      <td>-0.136481</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": -0.13648145173189616}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>campaign</td>
      <td>1</td>
      <td>-0.197302</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": -0.19730182905596638}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
  </tbody>
</table>
</div>

#### Decision Tree
The descision tree is more easily interpretable/explainable to help with the understanding how the model works and can help the bank make decisions about optimizing the campaign.
<a href="./analysis_results/module_17_01.step12.final_analysis..decision_tree_final.png" target="_blank"><img src="./analysis_results/module_17_01.step12.final_analysis..decision_tree_final.png"/></a>
### Bank Client Data + Other + Social and Economic
#### Feature Importance

Important features using voting approach:

['duration', 'euribor3m', 'emp.var.rate', 'cons.price.idx', 'month', 'cons.conf.idx', 'contact']

The specific values of these important features are:
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
      <th>feature</th>
      <th>votes</th>
      <th>sum_coefficients</th>
      <th>coefficients</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>duration</td>
      <td>2</td>
      <td>1.210274</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": 1.2102744249520136}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>euribor3m</td>
      <td>2</td>
      <td>0.822852</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": 0.8228518845810416}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>emp.var.rate</td>
      <td>2</td>
      <td>-2.559176</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": -2.559176244839346}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>cons.price.idx</td>
      <td>1</td>
      <td>1.111251</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": 1.1112514774811144}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>month_aug</td>
      <td>1</td>
      <td>0.318562</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": 0.3185617297972314}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>month_mar</td>
      <td>1</td>
      <td>0.219442</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": 0.21944204606069712}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>cons.conf.idx</td>
      <td>1</td>
      <td>0.000000</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": null}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>month_may</td>
      <td>1</td>
      <td>-0.223674</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": -0.22367410860697742}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>contact_telephone</td>
      <td>1</td>
      <td>-0.289197</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": -0.2891967435805612}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
  </tbody>
</table>
</div>

#### Decision Tree
The descision tree is more easily interpretable/explainable to help with the understanding how the model works and can help the bank make decisions about optimizing the campaign.
<a href="./analysis_results/module_17_01.step12.final_analysis..decision_tree_final.png" target="_blank"><img src="./analysis_results/module_17_01.step12.final_analysis..decision_tree_final.png"/></a>
### Bank Client Data + Other + Social and Economic without Duraton
#### Feature Importance

Important features using voting approach:

['euribor3m', 'month', 'emp.var.rate', 'cons.price.idx', 'contact']

The specific values of these important features are:
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
      <th>feature</th>
      <th>votes</th>
      <th>sum_coefficients</th>
      <th>coefficients</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>euribor3m</td>
      <td>2</td>
      <td>0.791708</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": 0.7917080369434308}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>month_may</td>
      <td>2</td>
      <td>-0.155023</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": -0.15502291627540207}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>emp.var.rate</td>
      <td>2</td>
      <td>-2.215338</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": -2.215338393324382}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>cons.price.idx</td>
      <td>1</td>
      <td>1.063062</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": 1.0630619619736053}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>month_aug</td>
      <td>1</td>
      <td>0.215161</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": 0.21516073777122205}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>month_mar</td>
      <td>1</td>
      <td>0.173054</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": 0.17305432280111097}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>month_oct</td>
      <td>1</td>
      <td>0.000000</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": null}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
    <tr>
      <td>contact_telephone</td>
      <td>1</td>
      <td>-0.360293</td>
      <td>{"KNN": {"accuracy": null}, "Logistic Regression": {"accuracy": -0.36029290947472237}, "Decision Tree": {"accuracy": null}, "SVC": {"accuracy": null}}</td>
    </tr>
  </tbody>
</table>
</div>

#### Analysis
#### Data Distributions
**NOTE:** Important features highlighted using different palette
<a href="./analysis_results/module_17_01.step12.final_analysis.important.categorical.data.distribution.png" target="_blank"><img src="./analysis_results/module_17_01.step12.final_analysis.important.categorical.data.distribution.png"/></a>
<a href="./analysis_results/module_17_01.step12.final_analysis.important.age.data.distribution.png" target="_blank"><img src="./analysis_results/module_17_01.step12.final_analysis.important.age.data.distribution.png"/></a>

<a href="./analysis_results/module_17_01.step12.final_analysis.important.numeric.data.distribution.png" target="_blank"><img src="./analysis_results/module_17_01.step12.final_analysis.important.numeric.data.distribution.png"/></a>

#### Decision Tree
The descision tree is more easily interpretable/explainable to help with the understanding how the model works and can help the bank make decisions about optimizing the campaign.
<a href="./analysis_results/module_17_01.step12.final_analysis..decision_tree_final.png" target="_blank"><img src="./analysis_results/module_17_01.step12.final_analysis..decision_tree_final.png"/></a>
