This post talks about uncertain related topics in machine learning. 

Overall, I classify all topics into **Data**, **Model**, **Label**, and **Outcome**. 

# Data/Model (disturb data/Model then understand)

Influence analysis
- Koh, P. W., & Liang, P. (2017). Understanding black-box predictions via influence functions. 34th International Conference on Machine Learning, ICML 2017, 4, 2976–2987. https://arxiv.org/pdf/1703.04730.pdf

Adversarial training
- I. J. Goodfellow, J. Shlens, and C. Szegedy. Explaining and harnessing adversarial examples. In ICLR, 2015. https://arxiv.org/pdf/1412.6572.pdf

Dropout
- Gal, Yarin, and Zoubin Ghahramani. "Dropout as a bayesian approximation: Representing model uncertainty in deep learning." international conference on machine learning. 2016. https://arxiv.org/pdf/1506.02142.pdf

Ensemble
- Lakshminarayanan, B., Pritzel, A., & Blundell, C. (2017). Simple and scalable predictive uncertainty estimation using deep ensembles. Advances in Neural Information Processing Systems, 2017-December(Nips), 6403–6414. https://arxiv.org/pdf/1612.01474.pdf

SDE-net

Multi-view training
- Combining Labeled and Unlabeled Data with Co-Training https://www.cs.cmu.edu/~avrim/Papers/cotrain.pdf

# Label (labels are disturbed)

Noise
- Natarajan, N., Dhillon, I. S., Ravikumar, P., & Tewari, A. (2013). Learning with noisy labels. Advances in Neural Information Processing Systems, 1–9. https://papers.nips.cc/paper/5073-learning-with-noisy-labels.pdf

Ambiguity
- Gao, B. Bin, Xing, C., Xie, C. W., Wu, J., & Geng, X. (2017). Deep Label Distribution Learning with Label Ambiguity. IEEE Transactions on Image Processing, 26(6), 2825–2838. https://doi.org/10.1109/TIP.2017.2689998
- 本文考虑的实际上是label uncertainty，实验是图片的年龄识别，标签给的“25岁”不一定仅仅是25岁，而实际上是一个范围

Imprecise
- Younes, Z., Abdallah, F., & Denœux, T. (2010). Evidential Multi-Label Classification Approach to Learning from Data with Imprecise Labels, 119–128.
- Imprecise Labels是指标签有随机的错误（noise）

Label incompleteness
- 是指有的标签没有标出来

- Li, Y., Xu, Z., & Zhang, Z. (2015). Learning with Incomplete Labels, (IJCAI), 4062–4068.
- Kong, X., Wu, Z., Li, L.-J., Zhang, R., Yu, P. S., Wu, H., & Fan, W. (2014). Large-Scale Multi-Label Learning with Incomplete Label Assignments. https://doi.org/10.1137/1.9781611973440.105


Uncertainty
- Irvin, J., Rajpurkar, P., Ko, M., Yu, Y., Ciurea-Ilcus, S., Chute, C., … Ng, A. Y. (2019). CheXpert: A Large Chest Radiograph Dataset with Uncertainty Labels and Expert Comparison. Retrieved from http://arxiv.org/abs/1901.07031
- 0，1，u 三类label


**Partial Label Learning， Superset Learning**
- Hüllermeier, E., & Beringer, J. (2006). Learning from ambiguously labeled examples. Intelligent Data Analysis, 10(5), 419–439. https://doi.org/10.3233/ida-2006-10503
- Hullermeier, E., & Chen, W. (2015). Superset Learning Based on Generalized Loss Minimization, 1, 441–457. https://doi.org/10.1007/978-3-319-23525-7
- 覆盖了若干个label的label称为superset

Multiple labels
- Learning with Multiple Labels https://papers.nips.cc/paper/2234-learning-with-multiple-labels.pdf
- each training instance is given a set of (or distribution over) candidate class labels and only one of the candidate labels is the correct one

**Disagreement**
- 每个training sample有多个人标记，且分歧很大。这个我目前在EEG seizure的数据就有这个问题

OOD (out-of-distribution)

Flip (二分类翻转)

# Metric 

Interpretability

Confidence
- Corbière, C., Thome, N., Bar-Hen, A., Cord, M., & Pérez, P. (2019). Addressing Failure Prediction by Learning Model Confidence, (NeurIPS), 1–12. Retrieved from http://arxiv.org/abs/1910.04851

TrustScore
- Jiang, H., & Kim, B. (2018). To Trust Or Not To Trust A Classifier, (NeurIPS).

Unknown-unknown
- Bansal, G., & Weld, D. S. (2017). A Coverage-Based Utility Model for Identifying Unknown Unknowns, 1463–1470.

Shapley
- A Unified Approach to Interpreting Model Predictions, NIPS 2017


Uncertainty
- Raghu, M., Blumer, K., Sayres, R., Obermeyer, Z., Kleinberg, R., Mullainathan, S., & Kleinberg, J. (2018). Direct Uncertainty Prediction for Medical Second Opinions. Retrieved from http://arxiv.org/abs/1807.01771