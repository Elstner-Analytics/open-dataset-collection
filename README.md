# Useful datasets and tooling for LLM finetuning
We collect dataset, tools and other resources that can help with various aspects of LLM model creation/finetuning. As well as embedding model tuning, re-rankers, classifiers and document vision/OCR tasks.

We focus on high quality entries, which means that everything you find here was tested and used by us (Elstner Analytics, [elstner.dev](https://elstner.dev)) in a project. If you have a dataset or a dataset tool, feel free to open a pull request.

## Instruction data

### Tooling

| Name | License | Link | Comment |
| ---- | ------- | ---- | ------- |
| augmentoolkit | MIT | [GitHub](https://github.com/e-p-armstrong/augmentoolkit) | Converts long form base documents (reports, books) into domain specific QA datasets grounded on the context given. Can use Ollama for local LLM or the typical model providers for LLM generation. Can also generate text classification dataset (and the model in a closed loop) at a very low price point.

## Search and rank

### Auxiliar tasks

| Name | Provider | License | Paper | Dataset | Comment |
| ---- | -------- | ------- | ----- | ------- | ------- |
| esci-data | Amazon Science | Apache-2.0 | [arXiv](https://arxiv.org/abs/2206.06588) | [GitHub](https://github.com/amazon-science/esci-data) | A large dataset of difficult Amazon search queries and results, publicly released to foster research in improving the quality of search results. The dataset aims to serve as a benchmark for research in the area of semantic matching of queries and products, with tasks including ranking, classifying product results into relevance categories, and identifying substitute products for a given query. |
