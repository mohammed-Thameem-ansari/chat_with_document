Chat with Document
chat_with_document is an innovative application that enables users to interact with and extract information from documents using cutting-edge AI technologies. This project leverages natural language processing and document parsing to create a seamless experience for users seeking to understand and query their documents efficiently.

Features
Document Parsing: Ability to parse and read various document formats (PDF, text, etc.).
AI-powered Queries: Interact with your document by asking questions in natural language and get accurate responses.
Generative AI Integration: Uses AI models for document-based information extraction and natural language understanding.
Tech Stack
Backend: Python, Streamlit
Libraries: google-generativeai, python-dotenv, langchain, pyPDF2, faiss-cpu, langchain_google_genai
API: Google API (for integration with generative AI models)
Deployment: Local deployment (plan for future deployment on cloud platforms like AWS, Heroku)
Setup Instructions
Follow these steps to get your environment up and running:

1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/mohammed-Thameem-ansari/chat_with_document.git
cd chat_with_document
2. Create a Virtual Environment
Create a virtual environment to isolate dependencies:

bash
Copy
Edit
python -m venv .venv
Activate the virtual environment:

On Windows:

bash
Copy
Edit
.\.venv\Scripts\activate
On macOS/Linux:

bash
Copy
Edit
source .venv/bin/activate
3. Install Dependencies
Install the required dependencies using pip:

bash
Copy
Edit
pip install -r requirements.txt
If requirements.txt is not available, you can install dependencies manually:

bash
Copy
Edit
pip install streamlit google-generativeai python-dotenv langchain pyPDF2 faiss-cpu langchain_google_genai
4. Set up the API Key
Make sure to create a .env file in the root directory of the project and add your Google API key:

makefile
Copy
Edit
GOOGLE_API_KEY=your_api_key_here
5. Run the Application
Once the environment is set up, you can run the application:

bash
Copy
Edit
streamlit run app.py
This will start the app, and you can interact with the document from the browser.

Usage
Upload a document to the system.
Ask questions related to the document in natural language.
The AI model will extract relevant information from the document and return answers.
Contributing
Contributions are welcome! If you'd like to contribute to the project, feel free to open a pull request. Here’s how you can contribute:

Fork the repository.
Create a new branch (git checkout -b feature-name).
Make your changes and commit them (git commit -am 'Add feature').
Push to your forked repository (git push origin feature-name).
Submit a pull request with a detailed description of your changes.
License
This project is licensed under the MIT License - see the LICENSE file for details.
