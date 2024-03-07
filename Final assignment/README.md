This repository contains 3 files: a pdf, a folder with model components and a Google Colab notebook. 

The pdf:
The pdf is created in the python script and comes from Llama datasets where it is the OriginOfCovid19Dataset dataset.
It is then processed and made to a single string and converted to a pdf, which then is uploaded to Github. 
The string consist of question and answers and is seperated by [SEP]. The pdf is then used in the python file. 

The Google Colab notebook:
The notebook contains the code which is used to create a RAG-model based on the Llama dataset with information 
about Covid-19. The file contains SBERT embedding and Chroma to store this embedding. 
The LLM which is the "mistralai/Mistral-7B-Instruct-v0.1" model. There is performed prompt engineering to try and 
optimize the responses recieved from the RAG model.
Lasatly the model is deployed in a Gradio interface.

The model components:
The model components saved in this repository is for a Streamlit app hosted on HugginFace. 
A link is attached, however this link will not be working, as the streamlit app cannot run without a
NVIDEA CUDA GPU, which is not used due to financial constraints. 
https://huggingface.co/spaces/1111111Alexander111111/Final_Assignment
