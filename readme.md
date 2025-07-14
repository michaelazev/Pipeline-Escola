# 🎓 API Escolar - FastAPI com Gerenciamento de Alunos, Cursos e Matrículas

Este projeto é uma API desenvolvida com FastAPI para gerenciar alunos, cursos e matrículas em uma instituição de ensino.

## Pré-requisitos

- [Python 3.10 ou superior instalado](https://www.python.org/downloads/)
- [Git](https://git-scm.com/downloads)
- [Docker](https://www.docker.com/get-started/)

## 🚀 Como rodar o projeto

1. **Faça o download do repositório:**
   [Clique aqui para realizar o download](https://github.com/michaelazev/Pipeline-Escola.git)

2. **Crie um ambiente virtual:**
   ```sh
   python3 -m venv ./venv
   ```

3. **Ative o ambiente virtual:**
   - No Linux/Mac:
     ```sh
     source venv/bin/activate
     ```
   - No Windows, abra um terminal no modo administrador e execute o comando:
   ```sh
   Set-ExecutionPolicy RemoteSigned
   ```

     ```sh
     venv\Scripts\activate
     ```

4. **Instale as dependências:**
   ```sh
   pip install -r requirements.txt
   ```

5. **Execute a aplicação:**
   ```sh
   uvicorn app:app --reload
   ```

6. **Acesse a documentação interativa:**

   Abra o navegador e acesse:  
   [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)

   Aqui você pode testar todos os endpoints da API de forma interativa.

---

## 🗂️ Estrutura do Projeto

- `app.py`: Arquivo principal da aplicação FastAPI.
- `models.py`: Modelos do banco de dados (SQLAlchemy).
- `schemas.py`: Schemas de validação (Pydantic).
- `database.py`: Configuração do banco de dados SQLite.
- `routers/`: Diretório com os arquivos de rotas (alunos, cursos, matrículas).
- `requirements.txt`: Lista de dependências do projeto.

---

## ⚙️ Funcionalidades da API

✅ Cadastro e gerenciamento de alunos
✅ Matrícula de alunos em cursos
✅ Documentação interativa via Swagger
✅ Banco de dados SQLite gerenciado automaticamente

---

- O banco de dados SQLite será criado automaticamente como `escola.db` na primeira execução.
- Para reiniciar o banco, basta apagar o arquivo `escola.db` (isso apagará todos os dados).

---

## 📌 Observação Final

Este projeto faz parte da Imersão DevOps - Alura Google Cloud e tem como objetivo praticar conceitos de APIs REST, FastAPI, Docker e boas práticas de versionamento.

Contribuições são bem-vindas! Bora codar 🚀
