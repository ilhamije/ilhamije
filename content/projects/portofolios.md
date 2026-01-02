---
title: "Portofolios"
date: 2026-01-02T22:44:13+07:00
draft: true
---

### [RAG Chatbot - Topic : LAW](lawrag.ilhamije.id "Open Live Project")

This project develops an **Indonesian legal RAG chatbot** that reads legal PDFs, retrieves relevant **pasal and ayat** from a vector database, and explains them **accurately in Indonesian** while preserving their original legal meaning. By using metadata-aware retrieval and structured synthesis, the system maintains  **context and inter-article relationships** , avoids hallucination, and produces clear, normatively correct legal explanations based strictly on the original statutory text.

Stacks : **Python + OpenAI (GPT-4o, text-embedding-3-large) + LangChain + ChromaDB + PDFPlumber + Gradio**

### [Receipt Scanner](receiptscan.ilhamije.id "Try this app")

This project is a **receipt-scanner MVP for expense tracking** that lets users scan receipts, extract key data, and monitor spending. Users can scan without signing in (data is temporary and wiped on app close), and if they later sign in with Google, the scanned receipts are permanently saved to their account. The system prioritizes fast input, clear data ownership, and a simple architecture that can be shipped within one week, including a landing page and market-fit validation.

Stack : ***FastAPI, React + Vite (PWA), PostgreSQL, OpenAI API (for text extraction, parsing, etc****)**, Docker, Google OAuth, Nginx.**
