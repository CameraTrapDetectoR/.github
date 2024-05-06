## :wolf: Welcome to the CameraTrapDetector Project :wolf:


**The CameraTrapDetector project is a set of customized object detection deep learning models that identify, classify, and count animals in camera trap images.** 
**The model can be run on personal computer as part of an existing workflow, saving time and preserving data privacy.**

Our mission is to provide an accurate, easy-to-use, free computer vision tool to process large camera trap datasets. Users with no coding experience can automate the time-intensive task of classifying images, and optimize their time spent thinking analytically. Our tool enables researchers and land managers to perform analyses and make decisions faster and with more comprehensive information.

---

:pig: To use the packaged model in R, RStudio, or the R Shiny interface, see the [CameraTrapDetectoR](https://github.com/CameraTrapDetectoR/CameraTrapDetectoR) repository.  
  
:cow: To use the interactive app on your desktop without any code interface, see the [Desktop App](https://github.com/CameraTrapDetectoR/DesktopApp) repository. 

:rabbit2: To deploy the models on HPC or via command line, see the [Model Training](https://github.com/CameraTrapDetectoR/model_training) repository.  

:evergreen_tree:  See our new package on creating your own randomly-placed camera trap array: [cameratrapgridR](https://github.com/CameraTrapDetectoR/cameratrapgridR.git)

:horse: To peruse the helper and template scripts related to our project, see the [Resources](https://github.com/CameraTrapDetectoR/CameraTrapDetectoR_Resources) repository.

:pig2: To collaborate with us by sharing images or offering feedback, send us a message: cameratrapdetector@gmail.com


---
## :sheep: Model Versions and Performance :sheep: ##

CameraTrapDetector hosts custom-trained deep object detection models at the taxonomic class, family, and species levels. The latest published version of each model is **Version 2**

<details>
<summary> <font size="3">  Species model performance:  </font> </summary>
 
![image](https://github.com/CameraTrapDetectoR/.github/assets/54477812/803730a6-8b98-4c47-b3d9-8e6bfb2173ed)

</details><br>

<details>
<summary> <font size="3">  Family model performance:  </font> </summary>

![image](https://github.com/CameraTrapDetectoR/.github/assets/54477812/cd6a14bb-2b27-453e-b780-86e58ee5da0b)

</details><br>

<details>
<summary> <font size="3">  Class model performance:  </font> </summary>
  
Class model performance:
![image](https://github.com/CameraTrapDetectoR/.github/assets/54477812/89a18f99-1df8-4520-acf3-546fdd9dfcd7)

</details><br>

---
## :paw_prints: Development Plan :paw_prints: ##

Track our progress as we work to advance CameraTrapDetector's mission of publishing new, more accurate models with multiple, accessible use options.

<details>
<summary> <font size="3">  Data curation:  </font> </summary>
 ✔️ Detection-level image features of contrast, complexity, self-similarity, and symmetry to our annotations for better representative sampling<br>
 :chart_with_upwards_trend: Animal-level orientation, size, distance annotation for better representative sampling<br>
 :chart_with_upwards_trend: Incorporate new images into training database <br>
 🔲 Generate images of rare/invasive species in various settings and orientations using SMOTE techniques<br>
 :chart_with_upwards_trend: Review existing database to flag poor quality training samples<br>
</details><br>

<details>
<summary> <font size="3">  Model Training:  </font> </summary>
✔️ Pretrain Faster-RCNN weights on OOS camera trap images<br> 
✔️ Pretrain YOLO weights on OOS camera trap images<br>
:chart_with_upwards_trend: transfer learning with pre-existing camera trap model weights<br>
:chart_with_upwards_trend: Faster-RCNN model comparison with differing CNN backbones<br>  
 🔲 Prediction on video files<br>  
</details><br>

<details>
<summary> <font size="3">  R Package Deployment:  </font> </summary>
✔️ Prediction verification toolkit<br>
🔲 R Shiny makeover<br>
🔲 Submit package to CRAN for greater visibility<br>
</details><br>

<details>
<summary> <font size="3">  Desktop Deployment:  </font> </summary>
🔲 Revamp approach for more nimble app<br>
</details><br>

<details>
<summary> <font size="3">  Command Line / HPC Deployment:  </font> </summary>
✔️ Standardize output, including prediction plots, to R package output<br>  
🔲 cross-platform generalizability via containerization<br>
🔲 Integrate parallel processing, multi-GPU deployment<br> 
</details><br>

<details>
<summary> <font size="3">  Evaluation / Verification Workflow:  </font> </summary>
✔️ Output compatibility with [Camelot](https://camelotproject.org/)<br>
:chart_with_upwards_trend: Model mis-classified images to determine feature association with prediction accuracy<br>
  
</details><br>

---
## :owl: Citations :owl: ##

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
