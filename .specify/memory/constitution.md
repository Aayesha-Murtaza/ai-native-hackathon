# Project Constitution

## Project Scope
This constitution applies to:
- All textbook content
- All AI-generated text
- All RAG chatbot responses
- All documentation in this repository

---

## Core Principles
1. Accuracy through source-grounded content
2. Clarity for undergraduate computer science learners
3. Reproducibility of knowledge and system behavior
4. No hallucination in AI responses

---

## Writing Standards
- Reading level: undergraduate (clear, precise, structured)
- No vague language ("some", "many", "etc.")
- Every technical term must be defined before use
- Step-by-step explanations required for concepts

---

## Technical Standards
- RAG responses must use retrieved context only
- No external knowledge outside indexed content
- Chunk size: 400–600 tokens
- Overlap: 10–15%

---

## Source & Content Rules
- All instructional content must be internally consistent
- No fabricated examples or tools
- No marketing language

---

## AI Behavior Constraints
- AI must refuse to answer if no relevant context is retrieved
- AI must cite chunk IDs internally (for debugging)

---

## Tooling Constraints
- Backend: FastAPI
- Vector store: Qdrant
- Docs: Docusaurus

---

## Success Criteria
- Queries return only source-backed answers
- No hallucinations in chatbot output
- All modules follow same instructional standard
