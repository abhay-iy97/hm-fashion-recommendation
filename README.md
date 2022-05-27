# hm-fashion-recommendation 
H&M Personalized Fashion Recommendations using Ensemble Learning
- Participated in a [Kaggle competition](https://www.kaggle.com/competitions/h-and-m-personalized-fashion-recommendations) as part of the final project for CSCI-567 Machine Learning.
- Preprocessed raw transactional data and utilized the cudf library to accelerate the workflow.
- Performed exploratory data analysis to understand the trends across the customer and transactional data. Consequently, devised methods for individual component models. 
- Designed an ensemble-based solution for the task, employing various strategies such as LightGBM Ranker, Singular value decomposition for collaborative filtering, product recommendation based on clustering customers on various factors and many more approaches.
- Achieved a private leaderboard rank of 200 out of 2,952 teams on Kaggle and a rank of 2 out of 80 teams in the CSCI-567 Machine Learning course.

## Setup

Install conda from [here](https://docs.anaconda.com/anaconda/install/linux/)

Download dataset files from [here](https://drive.google.com/drive/folders/1ZRUIx0aF_PISnn-rHIlyQI7suYhbIcsy?usp=sharing) to input

Following structure should be present

```bash

   |-input
   |---handmbestperforming
   |---h-and-m-personalized-fashion-recommendations
   |---hm-00224-solution
   |---hm-00231-solution
   |---h-m-framework-for-partitioned-validation
   |---hm-parquets-of-datasets
   |---radek-210
   |---svd-model-reranking-implicit-to-explicit-feedback
   |-working

```

To create conda environment run following command

```
conda create -n cs567 --file requirements.txt
```

To activate environment,

```
conda activate cs567
```

To execute the jupter notebooks, run following command

```
jupyter-notebook
```

Open ensemble.ipynb from working directory available from drive or D2L to build the file. Click on Cell-> Run All
