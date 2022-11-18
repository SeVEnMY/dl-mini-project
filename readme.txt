train.py: model training, default setting: 5-fold cross-validation with WRN as baseline model
test.py: model prediction, default setting: make final decision based on 5 models, using soft voting

data should be downloaded and put in the root folder of this project (same as readme.txt)
model will be saved in the folder called checkpoint_wrn (automatically created)