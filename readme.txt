4-5 Jul 2019
Project Submission for Red Dragon AI Course - Deep Learning Jumpstart Workshop

Medical Transcription Text Classification with Glove + LSTM / BERT

1) Objective: To classify 3 different diagnosis (i.e. Surgery, Consult - History and Phy and Radiology), out of the total 40 possible diagnosis based on Doctors' Transcription Texts**

2) Dataset: Obtained from https://www.kaggle.com/tboyle10/medicaltranscriptions, 5000 rows of labelled text data**

3) Challenges: Serverely imbalanced data, with classes having 6 - 100 rows of data.**

4) Approaches: 

   	Approach 1 (Transfer Learning Glove + LSTM)

	        i) Only consider top 3 distinct classes with resonable number of data, drop the remaining
        	ii) Adjust class_weights or upsample minority classess to handle imbalanced data
        	iii) Word Embedding with Pre-trained Gloved
        	iv) Train & Predict with LSTM Model

	Approach 2: (Fine Tuning BERT)
  
  	      i) Only consider top 3 distinct classes with resonable number of data, drop the remaining
              ii) Train & Predict with BERT
