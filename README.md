# AI-Powered Document Automation Platform: A RAG Journey 🚀
This repository documents my technical evolution from writing basic LLM prompts to engineering a production-ready **Retrieval-Augmented Generation (RAG)** Proof of Concept (PoC). Each folder and notebook represents a critical milestone in mastering LlamaIndex, open-source model deployment, and intelligent document orchestration.

##

## 🎯 Foundational Concepts

The foundational concepts to building a fully functional RAG application:

  - <b>RAG Fundamentals:</b> Gain a deep understanding of how RAG pipelines work and the core concepts of information retrieval and processing in the context of LLMs.

  - <b>LlamaIndex Mastery:</b> Learn to effectively use LlamaIndex for organizing, indexing, and efficiently searching through large, unstructured document sets.

  - <b>Model Integration:</b> Practice integrating open-source Large Language Models (LLMs) into the RAG workflow.

  - <b>Practical Application:</b> Build a functional, simple chatbot that uses the RAG pipeline to retrieve and synthesize relevant data for accurate, context-aware responses.

##

## 🗺️ The Development Roadmap

### **Phase 1: Foundations of LLM & RAG 🏗️**
<i>Focus: Establishing basic interaction, initial RAG logic, and environment setup.</i>

- <b>[Simple Chatbot with LlamaIndex CoLab Notebook](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Task_Build_a_Simple_Chatbot_with_LlamaIndex.ipynb)</b>
  
  - <i>Core Logic:</i> Configuring the LLM engine (LlamaIndex + Gemini) for basic chat loops.
  
  - <i>Review Demo:</i> [WATCH HERE](https://youtu.be/FFb6gzT8rfo)

- <b>[Build And Optimize A RAG Pipeline For Document Retrieval](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Task_Build_and_Optimize_a_RAG_Pipeline_for_Document_Retrieval.ipynb)</b>

  - <i>Core Logic:</i> Moving from simple chat to basic document-grounded answers using local data.

  - <i>Review Data</i>: [HERE](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/LenderFeesWorksheetNew.pdf)

<br>

### **Phase 2: Retrieval Science & Benchmarking 🧪**
<i>Focus: Optimizing how data is processed, stored, and retrieved.</i>

- <b>[RAG Optimization: Implementing Chunking & Embeddings in LlamaIndex and Gemini](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Task_Implementing_Chunking_and_Embeddings_in_LlamaIndex_and_Gemini.ipynb)</b>

  - <i>Core Logic:</i> Evaluating how various chunk sizes and embedding strategies impact accuracy.

- <b>[Comparing Open-Source Embedding Models for RAG](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Task_Comparing_Open_Source_Embedding_Models_for_RAG.ipynb)</b>

  - <i>Core Logic:</i> Systematic comparison of open-source vs. proprietary embeddings for domain-specific tasks.

  - <i>Review Data:</i> [HERE](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/sample_contract.pdf)

- <b>[Advanced PDF Retrieval and Optimization with LlamaIndex](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Task_Advanced_PDF_Retrieval_and_Optimization_with_LlamaIndex.ipynb)</b>

  - <i>Core Logic:</i> Implementing query expansion and hybrid search for complex PDF layouts.

  - <i>Review Data</i>: [HERE](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/sample_contract.pdf)

- <b>[Optimized RAG Pipeline with Interactive RAG Chatbot for Document Retrieval](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Optimized_RAG_Pipeline_with_An_Interactive_RAG_Chatbot_for_Document_Retrieval.ipynb)</b>

  - <i>Core Logic:</i> Integrating PyMuPDF and HuggingFace embeddings for high-speed retrieval.

  - <i>Review Data:</i> [HERE](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/LenderFeesWorksheetNew.pdf)

  - <i>Review Demo:</i> [WATCH HERE](https://youtu.be/e0FKElg2wrU)

<br>

### **Phase 3: Intelligent Routing & Privacy 🔓**
<i>Focus: Managing multi-document "blobs," metadata, and local open-source deployment.</i>

- <b>[RAG with Open-Source Model: Mistral 7B](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Task_RAG_with_Open_Source_Model_Mistral_7B.ipynb)</b>

  - <i>Core Logic: Transitioning to self-contained, local GGUF models on GPU to ensure data privacy.

  - <i>Review Data:</i> [HERE](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/sample_contract.pdf)

- <b>[LLM Evaluation for RAG](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Task_LLM_Evaluation_for_RAG.ipynb)</b>

  - <i>Core Logic:</i> Comparative accuracy testing across Gemini, Mistral, Phi-2, and TinyLlama.

  - <i>Review Data:</i> [HERE](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/sample_contract.pdf)

- <b>[Designing A Page-Level Detection Strategy Using RAG](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Task_Designing_a_Page_Level_Detection_Strategy_Using_RAG.ipynb)</b>

  - <i>Core Logic:</i> Developing the logic to separate and classify different documents inside a single PDF.

  - <i>Review Data:</i> [HERE](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/Blob%20File%20Sample.pdf)

- <b>[Tagging Chunks with Metadata in LlamaIndex](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Task_Tagging_Chunks_with_Metadata_in_LlamaIndex.ipynb)</b>

  - <i>Core Logic:</i> Enhancing retrieval precision through document attributes (page number, doc type).

  - <i>Review Data</i>: [HERE](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/Blob%20File%20Sample.pdf)

- Task: Routing Queries

  - <i>Core Logic:</i> Building a "Router" to automatically direct questions to specific document types.

- Task: End-to-End RAG Pipeline with Page-Level Detection

  - <i>Core Logic:</i> Finalizing the back-end architecture for multi-document stream processing.

<br>

### **Phase 4: UI Development & Lite Implementation 🎨**
<i>Focus: Creating user-friendly interfaces for research and deployment.</i>

- Task: Intro To Gradio

  - Core Logic: Learning to map Python functions to web-based UI components.

- Task: Gradio Chatbot with Lite RAG Implementation

  - Core Logic: Creating a minimalist workspace for high-speed indexing and keyword-based retrieval.

<br>

### **Phase 5: Production PoC Deliverable 🏆**
<i>Focus: Integrating all modules into a unified, enterprise-grade platform.</i>

- Task: Full RAG Pipeline with Interactive Gradio Chatbot

  - Core Logic: Merging the high-performance retrieval back-end with the interactive Gradio front-end.

- POC: AI-Powered Document Automation Platform

  - The Final Deliverable: A complete system featuring parallel ingestion, computer vision preprocessing, and semantic routing for complex document portfolios.

<br>

##

## 🛠️ Tech Stack & Skills
- <b>Orchestration:</b> LlamaIndex

- <b>Models:</b> Google Gemini, Mistral 7B (Local), Phi-2, TinyLlama

- <b>Vector DB/Indices:</b> FAISS, VectorStoreIndex

- <b>Embeddings:</b> BGE, HuggingFace Transformers

- <b>UI/UX:</b> Gradio 5.x

- <b>Processing:</b> PyMuPDF, OpenCV, Multithreading

<br>

##

## 🎯 Final POC Feature Highlights
|Feature | Technical Solution | Benefit |
| ---| ---| ---| 
| Context Isolation | Semantic Routing via Gemini | Prevents "Context Contamination" from irrelevant docs. |
| High-Speed Ingestion | Parallel ThreadPool Processing | 5x faster parsing of 100+ page documents. |
| Source Trust | Metadata Tagging & Citations | Real-time source badges for every AI response. |
| Open-Source Ready | GGUF & LlamaCPP Integration | Zero-cost, private deployment options. |

<br>

##



## 🖥 DELIVERABLES


  - <b>[RAG with Open-Source Model: Mistral 7B](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Task_RAG_with_Open_Source_Model_Mistral_7B.ipynb)</b>
    - <i>Review Data</i>: [HERE](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/sample_contract.pdf)
  <br><br>

  - <b>[LLM Evaluation for RAG](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Task_LLM_Evaluation_for_RAG.ipynb)</b>
    - <i>Review Data</i>: [HERE](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/sample_contract.pdf)
  
  <br>

  - <b>[Designing A Page-Level Detection Strategy Using RAG](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Task_Designing_a_Page_Level_Detection_Strategy_Using_RAG.ipynb)</b>
    - <i>Review Data</i>: [HERE](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/Blob%20File%20Sample.pdf)
  
  <br>

  - <b>[Tagging Chunks with Metadata in LlamaIndex](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Task_Tagging_Chunks_with_Metadata_in_LlamaIndex.ipynb)</b>
    - <i>Review Data</i>: [HERE](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/Blob%20File%20Sample.pdf)
  
  <br>

  - <b>[Routing Queries](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Task_Route_Queries.ipynb)</b>
    - <i>Review Data</i>:
      -  [Pay Statement](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/PayStatement-Nov_1__2024.pdf)
      -  [COE Sample](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/COE-Sample.pdf)
      -  [Lender Fees Worksheet](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/LenderFeesWorksheetNew.pdf)
      -  [Sample Contract](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/SampleContract-Shuttle.pdf)
      -  [Functional Sample](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/functionalsample.pdf)
      -  [Pay Slip 1752803610](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/payslip-1752803610.pdf)
      -  [PaySlip 1752804713](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/payslip-1752804713.pdf)
      -  [Sample Contract](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/sample_contract.pdf)
  
  <br>

  - <b>[End-to-End RAG Pipeline with Page-Level ](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Task_End_to_End_RAG_Pipeline_with_Page_Level.ipynb)</b>
    - <i>Review Data</i>: [HERE](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/Blob%20File%20Sample.pdf)
  
  <br>

##

## Gradio (Interactive Chatbot)
   - <b>[Intro To Gradio ](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/Gradio/Task_Intro_to_Gradio.ipynb)</b>

<br>

  - <b>[Gradio Chatbot with Lite RAG Implementation ](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/Gradio/Task_Gradio_Chatbot_with_Lite_RAG_Implementation.ipynb)</b>

<br>

##

## RAG & Gradio (Interactive Chatbot)

   - <b>[Full RAG Pipeline with Interactive Gradio Chatbot](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/Gradio/Task_Full_RAG_Pipeline_with_Interactive_Gradio_Chatbot.ipynb)</b>

<br>

  - <b>[POC - AI-Powered Document Automation Platform](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/POC/Task_Enhanced_Document_Q%26A_System_with_Intelligent_RAG_Pipeline.ipynb)</b>

<br>
