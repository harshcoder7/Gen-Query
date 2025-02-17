# GenQuery: AI-Driven Research Query Tool

GenQuery is an AI-powered platform designed to streamline academic research by enabling efficient article retrieval and query handling. It integrates LangChain, OpenAI's GPT-3.5 Turbo, and FAISS for rapid and cost-effective similarity searches.

## Key Features

- **Efficient Query Handling:** Process large documents by breaking them into manageable segments and minimizing token consumption.
- **Fast Retrieval:** Utilize FAISS for similarity-based searches and accurate query responses.
- **Seamless User Interaction:** Transparent query results with links to source URLs.

## Objectives

- Build an AI-driven platform using **LangChain**, **OpenAI embeddings**, and **FAISS** for efficient information retrieval.
- Implement **Map Reduce Document Chaining** to minimize API costs while preserving data integrity.

## Technologies

- **LLMs (e.g., GPT-3.5 Turbo):** Used for NLP tasks like query handling, summarization, and generating responses.
- **Transformer Models:** Self-attention mechanism for understanding context and scalability.
- **FAISS:** For high-dimensional data similarity searches.
- **LangChain:** Manages data processing and integrates models.

## System Design

![System Architecture](https://github.com/harshcoder7/Gen-Query/blob/main/system%20design)  
_Illustration of system architecture: Document retrieval, text segmentation, embedding construction, and FAISS for query handling._

### Map-Reduce Chaining

![Map-Reduce Process](https://github.com/harshcoder7/Gen-Query/blob/main/map%20reduce)  
_Illustrates how Map-Reduce Chaining efficiently processes documents._

### Stuff Method

![Stuff Method](https://link_to_your_image.com)  
_The Stuff Method optimizes API calls by reducing token consumption._

### RAG Mechanism

![RAG](https://link_to_your_image.com)  
_Overview of the RAG system for enhancing query responses with context._

## Demo

You can explore the tool in action by following this demo:  
**[Demo Link](https://link_to_your_demo.com)**

1. **Input:** Load URLs or text files for processing.
2. **Process:** The tool fetches, segments, and generates embeddings using OpenAI models.
3. **Retrieve:** FAISS handles similarity searches and returns accurate results.

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/GenQuery.git
