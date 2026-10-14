### Descrição
Adiciona o linter Ruff nas dependências de desenvolvimento, ajusta a versão do Python para 3.12 e atualiza o pipeline do GitHub Actions para validar o lint antes dos testes.

### Issue Relacionada
Closes #1

### Checklist de DoD
- [ ] Ruff executado localmente sem erros (`uv run ruff check .`)
- [ ] Pytest executado com sucesso (`uv run pytest -v`)