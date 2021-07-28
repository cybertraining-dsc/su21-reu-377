---
date: 2021-06-16
title: "Project: Pros and Cons of Artificial Intelligence for Breast Cancer Detection in Women"
linkTitle: "377"
tags: ["project", "reu", "breast cancer", "AI", "diagnosis detection", "women", "early detection", "advantages", disadvantages"]
description: "Breast Cancer is one of the most dangerous type of disease that affects many women. For detecting Breast Cancer, machine learning techniques are applied to improve the accuracy of diagnosis."
author: RonDaisja Dunn
github_url: https://github.com/cybertraining-dsc/su21-reu-377/edit/main/project/index.md
resources:
- src: "**.{png,jpg}"
  title: "Image #:counter"
---

[![Check Report](https://github.com/cybertraining-dsc/su21-reu-377/workflows/Check%20Report/badge.svg)](https://github.com/cybertraining-dsc/su21-reu-377/actions)
[![Status](https://github.com/cybertraining-dsc/su21-reu-377/workflows/Status/badge.svg)](https://github.com/cybertraining-dsc/su21-reu-377/actions)
Status: draft, Type: Project


RonDaisja Dunn, [su21-reu-377](https://github.com/cybertraining-dsc/su21-reu-377), [Edit](https://github.com/cybertraining-dsc/su21-reu-377/blob/main/project/index.md)

{{% pageinfo %}}

## Abstract

The AI system is improving its diagnostic accuracy by significantly decreasing unnecessary biopsies. AI's algorithms for workflow improvement and outcome analyses are advancing. Although artificial intelligence can be beneficial to detecting and diagnosing breast cancer, there are some limitations to its techniques. The possibility of insufficient quality, quantity or appropriateness is possible. When compared to other imaging modalities, breast ultrasound screening offers numerous benefits, including a cheaper cost, the absence of ionizing radiation, and the ability to examine pictures in real time. Despite these benefits, reading breast ultrasound is a difficult process. Different characteristics, such as lesion size, shape, margin, echogenicity, posterior acoustic signals, and orientation, are used by radiologists to assess US pictures, which vary substantially across individuals. The development of AI systems for the automated detection of breast cancer using Ultrasound Screening pictures has been aided by recent breakthroughs in deep learning.

Contents

{{< table_of_contents >}}

{{% /pageinfo %}}

**Keywords:** project, reu, breast cancer, Artificial Intelligence, diagnosis detection, women, early detection, advantages, disadvantages 

## 1. Introduction

The leading cause of cancer death in women worldwide is breast cancer. This deadly form of cancer has impacted many women across the globe. Specifically, African American women have been the most negatively impacted. Their death rates due to breast cancer have surpassed all other ethnicities. Serial screening is an essential part in detecting Breast cancer. Detecting the early stages of this disease and decreasing mortality rates is most effective by utilizing serial screening. Some women detect that they could have breast cancer by discovering a painless lump in their breast. Other women began to detect that there may be a problem due to annual and bi-annual breast screenings. Screening in younger women is not likely, because breast cancer is most likely to be detected in older women. Women from the age 55 to 69 are likely to be diagnosed with breast cancer. Women who frequently participate in receiving mammograms reduce the chance of breast cancer mortality.

Artificial Intelligence is the branch of computer science dedicated to the development of computer algorithms to accomplish tasks traditionally associated with human intelligence, such as the ability to learn and solve problems. This branch of computer science coincides with diagnosing breast cancer in individuals because of the use of radiology. Radiological images can be quantitated and can inform and train some algorithms. There are many terms that relate to Artificial Intelligence such as artificial neural networks (ANNs), machine and deep learning (ML, DL). These techniques complete duties in healthcare, including radiology. Machine learning interprets pixel data and patterns from mammograms. Benign or malignant features for inputs are defined by microcalcifications. Deep learning is effective in breast imaging, where it can identify several features such as edges, textures, and lines. More intricate features such as organs, shapes, and lesions can also be detected. Neural networks algorithms are used for image feature extractions that cannot be detected beyond human recognition.

A computer system that can perform complicated data analysis and picture recognition tasks is known as artificial intelligence (AI). Both massive processing power and the application of deep learning techniques made this possible, and are increasingly being used in the medical field. Mammograms are the x-rays used to detect breast cancer in women. Early detection is important to reduce deaths, because that is when the cancer is most treatable. Screenings have presented a 15%-35% false report in screened women. Errors and the ability to view the cancer from the human eye are the reasons for the false reports. Artificial Intelligence offers many advantages when detecting breast cancer. These advantages include less false reports, fewer cases missed because the AI program does not get tired and it reduces the effort of reading thousands of mammograms.


## 2. Methods From Literature Review 

The goal was to emphasize the present data in terms of test accuracy and clinical utility results, as well as any gaps in the evidence. Women are screened by getting photos taken of each breast from different views. Two readers are assigned to interpret the photographs in a sequential order. Each reader decides whether the photograph is normal or whether a woman should be recalled for further examination. Arbitration is used when there is a disagreement. If a woman is recalled, she will be offered extra testing to see if she has cancer.

Another goal is to detect cancer at an earlier stage during screening so that therapy can be more successful. Some malignancies found during screening, on the other hand, might never have given the woman symptoms. Overdiagnosis is a term used to describe a situation in which a person has caused harm to another person during their lifetime. As a result, overtreatment (unnecessary treatment) occurs. Since some malignancies are overlooked during screening, the women are misled.

The methods in diagnostic procedures vary between radiologists and Artificial Intelligence networks. In a breast ultrasound exam, radiologists look for abnormal abnormalities in each image, while AI networks analyze each image in an exam that is processed separately using a ResNet-18 model, and a saliency map is generated, identifying the most essential sections. With radiologists, the focus is on photos with abnormal lesions and with AI networks the image is given an attention score based on its relative value. To make a final diagnosis, radiologists consider signals in all photos, and AI computes final predictions for benign and malignant results by combining information from all photos using an attention technique.

<img src="https://github.com/cybertraining-dsc/su21-reu-377/blob/main/project/images/IMG_9446.jpg"

## 3. Results From Literature Review

Using pathology data, each breast in an exam was given a label indicating the presence of cancer. Image-guided biopsy or surgical excision were used to collect tissues for pathological tests. The AI system was shown to perform comparably to board-certified breast radiologists in the reader study subgroup. In this reader research, the AI system detected tumors with the same sensitivity as radiologists, but with greater specificity, a higher PPV, and a lower biopsy rate. Furthermore, the AI system outperformed all ten radiologists in terms of AUROC and AUPRC. This pattern was replicated in the subgroup study, which revealed that the algorithm could correctly interpret Ultrasound Screening examinations that radiologists considered challenging.

Figure -
Analysis of saliency maps on a qualitative level- This figure displays the sagittal and transverse views of the lesion (left) and the AI's saliency maps indicating the anticipated sites of benign (center) and malignant (right) findings in each of the six instances (a-f) from the reader study.

## 4. Datasets



![Figure 2](https://raw.githubusercontent.com/cybertraining-dsc/su21-reu-377/main/project/images/Dataset%20Image.png)

**Figure 2:** The probabilistic forecasts of each hybrid model were randomly divided to fit the reader's sensitivity. The dichotomization of the AI's predictions matches the sensitivity of the average radiologists. Readers' AUROC, AUPRC, specificity, and PPV improve as a result of the collaboration between AI and readers, whereas biopsy rates decrease.



## 5. Conclusion

There are some benefits of AI help with mammogram screenings. The reduction in treatment expenses is one of the advantages of screening. Treatment for people who are diagnosed sooner is less invasive and expensive, which may lessen patient anxiety and improve their prognosis. One or all human readers could be replaced by AI. AI may be used to pre-screen photos, with only the most aggressive ones being reviewed by humans. AI could be employed as a reader aid, with the human reader relying on the AI system for guidance during the reading process.

However, there is also fear that AI could discover changes that would never hurt women. Because the adoption of AI systems will alter the current screening program, it's crucial to determine how accurate AI is in breast screening clinical practice before making any changes. It's uncertain how effective AI is at detecting breast cancer in different sorts of women or in different groups of women (for example different ethnic groups). AI could significantly minimize staff workload, as well as the proportion of cancers overlooked during screening, and the amount of women who are asked to return for more tests despite the fact that they do not have cancer. According to the findings of the reader survey, such teamwork between AI systems and radiologists increases diagnosis accuracy and decreases false positive biopsies for all 10 radiologists. This research indicated that integrating the Artificial intelligence system's predictions enhanced the performance of all readers.


## 6. Acknowledgments

Thank you to the extremely intellectual, informative, patient and courteous instructors of the Research Experience for Undergraduates Program.

1. Carlos Theran, REU Intructor
2. Yohn Jairo Parra, REU Intructor
3. Gregor von Laszewski, REU Instructor
4. Victor Adankai, Graduate Student

## 7. References

Your report must include at least 6 references. Please use customary academic citation and not just URLs. As we will at 
one point automatically change the references from superscript to square brackets it is best to introduce a space before 
the first square bracket.

[^1]: Use of energy explained - Energy use in homes, [Online resource] 
      <https://www.eia.gov/energyexplained/use-of-energy/electricity-use-in-homes.php>


[^2]: Gregor von Laszewski, Cloudmesh StopWatch and Benchmark from the Cloudmesh Common Library, [GitHub] 
      <https://github.com/cloudmesh/cloudmesh-common>
      
