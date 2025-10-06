# 🌿 Guia GitFlow — LEMA-UFPB

## Branches principais

- `main`: versão de produção
- `develop`: branch de integração

## Branches secundárias

| Tipo    | Prefixo     | Função                         |
| ------- | ----------- | ------------------------------ |
| Feature | `feature/*` | novas funcionalidades          |
| Fix     | `fix/*`     | correções rápidas              |
| Release | `release/*` | preparação de versões          |
| Hotfix  | `hotfix/*`  | correções urgentes em produção |

---

## Exemplo de fluxo

```bash
# criar uma feature
git checkout develop
git checkout -b feature/login

# implementar código...

git commit -m "feat(auth): adiciona tela de login"
git push origin feature/login

# abrir PR -> develop
```

---

## Boas práticas

- Nomeie branches de forma clara.
- Mantenha commits pequenos e objetivos.
