# Building with LLMs

Hands-on lecture materials for learning prompt engineering and agentic AI, from zero-shot prompting to autonomous agents.

## What's covered

| Section | Technique | What you'll build |
|---------|-----------|-------------------|
| 0 | Model Parameters | Explore temperature, top-p, and top-k |
| 1 | Zero-Shot Prompting | Restaurant review classifier + structured outputs with Pydantic |
| 2 | Few-Shot Prompting | Dish extraction from reviews |
| 3 | Chain of Thought | Recipe scaling with step-by-step reasoning |
| 4 | RAG | Recipe Q&A grounded in a knowledge base |
| 5 | Tool Use & Agents | Autonomous restaurant agent with smolagents |

## Getting started

1. Open this repo in GitHub Codespaces
2. Set your `OPENAI_API_KEY` as a Codespaces secret
3. Open `activity.ipynb` and follow along

## Files

- `lecture-notes.md` — Lecture content and slide reference
- `activity.ipynb` — Hands-on notebook (follow along with the instructor)

## Requirements

All dependencies are installed in the first notebook cell:

```
pip install openai pydantic smolagents
```
