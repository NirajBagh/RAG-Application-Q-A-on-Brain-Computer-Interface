# RAG-Application-for-Brain-Computer-Interface

# How to run?
# Steps:
Clone the repository
https://github.com/NirajBagh/RAG-Application-for-Brain-Computer-Interface.git
# STEP 01- Create virtual environment after opening the repository in VS studio
py -m venv venv 
# STEP 02- Activate the enviroment
.\venv\Scripts\activate
# STEP 03- install the requirements
pip install -r requirements.txt
# Step 04- Create a .env file in the root directory and add your openai credentials as follows:
OPENAI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
# Step 05- Run the RAG application using following command:
streamlit run app1.py
