# Explanation-IAmodels- CT
The objective of this repository is to apply **LIME** and **Grad-CAM** to interpret the predictions of various artificial intelligence models, including:
* K-Nearest-Neighbours
* Support vector machine
* XGboost
* Convonutional Neural Network
* Random Forest

These models were trained to classify computed tomography (CT) images of the brain into three categories:
* 0: Normal
* 1: Hemorrhagic stroke (bleeding)
* 2: Ischemic stroke

As expected, models based on vectorized images provided explanations with little medical sense.  In contrast, the CNN demonstrated the ability to accurately identify regions associated with strokes.
