# Hyunseung091

This repository was scaffolded with a minimal Python project layout:

- `pyproject.toml` — project metadata
- `requirements.txt` — test dependencies (`pytest`)
- `src/hyunseung091` — package source
- `tests` — pytest tests
- `.github/workflows/ci.yml` — CI to run tests

To run tests locally:

```bash
python -m pip install -r requirements.txt
pytest -q
```