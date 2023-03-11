# Transformer Conditional VAE for music generation
YAI x POZAlabs 산학협력 1팀 <br>
NLP model for music generation <br>

## Members
👑조정빈<br>
박민수<br>
박수빈<br>
김성준<br>
김산<br>
김민서<br>
</br>

## Requirements
### Versions (Recommended)

<br>

## Model

<br>

## Dataset

### ComMU (POZAlabs)
https://github.com/POZAlabs/ComMU-code

<br>

## Pipeline

<br>

## Metrics (수정중)
To evaluate generation models we have to generate data with trained models and depending on what metrics we want to use, the generation proccess differ. 
Please refer to the explanations below to generate certain samples needed for evaluation.


### Classification Accuracy Score
- To compute Classicication Accuracy Score of Generated Music conditioned with certain meta data 
run
```
$ python compute_CAS.py --data_dir {./data} --meta_data {KEY}
```

### Diversity
- To compute the Diversity of Generated Music conditioned with certain meta data
run
```
$ python comput_diversity.py 
```

### Controllability


## Skills
Frameworks <br><img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/> 
