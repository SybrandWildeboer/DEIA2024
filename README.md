# Workshop Assignments
Welcome to the afternoon session of our workshop on Unlocking the Potential of Large Language Models (LLMs). This session focuses on practical, hands-on experience with LLMs using the OpenAI Playground and Google Colab.

# Schedule
Time: 12:00 PM – 4:30 PM (excluding breaks)
# Assignments:
Building a Retrieval-Augmented Generation (RAG) system using vector stores in OpenAI Playground.
Fine-tuning a language model using a Google Colab notebook.
## Assignment 1: Building a RAG System Using Vector Stores
### Objective
Learn how to enhance language model responses by integrating a vector store to retrieve relevant information, thereby building a Retrieval-Augmented Generation (RAG) system.

### Instructions
Access OpenAI Playground

Log in to the OpenAI Playground: https://platform.openai.com/playground
### Introduction to Vector Stores

Familiarize yourself with vector stores by reviewing the documentation: https://platform.openai.com/docs/assistants/tools/file-search/vector-stores
### Data Preparation

Select a Topic: Choose a specific topic of interest for your team.
Gather Documents: Collect example documents related to your topic. You can use the following resources:
- Kaggle Datasets: https://www.kaggle.com/datasets
- Project Gutenberg: https://www.gutenberg.org/
- Wikipedia Article Export: https://en.wikipedia.org/wiki/Special
- OpenAI Cookbook: https://github.com/openai/openai-cookbook/tree/main/examples/data
Ensure Compliance: Verify that the documents comply with ethical guidelines and do not contain disallowed content.

### Create a Vector Store

1. In the Playground, navigate to the vector store section.
2. Upload Documents: Add your collected documents to create a new vector store.
3. Generate Embeddings: Once documents are added, embeddings are generated automatically.
### Query the Vector Store

1. Develop Queries: Formulate queries relevant to your topic.
2. Retrieve Information: Use the vector store to find documents that best match your queries.

### Integrate with Language Model

1. Craft Prompts: Incorporate the retrieved information into your prompts.
2. Generate Responses: Use the language model to generate enriched responses based on the prompts.

### Team Discussion

Analyze Results: Evaluate the relevance and accuracy of the generated responses.
Optimize: Experiment with different prompts and retrieval strategies to improve outcomes.
### Resources
OpenAI Playground: https://platform.openai.com/playground
Vector Stores Documentation: OpenAI Vector Stores Guide
### Data Sources:
Kaggle Datasets: https://www.kaggle.com/datasets
Project Gutenberg: https://www.gutenberg.org/
Wikipedia Export: https://en.wikipedia.org/wiki/Special

## Assignment 2: Fine-Tuning a Language Model
### Objective
Understand the process of fine-tuning a language model to perform a specific task, such as Named Entity Recognition (NER), using a pre-prepared Google Colab notebook.

### Instructions
Access the Google Colab Notebook

Notebook Link: https://colab.research.google.com/drive/1SuZ7usUjsQS6-Y5_RXioj-k5d0Y_H_ic?usp=sharing

### Select a Dataset for Fine-Tuning

Choose a dataset suitable for NER tasks. Examples include:
It needs to have the following characteristics:
1. Have a title 
2. Have something that describes the item from which you want to extract.
3. The named entities that should be extracted from the description (the desired outcome from the LLM)
4. Make sure the dataset is available through an url, preferably github as a csv file.

#### Example dataset (simplified)
| Title                          | Description                                                      | Named Entity Outcome                                      |
|--------------------------------|------------------------------------------------------------------|-----------------------------------------------------------|
| Apple Unveils New iPhone       | Apple has announced the release of the new iPhone 13 in the USA. | Apple (ORG), iPhone 13 (PRODUCT), USA (GPE)               |
| SpaceX Launches Starship       | SpaceX successfully launched its Starship rocket from Texas.     | SpaceX (ORG), Starship (PRODUCT), Texas (GPE)             |
| Microsoft Acquires GitHub      | Microsoft Corporation has acquired GitHub for $7.5 billion.      | Microsoft Corporation (ORG), GitHub (ORG), $7.5 billion (MONEY) |
| Olympic Games in Tokyo         | The 2020 Summer Olympics were held in Tokyo, Japan.              | 2020 Summer Olympics (EVENT), Tokyo (GPE), Japan (GPE)    |
| Climate Summit in Paris        | Leaders met in Paris to discuss climate change initiatives.      | Paris (GPE), climate change initiatives (TOPIC)           |

### Prepare the Data

Follow the notebook instructions to use the dataset.
Ensure that the data complies with OpenAI's policies and ethical guidelines.
### Fine-Tune the Model

Run the cells in the notebook to fine-tune the language model on your selected dataset.
Adjust hyperparameters (training set size) as necessary, but keep coding changes to a minimum.
### Evaluate the Fine-Tuned Model

Test the model's performance on a validation set or sample inputs.
Compare the results to the base model to assess improvements.
### Team Discussion

1. Reflect on Findings: Discuss the impact of fine-tuning on model performance.
2. Ethical Considerations: Consider any ethical implications related to data use and model behavior.
### Resources
Fine-Tuning Guide: OpenAI Fine-Tuning Guide

# Team Collaboration Guidelines
- One Notebook Per Team: Only one team member needs to run the notebook.
- Collaboration: Work together to make decisions and interpret results.
- Avoid Interference: Do not access or edit other teams' notebooks.

# Ethical Considerations
- Data Privacy: Ensure all data used is publicly available and complies with privacy laws.
- Content Policy: Avoid using disallowed content as per OpenAI's Usage Policies.

# Assistance and Support
- Instructor Support: Instructor and assistant are available to help with any questions or issues.
- Discussion Encouraged: Share insights and challenges with your team and others.

# Accessing the Fine-Tuning Notebook via URL
To make it easy to access the fine-tuning notebook, you can use the following link: https://colab.research.google.com/drive/1SuZ7usUjsQS6-Y5_RXioj-k5d0Y_H_ic?usp=sharing
It is also attached in this repository. However, the link allows quicker access to google colab.

Notebook Link: Fine-Tuning Notebook
# Additional Resources
OpenAI API Documentation: https://platform.openai.com/docs/api-reference
OpenAI Cookbook: https://github.com/openai/openai-cookbook
Hugging Face Datasets: https://huggingface.co/datasets