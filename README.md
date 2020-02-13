### Cuisine-Detection 
<pre>
Domain             : Machine Learning
Sub-Domain         : Supervised Learning, Classification
Techniques         : 
Application        : 
</pre>

### Description
<pre>
1. Identified cuisines from recipe description using Linear Suppor Vector Machine, TFIDF.
2. Used One vs Rest model.
3. After 27 training iterations, attained testing accuracy of 78.147% <!--and loss 0.03 on 60K (12MB+) recipe dataset-->.
</pre>

#### Code
<pre>
GitHub Link      : <a href=https://github.com/anjanatiha/Cuisine-Detection>Cuisine Detection (GitHub)</a>
GitLab Link      : <a href=https://gitlab.com/anjanatiha/Cuisine-Detection>Cuisine Detection (GitLab)</a>
Kaggle Notebook  : <a href=https://www.kaggle.com/anjanatiha/cuisine-prediction>Cuisine Detection</a>
Portfolio        : <a href=https://anjanatiha.wixsite.com/website>Anjana Tiha's Portfolio</a>
</pre>

#### Dataset
<pre>
Dataset Name     : Cuisine Detection
Dataset Link     : <a href=https://www.kaggle.com/c/whats-cooking-kernels-only>whats-cooking-kernels-only (Kaggle)</a>
</pre>

### Dataset Details
<pre>
Dataset Name            : whats-cooking-kernels-only
Number of Class         : ---
</pre>

<!--
| Dataset Subtype | Number of Image | Size of Images (GB/Gigabyte) |
| :-------------- | --------------: | ---------------------------: |
| **Total**       | 40,000          | 12 MB                        |
| **Training**    | 34,000          | 10.2 MB                      |
| **Validation**  | 6,000           | 1.8 MB                       |
| **Testing**     | 44,004          |                       |
-->

### Model and Training Prameters
| Current Parameters   | Value                                                       |
| :------------------- | ----------------------------------------------------------: |
| **Base Model**       | Linear Support Vector Machine                               |
<!--
| **Optimizers**       | Adam                                                        |
| **Loss Function**    | Categorical Crossentropy                                    |
| **Learning Rate**    | 0.0001                                                      |
| **Batch Size**       | 128                                                         |                                     
| **Number of Epochs** | 27                                                          |
| **Training Time**    | 9 min                                                       |
-->

### Model Performance Metrics (Prediction/ Recognition / Classification)
| Dataset              | Training       | Validation    | Test      |                                 
| :------------------- | -------------: | ------------: | --------: |
| **Accuracy**         | 78.64%         | ---           | 78.147%    |
| **Loss**             | ---            | ---           | ---       |
| **Precision**        | ---            | ---           | ---       |
| **Recall**           | ---            | ---           | ---       |
| **Roc-Auc**          | ---            | ---           | ---       |

<!--
### Other Experimented Model and Training Prameters
| Parameters (Experimented) | Value                                                  |
| :------------------------ | -----------------------------------------------------: |
| **Base Models**           | Custom Convolutional Neural Network wwith 888K params  |
| **Optimizers**            | Adam                                                   |
| **Loss Function**         | Categorical Crossentropy                               |
| **Learning Rate**         | 0.01, 0.001, 0.0001                                    |
| **Batch Size**            | 32, 64, 96, 128, 256                                   |                                     
| **Number of Epochs**      | 27 - 100                                               |
| **Training Time**         | 9min                                                   |

-->

### Hardware
| Parameters (Experimented) | Value                                                  |
| :------------------------ | -----------------------------------------------------: |
| **Platform**              | Cloud/Online                                           |
| **Platform Name**         | Kaggle Notebook                                        |
| **GPU Brand**             | NVidea                                                 |
| **Model Name**            | Tesla P100-PCIE-16GB                                   |
| **Memory**                | 16 GB                                                  |
| **Number of Core**        | 2                                                      |

<!--
### Visualization
#### Class Distribution: 
<kbd>
<img src=https://github.com/anjanatiha/Kannada-MNIST-Classification-with-Deep-Learning/blob/master/demo/images/class-dist.png>
</kbd>
-->
<!--
#### Model Performance: 
<kbd>
<img src=https://github.com/anjanatiha/Kannada-MNIST-Classification-with-Deep-Learning/blob/master/demo/report/hist.png>
</kbd>

<!--
##### Sample Output: 
<kbd>
<img src=https://github.com/anjanatiha/Histopathologic-Cancer-Detection/blob/master/demo/sample/sample.png>
</kbd>

<kbd>
<a href=https://github.com/anjanatiha/Histopathologic-Cancer-Detection/blob/master/demo/images/result.png>See More Images</a>
</kbd>
-->
<!--
##### Confusion Matrix: 
<kbd>
<img src=https://github.com/anjanatiha/Histopathologic-Cancer-Detection/blob/master/demo/report/CM.png alt="Confusion Matrix" width=800px height=600px>
</kbd>
-->
#### Tools / Libraries
<pre>
Languages               : Python
Tools/IDE               : Kaggle
Libraries               : scikit-learn
</pre>

#### Dates
<pre>
Duration                : February 2019 
Current Version         : v1.0.0.10
Last Update             : 02.12.2019
</pre>
