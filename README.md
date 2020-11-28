# Project 4: Causal Inference

### [Project Description](doc/project4_desc.md)

Term: Fall 2020

+ Team # 6
+ Projec title: Causal Inference Algorithms Evaluation
+ Team members
	+ Akey, Kristen kka2120@columbia.edu
	+ Liang, Citina sl4671@columbia.edu
	+ Liang, Rui rl2886@columbia.edu
	+ Liu, Mubai ml4407@columbia.edu
	+ Yin, Wen wy2337@columbia.edu
	
+ Project summary: We evaluate three causal inference algorithms. The three models include inverse propensity weighting (IPW) + L1 penalized logistic regression, regression estimate, and weighted regression + L1 penalized logistic regression. We compute the average treatment effect (ATE) using these algorithms on two distinct datasets and compare their performance and computational efficiency. 

Performance - squared difference of true ATE and estimated ATE

| High Dim. Dataset |
| Model      |Computational Cost| Performance | 
| ----------- | ----------- | ------    |
| Inverse Propensity Weighting (IPW) + L1 penalized Logistics regression     |  -2.218    |  0.88     | 
| Regression Estimate (Dont need Propensity Score)      |  -2.959      |   0.20    | 
| Weighted Regression + L1 penalized Logistics regression      |   -2.980    |   0.14    |

| Low Dim. Dataset |
| Model      |Computational Cost| Performance | 
| ----------- | ----------- | ------    |
| Inverse Propensity Weighting (IPW) + L1 penalized Logistics regression     |   2.210    |  0.54     | 
| Regression Estimate (Dont need Propensity Score)      |   2.526   |  0.16     | 
| Weighted Regression + L1 penalized Logistics regression      |  2.519     |   0.14    |

**Contribution statement**: [default] All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement. 

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
