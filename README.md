# GPT from First Principles

An executable learning path that builds a small GPT one concept at a time.
The notebooks favor small tensors, visible intermediate values, and direct
implementations before reusable PyTorch modules.

## Setup

```bash
uv sync
uv run jupyter lab
```

Run Jupyter from the repository root. Each notebook locates the root before
loading shared data, so it can also be executed directly by notebook tooling.

## Learning path

1. **Text foundations**: tokenization, next-token training windows, and token
   plus positional embeddings.
2. **Attention**: attention by hand, trainable self-attention, causal masking,
   and multi-head attention.

The notebooks are intentionally numbered. Work through them in order because
each one assumes the shapes and vocabulary introduced by the previous one.

## Current progress

- Text foundations have been migrated from the original chapter 2 experiments.
- Dot-product attention by hand has been migrated from the chapter 3 experiment.
- The remaining attention notebooks mark the next implementation steps.
