# response-hallucination
Compared factual responses from ChatGPT and Claude across topics to detect hallucinations. Evaluated accuracy, consistency, and frequency of fabricated or misleading information.

#  Response Hallucination Detection (ChatGPT vs Claude)

This project investigates how often and in what ways ChatGPT and Claude generate hallucinated or fabricated responses across factual domains like science, history, and pop culture.

##  Project Overview

- **Objective**: Compare factual consistency and hallucination frequency between ChatGPT and Claude.
- **Method**: Created identical prompt sets, evaluated both model responses manually, and tagged them for hallucinations or misleading claims.
- **Focus Areas**: Science facts, historical accuracy, pop culture details.
- **Tools Used**: Manual annotation, Notion for tracking, GitHub for publishing results.

##  Key Findings

- ChatGPT showed slightly fewer hallucinations in scientific and historical prompts.
- Claude was more conversational but sometimes inferred or fabricated pop culture trivia.
- Detailed observations and test results are available in the `/results` folder.

##  Project Structure
```project-03-response-hallucination/
├── prompts/
│   ├── history_prompts.txt
│   ├── science_prompts.txt
│   └── popculture_prompts.txt
├── responses/
│   ├── chatgpt_responses.json
│   └── claude_responses.json
├── analysis/
│   └── hallucination_report.md
├── README.md
```
##  Next Steps

- Extend the test set to medical and legal queries.
- Automate response evaluation with QA benchmarks.
- Collaborate on hallucination mitigation strategies.

##  Methodology

```text
• Selected 10 fact-based prompts across:
   - History
   - Science
   - Pop Culture

• Both ChatGPT and Claude received identical prompts.

• Responses were manually compared based on:
   - Factual accuracy
   - Specificity of information
   - Confidence/tone of answer

• Each answer was reviewed for:
   - Hallucinations (fabricated or incorrect facts)
   - Clarity and completeness
   - Citation or lack thereof
```

## 🔮 Future Scope

```text
• Automate hallucination detection using NLP techniques.
• Expand dataset to 100+ prompts across diverse domains.
• Introduce quantitative metrics like BLEU, ROUGE for deeper evaluation.
• Test with multilingual prompts to assess non-English hallucination patterns.
• Evaluate newer models like GPT-4.5, Claude 3 Opus, Gemini, etc.
```
