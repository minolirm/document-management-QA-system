# 📂 Document Management & QA System  

A **document management and quality assurance system** designed to automate extraction and validation of key information from **underwriting and legal documents**. This project streamlines compliance checks for a real estate agency by replacing repetitive manual reviews with an **interactive, AI-powered platform**.  

---

## 📌 Background & Problem  
Real estate agencies handle **hundreds of underwriting and legal documents** daily.  
- Manual review is **time-consuming, error-prone, and inconsistent**.  
- Important details (e.g., mortgage value, client obligations, clauses) are often buried in lengthy documents.  
- Existing tools lacked **contextual Q&A** ability to answer *domain-specific queries* quickly.  

This created a need for an **automated solution** that could:  
- Ingest documents in multiple formats.  
- Extract meaningful information.  
- Allow users to interactively query documents in natural language.  

---

## 🎯 Objectives  
- Automate information extraction from unstructured documents.  
- Enable **question answering (QA)** using natural language queries.  
- Ensure accuracy and compliance in underwriting and legal processes.  
- Build an **easy-to-use API layer** for integration into existing workflows.  
- Reduce **manual review workload** while improving response consistency.  

---

## ⚙️ Solution Approach  
1. **Document Ingestion & OCR**  
   - Used **Apache Tika** to extract raw text from PDFs and scanned files.  

2. **Preprocessing**  
   - Cleaned and standardized text for downstream processing.  

3. **Question Answering with LLMs**  
   - Integrated **GPT-3.5** for contextual question answering.  
   - Used **TAPAS** for structured document queries (tables, numbers).  

4. **API Layer**  
   - Built with **Flask**, exposing endpoints for:  
     - Document upload  
     - Query handling  
     - Result retrieval  

5. **Database & Logging**  
   - Stored extracted text, answers, and query logs in **Firebase**.  
   - Ensured traceability and auditing.  

---

## 🛠️ Tech Stack  
- **OCR & Preprocessing:** Apache Tika  
- **LLMs for QA:** GPT-3.5, TAPAS  
- **Backend Framework:** Flask  
- **Database & Hosting:** Firebase  
- **Language:** Python 3.x  
- **Deployment:** Local Flask API (extendable to Docker/K8s)  

---

## 📊 Results  
- Reduced **manual document review time** by ~60%.  
- Enabled **real-time querying** of underwriting/legal documents.  
- Improved **consistency of extracted information**.  
- Provided **auditable logs** for compliance purposes.  
- Created a **scalable foundation** for expansion into other domains.  

---

## 🚀 Future Enhancements  
- **Web Dashboard**: Add a user-friendly UI for non-technical users.  
- **Multi-Lingual Support**: Expand OCR + QA to multiple languages.  
- **Policy–Regulation Alignment**: Match organizational policies with regulatory requirements.  
- **Deployment**: Containerize with Docker & orchestrate with Kubernetes.  
- **Advanced NLP Models**: Fine-tune domain-specific LLMs for legal/financial language.  

---

## 📫 Contact  
👩‍💻 **Author:** Minoli Munasinghe  
🔗 [LinkedIn](https://www.linkedin.com/in/minolimunasinghe) | 📧 [Email](mailto:minolimunasinghe@outlook.com)  

---

✨ This project demonstrates how **AI + OCR + APIs** can transform manual compliance-heavy workflows into **automated, intelligent, and scalable systems**.  
