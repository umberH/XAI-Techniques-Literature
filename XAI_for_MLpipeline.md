| ML  Pipeline  Stage                  | XAI  Method and  citation | Type of  Explanation               | Interpretable | Transparent | Data Type |   |    |   |
| ------------------------------------ | ------------------------- | ---------------------------------- | ------------- | ----------- | --------- | - | -- | - |
|                                      |                           |                                    |               |             | Tabular     | Image | Text | Graph |
| Data  Collection                     | Counterfactual            | Instance Based                     | o             | o           | v         | v | v  | v |
|                                      | Forward  Propogation      | Propagataion  Based                | o             | x           | v         | v | v  | v |
| Feature  Engineering  and  Selection | Vanilla  Gradients        | Saliency Based                     | o             | o           | v         | v | v  | v |
|                                      | Integrated  Gradients     | Saliency Based                     | o             | o           | v         | v | v  | v |
|                                      | SmoothGrad                | Saliency Based                     | x             | o           |           | v | v  |   |
|                                      | DeepRed                   | Automatic Rule  Extraction         | o             | o           | v         |   |    |   |
|                                      | DIFFI                     | Model Specific (Isolation Forest)  | o             | o           | v         |   |    | v |
|                                      | FuzzyRules                | Automatic Rule  Extraction         | o             | o           | v         |   |    |   |
|                                      | Adversarial  Examples     | Insatnce Based                     | o             | o           | v         | v | v  | v |
| Model  Training                      | LRP                       | Gradient Based                     | o             | o           | v         | v | v  | v |
|                                      | DeepLift                  | Gradient Based                     | o             | o           | v         | v | v  |   |
|                                      | Attention Rollouts        | Attention Based                    | o             | x           | v         |   | v  |   |
|                                      | SHAP                      | Model Agnostic  (Game Theory)      | o             | x           | v         | v | v  | v |
|                                      | LIME                      | Model Agnostic Perturbation  based | o             | x           | v         | v | v  |   |
|                                      | Decision Trees            | Intrinsic Rule Based               | o             | o           | v         | v | v  |   |
|                                      | Capture attention         | Self-attention Network             | o             | o           | v         |   |    | v |
| Model Evaluation                     | CAV/TCAV                  | Knowledge Based                    | o             | x           | v         | v | v  |   |
| Model  Optimization  and Tunning     | Semantically correct      | Knowledge Based                    | o             | x           | v         | v | v  |   |
|                                      | GradCAM                   | Gradient Based                     | o             | o           |           | v |    |   |
|                                      | TEXTVQA                   | Multimodel Expla.                  | o             | x           |           |   | v  |   |
| Deployment                           | Human Alliance            | Experience Based                   | o             | x           |           |   |    |   |
|                                      | Policy Abstraction        | Experience Based                   | o             | x           |           |   |    |   |
| Monitoring  and  Maintenance         | PFI                       | Feature Importance                 | o             | o           | v         |   | v  |   |
