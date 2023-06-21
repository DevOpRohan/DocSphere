# DocSphere
## Chat with Your Multilingual Documents(can be Handwritten) Collections
A user-friendly conversational AI that allows users to easily ask questions and receive accurate answers from their collection of multilingual documents, including handwritten notes and PDFs, with relevant references provided.
Used OCR to extract text from various document types, including handwritten notes, followed by embedding generation and storage in a custom VectorStore data structure for efficient semantic searches and content retrieval.
A hybrid of Cosine-Similarity and Euclidean distance is used for Semantic Search to rank top k contents, followed by answer generation using GPT-4 along with references.
Used GCP Document AI for OCR, OpenAI embedding model, GPT-4, Python & FastAPI, and React.js
