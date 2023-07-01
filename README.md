# DocSphere

DocSphere is a user-friendly conversational AI that allows users to interact with their collection of multilingual documents, including handwritten notes and PDFs. It uses OCR to extract text from various document types, generates embeddings, and stores them in a custom VectorStore data structure for efficient semantic searches and content retrieval. The system uses a hybrid of Cosine-Similarity and Euclidean distance for Semantic Search to rank top k contents, followed by answer generation using GPT-4 along with references.

The UI is designed like a chat, where the user can ask questions and the bot will provide answers along with references (document name, page number). DocSphere supports a wide range of document types and languages, including handwritten documents.

## Live Web App
- [DocSphere](https://docsphere.netlify.app/)

<img width="902" alt="image" src="https://github.com/DevOpRohan/DocSphere/assets/86923317/a7cd2fdb-7136-4d93-acaf-59b73e9c8a4e">

- Just Ask about my projects, or upload any doc/book/handwritten notes and ask about that.


Note: Default user is user1.

## Submodules

1. **DocSphereApi (Python)**: This is the backend of the DocSphere system, responsible for processing and responding to user queries.
2. **DocSphereUi (React)**: This is the client-side application that users interact with. It communicates with the DocSphereApi to provide responses to the user.

## Technology Stack

- GCP Document AI for OCR
- OpenAI embedding model
- GPT-4
- Python & FastAPI
- React.js



## Getting Started

To get a local copy up and running, follow these simple steps.

1. Visit the main branch of each submodule (DocSphereApi and DocSphereUi).
2. Clone each submodule to your local machine.

## Contact

Your Name - [rohanvermadev@gmail.com](mailto:rohanvermadev@gmail.com)

Project Link: [https://github.com/DevOpRohan/Vision](https://github.com/DevOpRohan/Vision)
