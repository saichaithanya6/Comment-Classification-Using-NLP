# Comment-Classification-Using-NLP and Machine Learning
The primary objective of this project is to classify comments into predefined categories using Natural Language Processing (NLP) techniques. This project can be used for various applications like detecting the
emotion of the person based on the product reviews, classifying the customer support ticket queries.

## About Data
The data set consists of 6k rows containing 2 columns. Each row have different comments and the type of emotion inferred from the comment. Emotion labels were assigned to each comment. The labels represent different
emotions, such as joy, anger, sadness, surprise, fear. Labeling was done manually by human annotators who were provided with guidelines for emotion classification.

### Steps for training and predicting the comments
In the first set, we will test these models using raw, unprocessed data, which includes all the textual elements such as stopwords and punctuation marks. Subsequently, in the second set of experiments, we will evaluate the 
models' performance after applying data preprocessing techniques, which involve the removal of stopwords and punctuation from the text. Then compare these results with the model that is done with processed data. Used Random 
forest and Multinomial Naive Bayes machine learning models.

The rationale behind this comparative analysis is to determine the extent to which data preprocessing affects the accuracy, efficiency, and overall performance of the Random Forest and Multinomial Naive Bayes models in a 
text-based task. By examining the models in both preprocessed and unprocessed data scenarios, we can gain valuable insights into the necessity and benefits of data cleaning steps in the context of these particular machine 
learning algorithms.

Random Forest is an ensemble learning method known for its robustness and capability to handle noisy data, while Multinomial Naive Bayes is a probabilistic classifier commonly used for text classification tasks. By 
comparing the results of these two models on unprocessed and preprocessed data, we can determine the impact of text cleaning on the models' ability to make accurate predictions.

### Conclusion
Successfully achieved an impressive 97% accuracy in text prediction by leveraging advanced techniques in Natural Language Processing (NLP) combined with powerful machine learning models. To gain deeper insights into the 
impact of data preprocessing, I compared the prediction results before and after applying text preprocessing techniques.
It's worth noting that in the current dataset, the difference in results caused by preprocessing was relatively minor. However, this observation serves as a valuable insight. It suggests that the dataset used for this
analysis might be well-structured and clean, leading to negligible variations post preprocessing.
Real-world data often comes with noise, inconsistencies, and unstructured formats. As a result, the preprocessing steps are likely to unveil their true significance. The anticipated dataset, being more complex and diverse,
is likely to exhibit a significantly greater disparity in outcomes due to the meticulous preprocessing steps taken.
