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

### **Phase 1: Foundations of Chat & Retrieval**

The journey began with establishing the core communication loop between user and machine.

- <b>The LLM Engine:</b> Initialized the project by connecting **LlamaIndex** with **Google Gemini** to build a basic interactive chatbot.

- <b>The Science of Context:</b> Moved beyond simple prompts to optimize **Chunking and Embeddings**. I experimented with how breaking text into meaningful "shards" directly impacts the AI's ability to recall facts accurately.

- <b>Benchmarking Embeddings:</b> Conducted a head-to-head comparison of open-source embedding models (like `all-MiniLM-L6-v2`) to find the perfect balance between retrieval speed and semantic accuracy.

<br>

### **Phase 2: Document Intelligence & Optimization**

Standard RAG fails on complex files. Phase 2 focused on "cleaning" the lens through which the AI sees documents.

- <b>Advanced PDF Handling:</b> Implemented Hybrid Retrieval (combining keywords and vectors) and Reranking to ensure the most relevant context always floats to the top.

- <b>Metadata Routing:</b> Developed a system to tag chunks with attributes like page_number and doc_type.

- <b>The Intelligent Librarian:</b> Built a Routing Engine that uses Gemini to classify a user's intent first (e.g., "This is a salary question"), then searches only relevant sub-indices (e.g., "Pay Stubs"), drastically reducing hallucinations.

<br>

### Phase 3: The Open-Source Pivot 🔓

To ensure data privacy and cost-efficiency, I transitioned the architecture to run entirely on local/open-source hardware.

- <b>Local GGUF Deployment:</b> Loaded Mistral 7B Instruct within Google Colab using GGUF format and CUDA acceleration, achieving high-performance inference without external API keys.

- <b>LLM Evaluation:</b> A systematic "battle royale" between Gemini, Mistral 7B, Microsoft Phi-2, and TinyLlama, evaluating them on factual accuracy and latency within a mortgage contract domain.

<br>

### Phase 4: Final Deliverable - "Deepsite Intelligence" 🏢

The culmination of the journey: a unified AI-Powered Document Automation Platform.

- <b>Multi-Stage Pipeline:</b> Integrated OCR (OpenCV), multithreaded ingestion (ThreadPoolExecutor), and semantic routing into a single workflow.

- <b>Enterprise UI:</b> Designed a custom-branded Gradio interface allowing users to upload multi-page "document blobs" and receive answers with page-level source attribution.

<br>

##

## 🛠️ Tech Stack & Skills
- <b>Orchestration:</b> LlamaIndex

- <b>Models:</b> Google Gemini, Mistral 7B (Local), Phi-2, TinyLlama

- <b>Vector DB/Indices:</b> FAISS, VectorStoreIndex

- <b>Embeddings:</b> BGE, HuggingFace Transformers

- <b>UI/UX:</b> Gradio 5.x

- <b>Processing:</b> PyMuPDF, OpenCV, Multithreading

##

## 🖥 DELIVERABLES

  - <b>[Simple Chatbot with LlamaIndex CoLab Notebook](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Task_Build_a_Simple_Chatbot_with_LlamaIndex.ipynb)</b>
    - <i>Review Demo</i>: [HERE](https://youtu.be/FFb6gzT8rfo)

  <br>
  
  - <b>[RAG Optimization: Implementing Chunking & Embeddings in LlamaIndex and Gemini](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Task_Implementing_Chunking_and_Embeddings_in_LlamaIndex_and_Gemini.ipynb)</b>

  <br>
  
  - <b>[Advanced PDF Retrieval and Optimization with LlamaIndex](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Task_Advanced_PDF_Retrieval_and_Optimization_with_LlamaIndex.ipynb)</b>
    - <i>Review Data</i>: [HERE](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/sample_contract.pdf)

  <br>
  
  - <b>[Build And Optimize A RAG Pipeline For Document Retrieval](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Task_Build_and_Optimize_a_RAG_Pipeline_for_Document_Retrieval.ipynb)</b>
    - <i>Review Data</i>: [HERE](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/LenderFeesWorksheetNew.pdf)
  
  <br>
  
  - <b>[Optimized RAG Pipeline with Interactive RAG Chatbot for Document Retrieval](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Optimized_RAG_Pipeline_with_An_Interactive_RAG_Chatbot_for_Document_Retrieval.ipynb)</b>
    - <i>Review Data</i>: [HERE](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/LenderFeesWorksheetNew.pdf)
    - <i>Review Demo</i>: [HERE](https://youtu.be/e0FKElg2wrU)
  
  <br>
  
  - <b>[Comparing Open-Source Embedding Models for RAG](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Task_Comparing_Open_Source_Embedding_Models_for_RAG.ipynb)</b>
    - <i>Review Data</i>: [HERE](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/sample_contract.pdf)
  
  <br>

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
