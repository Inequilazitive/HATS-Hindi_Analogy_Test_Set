# HATS
GitHub repository for the paper HATS: Hindi Analogy Test Set for Evaluating Reasoning in Large Language Models, presented at the Analogy Angle II Workshop (ACL 2025).

## Dataset Access

The HATS dataset is available as a pip package. You can install it using:

```bash
pip install hats-analogy-dataset
```

For more information, visit: https://pypi.org/project/hats-analogy-dataset/1.0.0/

## Prompts

All task-specific prompts are organized in the `prompts` folder, categorized by their linguistic settings as defined in the paper:

- **Hindi-Only (Hi+Hi)**: Both system and user prompts are in Hindi.  
- **English-Only (En+En)**: Both system and user prompts are in English.  
- **Mixed Setting (En+Hi)**: The system prompt is in English, while the user prompt is in Hindi.  

### Notes:

1. As mentioned in the paper, the **0-shot approach in Task B** was not evaluated separately for the Mixed Setting (En+Hi), since this setup is functionally equivalent to the English-Only (En+En) configuration.

2. **Task C** was conducted **only in the English-Only (En+En)** setting. Previous results from Task B showed poor performance in Hindi, so the best outcomes were expected using English prompts alone.