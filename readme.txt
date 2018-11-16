Human Activity Recognition dataset suite

This is a collection of Bayesian Network classifiers related to Human Activity Recognition(HAR). Each folder contains models, configurations and classification results for 3 (to-add-more) HAR datasets:

-uci_har: UCI dataset for HAR with smartphones. Includes features from gyroscope and accelerometer data and labels for 6 activities. Available in https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones  

-uci_uiwads: UCI dataset for user identification from walking activities. I have included two one-vs-all classifiers for the two first users. X-Y-Y-Z accelerometer data is used directly as the features. Available in https://archive.ics.uci.edu/ml/datasets/User+Identification+From+Walking+Activity.

-unimib_shar: Dataset for identification of Activities of Daily Life (ADL) and falls. Includes X-Y-Z accelerometer data. I have extracted features such as mean,min,max,kurtosis,etc for the identification of the first ADL activities. Available in http://www.sal.disco.unimib.it/technologies/unimib-shar/. Feature extraction in /hw_aware_BN/Datasets/UniMiB-SHAR/generate_datasets.m.

Each folder contains three file types:

- name.net: Bayesian Network classifier trained by Weka. (also available in .xml bif format)
- name.txt: Result buffer from Weka.
- name.model: Model used in Weka.





