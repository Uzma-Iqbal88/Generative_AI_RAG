Title: Generative AI Task 3 – RAG (Retrieval-Augmented Generation) Pipeline

Description:
This notebook implements a Retrieval-Augmented Generation (RAG) system using Python and Transformers. It demonstrates an end-to-end pipeline where:

PDF Reading: User-provided PDF documents are read and their text is extracted.
Embeddings: The extracted text is converted into sentence embeddings using SentenceTransformer for semantic search.
Document Search: Relevant documents for a user query are retrieved using a FAISS vector index.
Answer Generation: The retrieved context is fed into an AI model (Transformers or optional Unsloth 4-bit model) to generate an accurate answer.
Output: The system outputs a response to the user query based on the PDF content.

Tools & Libraries:

Python, PyPDF2, FAISS, sentence-transformers
Transformers (DistilGPT2 / optional Unsloth 4-bit model)
Google Colab with GPU

Use Case:
This RAG system can be used to generate contextual AI answers from educational notes, research PDFs, or other text-based resources.

Note:
Unsloth 4-bit models may produce runtime errors in some environments, so a stable transformer model is recommended for demonstration purposes.
