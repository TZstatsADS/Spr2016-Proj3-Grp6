# Project CatsDogs: Predictive analytics-model evaluation and selection

#### - for cats versus dogs image data

Read [full project description](doc/project3_desc.md)

In this project, we will carry out model evaluation and selection for predictive analytics on image data. As data scientists, we often need to evaluate different modeling/analysis strategies and decide what is the best. Such decisions need to be supported with sound evidence in the form of model assessment, validation and comparison. In addition, we also need to communicate our decision and supporting evidence clearly and convincingly in an accessible fashion.

![image](https://i.ytimg.com/vi/8Ryo8Pf4NNE/hqdefault.jpg)

---
Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.

Team Members: Juan Campos, Jingying Zhou, Rong Wang, Yueying Teng, Ziyue Jin
 
Summary: The team developed  two models to classify images of dogs and cats. First, a baseline model based on color histograms and Linear Support Vector Machines was implemented.Then, advanced models were fitted to improve the accuracy and the best was selected. The final model is a RBF SVM based on Bag of Words, which achieves an accuracy of 78%.

Contribution Statement

ZJ, JZ, RW and JC discussed the baseline model and worked on extracting the labels and color histograms. ZJ and JZ found a way to deal with unreadable images and fitted the Linear SVM model. To build an advanced model, JC proposed to use OpenCV library in Python to extract features from images and implemented a Bag of Words model using Linear SVM. JC, YT and JZ discussed the model, proposed possible enhancements and distributed the work. JC and JZ explored other ways of clustering for the BoW model. RW and ZJ fitted different classifiers and used cross validation to estimate the error rate of each. Based on this, the best model was selected. YT created the final codes for baseline model and organized the Github folders. JC created the final code for the BoW feature extraction, the train.R and test.R. ZJ created the presentation.  All team members approve our work presented in our GitHub repository including this contribution statement.
 
 


