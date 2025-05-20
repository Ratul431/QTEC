# QTEC
AI Chat Log Summarizer

Project Description:
AI Chat Log Summarizer is a Python-based tool that reads .txt chat logs between
a user and an AI, parses the conversation, and produces a simple summary
including message counts and frequently used keywords.
This project showcases basic NLP capabilities using Python, with an optional
TF-IDF-based keyword extraction.

What I have done:
Chat Log Parsing
   ■ Separate messages by speaker (User: and AI:).
   ■ Store messages in appropriate structures for further analysis.
Message Statistics
   ■ Count total messages.
   ■ Count messages from User vs. AI
Keyword Analysis
   ■ Extract the top 5 most frequently used words.
   ■ Exclude common stop words (e.g., "the", "is", "and").
Generate Summary
Output a clear summary that includes:
   ■ Total number of exchanges.
   ■ Nature of the conversation (based on keyword topics).
   ■ Most common keywords
Advanced Approach:
   ■ Used a simple TF-IDF approach or nltk library for better keyword extraction.
   ■ Allowes summarization of multiple chat logs from a folder.


   How to run the project:
     ■ Download the notebook and dataset to your system.
     ■ Import the notebook and dataset in Kaggle or Colab.
     ■ Start the season
     ■ Run each cell one by one or choose the run all option.
