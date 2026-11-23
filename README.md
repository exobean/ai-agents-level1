# Hands-On AI Agents, Level 1: Build Your First AI Agent in Python

**Free code companion** for the book by Exobean Engineering: the book's code, a notebook for every lesson, and self-grading exercises with answers.

## [⬇ Download the code companion](https://github.com/exobean/ai-agents-level1/releases/latest/download/shopassist-companion.zip)

`shopassist-companion.zip`. No account or sign-in needed.

## Set up in four steps

1. Unzip the file you downloaded.
2. Install [uv](https://docs.astral.sh/uv/), a free Python tool (it also installs Python for you).
3. Open a terminal inside the unzipped folder and run `uv sync`.
4. Check everything works: `uv run python -m shopassist.doctor`

Grade a lesson's exercises any time: `uv run pytest exercises/<lesson>`. The book explains every step with pictures.

## Browser only? Use Google Colab

Click **Open in Colab** next to your lesson, then run the first cell. It downloads the companion for you; then run the rest in order.

## Lesson notebooks

| Lesson | Notebook |
| --- | --- |
| 0.1 Set up your AI workshop in 15 minutes | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level1/blob/main/notebooks/m00_l01_setup.ipynb) |
| 0.2 API keys and costs, safely | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level1/blob/main/notebooks/m00_l02_keys_costs.ipynb) |
| 1.1 Tokens: how a model reads | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level1/blob/main/notebooks/m01_l01_tokens.ipynb) |
| 1.2 Next-token prediction and temperature | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level1/blob/main/notebooks/m01_l02_sampling.ipynb) |
| 1.3 The context window | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level1/blob/main/notebooks/m01_l03_context.ipynb) |
| 1.4 Hallucinations: fluent is not true | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level1/blob/main/notebooks/m01_l04_hallucinations.ipynb) |
| 2.1 Anatomy of an API call | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level1/blob/main/notebooks/m02_l01_api_call.ipynb) |
| 2.2 Messages, roles and system prompts | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level1/blob/main/notebooks/m02_l02_roles.ipynb) |
| 2.3 Structured output: JSON you can trust | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level1/blob/main/notebooks/m02_l03_json.ipynb) |
| 2.4 Streaming replies | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level1/blob/main/notebooks/m02_l04_streaming.ipynb) |
| 2.5 Errors, retries and rate limits | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level1/blob/main/notebooks/m02_l05_retries.ipynb) |
| 3.1 Prompts as specifications | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level1/blob/main/notebooks/m03_l01_spec.ipynb) |
| 3.2 Show, don't tell: examples in prompts | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level1/blob/main/notebooks/m03_l02_examples.ipynb) |
| 3.3 Version your prompts | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level1/blob/main/notebooks/m03_l03_versions.ipynb) |
| 3.4 Test your prompts | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level1/blob/main/notebooks/m03_l04_tests.ipynb) |
| 4.1 Function calling basics | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level1/blob/main/notebooks/m04_l01_function_calling.ipynb) |
| 4.2 Build the agent loop in 40 lines | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level1/blob/main/notebooks/m04_l02_agent_loop.ipynb) |
| 4.3 Designing good tools | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level1/blob/main/notebooks/m04_l03_tool_design.ipynb) |
| 4.4 When tools fail | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level1/blob/main/notebooks/m04_l04_tool_failures.ipynb) |
| 4.5 Lab: ShopAssist v1 | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level1/blob/main/notebooks/m04_l05_lab.ipynb) |
| 5.1 Conversations with memory | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level1/blob/main/notebooks/m05_l01_memory.ipynb) |
| 5.2 Answers from the store FAQ | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level1/blob/main/notebooks/m05_l02_faq.ipynb) |
| 5.3 Handing off to a human | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level1/blob/main/notebooks/m05_l03_handoff.ipynb) |
| 5.4 Traces: see every step | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level1/blob/main/notebooks/m05_l04_traces.ipynb) |
| 5.5 Capstone: ShopAssist v2 | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level1/blob/main/notebooks/m05_l05_capstone.ipynb) |
| 6.1 Unit tests with fake models | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level1/blob/main/notebooks/m06_l01_unit.ipynb) |
| 6.2 Record and replay | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level1/blob/main/notebooks/m06_l02_replay.ipynb) |
| 6.3 Your first evals | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level1/blob/main/notebooks/m06_l03_evals.ipynb) |
| 6.4 Ship it: a test plan and CI | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level1/blob/main/notebooks/m06_l04_release.ipynb) |

## Licence

Copyright 2026 Exobean Engineering. Free for your own learning and projects; see `LICENSE.txt`. For learning purposes only.
