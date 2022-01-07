中国科学技术大学 《机器学习与知识发现》 2021-22秋季学期

Materials for Machine Learning & Data Mining of USTC Autumn 2021

授课教师：陈恩红 徐林莉 徐潼 

Scope of Examination: 《机器学习》周志华 Ch.2-Ch.11,Ch.13

考试方式：开卷，建议使用提纲搭配《机器学习》《统计学习方法》

考试题目回忆：

1. (Linear Module) 
   1) Which model do we choose when dealing large quantities of features? Linear model or Non-linear models? Explain.
   2) What is normalization？Which of the following algorithms demands normalization？LR, Decision Tree, SVM, Random Forest, kNN.
   3) The reason or description of introducing $L_1\ \&\ L_2$ norm regularization to models. Since introducing regularization means introducing priori distribution to parameters, like $L_1$ introduces Laplacian distribution, what distribution does $L_2$ norm regularization introduce?

2. (Decision Tree) A sheet of several features to distinguish Martians & Humans，features consist of {Green,Legs,Height,Smelly}, each has two statuses:
   1) Construct a decision tree with ID3 algorithm
   2) The decision tree constructed by ID3 algorithm is not optimum，Can you construct a decision tree with only 3 features whose training error equals to 0?
   3) What can we do when the values of feature is continuous?

3. (PCA) A $2\times5$ data matrix is given. Use PCA to transform the matrix from 2-dimensional to 1-dimensional.

4. (Semi-supervised Learning)
   1) What is active learning?
   2) What's the difference between TSVM and SVM? Would TSVM always perform better than SVM? Explain it.

5. (Ensemble Learning)
   1) Explain why Random Forest computes faster than Bagging whose base learner is Decision Tree.
   2) What are the methods of ensemble learning? Explain why ensemble learning achieves better performance than base learners.
   
6. (Clustering)
   1) What are the limitations of k-means algorithm? How to overcome them?
   2) Analyse the difference of using minimum distance & maximum distance in AGNES algorithm.
   3) Give a real-life application of clustering algorithm.

7. (Bayesian Network) Hidden layers use $h(z)=cz$ as activate function.
   1) Write out a forward propagation equation of given network.  
   2) Can you construct a equivalent network without hidden layers?
   3) Prove that all MLPs using linear activate function has a equivalent network structure without hidden layers.

8. (SVM) Given positive sample (3,3),(4,3) & negative sample (1,1). Use SVM to find the maximum-margin classifier $\boldsymbol{w}^T\boldsymbol{x}+b=0$

9. (Open questions) A telecom-company provides various communicating packages，now we demand an algorithm on recommanding diverse packages to different users.
    1) What machine learning methods are suitable for this task?
    2) Select features from provided sheet that you think are significant. Our data sheet includes but is not limited to features like Calling time,
Network traffic consumption, etc.
    3) Give a brief description of the learning process you designed.
