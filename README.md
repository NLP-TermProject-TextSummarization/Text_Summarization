# Implementing Extractive and Abstractive Text Summarization to Enhance Student Comprehension

**Team Members:**  
- Shivam Jayeshkumar Mehta (sjmehta@uwm.edu)  
- Atharva Pradeep Vaishnav (vaishna2@uwm.edu)  
- Venkata Kailash Tanniru (vtanniru@uwm.edu)

**Semester:** Fall 2024  
**Instructor:** Dr. Susan Mcroy

## Summary
This project applies both extractive (TextRank) and abstractive (T5 Transformer) summarization techniques to academic texts, helping college students more easily understand complex content. Extractive summaries preserve factual accuracy, while abstractive summaries simplify language and improve readability.

## Implemented Features
- **Preprocessing:** Clean, tokenize, and vectorize academic content.
- **Extractive Summarization (TextRank):** Identify key sentences without altering their original wording.
- **Abstractive Summarization (T5):** Paraphrase and synthesize content for more coherent and accessible summaries.
- **Evaluation Metrics:**  
  - ROUGE scores for content coverage  
  - BERTScore for semantic similarity  
  - Flesch-Kincaid Grade Level for readability
- **User Feedback:** Gather qualitative ratings from students on clarity, relevance, and engagement.

## Results
- **Extractive:** High factual accuracy, but less readable.
- **Abstractive:** More engaging and easier to understand, with slight loss in precision.
- **Feedback:** Students preferred abstractive summaries for readability and comprehension.

## Project structure
- Main_data.json: this file contains the complete dataset created for this project
- test_data.json: this file contains the test dataset which is a subset of the Main_data.json to used for testing the code as the Main_data.json is too computationally expensive to run frequently and causes the output to be truncated creating problems in analysis of the results.
- Text summarization.ipynb: this file contains the code for the project
- TEXT_SUMMARIZATION.pptx: this file contains the final project presentation
- TextSummarization-Report.pdf: this file contains the final project report

## Notes
This work highlights the trade-offs between extractive and abstractive approaches. Future improvements include hybrid methods and domain-specific fine-tuning to further enhance the learning experience.
