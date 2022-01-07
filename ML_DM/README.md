Materials for Machine Learning & Data Mining of USTC Autumn 2021

Scope of Examination: 《机器学习》周志华 Ch.2-Ch.11,Ch.13

Recollections of final exam:

1. (Linear Module) 
   1) Which model do we choose when dealing with enormous features? Linear model or Non-linear models? Explain.
   2) What is normalization？Which of the following algorithms demands normalization？LR, Decision Tree, SVM, Random Forest, kNN.
   3) The reason or description of introducing $L_1\ \&\ L_2$ norm regularization to models. Since introducing regularization means introducing priori distribution to parameters, like $L_1$ introduces Laplacian distribution, what distribution does $L_2$ norm regularization introduce?

2. (Decision Tree) A sheet of several features to distinguish Martians & Humans，features consist of {Green,Legs,Height,Smelly}, each has two statuses:
   1) Construct a decision tree with ID3 algorithm
   2) The decision tree constructed by ID3 algorithm is not optimum，Can you construct a decision tree with only 3 features whose training error equals to 0?
   3) What can we do when the values of feature is continuous?

3. (PCA) A $2\times5$ data matrix is given. Use PCA to transform the matrix from 2-dimensional to 1-dimensional.

<!-- 半监督学习，集成，聚类分析，神经网络 -->

4. (Semi-supervised Learning)
   1) What is active learning?
   2) What's the difference between TSVM and SVM? Would TSVM always perform better than SVM? Explain it.

5. (Ensemble Learning)
   1) Explain why Random Forest computes faster than Bagging based on Decision Tree.
   2) What are the methods of ensemble learning? Explain why ensemble learning achieves better performance than base learners.
   
6. (Clustering)
   1) What are the limitations of k-means algorithm? How to overcome them?
   2) Analyse the difference of using minimum distance & maximum distance in AGNES algorithm.
   3) Give a real-life application of clustering algorithm.

7. (Bayes Network)
   1) 写出前向传播公式 
   2) 说明只用线性激活函数，多层神经网络等价于单层神经网络 

8. (SVM) Given positive sample (3,3),(4,3) & negative sample (1,1). Use SVM to find the maximum-margin classifier $\boldsymbol{w}^T\boldsymbol{x}$

9. 电信公司有多个套餐，推荐给用户合适的套餐
    1) 哪些机器学习方法可以选
    2) 选出你认为有用的数据
    3) 简述你使用的方法
