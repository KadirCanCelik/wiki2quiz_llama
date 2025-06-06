# wiki2quiz_llama
This project uses the **LLaMA 3 (8B Instruct)** language model to automatically generate multiple-choice quiz questions from **Wikipedia articles**.

## 📌 Features

- Generates **two high-quality multiple-choice questions** per topic
- Automatically pulls content from **Wikipedia** in English
- Uses a local LLaMA 3 model to generate questions from the content
- Runs fully offline, no API keys or internet access required
- This project uses the `[Meta LLaMA 3 8B Instruct (Q4_K_M)] (https://huggingface.co/bartowski/Meta-Llama-3-8B-Instruct-GGUF)` model in GGUF format.


## 📋 Sample Output

**Topic: Second World War**

**Question 1:**  
What was the primary reason for the start of World War II?  
A) The rise of fascism in Japan  
B) The invasion of Manchuria by Japan in 1931  
C) The annexation of Austria by Germany  
D) The invasion of Poland by Germany in 1939  

**Correct Answer: D) The invasion of Poland by Germany in 1939**

**Question 2:**  
Which international treaty led to the division of Poland between Germany and the Soviet Union?  
A) The Molotov–Ribbentrop Pact  
B) The Treaty of Versailles  
C) The Treaty of Berlin  
D) The Treaty of Paris  

**Correct Answer: A) The Molotov–Ribbentrop Pact**

