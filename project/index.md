---
date: 2021-06-16
title: "Project: Artificial Intelligence for Breast Cancer Detection in African American Women"
linkTitle: "377"
tags: ["project", "reu", "breast cancer", "AI", "diagnosis detection", "African American"]
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

Breast Cancer is one of the most dangerous type of disease that affects many women. For detecting Breast Cancer, machine learning techniques are applied to improve the accuracy of diagnosis. We collected data from African American women that have been diagnosed with Breast Cancer. Through the use of Artificial Intellingence, we will be able to detect the specific forms of Breast Cancer.

Contents

{{< table_of_contents >}}

{{% /pageinfo %}}

**Keywords:** tensorflow, example. 

## 1. Introduction

  The leading cause of cancer death in women worldwide is breast cancer. This deadly form of cancer has impacted many women across the globe. Specifically, African American women have been the most negatively impacted. Their death rates due to breast cancer have surpassed all other ethnicities. Serial screening is an essential part in detecting Breast cancer. Detecting the early stages of this disease and decreasing mortality rates is most effective by utilizing serial screening. Some women detect that they could have breast cancer by discovering a painless lump in their breast. Other women began to detect that there may be a problem due to annual and bi-annual breast screenings. Screening in younger women is not likely, because breast cancer is most likely to be detected in older women. Women from the age 55 to 69 are likely to be diagnosed with breast cancer. Women who frequently participate in receiving mammograms reduce the chance of breast cancer mortality.

  Artificial Intelligence is the branch of computer science dedicated to the development of computer algorithms to accomplish tasks traditionally associated with human intelligence, such as the ability to learn and solve problems. This branch of computer science coincides with diagnosing breast cancer in individuals because of the use of radiology. Radiological images can be quantitated and can inform and train some algorithms. There are many terms that relate to Artificial Intelligence such as artificial neural networks (ANNs), machine and deep learning (ML, DL). These techniques complete duties in healthcare, including radiology. Machine learning interprets pixel data and patterns from mammograms. Benign or malignant features for inputs are defined by microcalcifications. Deep learning is effective in breast imaging, where it can identify several features such as edges, textures, and lines. More intricate features such as organs, shapes, and lesions can also be detected. Neural networks algorithms are used for image feature extractions that cannot be detected beyond human recognition.

 


> Tip: Please note that an up to date version of these instructions is available at
>
> * <https://github.com/cybertraining-dsc/hid-example/blob/main/project/index.md>


Here comes a convincing introduction to the problem

## 2. Report Format

The report is written in (hugo) markdown and not commonmark. As such some features are not visible in GitHub. You can 
set up hugo on your local computer if you want to see how it renders or commit and wait 10 minutes once your report is 
bound into cybertraining.

To set up the report, you must first `replace` the word `hid-example in this example report with your hid. the hid will 
look something like `sp21-599-111`

It is to be noted that markdown works best if you include an empty line before and after each context change. 
Thus the following is wrong:

```
# This is My Headline
This author does ignore proper markdown while not using empty lines between context changes
1. This is because this author ignors all best practices
```

Instead, this should be 

```
# This is My Headline

We do not ignore proper markdown while using empty lines between context changes

1. This is because we encourage best practices to cause issues.
```

## 2.1. GitHub Actions

When going to GitHub Actions you will see a report is autmatically generated with some help on improving your markdown. 
We will not review any document that does not pass this check.

## 2.2. PAst Copy from Word or other Editors is a Disaster!

We recommend that you sue a proper that is integrated with GitHub or you use the commandline tools. We may include 
comments into your document that you will have to fix, If you juys past copy you will 

1. Not learn how to use GitHub properly and we deduct points
2. Overwrite our coments that you than may miss and may result in point deductions as you have not addressed them.

## 2.3. Report or Project

You have two choices for the final project.

1. Project, That is a final report that includes code.
2. Report, that is a final project without code.

You will be including the type of the project as a prefix to your title, as well as in the Type tag
at the beginning of your project.

## 3. Using Images

![Figure 1](https://github.com/cybertraining-dsc/fa20-523-314/raw/main/project/images/chart.png)

**Figure 1:** Images can be included in the report, but if they are copied you must cite them [^1].

## 4. Using itemized lists only where needed

Remember this is not a powerpoint presentation, but a report so we recommend

1. Use itemized or enumeration lists sparingly
2. When using bulleted lists use * and not

## 5. Datasets

Datasets can be huge and GitHub has limited space. Only very small datasets should be stored in GitHub.
However, if the data is publicly available you program must contain a download function instead that you customize.
Write it using pythons `request`. You will get point deductions if you check-in data sets that are large and do not use
the download function.

## 6. Benchmark

Your project must include a benchmark. The easiest is to use cloudmesh-common [^2]
 
## 6. Conclusion

  The AI system is improving its diagnostic accuracy by significantly decreasing unnecessary biopsies. AI's algorithms for workflow improvement and outcome analyses are advancing. Although artificial intelligence can be beneficial to detecting and diagnosing breast cancer, there are some limitations to its techniques. The possibility of insufficient quality, quantity or appropriateness is possible.

## 8. Acknowledgments

Please add acknowledgments to all that contributed or helped on this project.

## 9. References

Your report must include at least 6 references. Please use customary academic citation and not just URLs. As we will at 
one point automatically change the references from superscript to square brackets it is best to introduce a space before 
the first square bracket.

[^1]: Use of energy explained - Energy use in homes, [Online resource] 
      <https://www.eia.gov/energyexplained/use-of-energy/electricity-use-in-homes.php>


[^2]: Gregor von Laszewski, Cloudmesh StopWatch and Benchmark from the Cloudmesh Common Library, [GitHub] 
      <https://github.com/cloudmesh/cloudmesh-common>

