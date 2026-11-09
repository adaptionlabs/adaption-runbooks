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

| Runbook                                                                    | Docs                                                                     | Docs runbook                                                                    | Blog                                                                                                                                                                     |                                                                                                                                                                                                        |
| -------------------------------------------------------------------------- | ------------------------------------------------------------------------ | ------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [Invent a Dataset](adaptive-data/invent_a_dataset.ipynb)                   | [guide](https://docs.adaptionlabs.ai/adaptive-data/invent-a-dataset/)    | [runbook page](https://docs.adaptionlabs.ai/runbooks/invent-a-dataset/)         | [launch](https://adaptionlabs.ai/blog/introducing-invent-a-dataset), [research](https://adaptionlabs.ai/blog/measuring-dataset-generation-abilities-with-zero-seed-data) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/adaptionlabs/adaption-runbooks/blob/main/adaptive-data/invent_a_dataset.ipynb)   |
| [Expand a Dataset](adaptive-data/expand_dataset.ipynb)                     | [guide](https://docs.adaptionlabs.ai/adaptive-data/expand-data/)         | [runbook page](https://docs.adaptionlabs.ai/runbooks/expand-a-dataset/)         |                                                                                                                                                                          | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/adaptionlabs/adaption-runbooks/blob/main/adaptive-data/expand_dataset.ipynb)     |
| [Train a Model with AutoScientist](autoscientist/autoscientist.ipynb)      | [guide](https://docs.adaptionlabs.ai/autoscientist-quickstart/)          | [runbook page](https://docs.adaptionlabs.ai/runbooks/train-with-autoscientist/) | [launch](https://adaptionlabs.ai/blog/autoscientist), [API](https://adaptionlabs.ai/blog/autoscientist-api)                                                              | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/adaptionlabs/adaption-runbooks/blob/main/autoscientist/autoscientist.ipynb)      |
| [Extend Conversation Trajectories](adaptive-data/extendtrajectories.ipynb) | [guide](https://docs.adaptionlabs.ai/adaptive-data/extend-trajectories/) | [runbook page](https://docs.adaptionlabs.ai/runbooks/extend-trajectories/)      |                                                                                                                                                                          | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/adaptionlabs/adaption-runbooks/blob/main/adaptive-data/extendtrajectories.ipynb) |

## Layout

Runbooks are grouped by product area in folders named after the [docs](https://docs.adaptionlabs.ai) sections (`adaptive-data/`, `autoscientist/`, `inference-stacks/`, ...). Create a folder when its first runbook arrives.

New runbooks start from [`templates/runbook.ipynb`](templates/runbook.ipynb). See [CONTRIBUTING.md](CONTRIBUTING.md).
