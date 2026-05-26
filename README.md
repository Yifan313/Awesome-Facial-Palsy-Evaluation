# Awesome Facial Palsy Evaluation

This repository provides an overview of selected key publications on AI-based Facial Palsy Evaluation (FPE) from 2008 to 2024, as elaborated in the following survey.
```
@article{zhang2024artificial,
  title={Artificial intelligence-based facial palsy evaluation: a survey},
  author={Zhang, Yating and Gao, Weixiang and Yu, Hui and Dong, Junyu and Xia, Yifan},
  journal={IEEE Transactions on Neural Systems and Rehabilitation Engineering},
  volume={32},
  pages={3116--3134},
  year={2024},
  publisher={IEEE}
}
```
If you find our survey is helpful in your research, please consider citing our paper😺.

---
## Content
- [Facial Palsy Databases](#facial-palsy-databases)
- [Machine Learning Approaches for FPE](#machine-learning-approaches-for-fpe)
  - [Appearance Feature-based Approaches](#appearance-feature-based-approaches)
  - [Geometric Feature-based Approaches](#geometric-feature-based-approaches)
  - [ML System Applications](#ml-system-applications)
- [Deep Learning Approaches for FPE](#deep-learning-approaches-for-fpe)
  - [Single-frame Based Approaches](#single-frame-based-approaches)
  - [Multi-frame Based Approaches](#multi-frame-based-approaches)
  - [DL System Applications](#dl-system-applications)

---
## Facial Palsy Databases
|Database|Year|Samples|Subject|Source|Paper|
|:-:|:-:|:-:|:-:|:-:|-|
|YFP|2018|32 videos|21 patients|YouTub|[Hierarchical Network for Facial Palsy Detection](https://ieeexplore.ieee.org/abstract/document/8575249)|
|MEEI|2020|60 videos and 480 imagess|9 healthy subjects and 51 patientss|Lab|[The spectrum of facial palsy: The MEEI facial palsy photo and video standard set](https://doi.org/10.1002/lary.27986)|
|AFLFP|2023|5,632 images|88 subjects|Lab|[AFLFP: A Database with Annotated Facial Landmarks for Facial Palsy](https://ieeexplore.ieee.org/document/9831121)|

---
## Machine Learning Approaches for FPE
### Appearance Feature-based Approaches
1. \[2009\] Quantitative Analysis of Facial Paralysis Using Local Binary Patterns in Biomedical Videos [Paper](https://ieeexplore.ieee.org/abstract/document/4806065)
2. \[2014\] Automatic recognition of facial movement for paralyzed face [Paper](https://doi.org/10.3233/BME-141093)
3. \[2014\] Quantitative assessment of facial paralysis using local binary patterns and Gabor filters [Paper](https://dl.acm.org/doi/abs/10.1145/2676585.2676607)
4. \[2015\] Quantitative analysis of facial paralysis based on filters of concentric modulation [Paper](https://ieeexplore.ieee.org/abstract/document/7382213)
5. \[2016\] Automatic evaluation of the degree of facial nerve paralysis [Paper](https://link.springer.com/article/10.1007/s11042-015-2696-0)
6. \[2016\] A Two-Stage Method for Assessing Facial Paralysis Severity by Fusing Multiple Classifiers [Paper](https://link.springer.com/chapter/10.1007/978-3-030-31456-9_26)
7. \[2016\] Evaluation of Facial Paralysis Based on Spatial Features of Filtered Images [Paper](https://doi.org/10.17706/ijbbb.2016.6.1.1-8)
8. \[2016\] Quantitative analysis of facial paralysis based on limited-orientation modified circular Gabor filters [Paper](https://ieeexplore.ieee.org/abstract/document/7899658)
### Geometric Feature-based Approaches
1. \[2010\] An image based quantitative evaluation method for Facial Paralysis [Paper](https://ieeexplore.ieee.org/abstract/document/5542829)
2. \[2015\] Evaluation and Severity Classification of Facial Paralysis using Salient Point Selection Algorithm [Paper](https://www.researchgate.net/profile/Padma-S-2/publication/283040192_Evaluation_and_Severity_Classification_of_Facial_Paralysis_using_Salient_Point_Selection_Algorithm/links/5f4766db92851c6cfde52cb8/Evaluation-and-Severity-Classification-of-Facial-Paralysis-using-Salient-Point-Selection-Algorithm.pdf)
3. \[2016\] Efficient quantitative assessment of facial paralysis using iris segmentation and active contour-based key points detection with hybrid classifier [Paper](https://link.springer.com/article/10.1186/s12880-016-0117-0)
4. \[2016\] Quantitative Assessment of Facial Paralysis Based on Spatiotemporal Features [Paper](https://globals.ieice.org/en_transactions/information/10.1587/transinf.2015EDP7082/_p)
5. \[2018\] An Unobtrusive Computerized Assessment Framework for Unilateral Peripheral Facial Paralysis [Paper](https://ieeexplore.ieee.org/abstract/document/7933175)
6. \[2021\] Facial Paralysis Detection on Images Using Key Point Analysis [Paper](https://www.mdpi.com/2076-3417/11/5/2435)
7. \[2021\] Automatic Assessment of Facial Paralysis Based on Facial Landmarks [Paper](https://ieeexplore.ieee.org/abstract/document/9520746)
8. \[2022\] Automatic Facial Palsy Diagnosis as a Classification Problem Using Regional Information Extracted from a Photograph [Paper](https://www.mdpi.com/2075-4418/12/7/1528)
9. \[2022\] Automatic Analysis of Asymmetry in Facial Paralysis Patients Using Landmark-Based Measures [Paper](https://journals.sagepub.com/doi/abs/10.1089/fpsam.2021.0247)
10. \[2022\] SVM and Logistic Regression for Facial Palsy Detection Utilizing Facial Landmark Features [Paper](https://dl.acm.org/doi/abs/10.1145/3549206.3549216)
11. \[2022\] Towards an Automatic Diagnosis of Peripheral and Central Palsy Using Machine Learning on Facial Features [Paper](https://arxiv.org/abs/2201.11852) 
### ML System Applications
1. \[2014\] Mobile Application for Diagnosis of Facial Palsy [Paper](https://d1wqtxts1xzle7.cloudfront.net/72578087/Mobile_Application_for_Diagnosis_of_Faci20211014-24802-1ueo7l.pdf?1738439566=&response-content-disposition=inline%3B+filename%3DMobile_Application_for_Diagnosis_of_Faci.pdf&Expires=1779764877&Signature=Kql8nKEAbWyVQNveyElEvvwFW2VK6~9U~RNv2pulkKrb3ArfmuWf71-E8eG3lb3x4WYFG1foMPVEgLRVmGlNohF1HBOUcOSOnpl3abRS~5Xugd4sppsN4IZVRMNvPKegfAMdMwG1r-R0jfRjeWRP~A-QjktZ3ugbCiI23iPFp3lg~0tiJp36G7mB6sHjEqVAn38NdOjNROC0QmqKowPudxgXPeZPQaJDJGZ4D-nL8RvGUq4nVYdisbP7~gHSlFgz1r1hjiNQhklok~KkCNEXyjJz1SohYBow1YOP6i2-im1xWaOS3G1LuF~0ZOXBx3mpTpA~KBWgSQKwDXRnbc9cLg__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA)
2. \[2015\] A Smartphone-Based Automatic Diagnosis System for Facial Nerve Palsy [Paper](https://www.mdpi.com/1424-8220/15/10/26756#Experiment)
3. \[2018\] A Machine Learning Approach for Automated Facial Measurements in Facial Palsy [Paper](https://journals.sagepub.com/doi/abs/10.1001/jamafacial.2018.0030)
4. \[2021\] The Auto-eFACE: Machine Learning–Enhanced Program Yields Automated Facial Palsy Assessment Tool [Paper](https://journals.lww.com/plasreconsurg/abstract/2021/02000/the_auto_eface__machine_learning_enhanced_program.30.aspx)
5. \[2023\] The Feasibility of An Automatical Facial Evaluation System Providing Objective and Reliable Results for Facial Palsy [Paper](https://ieeexplore.ieee.org/abstract/document/10077606)

---
## Deep Learning Approaches for FPE
### Single-frame Based Approaches
1. \[2016\] Automatic feature point detection using deep convolutional networks for quantitative evaluation of facial paralysis [Paper](https://ieeexplore.ieee.org/abstract/document/7852821)
2. \[2017\] Deep assessment process: Objective assessment process for unilateral peripheral facial paralysis via deep convolutional neural network [Paper](https://ieeexplore.ieee.org/abstract/document/7950486)
3. \[2018\] Nasolabial Folds Extraction based on Neural Network for the Quantitative Analysis of Facial Paralysis [Paper](https://ieeexplore.ieee.org/abstract/document/9006682)
4. \[2018\] Neurologist Standard Classification of Facial Nerve Paralysis with Deep Neural Networks [Paper](https://www.mdpi.com/1999-5903/10/11/111)
5. \[2018\] Automatic Grading of Palsy Using Asymmetrical Facial Features: A Study Complemented by New Solutions [Paper](https://www.mdpi.com/2073-8994/10/7/242)
6. \[2018\] Hierarchical Network for Facial Palsy Detection [Paper](https://ieeexplore.ieee.org/abstract/document/8575249)
7. \[2018\] Deep Hierarchical Network With Line Segment Learning for Quantitative Analysis of Facial Palsy [Paper](https://ieeexplore.ieee.org/abstract/document/8558494)
8. \[2019\] Automatic Facial Paralysis Evaluation Augmented by a Cascaded Encoder Network Structure [Paper](https://ieeexplore.ieee.org/abstract/document/8843901)
9. \[2020\] Automatic and Objective Facial Palsy Grading Index Prediction Using Deep Feature Regression [Paper](https://link.springer.com/chapter/10.1007/978-3-030-52791-4_20)
10. \[2020\] Automatic Facial Recognition System Assisted-facial Asymmetry Scale Using Facial Landmarks [Paper](https://journals.lww.com/otology-neurotology/abstract/2020/09000/automatic_facial_recognition_system.32.aspx)
11. \[2021\] Few-Shot Learning with a Novel Voronoi Tessellation-Based Image Augmentation Method for Facial Palsy Detection [Paper](https://www.mdpi.com/2079-9292/10/8/978)
12. \[2021\] Facial Nerve Paralysis Assessment based on Regularized Correntropy Criterion SSELMvc and Cascade CNN [Paper](https://ieeexplore.ieee.org/abstract/document/9723091)
13. \[2022\] Comparative Study of Deep Learning Algorithms for the Detection of Facial Paralysis [Paper](https://ieeexplore.ieee.org/abstract/document/9946491)
14. \[2023\] Quantitative Analysis of Facial Paralysis Based on TCM Acupuncture Point Identification [Paper](https://ieeexplore.ieee.org/abstract/document/10217761)
15. \[2023\] Facial Paralysis Recognition Using Face Mesh-Based Learning [Paper](https://pdfs.semanticscholar.org/c52f/7ede2b2f38075614c8b0c3661f76a5fe3c52.pdf)
16. \[2023\] Deep learning-driven diagnosis: A multi-task approach for segmenting stroke and Bell's palsy [Paper](https://www.sciencedirect.com/science/article/pii/S0031320323005642)
17. \[2024\] Intelligent Bell facial paralysis assessment: a facial recognition model using improved SSD network [Paper](https://www.nature.com/articles/s41598-024-63478-x)
### Multi-frame Based Approaches
1. \[2019\] 3DPalsyNet: A Facial Palsy Grading and Motion Recognition Framework Using Fully 3D Convolutional Neural Networks [Paper](https://ieeexplore.ieee.org/abstract/document/8811497)
2. \[2019\] Automatic Degree Evaluation of Facial Nerve Paralysis Based on Triple-stream Long Short Term Memory [Paper](https://dl.acm.org/doi/abs/10.1145/3364836.3364838)
3. \[2020\] Region Based Parallel Hierarchy Convolutional Neural Network for Automatic Facial Nerve Paralysis Evaluation [Paper](https://ieeexplore.ieee.org/abstract/document/9186079)
4. \[2020\] Automatic evaluation of facial nerve paralysis by dual-path LSTM with deep differentiated network [Paper](https://www.sciencedirect.com/science/article/pii/S0925231220300412)
5. \[2022\] Automatic Facial Paralysis Estimation with Facial Action Units [Paper](https://arxiv.org/pdf/2203.01800)
6. \[2022\] Advanced Analysis of 3D Kinect Data: Supervised Classification of Facial Nerve Function via Parallel Convolutional Neural Networks [Paper](https://www.mdpi.com/2076-3417/12/12/5902)
7. \[2024\] Facial Paralysis Symptom Detection Based on Facial Action Unit [Paper](https://ieeexplore.ieee.org/abstract/document/10496057)
### DL System Applications
1. \[2023\] Computer Vision System for Facial Palsy Detection [Paper](https://journal.mtu.edu.iq/index.php/MTU/article/view/1133)
2. \[2022\] A Ready-to-Use Grading Tool for Facial Palsy Examiners—Automated Grading System in Facial Palsy Patients Made Easy [Paper](https://www.mdpi.com/2075-4426/12/10/1739)
3. \[2022\] Towards a Reliable and Rapid Automated Grading System in Facial Palsy Patients: Facial Palsy Surgery Meets Computer Science [Paper](https://www.mdpi.com/2077-0383/11/17/4998)
4. \[2023\] Automatic Facial Palsy, Age and Gender Detection Using a Raspberry Pi [Paper](https://www.mdpi.com/2673-7426/3/2/31)
5. \[2020\] Smart Prediction System for Facial Paralysis [Paper](https://ieeexplore.ieee.org/abstract/document/9102600)
