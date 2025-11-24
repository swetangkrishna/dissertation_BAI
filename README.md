# Development and Comparative Evaluation of a Fine-Tuned Multimodal LLM Against a Base Model and ChatGPT-4

This repository contains the dissertation **“Development and Comparative Evaluation of a Fine-Tuned Multimodal LLM Against Base Model and ChatGPT-4”** by Swetang Krishna (School of Engineering, 2025).

The work explores how educational chatbots can support personalized, context-aware learning, with a focus on probability and statistics. It develops and evaluates a **fine-tuned multimodal Large Language Model (LLM)** for context-based question answering and compares it against:

- a **base question-answering model**, and  
- **ChatGPT-4** as a strong external benchmark.  [oai_citation:0‡main.pdf](file-service://file_00000000e75071f4809b57c2f71dbe79)  

The system combines:

- **Retrieval-Augmented Generation (RAG)** using a custom full-text search pipeline (Whoosh) for document indexing and context retrieval.  
- A **fine-tuned LLM** trained on a curated probability and statistics QA dataset.  
- A **Django-based web interface** that acts as an educational agent/tutor, with user management and chat history storage in a database.  
- Evaluation of the base, fine-tuned, and GPT-4 models on accuracy, descriptiveness, and educational usefulness of responses.

Overall, the dissertation shows that **specialized fine-tuning + RAG** can yield a smaller, more efficient model that performs competitively on domain-specific educational QA tasks, while being more computationally and financially accessible than very large proprietary models.

---

## Full Dissertation (PDF)

You can read the full dissertation here:

- 📄 **[main.pdf](./main.pdf)**

Or view it inline (if your browser/GitHub viewer supports embedded PDFs):

<object data="./main.pdf" type="application/pdf" width="100%" height="800px">
  <p>
    Your browser does not support viewing PDFs inline.
    You can <a href="./main.pdf">download the PDF here</a>.
  </p>
</object>
