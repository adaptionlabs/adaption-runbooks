# Adaption Runbooks

Runnable notebooks for the [Adaption API](https://docs.adaptionlabs.ai). Open one in Colab or run it locally to go through a complete workflow from start to finish. Browse them all on the [Runbooks overview](https://docs.adaptionlabs.ai/runbooks/overview/).

## Getting started

1. Get an API key from the [Adaption app](https://adaptionlabs.ai/app/auth).
2. Open a runbook below in Colab and add `ADAPTION_API_KEY` to Colab secrets (🔑 in the sidebar).

To run locally:

```bash
export ADAPTION_API_KEY=...
uv run --with adaption --with jupyterlab jupyter lab
```

## Runbooks

| Runbook                                                                                 | Docs                                                                                   |                                                                                                                                                                                                                    |
| --------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [Invent a Dataset](adaptive-data/invent_a_dataset.ipynb)                                | [guide](https://docs.adaptionlabs.ai/adaptive-data/invent-a-dataset/)                  | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/adaptionlabs/adaption-runbooks/blob/main/adaptive-data/invent_a_dataset.ipynb)               |
| [Expand a Dataset](adaptive-data/expand_dataset.ipynb)                                  | [guide](https://docs.adaptionlabs.ai/adaptive-data/expand-data/)                       | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/adaptionlabs/adaption-runbooks/blob/main/adaptive-data/expand_dataset.ipynb)                 |
| [Extend Conversation Trajectories](adaptive-data/extendtrajectories.ipynb)              | [guide](https://docs.adaptionlabs.ai/adaptive-data/extend-trajectories/)               | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/adaptionlabs/adaption-runbooks/blob/main/adaptive-data/extendtrajectories.ipynb)             |
| [Train a Model with AutoScientist](autoscientist/autoscientist.ipynb)                   | [guide](https://docs.adaptionlabs.ai/autoscientist-quickstart/)                        | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/adaptionlabs/adaption-runbooks/blob/main/autoscientist/autoscientist.ipynb)                  |
| [Configure Adaptive Data](adaptive-data/configure_adaptive_data.ipynb)                  | [guide](https://docs.adaptionlabs.ai/adaptive-data/configure-adaptive-data/)           | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/adaptionlabs/adaption-runbooks/blob/main/adaptive-data/configure_adaptive_data.ipynb)        |
| [Combine Datasets](adaptive-data/combine_datasets.ipynb)                                | [guide](https://docs.adaptionlabs.ai/adaptive-data/combine-datasets/)                  | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/adaptionlabs/adaption-runbooks/blob/main/adaptive-data/combine_datasets.ipynb)               |
| [Evaluate Dataset Quality](adaptive-data/evaluate_dataset_quality.ipynb)                | [guide](https://docs.adaptionlabs.ai/adaptive-data/evaluate-dataset-quality/)          | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/adaptionlabs/adaption-runbooks/blob/main/adaptive-data/evaluate_dataset_quality.ipynb)       |
| [Train with Alignment (SFT → DPO)](autoscientist/alignment_training.ipynb)              | [guide](https://docs.adaptionlabs.ai/autoscientist/overview/)                          | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/adaptionlabs/adaption-runbooks/blob/main/autoscientist/alignment_training.ipynb)             |
| [Inference with the Responses API](inference-stacks/inference_quickstart.ipynb)         | [guide](https://docs.adaptionlabs.ai/inference-stacks/quickstart/)                     | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/adaptionlabs/adaption-runbooks/blob/main/inference-stacks/inference_quickstart.ipynb)        |

## Layout

Runbooks are grouped by product area in folders named after the [docs](https://docs.adaptionlabs.ai) sections (`adaptive-data/`, `autoscientist/`, `inference-stacks/`, ...). Create a folder when its first runbook arrives.

New runbooks start from [`templates/runbook.ipynb`](templates/runbook.ipynb). See [CONTRIBUTING.md](CONTRIBUTING.md).
