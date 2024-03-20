# Project: Weakly supervised learning-- label noise and correction


### [Full Project Description](doc/project3_desc.md)

Term: Spring 2024

+ Team 10
+ Team members
<<<<<<< HEAD
	+ Lei Bao
	+ Yonghao Xu
	+ Jiaqi Lu
	+ Ada Wei

+ Project summary: In this project, we first created a convolutional neural network (CNN) model with three layers as our Model 1. This model provided a foundation to assess the impact of noisy labels on image classification accuracy and however requires advanced strategies to refine label quality and model robustness. Acknowledging the limitations faced by Model 1, we then created Model 2, which introduced a weakly supervised learning approach aimed at enhancing classification accuracy by using a subset of clean labels. As a result, Model 2 demonstrated improved performance over Model 1, validating the hypothesis that including weak supervision can reduce the effects of label noise.


>>>>>>> 33cb457a61792b6f429342a86168b083060ff892
	
**Contribution statement**: 
+ Jiaqi Lu: Model1, Model2
+ Yonghao Xu: Model1, Model2
+ Jia Wei

Jiaqi and Yonghao write model 1 together and tried several ways to "add model and procedures" in model 2, and decided the best way, ie, the label cleaning network. The other methods included adding layers to CNN, address the overfitting in CNN, adding robust loss functions, loss functions, data augmentation, layers normalization, etc. It approximate cost 10 hours on coding trials.

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
