# LLM-Science-Exam

Completed training and inference notebooks. Fine-tuned deberta-v3-large [^1] on chatgpt3.5 generated multiple choice questions related to scientific topics. Used sentence-transformers [^2][^3]to find wikipedia exerpts likely to contain related information on prompts. Performed inference to generate predictions for unseen questions generated in the same method.

[^1]: https://huggingface.co/microsoft/deberta-v3-large
[^2]: https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2
[^3]: https://huggingface.co/sentence-transformers/multi-qa-mpnet-base-dot-v1
