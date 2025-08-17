# 📂 Document Management & Question Answering (QA) System  

An **AI-powered document management and question answering system** that automates information extraction from **underwriting and legal documents**.  
This platform allows users to upload documents and interactively **ask questions in natural language**, replacing repetitive manual reviews with an **intelligent API-based solution**.  

---

## 📌 Background & Problem  
Real estate agencies process **large volumes of underwriting and legal documents** every day.  
- Manual review is **slow, error-prone, and inconsistent**.  
- Key details (e.g., tenant name, lease duration, mortgage value, client obligations) are buried in lengthy text.  
- Traditional tools lacked the ability to provide **direct, contextual answers** to user queries.  

This created a need for an **automated Question Answering (QA) solution** that could:  
- Extract and structure information from unstructured documents.  
- Allow interactive Q&A over contracts and reports.  
- Reduce manual workload while improving compliance reliability.  

---

## 🎯 Objectives  
- Enable **document-level Q&A** using natural language queries.  
- Automate information extraction from PDFs, excel sheets, and scanned contracts.  
- Provide a **Flask-based API** for seamless system integration.  
- Store results securely for traceability and compliance.  
- Reduce reliance on manual document review.  

---

## ⚙️ Solution Approach  
1. **Document Ingestion & OCR**  
   - Used **Apache Tika** to extract raw text from PDFs and scanned documents. 

2. **Preprocessing**  
   - Standardized and cleaned extracted text for downstream NLP tasks.  

3. **Question Answering with LLMs**  
   - Integrated **GPT-3.5** for contextual understanding and answers.  
   - Used **TAPAS** for table-based Q&A (structured data queries).  

4. **Interactive API Layer**  
   - Built with **Flask**, supporting endpoints for:  
     - Document upload  
     - Q&A queries  
     - Structured JSON responses  

5. **Database & Logging**  
   - Implemented **Firebase** to store documents, answers, and logs.  
   - Enabled audit trails for compliance checks.  

---

## 🛠️ Tech Stack  
- **OCR:** Apache Tika  
- **LLMs for Q&A:** GPT-3.5, TAPAS  
- **Backend:** Flask  
- **Database & Hosting:** Firebase  
- **Language:** Python 3.x  
- **Deployment:** Local Flask API (extendable to Docker)  

---

## 📊 Results  
- Cut **manual review time** by ~60%.  
- Allowed **real-time question answering** over lengthy contracts.  
- Improved **accuracy and consistency** in extracting critical details.  
- Provided **auditable, query-based logs** for compliance assurance.  

---

## 🚀 Future Enhancements  
- **Web Dashboard** for non-technical users.  
- **Multi-Lingual OCR & Q&A** for international documents.  
- **Policy–Regulation Alignment** for compliance verification.  
- **Deployment via Docker/Kubernetes** for scalability.  
- **Fine-tuned Legal/Financial LLMs** for domain-specific language.  

---

✨ This project shows how **OCR + LLM-based Question Answering** can transform manual document review into an **automated, intelligent, and scalable workflow**.  
