# GeneratiGenAI-for-Customer-Support-RAG-Based-Ticket-Retrieval-Automated-Response-System
## Project Overview
This project implements a **Generative AI system for customer support** that can:
- Retrieve relevant past tickets using **RAG (Retrieval-Augmented Generation)**.
- Generate automated, helpful responses using a **language model (LLM)**.
- Simulate efficiency improvements in handling customer queries.
## Features
- **Ticket Retrieval:** Uses Sentence Transformers + FAISS to find top relevant tickets.
- **Response Generation:** Generates human-like responses to customer queries.
- **Portfolio-Ready Outputs:** Demo outputs showcase queries, retrieved tickets, and AI responses.
- **Optional Metrics Simulation:** Demonstrates potential classification accuracy and handling time reduction.

- ## Dataset
- Uses a sample customer support dataset with columns like:
  - `Ticket Description` (main text)
  - `Ticket Type` (category)
  - Other metadata: Customer Name, Product, Date, etc.
- Dataset is stored as `customer_support_tickets.csv`.
