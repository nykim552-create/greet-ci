# greet-ci

## 설치와 실행

```bash
uv lock
uv run --locked python greet.py Hee
uv run --locked python greet.py
uv run --locked pytest -q greet.py
uv run --locked black --check greet.py
uv run --locked flake8 greet.py
uv run --locked mypy greet.py
uv build
```
