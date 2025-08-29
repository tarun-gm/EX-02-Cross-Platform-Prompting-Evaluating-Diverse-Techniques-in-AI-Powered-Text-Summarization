

# EX-02 – Cross-Platform Prompting: Evaluating Diverse Techniques in AI-Powered Text Summarization

## AIM

To analyze and compare the performance of different prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across multiple AI platforms (ChatGPT, Gemini, Claude, Copilot) in the task of text summarization.

### REG. NO: 212223060003

### NAME: ABINANDHAN G

---

## Scenario

As part of an educational content curation team, the task was to summarize a 500-word technical article titled *“The Basics of Blockchain Technology”*. The target audience is undergraduate students, so the summaries needed to be accurate, coherent, and simple. The experiment evaluates which **prompting technique + platform combination** gives the best results in terms of:

* Accuracy
* Coherence
* Simplicity
* Speed
* User Experience

---

## Algorithm

1. **Article Selection**
   A \~500-word article *“The Basics of Blockchain Technology”* was chosen as the test input.

2. **Prompting Strategies Defined**

   * **Zero-shot** → Direct summarization without examples.
   * **Few-shot** → Summarization with 2–3 examples provided beforehand.
   * **Chain-of-Thought** → Step-by-step reasoning before the summary.
   * **Role-based** → Acting as a specific role (e.g., professor explaining to students).

3. **Platform Selection**
   The following AI platforms were tested:

   * ChatGPT (OpenAI)
   * Gemini (Google)
   * Claude (Anthropic)
   * Copilot (Microsoft)

4. **Execution**
   Each platform was tested with all four prompting strategies using the same article.

   * Summaries were recorded.
   * Time taken was noted.
   * Outputs were analyzed for readability and relevance.

5. **Evaluation**
   Each summary was graded on **Accuracy, Coherence, Simplicity, Speed, and User Experience** (scale of 1–5).

6. **Scoring & Analysis**
   Scores were tabulated, and the highest-performing combinations were identified.

---

## Result

| Platform | Prompt Type      | Accuracy | Coherence | Simplicity | Speed | UX | Total (/25) |
| -------- | ---------------- | -------- | --------- | ---------- | ----- | -- | ----------- |
| ChatGPT  | Zero-shot        | 4        | 4         | 4          | 5     | 5  | 22          |
| ChatGPT  | Few-shot         | 5        | 5         | 5          | 4     | 5  | 24          |
| ChatGPT  | Chain-of-Thought | 5        | 5         | 4          | 3     | 5  | 22          |
| ChatGPT  | Role-based       | 5        | 5         | 5          | 4     | 5  | 24          |
| Gemini   | Zero-shot        | 3        | 3         | 3          | 5     | 4  | 18          |
| Gemini   | Few-shot         | 4        | 4         | 4          | 4     | 4  | 20          |
| Claude   | Chain-of-Thought | 5        | 5         | 5          | 4     | 4  | 23          |
| Claude   | Role-based       | 5        | 5         | 5          | 4     | 5  | 24          |
| Copilot  | Zero-shot        | 3        | 3         | 3          | 5     | 4  | 18          |
| Copilot  | Few-shot         | 4        | 4         | 4          | 4     | 4  | 20          |

---

### Graphical Representation

<img width="2400" height="1600" alt="image" src="https://github.com/user-attachments/assets/223662a6-cf71-409a-b2c1-8e723b13dfde" />  

---

## Conclusion

From the evaluation, the **best-performing combinations** were:

* **Claude + Role-based Prompting**
* **ChatGPT + Few-shot Prompting**

Both scored **24/25**, showing strong accuracy, coherence, and simplicity, making them highly effective for summarizing technical content in an undergraduate-friendly manner.

---


