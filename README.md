# Smart Study Generator Agent
#IBMPROJECT
### AI-Powered Personalized Learning Assistant Using IBM Granite

## Overview
The Smart Study Generator Agent is an Agentic AI-powered web application that transforms study materials into personalized, exam-ready resources. It helps students learn efficiently through AI-generated summaries, flashcards, quizzes, and adaptive study plans.

## Key Features
- Upload and analyze study materials, PDFs, and textbook images.
- Generate concise summaries, flashcards, and practice quizzes.
- Create concept maps and simplify complex topics.
- Generate personalized study timetables.
- Identify important topics from past examination papers.
- Track quiz scores, learning progress, and weak areas.
- Provide adaptive study recommendations.

## Technologies Used
- IBM Langflow / watsonx Orchestrate – Agent workflow orchestration.
- IBM Granite Models – Summarization, reasoning, and study material generation.
- IBM watsonx.ai – Model inference and AI capabilities.
- RAG – Context-aware answers from study materials.
- FAISS / Chroma – Vector storage and semantic retrieval.
- Python and Streamlit – Backend and web interface.

## Installation

```bash
git clone https://github.com/YOUR-USERNAME/smart-study-generator.git
cd smart-study-generator
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
streamlit run app.py
```

Configure the required IBM API credentials before running the application.

## Workflow
1. Upload study materials.
2. Extract and retrieve relevant information using RAG.
3. Generate summaries, quizzes, and flashcards using IBM Granite.
4. Create personalized study plans.
5. Track progress and recommend topics for revision.

## Expected Outcome
An intelligent study companion that simplifies learning, improves revision, and supports personalized exam preparation.

Learn Smarter, Prepare Better!
