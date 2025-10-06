# 🤝 Guia de Contribuição

Obrigado por contribuir com os projetos do **LEMA-UFPB**!

---

## 🌿 Fluxo Git

1. Crie um branch a partir de `develop`:
   ```bash
   git checkout develop
   git pull
   git checkout -b feature/nome-da-feature
   ```

2. Faça commits descritivos:
   ```bash
   git commit -m "feat(auth): adiciona autenticação JWT"
   ```

3. Mantenha seu branch atualizado:
   ```bash
   git fetch origin
   git rebase origin/develop
   ```

4. Envie sua contribuição:
   ```bash
   git push origin feature/nome-da-feature
   ```

5. Abra um **Pull Request** no GitHub.

---

## 🔍 Revisão de Código

- PRs precisam de **2 aprovações** antes do merge.  
- Sempre execute os testes antes de enviar:  
  ```bash
  npm test
  python -m flake8 .
  ```
- Use o **template padrão de PR** (automaticamente carregado).

---

## 🧩 Convenção de Commits

Usamos o padrão **Conventional Commits**:
```
<tipo>(escopo): descrição
```

Exemplos:
- `feat(ui): adiciona botão de login`
- `fix(api): corrige endpoint de autenticação`
- `chore(deps): atualiza dependências`

---

