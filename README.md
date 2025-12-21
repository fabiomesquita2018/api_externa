
---

# 📁 README – **API EXTERNA**
👉 Repositório: `api_externa`

```markdown
# 🌐 Chatbot Jarvis – API Externa

## 📌 Descrição

A **API Externa do Chatbot Jarvis** simula um serviço externo de respostas automáticas, sendo consumida pela API Principal.

Esta API representa um **serviço público gratuito**, utilizado para demonstrar integração entre aplicações, conforme os requisitos do projeto.

---

## Integração com a API Principal

Esta API é consumida exclusivamente pela API Principal, conforme ilustrado no diagrama de arquitetura presente no repositório da API Principal.

## 🚀 Tecnologias Utilizadas

- Python 3.11+
- FastAPI
- Uvicorn
- Docker

---

## 📡 Rotas Disponíveis

### 🔹 POST – Gerar resposta automática


**Exemplo de body (JSON):**
```json
{
  "message": "Olá"
}

http://localhost:3001/docs

🐳 Docker
▶️ Build da imagem

docker build -t api_externa .

▶️ Executar container

docker run -p 3001:8000 api_externa

📁 Estrutura do Projeto

api_externa/
│── main.py
│── Dockerfile
│── README.md

ℹ️ Observações Importantes

A API é gratuita

Não requer autenticação

Não redireciona o usuário

Os dados são tratados pela API Principal




