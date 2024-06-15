# augmented-llm-coder
A low-complexity LLM augmenting approach geared towards making a better Java coding assistant  
 
Provided are the jupyter notebooks used for the research as well as the CodeNet Project benchmarking problem descriptions, (Java200.csv) and the labelled results for code acceptance and completeness (Result_report.csv).
 
## HOW TO
To run the RAG framework, clone the repository and go through the Loading.ipnyb file to create the embeddings vectorstore. You will need Ollama with the desired model downloaded as well as the Langchain libraries installed. 
Once the Chroma vectorestore is created on your local, you can run any of the QA notebooks to invoke the models' responses to the Java problems.
