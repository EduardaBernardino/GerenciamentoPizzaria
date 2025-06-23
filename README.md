# 🍽️ API REST para Gerenciamento de Restaurante

Este projeto é uma API RESTful desenvolvida com **FastAPI** para gerenciar operações de um restaurante, incluindo cadastro de produtos, clientes, mesas, pedidos e usuários.

---

## 🚀 Tecnologias Utilizadas

- **[FastAPI](https://fastapi.tiangolo.com/)** – Framework rápido e moderno para APIs com Python
- **[SQLAlchemy](https://www.sqlalchemy.org/)** – ORM para interagir com o banco de dados
- **[SQLite](https://www.sqlite.org/)** – Banco de dados leve e local
- **[Pydantic](https://docs.pydantic.dev/)** – Validação e serialização de dados
- **[Uvicorn](https://www.uvicorn.org/)** – Servidor ASGI para rodar a aplicação
- **[Insomnia](https://insomnia.rest/)** – Cliente HTTP para testes de endpoints

---

## 🗂️ Estrutura de Arquivos


---

## 🔧 Como Executar o Projeto

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/api-restaurante.git
   cd api-restaurante

2.Crie e ative o ambiente virtual:
python -m venv .venv
.venv\Scripts\activate  # Windows


3.Instale as dependências:
pip install fastapi uvicorn sqlalchemy pydantic


4.Execute o servidor:
uvicorn main:app --reload

5. Acesse a documentação interativa:
* Swagger UI: http://localhost:8000/docs
* Redoc: http://localhost:8000/redoc


📚 Endpoints Disponíveis
Produtos
POST /produtos → Criar produto

GET /produtos → Listar produtos

Clientes
POST /clientes → Criar cliente com nome e email

GET /clientes → Listar clientes

Mesas
POST /mesas → Criar mesa com número e capacidade

GET /mesas → Listar mesas

Pedidos
POST /pedidos → Criar pedido com itens

GET /pedidos → Listar pedidos

Usuários
POST /usuarios → Criar usuário com nome, email, cargo e senha

GET /usuarios → Listar usuários

****
