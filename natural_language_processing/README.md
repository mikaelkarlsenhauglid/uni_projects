# NLP-Duplicate-Detection
This project applies natural language processing techniques to detect duplicate questions on Quora. By combining various vectorization methods with a range of classification models—from simple baselines to advanced neural networks—we aim to find a balance between predictive performance and computational efficiency.
We explore methods such as Bag-of-Words, TF-IDF, Word2Vec, SBERT, and NeoBERT for embedding question pairs, and test models including logistic regression, Naïve Bayes, XGBoost, Siamese BiLSTM, and NeoBERT. The best-performing models are evaluated in terms of F1 score and inference time.

**Research Question**
What is the most practical solution for real-time duplicate question detection?

**Keywords:**
Semantic similarity, classification, duplicate questions, NeoBERT, SentenceBERT, Siamese BiLSTM, Word2Vec, TF-IDF, Bag-of-words, cosine, Quora dataset

**Abstract:**
This project evaluates the performance of 14 different model and vectorization technique combinations to identify effective combinations to classify duplicate questions on the Quora dataset. By testing two simple, count-based representations, Bag-of-words and TF-IDF, and benchmarking them against more sophisticated embedding methods, such as Word2Vec and SentenceBERT in combination with different classification tech- niques, such as a baseline threshold model, Logistic Regression, Na ̈ıve Bayes, XG Boost and a Siamese BiLSTM neural network, we can compare the relative effectiveness of the selected methods. The models assess text similarity using a combination of string-level and vector-based distance features derived from the various embeddings. Additionally, we tested a fine-tuned NeoBERT model which optimizes its embeddings and classification simultaneously, achieving the highest F1 score of 0.88 in our tests. It was shown that despite the high F1 score of the NeoBERT model, using the SentenceBERT encoder with cosine threshold- ing, Logistic Regression, and Na ̈ıve Bayes is significantly faster while still achieving a solid F1 score of 0.81, making it a good balance between predictive performance and computational efficiency.
The project shows that while transformer-based encoders can classify duplicate questions well, there is still room for improvement. Simple models can distinguish questions based on lexical overlap, while advanced models can capture semantic similarities. However, some question pairs require a very fine understanding of language and intent, which is not perfectly captured by the methods used in this project.
