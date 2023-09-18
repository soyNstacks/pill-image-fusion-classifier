# pill-image-fusion-classifier [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/soyNstacks/pill-image-fusion-classifier/blob/main/final_implementation.ipynb)

This repository contains the official submission of the author for their final year project (BSc in Computer Science, UoL). 


## In This Repository
- [classed_dataset](https://github.com/soyNstacks/pill-image-fusion-classifier/classed_dataset.zip): Contains image samples in folders arranged according to their respective classes (NDC); top 40 classes with highest sample counts extracted from [ePillID-benchmark](https://github.com/usuyama/ePillID-benchmark/releases) 
- [original_directory.csv](https://github.com/soyNstacks/pill-image-fusion-classifier/original_directory.csv): Contains image file names, and completed alignment of pill metadata initially provided by [NIH Pill Image Data](https://www.nlm.nih.gov/databases/download/pill_image.html)
- [requirements.txt](https://github.com/soyNstacks/pill-image-fusion-classifier/requirements.txt): Contains list of the modules and packages required in this project
- [final_implementation.ipynb](https://github.com/soyNstacks/pill-image-fusion-classifier/final_implementation.ipynb): Interactive Python Notebook of final model implementation
- [experiments/experiment_feature-eng.ipynb](https://github.com/soyNstacks/pill-image-fusion-classifier/experiments/experiment_feature-eng.ipynb): Contains a few computer vision techniques that achieved satisfactory outcomes
- [experiments/experiment_model-development.ipynb](https://github.com/soyNstacks/pill-image-fusion-classifier/experiments/experiment_model-development.ipynb): Contains a ierative model development including baseline model amongst others
  
![usecase_jpg](https://github.com/soyNstacks/pill-image-fusion-classifier/assets/84957027/70666568-04cf-4e79-97c7-8b61777dba05)


## Aims
To build a pharmaceutical pill image classifier that sets forth a preliminary stage of developing a tool that allows patients to utilise image searching to potentially lower high rates of medication non-adherence in Singapore. At the same time, to investigate the impact and effectiveness of a distinctive method in combining hand-crafted features used in traditional CBIR systems with deep-learned features.


## Objectives
Aligned with the initial problem space, this project intends to serve as an intermediary stage of utilising deep learning to motivate a possible implementation of classification in pill image retrieval systems in Singapore, to minimise confusion caused by the visual appearance of medicines and encourage an improvement in the responsibility of patient-side drug adherence through automation. 

The main objective of the project is the encompassment of a multi-input fine-tuned model, adopting the craft of specific low-level features for feature engineering that differ from existing work in the domain for predictive power in pill image tools.


## Proposed Methodology 
![methodology_jpg](https://github.com/soyNstacks/pill-image-fusion-classifier/assets/84957027/90b9f176-236b-4152-9f9e-0cab72ad8336)


## Model Build-up 
<img width="2807" alt="Frame 1 (1)" src="https://github.com/soyNstacks/pill-image-fusion-classifier/assets/84957027/f2141d61-896e-4da8-8717-550cb6cbdc77">


## Final Model Workflow
![Fusion Model Illustration](https://github.com/soyNstacks/pill-image-fusion-classifier/assets/84957027/911f1739-2b18-49e6-99f1-e5e88d318669)
