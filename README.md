# Introduction

This is a repository that contains the code for the article - Language Models for Search.

We've published it on the Timescale blog and you can read it [here](https://blog.timescale.com/blog/language-models-for-search/).

We've created three different notebooks to demonstrate three different ways that language models are used to improve search results

1. [Embedding Search](1. Embedding%20Search.ipynb) - Why embedding search alone is insufficient and how query understanding can significantly improve search results by filtering out irrelevant entries

2. [Synthetic Data Generation](2. Synthetic%20Data%20Generation.ipynb) - How to use language models to generate synthetic user queries to test the robustness of our search pipeline and metrics that we can use to evaluate our results

3. [AI-Powered Content Enrichment](3. AI-Powered%20Content%20Enrichment.ipynb) - A walkthrough on how to use language models to generate enriched metadata for products to improve search quality

To get started, make sure to install the required dependencies that we've outlined in the `pyproject.toml` file in the repository with the command

```bash
uv pip install -r pyproject.toml
```
