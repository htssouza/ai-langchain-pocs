# LangChain POCs

My personal playground for experimenting with LangChain, LangGraph, and related tools.

## Setup

### Prerequisites

- Python 3.11 - 3.13
- [uv](https://docs.astral.sh/uv/) package manager
- API keys configured in `.env` (see `example.env`)

### Installation

```bash
# Install dependencies
uv sync

# Run notebooks
uv run jupyter lab
```

### Environment Variables

Copy `example.env` to `.env` and fill in your keys:

```bash
cp example.env .env
```