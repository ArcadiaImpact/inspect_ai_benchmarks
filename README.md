# Inspect Benchmarks

Registry of benchmarks for evaluating LLMs with the [AI Safety Institute's](https://www.aisi.gov.uk/) [Inspect](https://github.com/UKGovernmentBEIS/inspect_ai) framework.

> *This repository has been initially developed by the participants of the [ASET](https://drive.google.com/file/d/1y6Q0jsbBMhBNbekBcIkejHaZ5kdqyfm2/view) (AI Safety Engineering Taskforce) pilot program.*

## Prerequisites

```
python -m venv env
source env/bin/activate
pip install -r requirements.txt
```

## Running evals

```
export OPENAI_API_KEY=your-openai-api-key
inspect eval benchmarks/mmlu.py --model openai/gpt-4o
```

## Benchmark registry

These are the benchmarks available in this repository. Datasets are either locally embedded in the repository, directly downloaded from their source URL or via Hugging Face datasets.

| Benchmark                                                | Reference                          | Code                          | Dataset  |
|:--------------------------------------------------------:|:----------------------------------:|:-----------------------------:|:--------:|
| MMLU: Measuring Massive Multitask Language Understanding | <https://arxiv.org/abs/2009.03300> | [mmlu.py](benchmarks/mmlu.py) | Download |

## Benchmark results

| Model           | MMLU |
|:---------------:|:----:|
| GPT-4o          | TBA  |
| GPT-4 Turbo     | TBA  |
| Claude 3 Opus   | TBA  |
| Claude 3 Sonnet | TBA  |
| Llama3 8b       | TBA  |
| Llama3 70b      | TBA  |

## FAQ

> What is Inspect and why are you using it for running evals for benchmarks?

*TBD*

## Contribute

*TBD*
