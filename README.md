# Advanced Research Paper Retrieval System

## Overview
The Advanced Research Paper Retrieval System is designed to efficiently search and retrieve research papers from a database. It extracts metadata, such as titles, abstracts, DOIs, and publication dates, and enables users to query the database using natural language. This system leverages modern AI techniques to offer a robust and user-friendly experience for academic research.

## Features
- **Metadata Extraction**: Extracts key metadata from research papers using APIs.
- **Query System**: Built with Streamlit for an interactive and intuitive interface.
- **Data Retrieval**: Utilizes Hugging Face embeddings and LLaMA-3 LLM for effective querying and search.
- **Flexible Search**: Offers keyword-based and semantic search capabilities.


2. **Search for research papers**:
   - Enter relevant keywords in the search bar.
   - View the results displayed in the app, including titles, abstracts, and publication details.

## Dependencies
- `Hugging Face transformers`: For embedding models.
- `pandas`, `xmltodict`: For data processing and parsing.
- Other required Python libraries.

## Example Workflow
1. **Input**: Enter a query or keywords related to your research interest.
2. **Processing**: The system uses embeddings and the LLaMA-3 LLM to find relevant documents.
3. **Output**: View a list of papers with metadata for further exploration.

## Contributions
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch: `git checkout -b feature-name`.
3. Commit changes: `git commit -m "Add feature description"`.
4. Push changes: `git push origin feature-name`.
5. Open a pull request.
