# cassandradb_pdfquery
🔍 Project Title: AI-Powered PDF Question-Answering System with Astra DB and LangChain
Description:

Developed an intelligent question-answering system that enables users to query content from large PDF documents in natural language. The system uses LangChain, OpenAI, and Astra DB to build a scalable RAG (Retrieval-Augmented Generation) pipeline. It integrates OpenAI embeddings for semantic understanding and AstraDB Vector Store for persistent vector storage and fast retrieval.

Key Features:

📄 PDF Text Extraction: Utilized pdfplumber for high-quality text extraction from multi-page PDFs (e.g., Indian Union Budget).

✂️ Smart Chunking: Implemented LangChain’s CharacterTextSplitter to divide documents into semantically meaningful chunks optimized for token limits.

🧠 Embeddings & Indexing: Generated vector embeddings using OpenAI and stored them in a managed AstraDB Vector Store (AstraDBVectorStore).

🔍 Semantic Search: Enabled real-time, relevance-ranked document retrieval and similarity scoring for user queries.

💬 Interactive QA: Built an interactive command-line interface allowing users to input questions and receive answers powered by OpenAI’s LLM via LangChain.

🌐 Vector Database Integration: Leveraged Astra DB for scalable and cloud-native vector storage with LangChain compatibility.

Technologies Used: LangChain, OpenAI, Astra DB, Cassio, pdfplumber, VectorStoreIndexWrapper, Python, PyPDF2
