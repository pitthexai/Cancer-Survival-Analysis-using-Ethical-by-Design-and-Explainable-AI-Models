# Cancer-Survival-Analysis-using-Ethical-by-Design-and-Explainable-AI-Models

## Table of Contents
- [Abstract](#abstract)
- [Directory Descriptions](#directory-descriptions)
- [The Proposed Computational Pipeline](#the-proposed-computational-pipeline)
- [KneeXNet-2.5D: App Interface](#kneexnet-25d-app-interface)
- [The Osteoarthritis Initiative (OAI) Dataset](#the-osteoarthritis-initiative-oai-dataset)
- [Publications](#publications)
- [Acknowledgments](#acknowledgments)
- [Citation](#citation)





### Abstract
<p align="justify">Artificial intelligence (AI) continues to demonstrate substantial potential in predictive oncology, yet clinical translation demands models that are transparent, robust, and ethically aligned. This study presents an ethical-by-design and explainable AI framework for cancer survival analysis using the large-scale, population-based Surveillance, Epidemiology, and End Results (SEER) dataset. Our computational strategy integrates stage-stratified modeling with social and environmental determinants of health to enable context-aware survival prediction across ten major cancer types. We trained and validated multiple machine learning (ML) models incorporating both clinical features and contextual indices, including the Yost Index (YOST), Social Vulnerability Index (SVI), and Air Quality Index (AQI). To promote fairness, an Equalized Odds constraint was applied during ML training and evaluation, building more equitable performance across patient subgroups. Model-agnostic explainability techniques, SHapley Additive exPlanations (SHAP) and Local Interpretable Model-Agnostic Explanations (LIME), provided global and patient-level interpretability, revealing clinically coherent and biologically admissible attribution patterns. The proposed trustworthy AI framework achieved strong predictive performance across cancer types and stages while improving parity among demographic and socioeconomic groups. Collectively, this work introduces a scalable, interpretable, and fairness-aware paradigm for cancer survival modeling that advances safe and clinically meaningful AI development in oncology.
</p>



### Directory Descriptions
+ <p align="justify"><strong>Code:</strong> This directory contains all the Python code we implemented to carry out the study.</p>
+ <p align="justify"><strong>Annotation_guideline:</strong> This directory contains the annotation guidelines developed by domain experts for creating manual segmentation masks. </p>
+ <p align="justify"><strong>Fully_annotated_dataset:</strong> This directory contains the fully annotated imaging dataset used in this study, featuring the gold-standard manual segmentations.</p>
+ <p align="justify"><strong>Lightweight_application:</strong> This directory includes a lightweight, interactive software application designed to deploy KneeXNet-2.5D in both clinical and research settings.</p>
+ <p align="justify"><strong>Models:</strong> This directory includes all AI models developed for this study.</p>






### The proposed computational pipeline

![alt text](https://github.com/pitthexai/Knee_MRI_Segmentation_2.5D/blob/main/Figures/pipeline.png  "The proposed computational pipeline")
</p>
<p>
</p>

### KneeXNet-2.5D: App Interface 

![alt text](https://github.com/pitthexai/Knee_MRI_Segmentation_2.5D/blob/main/Figures/app.png  "The software app")
<p align="center">
  <a href="https://www.youtube.com/watch?v=rZD0lrhb_KE" target="_blank">
     Click here to watch the App demo 
  </a>
</p>

### The Osteoarthritis Initiative (OAI) Dataset
<p>The authors thank the <a href="https://nda.nih.gov/oai" target="_blank"> Osteoarthritis Initiative (OAI)</a> for the datasets utilized in this research contribution.</p>


### Publications
+ <p align="justify"> KneeXNet-2.5D: A Clinically-Oriented and Explainable Deep Learning Framework for MRI-Based Knee Cartilage and Meniscus Segmentation <i>(under review at npj Health Systems)</i> </p>



### Acknowledgements
<p align="justify"> We gratefully acknowledge the Department of Health Information Management at the School of Health and Rehabilitation Sciences (SHRS), University of Pittsburgh, for providing the computational infrastructure and support that enabled the training and evaluation of our deep learning models. Their resources and technical assistance were instrumental in the successful completion of this study. </p>

### Citation:

<p align="justify">This contribution is fully described in our manuscript, entitled "<i>KneeXNet-2.5D: A Clinically-Oriented and Explainable Deep Learning Framework for MRI-Based Knee Cartilage and Meniscus Segmentation</i>", which is currently under review at <a href="https://www.nature.com/npjhealthsyst/" target="_blank">npj Health Systems</a>. Any publication or use of this work should cite this manuscript accordingly.</p> 


<p align="center">
  <a href="https://pitthexai.github.io/index.html" target="_blank">
    <img src="Figures/Pitthexai_QR.jpg" alt="Support QR Code" width="200"/>
  </a><br/>
  <b>Pitt Health + Explainable AI (Pitt HexAI) Research Laboratory</b>
</p>


