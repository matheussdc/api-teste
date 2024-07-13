Executar:
```
uvicorn store.main:app --reload
```

precommit package:
```
poetry run pre-commit install
```
Rodar testes:
```
poetry run pytest
```
test-matching:
```
poetry run pytest -s -rx -k $(K) --pdb store ./tests/
```
