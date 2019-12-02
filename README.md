## Project 3: Facial Expression Recognition
<img src="figs/CE.jpg" alt="Compound Emotions" width="500"/>
(Image source: https://www.pnas.org/content/111/15/E1454)

+ Project summary: 

In this project, we created a classification engine for images of different facial expressions. We firstly extract linear distance features using SFFS and KSVM. Then, we also added some nonlinear features such as areas and slopes based on basic features.

In terms of classifiers, we considered GBM, LDA, KNN, Boosting, Random Forest and SVM methods. We cross compared the combinations of feature extraction methods and classifiers in order to find the optimal feature-classifer pair.

We also applied GBM as our baseline model with selected feature set to compare with our advanced model. The final advanced model chosen is (k) SVM+. For code details, please check on lib directory.

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
