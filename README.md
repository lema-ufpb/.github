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
   git clone git@github.com:lema/frontend.git
   git clone git@github.com:lema/backend.git
   git clone git@github.com:lema/infrastructure.git
   ```

4. Configure seu ambiente local:  
   Consulte [`docs/setup-dev-environment.md`](./docs/setup-dev-environment.md)

---

## 🧩 2. Estrutura da organização

| Área        | Repositório                | Descrição |
|--------------|----------------------------|------------|
| Frontend     | [`acme/frontend`](https://github.com/acme/frontend) | Aplicação React/Next.js |
| Backend      | [`acme/backend`](https://github.com/acme/backend)   | API FastAPI/Python |
| DevOps       | [`acme/infrastructure`](https://github.com/acme/infrastructure) | Helm Charts, Terraform, CI/CD |

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

---

