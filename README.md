# CS198 CVMIL Source Code
- Jeezer Lee

## Overview
This repository shows all the code and data used for this project.

## Running the notebooks
- To run the colab notebooks, ensure that you are using the T4 GPU environment as it is strictly required during training and testing.
- Also, for notebooks `198_2_Fine-tuning_for_RE_.ipynb` and `198_3_Base Case_for_RE_.ipynb`, ensure that your google drive is mounted and the following files are found in your drives root directory:
  -  `final_dev.xlxs`
  -  `final_test.xlxs`
  -  `final_train.xlxs`

 These are all found in the repository's `dataset` directory, 

 - As indicated in the notebook for fine-tuning (`198_2_Fine-tuning_for_RE_.ipynb`), each model during the grid search was saved. However, due to memory constraints, 
