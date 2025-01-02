# FinGraph: Knowledge Graph-RAG Chatbot for Financial FAQs

FinGraph is an innovative Knowledge Graph-RAG (Retrieval-Augmented Generation) chatbot designed to address complex financial FAQs. By integrating knowledge graphs with RAG technology, FinGraph delivers precise, up-to-date answers to financial queries.

## Key Features

- Integration of knowledge graphs with RAG technology
- Latest news extraction and graph storage using Neo4j
- Vector databases for efficient similarity searches
- Powered by OpenAI's LLMs (GPT 3.5)
- Conversational interface for natural financial query interactions

## System Architecture

FinGraph leverages a hybrid approach combining:

- Knowledge Graph: Structured representation of financial entities and relationships
- Vector Database: Efficient similarity search for relevant information
- Large Language Model: OpenAI's GPT 3.5 for natural language understanding and generation

## Performance

FinGraph demonstrates superior performance compared to traditional RAG systems:

- Improved comprehensiveness and diversity with a 70-80% win rate
- Enhanced faithfulness in responses

## Applications

- Financial institutions
- Investors
- Market analysts
- Economic researchers

## Implementation Details

- Graph Database: Neo4j
- Vector Store: Chroma
- Embedding Model: BERT-base (768-dimensional vectors)
- Language Model: OpenAI's GPT 3.5
- Indexing: HNSW for optimized retrieval

## Dataset

- 500 financial news URLs spanning business and technology domains
- 1000+ entity nodes with 5000+ relationship edges in the knowledge graph
- 100 curated financial queries for testing

## Evaluation

Evaluation metrics include:

- Mean Average Precision (MAP)
- Precision/Recall@10
- Response quality assessed through human evaluation

## Future Work

- Expanding the knowledge graph with more diverse financial data sources
- Implementing advanced role-based access control (RBAC) for enhanced security
- Incorporating encryption and audit trails for data integrity and confidentiality

## Ethical Considerations

The project addresses privacy protection and aims to mitigate risks of biased outcomes in financial information retrieval and generation.

For detailed implementation and results, please refer to the full project documentation.
