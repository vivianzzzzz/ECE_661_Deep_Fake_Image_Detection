# ECE661: DeepFake Detection Group 17 
Members: Adler Viton, Jeremy Tan, Xiyue Zhang

## Requirements 
1. All models were trained on the lightning.ai platform as storing the data needed 1TB of storage to process all the videos. We worked on a teamspace, a feature of lighting.ai, and imported the code here for submission.
2. See requirements.txt fle for other installs. We include all dependencies to ensure replication of environment if you choose not use the lightning.ai platform.
3. Request access to data from the creators of FakeAVCeleb: https://sites.google.com/view/fakeavcelebdash-lab/

## Notebooks 
The `code` folder has various notebook files we used for experiments. 
### Download 
1. `code/download.ipynb` shows downloading the dataset from Kaggle. 
### Pre-processing 
1. `code/preprocessing.ipynb` shows how we processed the dataset to crop them into images. We include the FakeAVCeleb version to give you the general idea of how it was cropped.
### Experiments 
We show the notebooks we used to run our 4 experiments 
#### Experiment 1 
1. `code/model.ipynb` for the model training and inference 
2.  `code/Exp1_3Hodlout.ipynb` for tesing on holdout dataset 
#### Experiment 2
1. `code/Classifier.ipynb` for the model training of embedding model with classifers
2. `code/Holdout_Eval.ipynb` for tesing on holdout dataset  
#### Experiment 3
1. `code/model.ipynb` for the model training and inference 
2. `code/Exp1_3Hodlout.ipynb` for tesing on holdout dataset 
#### Experiment 4
1. `code/Exp4.ipynb` for testing base, pretrained, and finetuned models on blackbox dataset 
2. `code/Generalize_Eval.ipynb` for testing embedding model with classifers on blackbox dataset 


### References 
1. The DeepFake Detection Challenge Dataset,” 2020. [Online]. Available: http://arxiv.org/
abs/2006.07397
2. H. Khalid, S. Tariq, M. Kim, and S. S. Woo, “FakeAVCeleb: A Novel Audio-Video Multi-
modal Deepfake Dataset,” in Thirty-fifth Conference on Neural Information Processing Systems
Datasets and Benchmarks Track (Round 2), 2021. [Online]. Available: https://openreview.
net/forum?id=TAXFsg6ZaOl



