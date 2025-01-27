Chat_With_Document

Chat_With_Document is an advanced web application designed to enable seamless interaction with document-based content. It leverages state-of-the-art AI models to provide users with the ability to upload, process, and interactively chat with their documents for insights, summaries, and context-specific answers.

Key Features

Interactive Document Chat: Users can ask questions directly from the uploaded documents and receive AI-powered answers in real-time.

Advanced AI Integration: Built using cutting-edge AI models like LLaMA 3, Gemini Pro, and Google Generative AI.

Document Support: Handles a wide range of document formats such as PDFs, Word documents, and more.

Seamless User Experience: Intuitive interface built using Streamlit for simplicity and accessibility.

Efficient Retrieval: Enhanced by FAISS for fast and scalable similarity search.

Customizable Responses: Fine-tuned responses using LangChain for better contextual understanding.

Tech Stack

Frontend:

Streamlit: A simple and effective framework for creating web apps.

Backend:

Python: Core programming language for logic implementation.

PyPDF2: Extracts text and metadata from PDF files.

FAISS: Facilitates efficient document chunk searching and similarity.

LangChain: Provides a framework for creating conversational AI applications.

AI Models:

Google Generative AI: Ensures powerful and contextual language understanding.

LLaMA 3/Gemini Pro: Free and advanced large language models integrated for answering user queries.

Deployment:

Requirements managed via a requirements.txt file.

Virtual environment for dependency isolation.

Installation and Setup

Follow these steps to set up and run Chat_With_Document locally:

Prerequisites:

Python 3.8 or higher

Git

Steps:

Clone the Repository:
git clone https://github.com/yourusername/Chat_With_Document.git
cd Chat_With_Document

Create and Activate a Virtual Environment:
python -m venv .venv
.\.venv\Scripts\activate  # On Windows
source .venv/bin/activate   # On macOS/Linux

Install Dependencies:
        pip install -r requirements.txt

Run the Application:
         streamlit run app.py

Access the App:
Open your browser and navigate to http://localhost:8501/.

File Structure

C:\Users\Thameem Ansari\Chat_With_Document
├── .venv/                 # Virtual environment files (excluded in Git)
├── static/               # Static assets (CSS, images, JS)
├── app.py               # Main application logic
├── requirements.txt     # Project dependencies
├── .gitignore           # Git ignore rules

Features in Development

Multi-language Support: Enable interactions in multiple languages.

Database Integration: Store user sessions and document data.

Enhanced Document Parsing: Add support for more complex document structures.

Contribution

Contributions are welcome! To contribute:

Fork the repository.

Create a feature branch.

Commit your changes.
Submit a pull request.

License

This project is licensed under the MIT License. See the LICENSE file for details.