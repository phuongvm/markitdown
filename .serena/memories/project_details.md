# MarkItDown Project Details

## Overview
MarkItDown is a Python utility for converting various file formats (PDF, Office, HTML, etc.) to Markdown, preserving structure for LLMs.

## Tech Stack
- **Language**: Python (>= 3.10)
- **Build**: Hatch (hatchling)
- **Dependencies**: `beautifulsoup4`, `requests`, `markdownify`, `magika`, `python-pptx`, `pdfminer.six`, etc.
- **Testing**: `pytest` via `hatch test`
- **Lint/Type**: `black`, `mypy`

## Directory Structure
- `packages/markitdown`: Main package.
- `packages/markitdown/src/markitdown`: Source.
- `packages/markitdown/src/markitdown/converters`: Converters.
- `packages/markitdown/tests`: Tests.
- `packages/markitdown-mcp`: MCP server.

## Features
- Native Python API & CLI.
- Extensible plugins.
- Azure Doc Intelligence & LLM integration.
