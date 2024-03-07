# M4_Exam_Assignment

## Introduction
This assignment is designed to explore the frontier of AI applications, focusing on the integration of Retrieval-Augmented Generation (RAG) with vector databases such as ChromDB and LanceDB, and the comparison of various prompt engineering techniques. The goal is to build generative responses with retrieved information as an application that not only showcases advanced AI and DL capabilities but also evaluates the impact of different prompt strategies on model performance.

## Objective
### Task Description
Create an application that utilizes RAG and vector databases, and systematically compares the effectiveness of at least three distinct prompt engineering techniques.

The initiative of the application is to create an application that can act as a Food Recipe Recommender. The file we're loading is a document of different recipes. The document is created by the group.

### Key Components
- RAG and Vector Database Integration: Implement RAG with ChromDB and LanceDB to enhance information retrieval and content generation.
- Transformer Model Adaptation: Use transformer models (SBERT or BERT)
- Prompt Engineering Comparison: Experiment with and evaluate at least three different prompt engineering techniques to determine their impact on the model’s performance.
- Platform Integration: Deploy the application on Hugging Face, with interactive access provided via Gradio or HF Spaces.

### Data/Document
The data used for conducting RAG is the recipes.pdf, this document contains 10 recipes of any kind of food around the world.

### Approach

#### 1. RAG and Vector Database Integration: Implement RAG with ChromDB and LanceDB to enhance information retrieval and content generation.
Using ChromaDB as a vector database with our document to integrate into the pretrained language model from HuggingFace "Mistral-7B-Instruct-v0.1" as our Retrieval-Augmented Generation approach.

#### 2. Transformer Model Adaptation: Use transformer models (SBERT or BERT)
Transformer Model Adaptation refers to the process of fine-tuning or adapting pre-trained Transformer models to specific downstream tasks or domains. We initialize the General Text Embeddings (GTE) model, which is based on BERT transformer model.

#### 3. Prompt Engineering Comparison: Experiment with and evaluate at least three different prompt engineering techniques to determine their impact on the model’s performance.
Experimenting with Prompt Engineering techniques such as N-shot, Chain of Thought and Self-consistency. 

#### 4. Platform Integration: Deploy the application on Hugging Face, with interactive access provided via Gradio or HF Spaces.
The Platform which it was integrated in is Gradio, that way we can provide an interactive experience with the generative responses and retrieved information function.

### Results
We get different outputs based on the structure and technique used to prompt the model.
This illustrates the importance of considering which purpose we want to fulfill with the application and how we structure the prompt for the model to provide an answer that aligns with the intentions.

For the Platform Integration, we proceed with the N-Shot Prompting as this seems to be the technique that fits the intentions the best and effectively contributes to the application's capabilities.



