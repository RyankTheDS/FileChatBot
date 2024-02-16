# File Chatty, the FileChatBot
In order to create a chatbot with the capability of allowing the user to upload **PDF, DOCX and TXT** files,
we used **Streamlit** for the user interface. Because Streamlit is considered as one of the top open source
Python web frameworks for Data Science and Machine Learning projects, most professionals use this
framework to create creative, innovative and responsive user interfaces. Apart from the user interface, we
used the **Spyder IDE** to write our code and Anaconda prompt to run the source code. We chose **Python**
as the programming language. As for the **Large Language Model (LLM)**, we decided not to use
OpenAI’s LLM because it’s a paid service. Since there are other alternative free LLMs, we chose the
**google/flan-t5-xxl** LLM from HuggingFace, which is a Data Science and Machine Learning platform
that is open source, serving as a central hub for AI professionals and enthusiasts, functioning akin to a
GitHub specifically designed for AI. As for creating the **embeddings**, we will use
**sentence-transformers/all-MiniLM-L6-v2**.

We have provided the source code as well as a sample PDF file, which you can use to test out the File ChatBot. 
If you would like to upload your own file, please do not upload a large file as it may take a long time for the
chatbot to process your file.

Before executing the code, there are some important steps and configurations that have to be done in order to successfully run the
code without errors. You have to follow the steps written in both **part 1**, **part 2** and **part 3**

## Part 1: Downloading anaconda
You can find the download link through this link: https://www.anaconda.com/download
If you have trouble installing anaconda please use this link:
https://support.anaconda.com/hc/en-us

## Part 2: Necessary packages must be installed in anaconda prompt after successful installation of anaconda
_We did this project in another environment in Anaconda. Please refer to this youtube video:_
Refer to this video to create an environment in anaconda:
https://youtu.be/dkvgzL3gJVY?si=LiJWykBTxcHrlCVF

_Type the following commands in anaconda prompt:_
pip install streamlit pypdf2 langchain python-dotenv faiss-cpu
huggingface_hub
pip install python-docx
pip install InstructorEmbedding
pip install nltk
pip install streamlit-mic-recorder
pip install pyttsx3
pip install transformers
pip install googletrans==4.0.0-rc1
pip install autocorrect
pip install gTTS

## Part 3: How to run our program?
To run the program, please open Anaconda prompt and enter the following command:
streamlit run [absolute or relative file path to FileChatty.py]

Have fun testing out FileChatty!! 😀
