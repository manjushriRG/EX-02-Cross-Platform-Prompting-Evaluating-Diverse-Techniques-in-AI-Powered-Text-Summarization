# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## Algorithm

The following algorithm was designed to conduct the evaluation in a systematic way:

1. **Platform Identification**: Select multiple AI platforms widely used for text summarization (ChatGPT, Gemini, Claude, Copilot).
2. **Prompt Selection**: Define and prepare four prompting techniques (Zero-shot, Few-shot, Chain-of-thought, Role-based).
3. **Input Dataset**: Use a 500-word article on *“The Basics of Blockchain Technology”* as the test text.
4. **Prompt Execution**: Apply each prompting technique across all platforms to generate summaries.
5. **Output Collection**: Record generated summaries while noting speed and ease of use.
6. **Evaluation Criteria**: Rate outputs on Accuracy, Coherence, Simplicity, Speed, and User Experience (scale 1–5).
7. **Comparison**: Tabulate results and analyze which combinations perform best.
8. **Conclusion**: Highlight strengths and weaknesses of each platform + prompting pair.


## Detailed Explanation of Prompting Techniques

Prompting techniques are at the heart of effective AI use. Each method interacts differently with a platform’s internal architecture and training.

* **Zero-shot prompting**: This method assumes the AI can handle the task directly without prior guidance. It is useful for quick results but may lack depth.
* **Few-shot prompting**: By giving small examples, this technique improves model performance by showing the expected style and level of detail.
* **Chain-of-thought prompting**: Encourages the model to reason step by step before summarizing. This enhances logical flow but can increase response time.
* **Role-based prompting**: The AI is assigned a persona (e.g., teacher, researcher, or student) to tailor the output tone and complexity.
  


## Table 1 – Prompting Techniques and Example Prompts**

| **Prompting Technique** | **Description & Example**                                                                                                   |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| **Zero-shot**           | Task is given without examples. <br> *Example*: “Summarize the following article in 150 words for undergraduates.”          |
| **Few-shot**            | A few sample summaries are given first. <br> *Example*: “Here are 2 summaries: \[A], \[B]. Now summarize this article.”     |
| **Chain-of-thought**    | Model reasons step-by-step. <br> *Example*: “Identify key points → explain briefly → produce a summary.”                    |
| **Role-based**          | Assign a role or persona. <br> *Example*: “You are a professor explaining blockchain to beginners. Summarize in 150 words.” |

---

## Evaluation Criteria

The generated summaries were tested on **five evaluation dimensions

1. **Accuracy** → How correctly the summary covered blockchain basics.
2. **Coherence** → Logical flow and readability.
3. **Simplicity** → Ease of understanding for undergraduates.
4. **Speed** → Time taken by the platform to return the result.
5. **User Experience (UX)** → Presentation, formatting, and readability.

<img width="470" height="717" alt="image" src="https://github.com/user-attachments/assets/c9ec82ba-2402-4264-b827-2cc908c129f3" />



## Table 2 – Comparative Evaluation of Platforms & Prompting Styles

| **Platform** | **Prompt Style** | **Accuracy (5)** | **Coherence (5)** | **Simplicity (5)** | **Speed (5)** | **UX (5)** | **Total (25)** |
| ------------ | ---------------- | ---------------- | ----------------- | ------------------ | ------------- | ---------- | -------------- |
| **ChatGPT**  | Zero-shot        | 4                | 4                 | 4                  | 5             | 4          | **21**         |
| **ChatGPT**  | Few-shot         | 5                | 5                 | 4                  | 4             | 5          | **23**         |
| **Gemini**   | Role-based       | 4                | 4                 | 5                  | 4             | 5          | **22**         |
| **Claude**   | Chain-of-thought | 5                | 5                 | 4                  | 3             | 4          | **21**         |
| **Copilot**  | Zero-shot        | 3                | 3                 | 3                  | 5             | 3          | **17**         |


## Discussion

From the tabulated results, several insights emerge:

* **ChatGPT Few-shot** achieved the best overall performance (23/25), showing that structured examples help the model produce accurate and well-flowing summaries.
* **Gemini Role-based** scored highest in simplicity (5/5), producing student-friendly explanations, which is critical for undergraduates.
* **Claude Chain-of-thought** excelled in accuracy and coherence but had slightly slower responses.
* **Copilot Zero-shot** struggled with depth and clarity, even though its response time was fast.

These results indicate that **the choice of prompting technique matters as much as the platform itself**. While ChatGPT performs best overall, Gemini may be better for beginner audiences, and Claude works well when depth is required.

## Result

ChatGPT with **few-shot prompting** gave the most accurate and coherent summaries, while Gemini with **role-based prompting** provided the simplest and most student-friendly outputs.



