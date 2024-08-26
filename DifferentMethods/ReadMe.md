# Description
1.
- Developed a neural network comprising two hidden layers, each containing 128 neurons, and utilized CountVectorizer to extract features. Conducted a 5-fold cross-validation with 10 epochs. The validation accuracy achieved was 94.6%, while the training accuracy reached 100%.
- Utilized feature extraction methods such as Count Vectorizer, and TFIDF and word embedding methods such as GloVe, and BERT. Employed 5-fold cross-validation with 10 epochs for evaluation. Found that BERT delivered the best results, attaining a validation accuracy of 96.8%. 
- Text pre-processing like one-hot encoding is done on categorical data and additional features like n-grams and word embeddings are constructed. Different methods such as CountVectorizer, TF-IDF, GloVe and BERT are employed for feature extraction. Performance is evaluated using 5-fold cross-validation to assess the effectiveness of each feature construction approach.
- Conducted 5-fold cross-validation for various features with 10 epochs, and the results indicate that BERT achieved the highest validation accuracy of 96.8%, as clearly observed from the table.

<img width="412" alt="image" src="https://github.com/user-attachments/assets/a86b2355-ef1c-4d87-962d-4bc5a4165a20">

- Plotted the below graph

 <img width="507" alt="image" src="https://github.com/user-attachments/assets/0ce52d3e-afc0-4c57-9587-f79d8405c797">

2.	
- Utilized a neural network with two hidden layers, each containing 128 neurons. One-hot encoding was applied to categorical data. Various learning rates and optimizers were experimented with, and performance was evaluated using 5-fold validation and visualized through plotted graphs.
- Employed 5-fold cross-validation to assess performance with different learning rates using Adam optimizer. Average training and validation accuracy, along with their standard deviation, were tabulated for each learning rate.

<img width="348" alt="image" src="https://github.com/user-attachments/assets/f8159759-4aa8-4608-9c5a-b2ce49a80ade">

- Created a line graph illustrating the training and validation accuracy.

<img width="473" alt="image" src="https://github.com/user-attachments/assets/a7efeb80-d601-49e3-a854-6a9d31af9940">

- Conducted 5-fold cross-validation to evaluate performance with different optimizers such as Adam, SGD, RMSprop. Average training and validation accuracy, along with their standard deviation, were tabulated for each optimizer.

<img width="254" alt="image" src="https://github.com/user-attachments/assets/f74a0ed3-a128-49d1-8eee-8635311dc549">

- Generated a graph depicting the training and validation accuracies for different optimizers.

 <img width="522" alt="image" src="https://github.com/user-attachments/assets/f7da7239-924d-449f-965d-a2a689ca9501">

3.	
- Utilized a pre-trained Bert tokenizer sourced from the 'Bert-base-uncased' model for tokenization and implemented Bert to produce embeddings. This method involves converting textual data into tokens using Bert's tokenizer and subsequently generating embeddings to capture the semantics and context of the text.
- Utilized Keras GridSearch to assess performance across various combinations of optimizers and learning rates, determining that RMSprop combined with a learning rate of 0.003 yielded the optimal results. Consequently, employed neural networks comprising two hidden layers, each containing 128 neurons, and employed RMSprop as the optimizer with a learning rate of 0.003.
- Achieved an accuracy of 0.96, precision of 0.9618393483709272, recall of 0.96, and F1-score of 0.9601441767001727.
- Utilized a neural network for label prediction and saved the results to labels.csv.

