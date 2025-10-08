# 🧭 Guia de Onboarding Técnico

Bem-vindo(a) à equipe!  
Este guia serve como **ponto de partida** para qualquer novo colaborador técnico do LEMA-UFPB.

---

## 🚀 1. Primeiros passos

1. Solicite acesso à organização GitHub: **@admin**
2. Configure sua chave SSH seguindo o [guia oficial](https://docs.github.com/pt/authentication/connecting-to-github-with-ssh).
3. Clone os repositórios principais:

   ```bash
   # Exemplos hipotéticos
   git clone git@github.com:lema-ufpb/frontend.git
   git clone git@github.com:lema-ufpb/backend.git
   git clone git@github.com:lema-ufpb/infrastructure.git
   ```

4. Configure seu ambiente local:  
   Consulte [`docs/setup-dev-environment.md`](./docs/setup-dev-environment.md)

---

## 🧩 2. Estrutura da organização

| Área     | Repositório                                                               | Descrição                     |
| -------- | ------------------------------------------------------------------------- | ----------------------------- |
| Frontend | [`lema-ufpb/frontend`](https://github.com/lema-ufbp/frontend)             | Aplicação React/Next.js       |
| Backend  | [`lema-ufpb/backend`](https://github.com/lema-ufpb/backend)               | API FastAPI/Python            |
| DevOps   | [`lema-ufpb/infrastructure`](https://github.com/lema-ufpb/infrastructure) | Helm Charts, Terraform, CI/CD |

---

## 🔁 3. Fluxo de trabalho (GitFlow)

Seguimos o padrão **GitFlow**:

- `main`: produção
- `develop`: integração de features
- `feature/*`: novas funcionalidades
- `fix/*`: correções rápidas
- `release/*`: preparação para release

Consulte o guia completo: [`docs/gitflow-guide.md`](./docs/gitflow-guide.md)

---

## 🧱 4. Contribuição

Antes de abrir uma PR, leia:

- [`CONTRIBUTING.md`](./CONTRIBUTING.md)
- [`CODE_OF_CONDUCT.md`](./CODE_OF_CONDUCT.md)

Use sempre o template de PR (`.github/PULL_REQUEST_TEMPLATE.md`).

---

## ⚙️ 5. CI/CD

Nosso pipeline automatiza:

- Build
- Testes
- Deploy no Kubernetes

Documentação: [`docs/ci-cd-pipelines.md`](./docs/ci-cd-pipelines.md)

---

## 🛡️ 6. Segurança e Boas Práticas

- Não comitar `.env` ou credenciais.
- Use `pre-commit` hooks.
- Revise o [`SECURITY.md`](./SECURITY.md)

---

## 💬 7. Comunicação

- E-mail: `ufpblema@gmail.com`

---

## 🧾 8. Recursos úteis

- [Documentação oficial GitHub](https://docs.github.com)
- [Guia de Design System](https://ds.lema.ufpb.br)
- Tipos de APIs explicados: [https://youtu.be/pBASqUbZgkY?si=90PvDFvyI8uYn8uc](https://youtu.be/pBASqUbZgkY?si=90PvDFvyI8uYn8uc)
- Conceitos do NextJS em 10 min: [https://www.youtube.com/watch?v=MYdvzQ0-cis](https://www.youtube.com/watch?v=MYdvzQ0-cis)


---
