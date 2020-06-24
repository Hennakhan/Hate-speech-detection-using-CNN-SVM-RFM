# Hate-speech-detection-using-RFM-SVM-and-CNN-model
In this research two different type of methods Natural Language Processing using multiclass RFM, SVM and Deep learning CNN method are used to identify hatespeech.
We are using the dataset provided by TRAC. The data is divided into two task. Task1 - Facebook comments, Task2 - Twitter tweets
The file name for TASK 1 is data-task1.csv and for task 2 it is data-task2.csv.

Run your code 

```shell
# 1. First, clone the repo
$ git clone https://github.com/Hennakhan/Hate-speech-detection-using-CNN-SVM-RFM.git
$ cd Hate-speech-detection-using-CNN-SVM-RFM

# 2. Install Python packages
$ pip install -r requirements.txt

#3. Download Word2vec pretrained  model (GoogleNews-vectors-negative300.bin.gz) and store it in main folder "Hate-speech-detection-using-CNN-SVM-RFM-model"
download from: https://github.com/mmihaltz/word2vec-GoogleNews-vectors

# 4. Run!
$ Run jupyter notebook "Task 1 - TextClassification_CNN_SVM_RFM.ipynb" or "Task 2 - TextClassification_CNN_SVM_RFM.ipynb"

# 5. Done
```

Note: You can replace the data file with your dataset and change the name of the file you are reading in the beginning (2nd cell) of "Task 1 - TextClassification_CNN_SVM_RFM.ipynb"

## Abstract
The Indian Institute of Technology’s(ISM) 2018 Workshop on Trolling, Aggression, and Cyberbully (TRAC) hosted a shared task focused on detecting aggressive text in both English and
Hindi. Our paper is inspired by one of the papers introduced during this workshop ’TRAC-1
Shared Task on Aggression Identification in Social Media for COLING 2018’ [10]. In our paper,
we are using the same dataset used by them; our dataset is labeled as Overtly Aggressive, Covertly
Aggressive, and Non-aggressive. We have trained our model for two tasks, English (Facebook)
task and English (Social Media) task, which also contains multi-lingual comments. We have used
a Deep Learning Convolution Neural Network, and multi-class classifiers Support Vector Machine
and Random Forest Method. Our accuracy for task 1 CNN model is 11% above average 10-fold
validation 44% and task 2 CNN model is 11% above average 10-fold validation of 45%. Our
accuracy for task 1 SVM model is same as average 10-fold validation of 54%, task 2 SVM model is
2% above average 10-fold validation of 53%, for task 1 RFM model has same accuracy as average
10-fold validation of 50%, and for task 2 RFM model is 4% below average 10-fold validation of
54%. We have also implemented SVM using bag of words our accuracy is 51% for Task 1 and
52% for Task 2.
