Large Language Models (LLMs) exhibit remarkable capabilities across diverse applications. However, their potential to generate toxic content remains a significant concern. We introduce a novel
methodology combining Self Supervisor, External Monitor, and Adversarial Trained System Prompt
to prevent toxic generation while maintaining engagement. The Self Supervisor method involves
the LLM evaluating its outputs for toxicity and regenerating responses if necessary. The External
Monitor uses the PERSPECTIVE API to assess and guide the detoxification process. Furthermore,
the Adversarial Trained System Prompt leverages adversarial training techniques to iteratively refine
prompts and enhance the model’s defense mechanisms. Our empirical studies using the REALTOXICITYPROMPTS dataset demonstrate the effectiveness of our methods in significantly reducing toxic
outputs across various LLMs, including GPT-3.5-turbo, GPT-4o, Llama-3-8b, and Vicuna-1.5-7b.
The results highlight the robustness and transferability of our approach, presenting a comprehensive
solution for mitigating toxicity in LLMs.
