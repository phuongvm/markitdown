# Task Completion Workflow

When a task is completed:

1. **Verify Changes**:
   - Run tests: `hatch test` (in `packages/markitdown`)
   - If new features were added, ensure new tests cover them.

2. **Quality Checks**:
   - Run formatting: `pre-commit run --all-files` (or `black .`)
   - Run type checking: `hatch run types:check` (in `packages/markitdown`)

3. **Documentation**:
   - Update `README.md` if user-facing changes were made.
   - Update docstrings.

4. **Final Review**:
   - Check if `pyproject.toml` needs updates (dependencies).
