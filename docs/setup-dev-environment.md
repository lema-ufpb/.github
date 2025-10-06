# ⚙️ Configuração do Ambiente de Desenvolvimento

## Pré-requisitos

- Git
- Node.js ≥ 18
- Python ≥ 3.10
- Docker e Docker Compose

---

## Passos

1. Clone os repositórios necessários:
   ```bash
   git clone git@github.com:lema/frontend.git
   git clone git@github.com:lema/backend.git
   ```

2. Instale dependências:
   ```bash
   cd frontend && npm install
   cd ../backend && pip install -r requirements.txt
   ```

3. Configure variáveis de ambiente:
   ```bash
   cp .env.example .env
   ```

4. Suba os serviços:
   ```bash
   docker-compose up -d
   ```

5. Acesse:
   - Frontend → http://localhost:3000  
   - Backend → http://localhost:8000
