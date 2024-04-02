## :wolf: Welcome to the CameraTrapDetector Project :wolf:



**The CameraTrapDetector project is a customized object detection deep learning model that identifies, classifies, and counts animals in camera trap images.** 
**The model can be run on personal computer as part of an existing workflow, saving time and preserving data privacy.**

---

:pig: To use the packaged model in R, RStudio, or the R Shiny interface, see the [CameraTrapDetectoR](https://github.com/CameraTrapDetectoR/CameraTrapDetectoR) repository.  
  
:cow: To use the interactive app on your desktop without any code interface, see the [Desktop App](https://github.com/CameraTrapDetectoR/DesktopApp) repository. 

:bear: To peruse the Python model pipeline, see the [Model Training](https://github.com/CameraTrapDetectoR/model_training) repository.  

:cat: To peruse the helper and template scripts related to our project, see the [Resources](https://github.com/CameraTrapDetectoR/CameraTrapDetectoR_Resources) repository.

:eagle: To collaborate with us by sharing images or offering feedback, send us a message: cameratrapdetector@gmail.com


---
## Model Versions and Performance ##

CameraTrapDetectoR hosts custom-trained deep object detection models at the taxonomic class, family, and species levels. The latest published version of each model is **Version 2**

Species model performance:  
![image](https://github.com/CameraTrapDetectoR/.github/assets/54477812/803730a6-8b98-4c47-b3d9-8e6bfb2173ed)

Family model performance:  
![image](https://github.com/CameraTrapDetectoR/.github/assets/54477812/cd6a14bb-2b27-453e-b780-86e58ee5da0b)

Class model performance:
![image](https://github.com/CameraTrapDetectoR/.github/assets/54477812/89a18f99-1df8-4520-acf3-546fdd9dfcd7)



---
## Citations ##

Each model type comes with its own DOI. If you use CameraTrapDetectoR in your work, please cite the model type(s) you deploy:  
  
**Species Model:**

@article{Burns2023,
author = "Amira Burns and Ryan Miller and Hailey Wilmer and Michael Tabak and Daniel Falbel and Tess Hamzeh and Ryan K. Brook and John A. Goolsby and Lisa D. Zoromski and Raoul Boughton and Nathan Snow and Kurt VerCauteren",
title = "{CameraTrapDetectoR Species Model}",
year = "2023",
month = "5",
url = "https://agdatacommons.nal.usda.gov/articles/model/CameraTrapDetectoR_Species_Model/25234231",
doi = "10.15482/USDA.ADC/1528955"
}

**Family Model:**  
  
@article{Burns2023,
author = "Amira Burns and Michael Tabak and Daniel Falbel and Tess Hamzeh and Ryan K. Brook and John A. Goolsby and Lisa D. Zoromski and Raoul Boughton and Nathan Snow and Kurt VerCauteren and Ryan Miller and Hailey Wilmer",
title = "{CameraTrapDetectoR Family Model}",
year = "2023",
month = "5",
url = "https://agdatacommons.nal.usda.gov/articles/model/CameraTrapDetectoR_Family_Model/25234243",
doi = "10.15482/USDA.ADC/1528979"
}

**General Model:**  
  
@article{Burns2023,
author = "Amira Burns and Ryan Miller and Hailey Wilmer and Michael Tabak and Daniel Falbel and Tess Hamzeh and Ryan K. Brook and John A. Goolsby and Lisa D. Zoromski and Raoul Boughton and Nathan Snow and Kurt VerCauteren",
title = "{CameraTrapDetectoR General Model}",
year = "2023",
month = "5",
url = "https://agdatacommons.nal.usda.gov/articles/model/CameraTrapDetectoR_General_Model/25234258",
doi = "10.15482/USDA.ADC/1528970"
}
  

  
To cite our supporting paper:

Tabak, M. A., Falbel, D., Hamzeh, T., Brook, R. K., Goolsby, J. A., Zoromski, L. D., Boughton, R. K., Snow, N. P., VerCauteren, K. C., & Miller, R. S. (2022). CameraTrapDetectoR: Automatically detect, classify, and count animals in camera trap images using artificial intelligence (p. 2022.02.07.479461). bioRxiv. [link to manuscript](https://www.biorxiv.org/content/10.1101/2022.02.07.479461v1)

Or  
  
@article {Tabak2022.02.07.479461, author = {Tabak, Michael A and Falbel, Daniel and Hamzeh, Tess and Brook, Ryan K and Goolsby, John A and Zoromski, Lisa D and Boughton, Raoul K and Snow, Nathan P and VerCauteren, Kurt C and Miller, Ryan S}, title = {CameraTrapDetectoR: Automatically detect, classify, and count animals in camera trap images using artificial intelligence}, elocation-id = {2022.02.07.479461}, year = {2022}, doi = {10.1101/2022.02.07.479461}, publisher = {Cold Spring Harbor Laboratory},, URL = {https://www.biorxiv.org/content/10.1101/2022.02.07.479461v1}, eprint = {https://www.biorxiv.org/content/10.1101/2022.02.07.479461v1.full.pdf}, journal = {bioRxiv} }
