# ⚙️ CI/CD Pipelines — ACME

## Integração Contínua (CI)

- Build automatizado com GitHub Actions
- Execução de testes unitários
- Linter e formatação de código
- Verificação de segurança (Dependabot)

---

## Entrega Contínua (CD)

- Deploy automatizado em ambiente de staging
- Revisão e aprovação manual para produção
- Deploys via Helm + ArgoCD no Kubernetes

---

## Arquitetura Simplificada

```
GitHub → Actions → Docker Registry → ArgoCD → Kubernetes
```

---

## Variáveis Sensíveis

- Armazenadas apenas em **GitHub Secrets** ou **Bitwarden Secrets Manager**
- Nunca commitadas no repositório

---
