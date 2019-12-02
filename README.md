## Project 3: Facial Expression Recognition
<img src="figs/CE.jpg" alt="Compound Emotions" width="500"/>
(Image source: https://www.pnas.org/content/111/15/E1454)

### ** To quickly overview the whole project and results, go to "doc" folder and look for "Presentation Slides.pdf", which is the one I used to give a speech about this project.

### ** To rerun the codes and examine all the details, go to "doc" folder and run "Main.Rmd".


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
