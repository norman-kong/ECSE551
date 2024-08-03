# Machine Learning Models

These projects were completed for the course ECSE 551 (Machine Learning for Engineers) at McGill University (W2023). 

### MP1: Linear Classifiers - Logistic Regression
- Performed standard statistical analyses on 2 datasets.
- Implemented logistic regression (from scratch, in Python) to classify the data.
- Analyzed and discussed its performance and the significance of the results. Our model gave a test accuracy of 74.8% and 70% on the datasets, respectively.
- Datasets:
  - kidney dataset: class 0 vs class 1 based on person attributes like glucose levels, heart rate, etc.
  - wine dataset: low vs. high quality based on wine attributes like hue, alcohol content, etc.
- Submitted in collaboration with Yinuo Li and Yicheng Yuan.
  
### MP2: Naive Bayes Model with K-Fold Cross Validation 
- Preprocessed text data for machine learning experiments (tokenization of text, conversion to word vectors, etc.). 
- Implemented the Bernoulli Naive Bayes model (from scratch) to classify text data.
- Analyzed and discussed its performance and the significance of the results. The model achieved a score of 95.18% and 91.3% on a preliminary test set and the official test set of an academic Kaggle competition (placing 12th, the highest from a submission by a single individual), respectively. 
- Dataset: text originated from reddit, classified into its originating subreddit (where it came from).

### MP3: Convolutional Neural Networks & Images
- Implemented a CNN to classify images. The model composed of two convolutional layers which apply filters to the input image to extract features, and two full connected layers to classify the extracted features. Following each convolutional layer is a max pooling layer to reduce the spatial size of the feature maps. The ReLU activation function is applied after each layer (Except the output layer, which uses the softmax activation function).
- Analzed and discussed its performance and the significance of the results. The model achieved a score of 78.6% on the official test set of an academic Kaggle competition (placing 17th). 
- Datasets:
  - Japanese digits: categories of Japanese digits.
  - clothing: categories of clothing ().
- Submitted in collaboration with Hongtao Xu and Homayoun Sohrabpour Shafti. 

note: datasets provided by Prof. Armanfard. 
