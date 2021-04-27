## Book-Genre-Classification-using-Natural-Language-Processing 
I have done this project along with Sravani Subraveti

Introduction: The book genre helps in classifying the books into various categories and thus summarizing the book into a label. The extraction of information about the book genres through its cover can be useful in various domains. The project focuses on implementing a complete application that inputs book cover image and outputs the genre of the book. The task of classifying the book title into its respective genres is cumbersome owing to the ambiguity in the title and the overlapping of labels. However, the application utilizes several deep learning models, different embedding matrix implementations, Natural Language Processing(NLP), and Optical Character Recognition(OCR) to develop a complete end-to-end solution for book title extraction and classification of the book into its genre. We also compare various models implemented based on their test accuracy and select the best one.

<img width="514" alt="ApplicationFlow" src="https://user-images.githubusercontent.com/55220359/116310243-bbe18d00-a777-11eb-9c13-1ee633abb55f.png">


The classification is performed using various Deep Learning algorithms like Convolutional Neural Layer Networks(CNN), Recurrent Neural Networks(RNN), Long Short-Term Memory(LSTM), etc. These algorithms require data to be in numeric form. Therefore, the main objective is to convert the unstructured text data into an equivalent structured numeric data.

Embedding Layer: The Embedding layer is used as the first layer of the neural network and is fitted using a supervised learning approach via the Back-propagation algorithm. The vectors are treated as trainable parameters of the model. The one-hot encoded representation of a word is mapped to the word vectors. The word vectors are joined together and fed as input to a Multi-Layer Perceptron model. In the case of Recurrent Neural Network, each word is passed as input in a sequence.
The training procedure and testing process is defined in the flowchart

<img width="213" alt="TrainingProcess" src="https://user-images.githubusercontent.com/55220359/116310435-02cf8280-a778-11eb-8150-3d8fff728a0b.png">
<img width="184" alt="TestingProcess" src="https://user-images.githubusercontent.com/55220359/116314242-d8cc8f00-a77c-11eb-8cfd-c7bca0af161e.png">
Several models were designed to perform the task of classification. Each model was initialized with its first layer as the Embedding layer to generate the Embedding
matrix that holds the real-value representation of the input text data. 
