# Project Overview

The JibChain PoC project is a specialized tool developed to automate the risk assessment of articles retrieved from external sources. This is achieved by integrating IBM Watson's Natural Language Understanding (NLU) service, which analyzes the content of these articles to determine associated risks.

## Key Features

- **Article Retrieval**: The system uses APIs to fetch articles from various sources, ensuring up-to-date and relevant content for analysis.
- **Risk Categorization**: IBM Watson's NLU is employed to categorize articles based on identified risk factors, such as financial risk, reputational risk, or regulatory risk.
- **Scalable Architecture**: The system is designed to handle large volumes of data, making it suitable for organizations that need to analyze numerous articles quickly and efficiently.

## Technical Concepts

This section provides an overview of the technical concepts and terms used throughout the project, helping to clarify their role and importance.

### Natural Language Processing (NLP)
NLP is a field of artificial intelligence that focuses on the interaction between computers and human languages. It involves understanding, interpreting, and generating human language in a way that is both meaningful and useful.

### Risk Categorization
Risk categorization involves analyzing text to identify potential risks. In this project, risks are categorized using IBM Watson's NLU, which processes the content of articles to detect indicators of various risk types.

### API Integration
APIs (Application Programming Interfaces) enable the project to interact with external services to retrieve article content and send it to IBM Watson for analysis. API integration is crucial for automating the data retrieval and processing workflow.

### Tokens
In NLP, a token is a single unit of text, such as a word or punctuation mark, that the algorithm processes individually. Tokenization is the process of breaking down text into these tokens, which are then analyzed to extract meaning and context.

### Entities
Entities are specific pieces of information, such as names of people, organizations, or locations, extracted from text. IBM Watson's NLU service identifies entities to help categorize articles based on their content.

### Sentiment Analysis
Sentiment analysis determines the emotional tone or attitude expressed in a piece of text. This analysis helps to understand whether the content is positive, negative, or neutral, which can influence the risk categorization.

### Tone Analysis
Tone analysis identifies the emotional tone of the text, such as joy, anger, fear, or sadness. Understanding the tone helps in assessing the underlying sentiment of the article, which is important for risk assessment.

This overview sets the stage for understanding how these concepts are applied throughout the project.
