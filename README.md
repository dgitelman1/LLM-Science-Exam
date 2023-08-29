# LLM-Science-Exam

Completed training and inference notebooks. Fine-tuned deberta-v3-large [^1] on chatgpt3.5 generated multiple choice questions related to scientific topics. Embedded prompts and Wikipedia content using sentence-transformers [^2][^3] to find exerpts likely to contain related information to prompts by embedding similarity. Performed inference on unseen questions with added context to predict correct answers.

[^1]: https://huggingface.co/microsoft/deberta-v3-large
[^2]: https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2
[^3]: https://huggingface.co/sentence-transformers/multi-qa-mpnet-base-dot-v1
