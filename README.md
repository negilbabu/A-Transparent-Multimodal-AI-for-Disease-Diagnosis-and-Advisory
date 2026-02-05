# A-Transparent-Multimodal-AI-for-Disease-Diagnosis-and-Advisory
A Transparent Multimodal AI Chatbot for Disease Diagnosis and Advisory Using RAG and Explainable AI  (For Radiology and Dermatology)

Environment
  All experiments were conducted in Google Colab using a fixed hardware configuration (NVIDIA T4 GPU).
  The implementation is fully based on Python and widely adopted open-source libraries.

Dataset:
  The system relies on publicly available datasets:
  HAM10000 (Dermatology)
  CheXpert-Small (Radiology)

  Due to licensing and size constraints, datasets are not redistributed in this repository.

Implementation Environment:
  Python, PyTorch, Hugging Face Transformers 
  FAISS and BM25 for retrieval 
  Google Colab with NVIDIA T4 GPU 
  Gradio for interactive prototyping 
  NumPy, Pandas, Scikit-learn, Matplotlib 

Evaluation Framework 
  The system is evaluated across three dimensions: 
    Diagnostic Performance Accuracy, Precision, Recall, F1-Score, AUC-ROC 
    Explainability Quality Fidelity, consistency, and stability of explanations 
    RAG Effectiveness Recall@K, Mean Reciprocal Rank (MRR) Groundedness and hallucination analysis 
  This stratified evaluation ensures transparency and traceability of performance improvements.


Ethical and Safety Considerations: 
  The system is not a clinical diagnostic tool 
  Outputs are advisory and educational only 
  Clear disclaimers and confidence thresholds are enforced 
  Human oversight is required at all stages 
  Retrieved medical evidence is cited to support transparency
