# Suggested Commands for MarkItDown

## Setup
- Create virtual env: `python -m venv .venv`
- Activate env: `.venv\Scripts\activate` (Windows) or `source .venv/bin/activate` (Linux/Mac)
- Install dependencies: `pip install -e "packages/markitdown[all]"`

## Development
- Run CLI: `markitdown <file>`
- Run from source: `python -m markitdown <file>`

## Testing & Quality
- Run tests: `cd packages/markitdown && hatch test`
- Run type checks: `cd packages/markitdown && hatch run types:check`
- Run formatting (Black): `pre-commit run --all-files`
