NLP chatbot Project
---

## Overview

This project implemented an AI chatbot designed to manage calendar events, engage in small talk, and answer Q&A using natural language processing techniques. The chatbot leverages tokenisation, stemming, TF-IDF vectorisation, and logistic regression for intent matching and personalised interactions.

## Introduction

The chatbot focuses on handling calendar-related queries and general conversation. It preprocesses user inputs, classifies intents, and accesses calendar data to provide personalised and context-aware responses.

---

## Chatbot Architecture

- **Preprocessing:** Tokenisation, stemming, stop word removal, and lowercasing for uniform input processing.  
- **Intent Matching:** Uses TF-IDF vectorisation with uni- and bi-grams (top 5000 features) and cosine similarity to classify queries.  
- **Classification & Calendar Data:** Reads student calendar URLs, parses events, and classifies queries to handle calendar-specific requests.  
- **Context Tracking:** Maintains conversation context to support follow-up questions related to calendar events.  
- **Identity Management:** Stores and uses user names to personalise interactions.

---

## Conversational Design

- **Prompt Design:** Clear, empathetic prompts guide users.  
- **Discoverability:** The chatbot can provide instructions on its capabilities when asked.  
- **Error Handling:** Provides fallback responses and asks for clarifications to handle unexpected inputs gracefully.  
- **Personalisation:** Uses stored user names in responses to enhance engagement.  
- **Context Awareness:** Tracks event contexts for smooth multi-turn conversations.

---

## Evaluation

The chatbot was tested in two phases:

- **Early-stage testing:** Elicitation study using Wizard-of-Oz simulation to collect real user inputs for training and refining intent recognition.  
- **Pilot-stage testing:** Dialogue traversal testing with valid/invalid prompts to ensure smooth conversation flows and robust error handling.

---

## Discussion

- Strengths include effective intent matching, error management, and context retention.  
- Limitations relate to handling extremely vague or rare queries, suggesting the need for more advanced NLP techniques and expanded datasets.  
- The iterative development process, including user feedback, was critical in shaping the final system.


---

**Jonathan Moore**  
School of Computer Science — December 2024
