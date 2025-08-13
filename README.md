# Supplementary Codes for the MyData
This repository is for supplementary codes used to explore and analyze the Opportune moment dataset.

Data descriptor URL: ______________________

Dataset (without image and sound data) URL: https://doi.org/10.5281/zenodo.15922655

# Enironment 
We have run this code under the environment as below:

OS: Windows 10

CPU: Intel(R) Core(TM) Ultra 7 155H 3.80 GHz  (16-Core)

RAM: 32GB

* This is not mandatory; you can run this code although you have the smaller number of cores or RAM.

In addition, you need to install [conda](https://conda.io/projects/conda/en/latest/index.html) for managing packages and virtual environment.

# HOW-TO
Download the Dataset (without image and sound data). 

Download this repository
```console
$ git clone https://github.com/HAI-lab-KNU/MyData-SupplementaryCodes.git
$ cd MyData-SupplementaryCodes
```
Replicate our conda environment [environment.yml](environment.yml), referring to this.

Make sure that the Dataset folder (which contains ParticipantInfo.csv, Service.csv, ContextualFactor.csv, and Availability.csv) and the [technical_validation.ipynb](technical_validation.ipynb) notebook are placed in the same directory.

Run your own Jupyter environment.

Then, open [technical_validation.ipynb](technical_validation.ipynb).
