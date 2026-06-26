# 💻 School Computer Loan System API

API REST desenvolvida com **FastAPI** para gerenciamento de empréstimos de computadores escolares.

## 🚀 Tecnologias

* Python
* FastAPI
* SQLAlchemy
* Pydantic V2
* SQLite
* Uvicorn

## ✨ Funcionalidades

* Cadastro de equipamentos
* Listagem de equipamentos
* Busca de equipamento por ID
* Cadastro de usuários
* Listagem de usuários
* Registro de empréstimos
* Listagem de empréstimos
* Registro de devolução de equipamentos
* Documentação automática com Swagger

## 📌 Endpoints

| Método | Endpoint                                | Descrição           |
| ------ | --------------------------------------- | ------------------- |
| POST   | `/equipments/`                          | Criar equipamento   |
| GET    | `/equipments/`                          | Listar equipamentos |
| GET    | `/equipments/{equipment_id}`            | Buscar equipamento  |
| POST   | `/users/`                               | Criar usuário       |
| GET    | `/users/`                               | Listar usuários     |
| POST   | `/emprestimos/`                         | Criar empréstimo    |
| GET    | `/emprestimos/`                         | Listar empréstimos  |
| PUT    | `/emprestimos/{emprestimo_id}/devolver` | Registrar devolução |

## ▶️ Executando o projeto

```bash
git clone https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git

cd SEU-REPOSITORIO

python -m venv .venv

# Windows
.venv\Scripts\activate

pip install -r requirements.txt

uvicorn src.main:app --reload
```

A documentação ficará disponível em:

* `http://localhost:8000/docs`
* `http://localhost:8000/redoc`

## 📄 Licença

Projeto desenvolvido para fins acadêmicos e estudo de desenvolvimento de APIs com FastAPI.
