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

Make sure that the Dataset folder (which contains UserInfo.csv, ServiceSession.csv, UserContexts.csv, and Availability.csv) and the [technical_validation.ipynb](technical_validation.ipynb) notebook are placed in the same directory.

Run your own Jupyter environment.

Then, open [technical_validation.ipynb](technical_validation.ipynb).

## Optional 
In [technical_validation.ipynb](technical_validation.ipynb), we used LONG_INTERACTION defined with a 3 minute threshold in our study. 

Researchers using our dataset can redefine the LONG_INTERACTION threshold to fit their needs in [interaction_thresholds.ipynb](interaction_thresholds.ipynb), which can be adjusted as follows: 

* for 5 minutes -> continue-to-nextInquiry2
* for 7 minutes -> continue-to-nextInquiry3
* for 9 minutes -> continue-to-nextInquiry4

After changing the threshold and running the [interaction_thresholds.ipynb](interaction_thresholds.ipynb), the Interruptibility.csv file in the Dataset folder will be updated; it can then be used in [technical_validation.ipynb](technical_validation.ipynb).
