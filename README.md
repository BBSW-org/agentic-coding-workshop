# agentic-coding-workshop

This repository contains materials for a hands-on workshop on agentic coding and harness engineering.

Preview is available at <https://bbsw-org.github.io/agent-coding-workshop/>.

## Quick start

To explore code in this book, use the "Open in GitHub Codespaces" button below.

[![](https://github.com/codespaces/badge.svg)](https://codespaces.new/BBSW-org/agentic-coding-workshop?quickstart=1&devcontainer_path=.devcontainer%2Fdevcontainer.json)

## Build the book

Restore and activate the virtual environment using `uv`:

```bash
uv sync
source .venv/bin/activate
```

Render all formats:

```bash
quarto render
```

Render HTML only:

```bash
quarto render --to html
```

Render slides:

```bash
quarto render slides/<TBA>/index.qmd
```

## Maintenance

Update Python version:

```bash
uv python pin x.y.z
uv sync
```

Update dependencies:

```bash
uv lock --upgrade
uv sync
```
