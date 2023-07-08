# Text Summarizer 
* An NLP-based project which summarizes a long paragraph into a few sentences while preserving the semantics and important information.
* It takes input text from the user and generates both an Extractive and Abstractive summary of it.
* Extractive summarization means identifying important sections of the text and generating them on a frequency or closeness basis, verbatim producing a subset of the sentences from the original text.
* Abstractive summarization reproduces important material in a new way after interpretation and examination of the text using advanced natural language techniques to generate a new shorter text that conveys the most critical information from the original one.
* Extractive summary is generated using cosine distance to measure the closeness between two sentences and arrange them in descending order to find the most important sentences.
* Abstractive summary is generated using BART and Pegasus pre-trained models.
