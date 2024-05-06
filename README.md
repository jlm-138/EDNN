# An evidential deep neural network for set-valued classification and novelty detection
Brief Introduction:
The code only gives the specific implementation of EDNN on the MNIST dataset, and when using other datasets, only need to change the backbone network and make corresponding parameter adjustment.
gecm_layers.py : the realization of the generalized evidential classifier module;
decision_layers.py : the realization of the utility-based decision module;
loss.py : loss for training;
all_data_train.py : training on all classes of MNIST;
ood_train.py : select several classes of MNIST for training as known classes and the rest as unknown classes;
set_valued_classification.py : the realization and evaluation of EDNN on set-valued classification;
ood_evaluation.py : evaluate the performance of EDNN on novelty detection;
lenet2_model.py : use LeNets++ as the backbone network of EDNN.
