---
license: apache-2.0
---
**requirement**
minimal hardware: RTX3060 12GB vram / 64GB ram / 1TB SSD
software: 
1. n8n on node.js
2. docker for supabase
3. ollama with local LLM (or LLM api keys)
4. ngrok for line webhook (or certified https server)
5. Faster-Whisper-XXL
6. line bussiness and development account

**installation**
The n8n workflow file is available upon request
The workflow snapshot:
![image](https://github.com/user-attachments/assets/c57ee1ac-edd1-4253-9f75-d77198eac64a)

**Zebrafisher is linebot of LLM-based Lab assistant**
Zebrafisher can be either locally installed or linked to cloud LLM+VectorDB
The n8n workflow is available upon request.
For more details, please read the abstract below.

**Zebrafisher: the LLM-Based Lab Assistant Agent for Zebrafish Research** 
Bo-Kai Liao
Department of Aquaculture, National Taiwan Ocean University, Keelung, Taiwan
Email: liaobk@email.ntou.edu.tw

In Taiwan, zebrafish laboratories commonly use LINE as their primary platform for group communication. A well-designed LINE bot assistant can significantly enhance laboratory operations. Here, we introduce Zebrafisher, an open-source, locally deployable lab assistant agent powered by large language models (LLMs). Zebrafisher is built on the n8n workflow automation platform and integrates multimodal LLMs, databases, and tools into a LINE bot. The agent can be fully installed on local systems with high privacy, also providing flexibility to choose LLMs based on available GPU resources or to connect with paid APIs for advanced LLM capabilities. Zebrafisher offers the following key features:  
1. General Inquiry and Conversation: Supports natural language interactions with translation between Chinese and English.
2. Retrieval-Augmented Generation (RAG): Indexes lab-specific experimental protocols and zebrafish-related data into a vector database, enabling precise document-based question answering.
3. Wikipedia Integration: Queries Wikipedia for questions beyond the scope of the indexed database.
4. Mathematical Computation: Connects to a calculator for tasks such as determining reagent quantities, e.g., "How much yeast powder is required to culture 12 liters of ciliates if 5 liters require 2.5 g?"
5. Text Summarization: Records LINE group discussions and generates summaries for easy review.
6. PubMed Abstract Parsing: Extracts and summarizes research abstracts from PubMed links in Chinese.
7. Image Recognition: Processes uploaded images to recognize content or extract English text for note-taking purposes.

Zebrafisher streamlines group and individual communications in zebrafish labs by assisting with protocol retrieval, research summaries, FAQs, and more. It reduces onboarding barriers for new members by facilitating quick access to essential knowledge and resources. With its versatile capabilities, Zebrafisher serves as a powerful tool for enhancing efficiency and productivity in zebrafish research laboratories.  

**Lab Webpage: [http://lbk.tw/](http://lbk.tw/)**




