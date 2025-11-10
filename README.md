Trustworthy NLP README File

## Author

Eva Gavaller


## Directory Structure
- |--  nlp_project_finding_bias.ipynb 
- |--  nlp_project_replacing_preds.ipynb 
- |--  nlp_project_testing_bias.ipynb 
- |--  nlp_project_counterfactual_dataset.ipynb
- |--  nlp_project_Hooked_SAE_Transformer_Demo.ipynb
- |--  nlp_project_unlearning.ipynb



## Versions

Python : 3.11.12

## Notes
- The main two parts of the code are nlp_project_unlearning.ipynb and nlp_project_Hooked_SAE_Transformer_Demo.ipynb. The nlp_project_unlearning.ipynb is for the paper replication stage of my project, while the nlp_project_Hooked_SAE_Transformer_Demo.ipynb is for the second stage of my project: adding an SAE. The other files are for either preparing the dataset and making a counterfactual dataset to use in the nlp_project_unlearning.ipynb or for scoring accuracy/bias in the models after unlearning with Shapley values or adding an SAE to help in unlearning bias. 
- The nlp_project_unlearning.ipynb is a modified file from BiasWipe: Mitigating Unintended Bias in Text Classifiers through Model Interpretability 
from Mamta et al. The GitHub page can be found at https://github.com/20118/BiasWipe. I modified it to fit in a Jupyter notebook file, as well as lowering the memory requirements of the code. It was modified using suggestions from my research as well as GPT suggestions (which is noted in the code comments). 
- The nlp_project_Hooked_SAE_Transformer_Demo.ipynb uses code from a tutorial by Connor Kissane that I modified to use with a Gemma model. I also added code to prompt the model and save its answers at the bottom of the file. 
