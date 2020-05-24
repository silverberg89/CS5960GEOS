# CS5960GEOS
Master Thesis: "Feature and event analysis of seismic data using machine learning at Åknes."

List of packages needed:

Package | Version
------------ | -------------
numpy:          |          1.15.4
obspy:            |        1.1.0
pytorch:         |         1.2.0
sklearn:           |       0.20.3
matplotlib        |        3.1.1
seaborn:         |         0.9.0
torchvision:     |         0.4.0
re:              |         2.2.1
PIL:             |         6.2.1
pandas:          |         0.25.1
torch:           |         1.2.0
scipy:          |          1.2.1
glob:           |          Na
gc:             |          Na
pickle:         |          Na
os:             |          Na
copy:           |          Na
datetime:       |          Na
sys:            |          Na
random:         |          Na
time:           |          Na
apex:           |          Na

File description:

Package | Version
------------ | -------------
training.py:             |       Running training sessions.
classify.py:             |       Classifies data.
event_data_methods.py:   |       Load or create data.
methods.py:              |       Various functions used across the project.
cnn.py:                  |       Hold the core code for CNN (trainer,classifier,feature analyser).
nn.py:                   |       Hold the core code for NN (trainer,classifier,feature analyser).
cnn_nn.py:               |       Hold the core code for CNN\_NN (trainer,classifier,feature analyser).
svm.py:                  |       Hold the core code for SVM (trainer,classifier,feature analyser).
rf.py:                   |       Hold the core code for RF (trainer,classifier,feature analyser).
grid_search.py:          |       Na
features.py:             |       Hold all functions calculating the high level features.
backcam.py:              |       Core of Grad Cam and Guided backpropagation.
PCA_extractor.py:        |       Code for running the principal component analysis.
load_model.py:           |       Loads architectures from by PyTorch
unsupervised_learning.py:|       Code for performing unsupervised methods (K-means & Mean shift)
