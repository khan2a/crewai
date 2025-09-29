# crewai
Crew AI integration with Vonage Communications API.
## Environment Setup
```
curl -LsSf https://astral.sh/uv/install.sh | sh
uv self update
uv venv .venv
source .venv/bin/activate
uv init
uv add --dev ruff flake8
ruff check .
flake8 .
wget https://github.com/pre-commit/pre-commit/blob/main/.pre-commit-config.yaml
uv pip install pre-commit
uv pip install pre-commit-hooks
pre-commit
pre-commit run --all-files
uv tool install crewai
uv tool install crewai --upgrade
uv tool list
crewai create crew debate

```