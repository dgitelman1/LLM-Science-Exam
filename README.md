# LLM-Science-Exam

Completed training and inference notebooks. Fine-tuned deberta-v3-large [^1] on complex chatgpt3.5 generated multiple choice questions related to scientific topics. Embedded prompts and Wikipedia content using sentence-transformers [^2][^3] to find exerpts likely to contain related information to prompts by embedding similarity. Performed inference to generate predictions for unseen questions generated in the same method.

# Example Question:
Which of the following statements accurately describes the impact of Modified Newtonian Dynamics (MOND) on the observed "missing baryonic mass" discrepancy in galaxy clusters?
A. MOND is a theory that reduces the observed missing baryonic mass in galaxy clusters by postulating the existence of a new form of matter called "fuzzy dark matter."

B. MOND is a theory that increases the discrepancy between the observed missing baryonic mass in galaxy clusters and the measured velocity dispersions from a factor of around 10 to a factor of about 20.

C. MOND is a theory that explains the missing baryonic mass in galaxy clusters that was previously considered dark matter by demonstrating that the mass is in the form of neutrinos and axions.

D. MOND is a theory that reduces the discrepancy between the observed missing baryonic mass in galaxy clusters and the measured velocity dispersions from a factor of around 10 to a factor of about 2.

E. MOND is a theory that eliminates the observed missing baryonic mass in galaxy clusters by imposing a new mathematical formulation of gravity that does not require the existence of dark matter.

Answer: D

[^1]: https://huggingface.co/microsoft/deberta-v3-large
[^2]: https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2
[^3]: https://huggingface.co/sentence-transformers/multi-qa-mpnet-base-dot-v1
