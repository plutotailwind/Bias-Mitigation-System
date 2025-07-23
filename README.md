Bias Mitigation Framework for Large Language Models

🔍 Overview
This project presents a bias mitigation framework built for evaluating and reducing stereotypical biases in large language models (LLMs). Leveraging the StereoSet benchmark and the Mistral-7B-Instruct model, this system modifies and fine-tunes input prompts to encourage fairer and more balanced text generation.

🧠 Key Features
⚡ Fast LLM Fine-tuning: Utilizes Unsloth for lightweight, 4-bit efficient training of transformer models.

🗣 Prompt Engineering: Applies structured prompts to supervise the LLM via trl’s SFTTrainer.

🧪 Bias Evaluation Dataset: Supports datasets like StereoSet for benchmarking stereotype bias in language.

📊 Pre/Post Bias Analysis: Incorporates word-level replacements (synonym substitutions) using NLTK WordNet to test and mitigate biased associations.

🔧 Easy to Extend: Modular design for adapting to different LLMs, datasets, or bias metrics.
