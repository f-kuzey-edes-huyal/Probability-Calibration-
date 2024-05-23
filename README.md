# Probability-Calibration 


Algorithms that use maximum margin methods, such as **support vector machines** and **boosted decision trees**, tend to produce **mis-calibrated results** with probability estimates far from 0 and 1. We expect machine learning classifiers to reflect real probabilities accurately. Trusting a machine learning algorithm that says a tumor cell is not cancerous with 90% probability is different from relying on an algorithm that says with 58% probability that the cancer cell is not cancerous. In some classification tasks, an algorithm may give you a high probability for a specific class, but this may not correspond to the real probability. This discrepancy can lead to significant consequences, such as losing a patient or incurring a high profit loss for a company. Therefore, we must calibrate our classifiers to ensure we can rely on their outcomes.

In this Jupyter notebook, my goal is to illustrate the application of probability calibration and its impact on classification performance using a synthetic dataset. The kernel also compares classifier performance for a multi-class classification task. To avoid potential bias during calibration, I used different datasets to train our classifier and for calibration.

The Jupyter notebook was executed in the **Google Colab** environment. The **Python version** used was **3.10.12**, and the **scikit-learn** version was **1.2.2** .

If you're interested in delving into the theoretical background of probability calibration and understanding how various algorithms perform under such calibration, I highly recommend the two papers linked below:

- [Predicting Good Probabilities With Supervised Learning](https://www.cs.cornell.edu/~alexn/papers/calibration.icml05.crc.rev3.pdf)

* [Classifier Calibration: A survey on how to assess and improve predicted class probabilities](https://arxiv.org/abs/2112.10327)




