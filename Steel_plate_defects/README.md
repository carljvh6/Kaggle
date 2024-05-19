This is my work on the Kaggle competition [Steel Plate Defect Detection](https://www.kaggle.com/competitions/playground-series-s4e3). In this competition the aim was to predict a type of defect given some parameters.

In this competition I approached it as a multilabel problem, meaning that the model could predict one or more types of defect, or the model could predict none of the defects. Almost all of the code that I looked at converted the problem to a multiclass problem, meaning that it would be simpler and faster to train the models. But I used this as an opportunity to practice multilabel problems and I do think this approach is more true to the problem set.

Maintakeaways for me are the following
* XGBoost performed really well. It was very accurate and fast to train, even on a CPU
* Neural nets still performed reasonably well and were very fast to train and easy to implement. They did not perform as well as the XGBoost models, but may still be a useful tool to keep in the kit for a tabular data type problem

In this repository we have
* [Data exploration and preprocessing](https://github.com/carljvh6/Kaggle/blob/main/Steel_plate_defects/1_Data_exploration_preprocessing.ipynb)
* [XGBoost with Optune for optimisation of hyperparameters](https://github.com/carljvh6/Kaggle/blob/main/Steel_plate_defects/2_XGBoost_Optuna.ipynb)
* [Random Forests](https://github.com/carljvh6/Kaggle/blob/main/Steel_plate_defects/3_Random_forests.ipynb)
* [Neural nets usint FasAI API on Pytorch](https://github.com/carljvh6/Kaggle/blob/main/Steel_plate_defects/4_Neural_nets.ipynb)
* [Model evaluation](https://github.com/carljvh6/Kaggle/blob/main/Steel_plate_defects/1_Data_exploration_preprocessing.ipynb)