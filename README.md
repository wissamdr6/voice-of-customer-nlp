# Voice-of-Customer NLP Intelligence

An end-to-end NLP system that analyzes user feedback to extract sentiment, detect negative aspects, and identify recurring issues in order to drive product improvement.  
Built with transformer models, aspect-based sentiment analysis, topic modeling and production-grade inference services.

---

## 🚀 Key Features
- Sentiment classification (positive / neutral / negative)
- Aspect extraction (ABSA)
- Per-aspect polarity detection
- Topic modeling on negative feedback (BERTopic)
- Scalable API inference (FastAPI + Docker)
- Model versioning, CI/CD and monitoring
- Ready for production deployment

---

## 🧠 High-Level Architecture
```mermaid
flowchart LR
A[Raw Feedback] --> B[Preprocessing]
B --> C[Aspect Extraction (NER)]
C --> D[Sentiment Classifier]
D --> E[Aspect-level Polarity]
E --> F[Topic Modeling (BERTopic)]
F --> G[Insights Dashboard]
