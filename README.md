This application, built with Streamlit, enables users to upload, analyze, and interact with PDF and text documents using locally hosted AI models.  

Key Features  
Document Upload:Supports PDF and text files  
Web Content Scrapig Extract text directly from URLs  
Document Visualization:Includes word clouds and frequency analysis  
AI-Powered Chat:Chat with documents using local AI models  
History Tracking:Maintains document and chat history  

Requirements
Python 3.8 or higher  
Ollama (for running local AI models)  
Llama3.2 model installed  

Setup Instructions
Clone the Repository: 
git clone https://github.com/QaissAA/ollama_final_ap.git  

Create and Activate a Virtual Environment: 
python -m venv venv  
source venv/bin/activate  # On Windows: venv\Scripts\activate  

Install Dependencies: 
pip install -r requirements.txt  

Install Ollama and Llama3.2 Model:
Follow installation steps at Ollama(https://ollama.com)  
Pull the model:ollama pull llama3.2  

Running the Application
streamlit run app.py  

How to Use
Manage Documents:
Upload PDFs or text files via the sidebar  
Add content by entering web URLs  
Chat with documents and delete files when needed  

Chat Functionality: 
Select a document from the sidebar  
Ask questions in the chat interface  
Receive AI-generated, context-aware answers  

Configuration  
Customize the application by editing `app.py`:  
Switch embedding or chat models  
Modify document chunk sizes  
Adjust logging settings  

Dependencies:
Streamlit  
ChromaDB  
LangChain  
Ollama  
WordCloud  
Matplotlib  

Troubleshooting Tips 
Confirm Ollama is running correctly  
Ensure the Llama3.2 model is available  
Verify Python version and library installations
