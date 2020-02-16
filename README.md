# vague-labels

## Ambiguity

Gao, B. Bin, Xing, C., Xie, C. W., Wu, J., & Geng, X. (2017). Deep Label Distribution Learning with Label Ambiguity. IEEE Transactions on Image Processing, 26(6), 2825–2838. https://doi.org/10.1109/TIP.2017.2689998
* 本文考虑的实际上是label uncertainty，实验是图片的年龄识别，标签给的“25岁”不一定仅仅是25岁，而实际上是一个范围

## Imprecise
Younes, Z., Abdallah, F., & Denœux, T. (2010). Evidential Multi-Label Classification Approach to Learning from Data with Imprecise Labels, 119–128.
* Imprecise Labels是指标签有随机的错误（noise），与我们的定义不同

## label incompleteness
是指有的标签没有标出来，与我们的定义不同

Li, Y., Xu, Z., & Zhang, Z. (2015). Learning with Incomplete Labels, (IJCAI), 4062–4068.
* label incompleteness

Kong, X., Wu, Z., Li, L.-J., Zhang, R., Yu, P. S., Wu, H., & Fan, W. (2014). Large-Scale Multi-Label Learning with Incomplete Label Assignments. https://doi.org/10.1137/1.9781611973440.105
* label incompleteness
* PU Stochastic Gradient Descent
* 使用stacking，每个循环把上一次预测的label也作为输入


## Uncertainty
Irvin, J., Rajpurkar, P., Ko, M., Yu, Y., Ciurea-Ilcus, S., Chute, C., … Ng, A. Y. (2019). CheXpert: A Large Chest Radiograph Dataset with Uncertainty Labels and Expert Comparison. Retrieved from http://arxiv.org/abs/1901.07031
* 0，1，u 三类label


## Partial Label Learning， Superset Learning
Hüllermeier, E., & Beringer, J. (2006). Learning from ambiguously labeled examples. Intelligent Data Analysis, 10(5), 419–439. https://doi.org/10.3233/ida-2006-10503

Hullermeier, E., & Chen, W. (2015). Superset Learning Based on Generalized Loss Minimization, 1, 441–457. https://doi.org/10.1007/978-3-319-23525-7
