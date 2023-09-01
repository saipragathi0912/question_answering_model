# Question Answering Model
## Description
The Question Answering Model is an Information Retrieval Based Question Answering system developed in Python. It leverages state-of-the-art natural language processing techniques using the Transformers library, and it utilizes Wikipedia as its primary source of information. This project allows users to input questions and receive precise answers based on the information available in Wikipedia articles.

## Frameworks and Modules Used
Wikipedia: We use the Wikipedia module to fetch and access information from the vast Wikipedia knowledge base.

Transformers: Transformers provide the core architecture for building and fine-tuning our question-answering model.

StanfordPOSTagger: This module is used for part-of-speech tagging to extract relevant words from text sequences.

Requests: We use the Requests library to make HTTP requests to Wikipedia and other web resources.

BM25Okapi: This module implements the BM25 Okapi algorithm, which aids in ranking and retrieving relevant documents.

## File Descriptions
main.py: This is the main entry point of our Question Answering Model. It imports the pre-trained model checkpoint, executes the model to process user questions, and returns the model's responses.

pos_tag.py: This module is responsible for part-of-speech tagging of text sequences. It helps identify and extract only the necessary words for question analysis and answer extraction.

question_answer.py: In this module, we retrieve relevant passages from Wikipedia articles based on user questions and extract answers from these passages.

retrieve_answer.py: This module is focused on extracting answers from the given passages, applying relevant ranking algorithms to provide the most accurate responses.

retrieve_documents.py: This module allows users to extract relevant documents from Wikipedia or other sources based on specific keywords or topics.

retrieve_passages.py: This module specializes in retrieving relevant passages from the selected documents, making it easier to narrow down the search for answers.
