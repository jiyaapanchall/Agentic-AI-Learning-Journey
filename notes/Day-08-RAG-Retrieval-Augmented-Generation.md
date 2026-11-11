# Day 08 – RAG (Retrieval-Augmented Generation)

## 1. Introduction
RAG stands for Retrieval-Augmented Generation.

It is a technique that allows AI systems to retrieve relevant information from external sources and use it to generate answers.

## 2. Why is RAG Important?
- Helps AI work with external documents.
- Provides relevant context to an LLM.
- Makes private knowledge sources accessible to AI applications.
- Can reduce unsupported or inaccurate responses.

## 3. How RAG Works

### Document Preparation
1. Document loading.
2. Text chunking.
3. Embedding generation.
4. Storing embeddings in a vector database.

### Question Answering
1. User submits a question.
2. The question is converted into an embedding.
3. Relevant chunks are retrieved.
4. Retrieved information is passed to the LLM.
5. The LLM generates an answer.

## 4. Important Terminology
- **Chunking:** Dividing documents into smaller pieces.
- **Embedding:** Converting text into numerical representations.
- **Vector Database:** Storing and searching vector representations.
- **Retrieval:** Finding relevant information.
- **Generation:** Producing an answer using the retrieved information.
- **LLM:** Large Language Model.

## 5. RAG vs. Fine-tuning
- RAG retrieves external information when answering a question.
- Fine-tuning adapts a model through additional training.

## 6. Applications of RAG
- Document question-answering systems.
- Resume analysis.
- Educational assistants.
- Knowledge-base chatbots.
- Career guidance applications.

## 7. Application in CareerPilot AI
RAG can help CareerPilot AI retrieve information from resumes, job descriptions and career-related knowledge sources to provide relevant answers and guidance.

## 8. Key Takeaways
- RAG combines retrieval with generation.
- Documents are divided into chunks.
- Embeddings represent information numerically.
- Vector databases support semantic search.
- Retrieved context helps an LLM generate more relevant answers.
- RAG does not guarantee that every answer is correct.

## 9. My Learning Reflection
Today, I learned the basics of Retrieval-Augmented Generation, how it works, and how it can help AI applications answer questions using external documents.

**Day 08 Completed – Learning Agentic AI step by step!**
