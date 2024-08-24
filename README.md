# LangChain

## LangChain_SarvamAI2B_Demo.ipynb

This project demonstrates a Retrieval-Augmented Generation (RAG) application using LangChain and the Sarvam AI 2B-v0.5 language model.

### Overview

This application allows users to ask questions and receive answers based on information retrieved from a set of URLs. The process involves:

1. **Fetching URLs:** The application retrieves relevant URLs based on the user's query.
2. **Creating Embeddings:** The content from the fetched URLs is converted into embeddings after being converted into smaller chunks using Google BERT multilingual uncased. Embeddings are numerical representations of text that capture the semantic meaning of the content.
3. **Responding to Queries:** The application uses the embeddings to find the most relevant information and generates a response to the user's query using the Sarvam AI 2B-v0.5 language model.

## Technologies Used

* **LangChain:** A framework for developing applications powered by language models.
* **Sarvam AI 2B-v0.5:** A powerful language model from Sarvam AI.
* **Google BERT multilingual uncased:** A pre-trained language model used for creating embeddings.

## How to Run

1. **Install Dependencies:** Make sure you have the necessary libraries installed. You can install them using `pip install -r requirements.txt`.
2. **Provide URLs:**  Provide a list of URLs or a method to fetch relevant URLs based on user queries.
3. **Run the Application:** Execute the main script to start the application.


