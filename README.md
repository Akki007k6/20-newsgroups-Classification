# A Brief Introduction to The 20-Newsgroups Classification Case Study
<h2> 1. Business/Real-world Problem</h2>
The 20 Newsgroups data set is a collection of approximately 20,000 newsgroup documents, partitioned (nearly) evenly across 20 different newsgroups.
The 20 newsgroups collection has become a popular data set for experiments in text applications of machine learning techniques, such as text classification and text clustering.<br>
Source: http://qwone.com/~jason/20Newsgroups/ <br>
Kaggle : https://www.kaggle.com/datasets/crawford/20-newsgroups

<h3> 1.1. Problem Statement </h3> 
The data is taken from http://qwone.com/~jason/20Newsgroups/20news-18828.tar.gz . <br>
Each subdirectory in the bundle represents a newsgroup; each file in a subdirectory is the text of some newsgroup document that was posted to that newsgroup.
It consists of 20 Newsgroups; duplicates removed, only "From" and "Subject" headers (18828 documents).<br>
The objective is to classify the documents into their respective newsgroups.<br>
The subdirectory structure was removed and all the files were stored in the format <class_label>_filename.txt

<h3> 1.2. Performance Metrics </h3>
We will be evaluating our results based on Log Loss, Accuracy and Micro F1 Score.

<h2> 2. Deep Learning Approach </h2>
Here, we will use CNN with Word Embedding for Text Classification as the 1st Model. <br>
We will use CNN with Character Embedding for Text Classification as the 2nd Model. <br>
Also, we will use pre-trained glove vectors of static length. <br>

<h3> 3. Summary </h3>
![image](https://user-images.githubusercontent.com/102152085/159570198-4a05017d-c4aa-4013-93ed-87058c743319.png)
The model (CNN using word embedding) worked better than the model (CNN using character embedding).
