# Chatbot_LangChain_LLMs_VectorDB_StreamlitChatbot with LangChain and Streamlit
This project features an AI-powered chatbot that utilizes LangChain and Streamlit to provide intelligent and multilingual interactions based on PDF document content. Here’s an overview of its capabilities:

Features:
Multilingual Support: The chatbot translates text between French and English, allowing users to interact in their preferred language.

PDF Document Processing: Users can upload PDF files, and the chatbot extracts and translates the text from these documents for easier understanding.

Advanced Text Analysis: The chatbot uses LangChain’s RecursiveCharacterTextSplitter to handle large texts efficiently, improving response accuracy.

Conversational AI: The system employs ConversationalRetrievalChain and Google Palm LLM to generate context-aware responses based on the content of the uploaded PDFs.

Streamlit Interface: A user-friendly web interface built with Streamlit for easy document upload and question submission.
How It Works

Upload PDFs: Use the sidebar to upload your PDF files.

Submit Documents: Click on "Submit" to process the PDFs. The chatbot will extract and translate the text.

Ask Questions: Enter your questions in the text input field, and the chatbot will provide answers based on the PDF content.
Getting Started

Clone the repository: git clone https://github.com/ABAKHAR721/Chatbot_LangChain_LLMs_VectorDB_Streamlit.git

Install the required packages using pip install -r requirements.txt.
Set up your environment variables, including GOOGLE_API_KEY.
Run the application: streamlit run app.py
For more details and to explore the code, visit the GitHub Repository.

Feel free to contribute or reach out if you have any questions!
