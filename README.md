# Paper Collection for Confidence Calibration
Confidence calibration or uncertainty calibration - the process to calibrate the output probability distribution - is essential for neural networks. Papers with bold names are the representative works from my understanding. Feel free to contact me via linwei.tao@sydney.edu.au.

---

## Survey and Study
- [Revisiting the Calibration of Modern Neural Networks](https://arxiv.org/pdf/2106.07998.pdf) [NeurIPS 2021]
- [Rethinking Calibration of Deep Neural Networks: Do Not Be Afraid of Overconfidence](https://openreview.net/pdf?id=NJS8kp15zzH) [NeurIPS 2021]

 

## Calibration by Loss
- MMCE Loss: [Trainable calibration measures for neural networks from kernel mean embeddings](https://proceedings.mlr.press/v80/kumar18a/kumar18a.pdf) [ICML 2018]
- AvUC Loss: [Improving model calibration with accuracy versus uncertainty optimization](https://papers.nips.cc/paper/2020/file/d3d9446802a44259755d38e6d163e820-Paper.pdf) [NeurIPS 2020]
- **Focal Loss**: [Calibrating Deep Neural Networks using Focal Loss](https://proceedings.neurips.cc/paper/2020/file/aeb7b30ef1d024a76f21a1d40e30c302-Paper.pdf)[NeurIPS 2020]
- Soft Calibration Objective: [Soft Calibration Objectives for Neural Networks](https://arxiv.org/pdf/2108.00106.pdf) [NeurIPS 2021]

## Post-hoc Calibration 
- **Temperature Scaling**: [On Calibration of Modern Neural Networks](https://arxiv.org/pdf/1706.04599.pdf) [ICML2017]
- Isotonic regression: [Transforming classifier scores into accurate multiclass probability estimates](https://dl.acm.org/doi/pdf/10.1145/775047.775151) [KDD2002]
- Histogram binning: [Obtaining calibrated probability estimates from decision trees and naive Bayesian classifiers](https://cseweb.ucsd.edu/~elkan/calibrated.pdf) [ICML 2001]
- Bayesian Binning into Quantiles (BBQ): [Obtaining well calibrated probabili- ties using bayesian binning](https://people.cs.pitt.edu/~milos/research/AAAI_Calibration.pdf) [AAAI 2015]
- Beta calibration: [Beta calibration: a well-founded and easily implemented improvement on logistic calibration for binary classifiers](http://proceedings.mlr.press/v54/kull17a/kull17a.pdf) [AISTATS 2017]


## Regularization Methods
- Label Smoothing [When Does Label Smoothing Help?](https://arxiv.org/pdf/1906.02629.pdf)
- Mixup: [On Mixup Training: Improved Calibration and Predictive Uncertainty for Deep Neural Networks](https://arxiv.org/pdf/1905.11001.pdf) [NeurIPS 2019]
- AugMix: [AUGMIX: A SIMPLE DATA PROCESSING METHOD TO IMPROVE ROBUSTNESS AND UNCERTAINTY](https://arxiv.org/pdf/1912.02781.pdf) [ICLR 2020]
