# Models for Programming Languages



💡 **Notion Tip:  The mentioned models are intended for quick start, and more models can be found online.**


## For Multiple Prgramming languages:

- CodeBERTa is a RoBERTa-like model trained on the **[CodeSearchNet](https://github.blog/2019-09-26-introducing-the-codesearchnet-challenge/)** dataset from GitHub.

Languages supported: 

```
"go"
"java"
"javascript"
"php"
"python"
"ruby"
```

[microsoft/codebert-base · Hugging Face](https://huggingface.co/microsoft/codebert-base)

- **CodeBERT-base**

[microsoft/codebert-base · Hugging Face](https://huggingface.co/microsoft/codebert-base)

- codet5-base

Built using OpenAI’s [GPT-2](https://github.com/openai/gpt-2) language model, [Polycoder](https://github.com/VHellendoorn/Code-LMs) was trained on a dataset of 249GB of code spanning 12 programming languages.

It was designed as an open source alternative to OpenAI’s Codex (see above). While not as powerful as some of the code generation models on this list, Polycoder surpasses Codex at writing code in the programming language C.

[Salesforce/codet5-base · Hugging Face](https://huggingface.co/Salesforce/codet5-base)

- StarCoder is a 15 billion-parameter AI model designed to generate code for the open-scientific AI research community. StarCoder was trained on licensed data from GitHub spanning over 80 programming languages, and fine-tuning it on 35 billion Python tokens.

[bigcode/starcoder · Hugging Face](https://huggingface.co/bigcode/starcoder)

- PolyCoder

This is a PolyCoder model with **2.7B** parameters, presented in the paper **["A Systematic Evaluation of Large Language Models of Code"](https://arxiv.org/pdf/2202.13169.pdf)** (MAPS'2022 and ICLR'2022 Workshop Deep Learning 4 Code).

The model was trained on **249 GB** of code across **12** programming languages.

[NinedayWang/PolyCoder-2.7B · Hugging Face](https://huggingface.co/NinedayWang/PolyCoder-2.7B)

## For Java:

- A BERT-like model pretrained on Java software code.

[CAUKiel/JavaBERT · Hugging Face](https://huggingface.co/CAUKiel/JavaBERT)

- This is a `microsoft/codebert-base-mlm` model, trained for 1,000,000 steps (with `batch_size=32`) on **Java** code from the `codeparrot/github-code-clean` dataset, on the masked-language-modeling task.

[neulab/codebert-java · Hugging Face](https://huggingface.co/neulab/codebert-java)