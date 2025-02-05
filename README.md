# **Custom Query Response System**  

## **Overview**  
This project implements a **Retrieval-Augmented Generation (RAG) system** using **GPT-2**, **Hugging Face transformers**, and **FAISS** for efficient and accurate contextual question answering.  

## **Features**  
- **Text Processing**: Converts structured documents into vector embeddings using **all-MiniLM-L6-v2**.  
- **Efficient Retrieval**: Uses **FAISS** for fast and relevant query retrieval.  
- **Language Model**: Implements **GPT-2 and google/flan-t5-base** for generating coherent responses.  
- **Optimized Performance**: Achieves a **5.15% improvement in response time** compared to the baseline model.  

## **Implementation Details**  
1. **Data Processing**: Text is converted into structured documents using **LangChain**.  
2. **Vector Storage**: Uses **FAISS** for embedding storage and retrieval.  
3. **Model Setup**: GPT-2 and flan-t5-base are configured with optimized hyperparameters.  
4. **Question-Answer Pipeline**: Uses a custom prompt template and LangChain’s **RetrievalQA module**.  
5. **Performance Metrics**:  
   - **Baseline (flan-t5-base)**: 2.91 sec  
   - **Optimized (GPT-2)**: 2.76 sec (**5.15% faster**)  

## **How to Use**  
1. Clone the repository:  
   ```bash
   git clone <repo_link>
   cd <repo_name>
   ```  
2. Open the **Colab Notebook**: [Colab Link](https://colab.research.google.com/drive/1H4MOs1kHVAtVE7nIvwKZk-pH5G8vqO-I?usp=sharing)  
3. Run the notebook to process text, store embeddings, and query the system.  

## **Key Achievements**  
✅ Developed a fully functional **RAG model** for contextual queries.  
✅ **Improved response time by 5.15%** using GPT-2.  
✅ Robust performance on **large-scale unstructured text**.  

## **Future Enhancements**  
- Support for **larger datasets** and multilingual processing.  
- Fine-tuning the model for domain-specific applications.  
- Deploying as a web-based API for real-world usage.
