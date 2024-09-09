# **📝 Quizify**

**Quizify: AI-Driven Quiz Builder**

Quizify is an AI-powered tool that generates multiple-choice quizzes from user-uploaded PDFs. The system loads the PDF files using a **PDF Loader** and processes the content with embeddings via **textembedding-gecko@003** using the **Vertex AI API**. Once processed, **Google Gemini** receives the data and returns the questions and answers in JSON format, ensuring the results stay true to the document. The user interface, built with **Streamlit**, displays the generated quiz in an interactive format.

The project also leverages:
- **Google Service Account** for authentication
- **Langchain** for structured output parsing
- **Chroma** for embedding persistence
