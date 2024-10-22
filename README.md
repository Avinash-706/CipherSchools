🧠 MinAI – Chat with Multiple PDFs! 📄🤖
MinAI is a web-based AI application that allows you to interact with multiple PDF files. Upload your documents, and MinAI will process them, allowing you to ask questions and receive context-aware answers from the content of your files.

🌐 Live Demo: Check it out here!

💻 GitHub Repository: Explore the project here!



✨ Features
📁 Upload PDFs: Easily upload one or multiple PDFs, and MinAI will process them for you.
❓ Ask Questions: Chat with MinAI by asking questions about the content of your uploaded PDFs.
⚡ Fast Processing: MinAI processes PDFs quickly, allowing for efficient information retrieval.
🛠️ Multi-PDF Support: Manage multiple PDFs with a total size of up to 200MB per file.
💬 Chat History: MinAI stores your conversation history for continuous and contextual interactions.
🛠️ Tech Stack
Frontend: Streamlit for a responsive UI.
Backend: Python, LangChain, FAISS for vector storage, and Google Generative AI for embeddings and response generation.
PDF Processing: PyPDF3 to extract text from PDFs.
Hosting: Deployed on Render.com.
🚀 How to Run Locally
Clone the Repository:
bash
Copy code
git clone https://github.com/bhargava-prashant/MinAI.git
cd MinAI
Install Dependencies:
bash
Copy code
pip install -r requirements.txt
Set Up Environment:
Create a .env file in the root directory.
Add your Google API Key:
plaintext
Copy code
GOOGLE_API_KEY=your_google_api_key_here
Run the App:
bash
Copy code
streamlit run app.py
Access the App:
Once the app is running, visit http://localhost:8501 to interact with MinAI.

📸 Screenshots
Here's a sneak peek of the app in action:



🎥 Demo Video
Check out a video demo to see how MinAI works in real-time.

🌐 How It Works:
Upload one or more PDF files (max 200MB per file).
MinAI processes the text from the PDFs.
Ask questions, and MinAI will give detailed responses based on the context from your files.
Chat history is preserved for reference and continuity.
🔧 Key Functions
Text Extraction: Extracts text from each page of the uploaded PDFs using PyPDF3.
Text Splitting: Splits the extracted text into manageable chunks for easier processing.
Vector Storage: Utilizes FAISS to store text chunks in a vector format for efficient searching.
Conversational Chain: MinAI uses LangChain with Google Generative AI models to provide detailed answers based on context.
📜 License
This project is licensed under the MIT License.

🤝 Contributions
Contributions are welcome! Feel free to fork the repository and create a pull request.

💡 Made with ❤️ by Prashant Bhargava
