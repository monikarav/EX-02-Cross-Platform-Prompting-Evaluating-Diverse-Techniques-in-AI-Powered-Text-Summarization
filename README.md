# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## SCENARIO
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

## ALGORITHM
### 1. Article Selection: 
Use a 500-word article explaining blockchain basics in a technical tone.

### 2. Prompt Design:

* Zero-shot: A direct instruction like “Summarize the following text in simple terms for undergraduate students.”

* Few-shot: Provide two or three example summaries of similar articles before asking the model to generate a new one.

* Chain-of-thought: Instruct the AI to reason through key ideas step-by-step before composing a summary.

* Role-based: Ask the AI to take on a persona (e.g., a professor) and explain the article to beginners.

### 3. Execution:
Input each prompt variant into ChatGPT, Gemini, Claude, and Copilot. Measure:

* Accuracy of content

* Coherence and flow

* Simplicity of language

* Speed of response

* User experience with the interface

### 4. Evaluation: 
Manually assess each output using a 1–5 scale for each of the five criteria. Averages help identify the best-performing combinations.

### 5. Comparison and Ranking:
Review overall performance across all combinations to determine the most effective platform + prompt strategy.

## RESULT
* The results showed that Claude combined with Chain-of-Thought prompting delivered the most effective summaries. This combination excelled in accuracy, logical flow, and maintaining clarity, especially when simplifying technical terms. While slightly slower than zero-shot methods, the quality trade-off was worth it.

* ChatGPT with zero-shot prompting was the fastest, producing quick summaries that were generally accurate and simple, though sometimes lacked depth.

* Gemini with few-shot prompting provided solid results, especially when the examples were well-chosen. However, performance depended heavily on the quality and relevance of the examples provided.

* Copilot using role-based prompting was easy to work with and produced relatable summaries, but occasionally lost technical accuracy due to over-simplification.
