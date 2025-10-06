# 🔒 Política de Segurança

## Relato de Vulnerabilidades

Se você encontrar uma vulnerabilidade em qualquer projeto do **LEMA-UFPB**, **não abra uma issue pública**.  
Envie um e-mail diretamente para:

📧 **ufpblema@gmail.com**

---

## Boas Práticas Internas

- **Nunca** faça commit de credenciais, chaves ou tokens.
- Armazene segredos apenas em gerenciadores como:
  - HashiCorp Vault
  - AWS Secrets Manager
  - Kubernetes Secrets
  - BitWarden Secrets Manager

---

## Processo de Correção

1. A vulnerabilidade será analisada.
2. Um patch será desenvolvido e testado.
3. O time de segurança fará o merge e criará um release seguro.
