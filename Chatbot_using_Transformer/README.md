
# Build a Chatbot with Transformers


## Installation

- Clone this repo to your local machine using `https://github.com/RaviVaishnav20/Deep_Learning_Applications.git`
- Extract the folder and upload on your Google Drive
- Open the notebook `Chatbot_using_Transformer.ipynb` in colab and Run it on GPU

## Target

### Dataset
We are using the Cornell Movie-Dialogs Corpus as our dataset, which contains more than 220k conversational exchanges between more than
10k pairs of movie characters. “+++$+++” is being used as a field separator in all the files within the corpus dataset. 
movie_conversations.txt has the following format: ID of the first character, ID of the second character, ID of the movie 
that this conversation occurred, and a list of line IDs. The character and movie information can be found in 
movie_characters_metadata.txt and movie_titles_metadata.txt respectively.

#### We are going to build the input pipeline with the following steps:
* Dataset Preprocessing
* Data Loading and Masking
* Embeddings
* MultiHead Attention Implementation 
* Feed Forward Implementation
* Encoder Layer
* Decoder Layer
* Transformer
* AdamWarmup
* Loss with Label Smoothing
* Defining the Model
* Training Function
* Evaluation Function
* Main Function and User Evaluation

## Formula and Architecture

### Positional Encoding
![Positional Encoding](https://github.com/RaviVaishnav20/Deep_Learning_Applications/blob/master/Chatbot_using_Transformer/images/Positional_encoding_formula.PNG)

### Scaled dot product attention
![Scaled dot product attention](https://github.com/RaviVaishnav20/Deep_Learning_Applications/blob/master/Chatbot_using_Transformer/images/attention_softmax.PNG)

### Optimizer
![Optimizer](https://github.com/RaviVaishnav20/Deep_Learning_Applications/blob/master/Chatbot_using_Transformer/images/optimizer.PNG)

### Transformer
![Transformer](https://github.com/RaviVaishnav20/Deep_Learning_Applications/blob/master/Chatbot_using_Transformer/images/transformer_architecture.png)

### Encoder Layer
![Encoder Layer](https://github.com/RaviVaishnav20/Deep_Learning_Applications/blob/master/Chatbot_using_Transformer/images/Encoder.png)

### Decoder Layer
![Decoder Layer](https://github.com/RaviVaishnav20/Deep_Learning_Applications/blob/master/Chatbot_using_Transformer/images/Decoder.png)

### Training Losses
![Training Losses](https://github.com/RaviVaishnav20/Deep_Learning_Applications/blob/master/Chatbot_using_Transformer/images/training_loses.PNG)

### Chatbot Action
![Chatbot Action](https://github.com/RaviVaishnav20/Deep_Learning_Applications/blob/master/Chatbot_using_Transformer/images/evaluate.PNG)




