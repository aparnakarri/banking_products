## CRISP DM: Data Preparations
### Feature Engineering Decisions
We are asked to focus on just the "bank client data" features. In order to simplify later steps though we will also make some decisions around the "other attributes" and "social and economic context attributes" features to be efficent in our data preparation.
| Fields | Operation | Notes |
| ------ | ----- | -------- |
| [] | Drop duplicates |  |
| ['poutcome', 'default', 'pdays', 'nr.employed'] | Drop columns |  |
| [] | Filter rows | Query: job != "unknown" & marital != "unknown" & education != "unknown" & housing != "unknown" & loan != "unknown" |
| ['ALL CATEGORICAL'] | One hot encode | All categorical columns with < 255 unique values |
| ['ALL CATEGORICAL'] | Drop |  |
| ['y_yes'] | rename | rename to y |
### Data Distributions
<a href="./analysis_results/module_17_01.step05.engineering_features.categorical.data.distribution.png" target="_blank"><img src="./analysis_results/module_17_01.step05.engineering_features.categorical.data.distribution.png"/></a>

<a href="./analysis_results/module_17_01.step05.engineering_features.numeric.data.distribution.png" target="_blank"><img src="./analysis_results/module_17_01.step05.engineering_features.numeric.data.distribution.png"/></a>

### Data Composition Change Tracking
<a href="./analysis_results/module_17_01.step05.engineering_features.unique_values.png" target="_blank"><img src="./analysis_results/module_17_01.step05.engineering_features.unique_values.png"/></a>

