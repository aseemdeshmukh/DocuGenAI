# DocuGenAI: Technical Documentation Assistant

**Webpage for the project:** https://kzmq9cy6n6cma4221npm.lite.vusercontent.net/#features

**Demo Video of the project**: https://www.youtube.com/watch?v=tAkFtXKmvPg

## Team Members
- Aseem Deshmukh (deshmukh.as@northeastern.edu)
- Diya Gandhi (gandhi.di@northeastern.edu)

## Overview
DocuGenAI is an AI-powered assistant that automates the creation, management, and visualization of technical documents. It combines Prompt Engineering, Retrieval-Augmented Generation (RAG), Multimodal Integration, and Synthetic Data Generation to enhance documentation workflows.

Built with an intuitive Streamlit UI, integrated with OpenAI GPT-4 Turbo models and ChromaDB vector store, DocuGenAI delivers a modern, scalable, and efficient solution for technical writers, developers, and teams.

---

## Key Features
- **Documentation Generator**: Create API documentation, code explanations, troubleshooting guides, and code generation with AI.
- **Knowledge Base Management**:
  - Upload ZIP files containing multiple file formats (.txt, .md, .json, .csv, .py, .html).
  - Generate synthetic documentation data for testing and training.
- **Retrieval-Augmented Generation (RAG)**: Retrieve relevant documents from ChromaDB to enrich AI-generated outputs.
- **Visualization Module**: Interactive similarity graphs using PCA or t-SNE reduction and Plotly charts.
- **Modern Frontend**: Beautiful and responsive Streamlit UI enhanced with custom CSS styling.

---

## Technical Architecture
- **Programming Language**: Python
- **Frontend**: Streamlit UI with custom CSS.
- **Backend**:
  - OpenAI API integration for documentation generation.
  - Prompt engineering and context retrieval.
  - Document processing and synthetic data generation using Faker.
- **Vector Store**: ChromaDB for storing and retrieving document embeddings.
- **Visualization Layer**:
  - PCA and t-SNE for dimensionality reduction.
  - Interactive visualization using Plotly.
- **Environment Management**: Secure API key management using dotenv.

---

## Results and Performance
- **Fast Document Generation**: Few seconds per documentation task.
- **Knowledge Base Scalability**: Supports hundreds of synthetic and real documents.
- **High Accuracy**: >85% task completion accuracy observed through manual evaluation.
- **Efficient Visualization**: Smooth document similarity mapping, even with large datasets.

---

## Lessons Learned
- Importance of fine-tuned **Prompt Engineering**.
- Handling t-SNE instability with small datasets via dynamic perplexity.
- The necessity of **Secure API Key Management**.
- The value of **Synthetic Data** for robust testing.
- Future enhancements include multi-model integration, semantic search, and user authentication.

---

## How to Run the Project

### Prerequisites
- Python 3.9+
- Install required libraries:
  ```bash
  pip install -r requirements.txt
  ```
- Create a `.env` file in the project root with the following:
  ```env
  OPENAI_API_KEY=your-openai-api-key
  ```

### Running the App
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/docugenai.git
   cd docugenai
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```bash
   streamlit run Document.py
   ```
4. Open the local Streamlit URL in your browser (typically http://localhost:8501).

### Optional
- To visualize document similarity, ensure at least two documents are uploaded or generated.
- To generate synthetic documentation samples, use the sidebar feature "✪ Generate Samples."

---

## License
This project is open-source and available under the MIT License.

---

## Acknowledgments
- OpenAI for GPT-4 Turbo API.
- ChromaDB for vector storage and retrieval.
- Streamlit for an easy and flexible frontend experience.
- Faker for synthetic data generation.
- Plotly for beautiful interactive charts.

---


