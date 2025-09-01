# Workout API

![Python](https://img.shields.io/badge/Python-3.12-blue.svg)
![FastAPI](https://img.shields.io/badge/FastAPI-0.100.1-green.svg)
![Docker](https://img.shields.io/badge/Docker-blue.svg)
![Status](https://img.shields.io/badge/status-concluído-brightgreen)

## 🚀 Sobre o Projeto
Esta é uma API robusta para gestão de academias, desenvolvida em Python utilizando o framework FastAPI. O projeto foi parte de um desafio proposto pela [Digital Innovation One](https://web.dio.me/home) e implementa funcionalidades completas de CRUD (Create, Read, Update, Delete) para atletas, categorias e centros de treinamento. A aplicação é totalmente containerizada com Docker.

## ✨ Funcionalidades
- **Categorias**: CRUD completo para gerenciar as categorias das atividades (ex: Musculação, Natação).
- **Centros de Treinamento**: CRUD completo para gerenciar as unidades da academia.
- **Atletas**: CRUD completo para gerenciar os atletas, com relacionamento obrigatório com Categorias e Centros de Treinamento.
- **Validação de Dados**: Uso de Pydantic para garantir a integridade dos dados na entrada e saída da API.
- **Banco de Dados**: Persistência de dados com PostgreSQL rodando em um contêiner Docker.
- **Migrações**: Controle de versionamento do banco de dados com Alembic.
- **Documentação Automática**: Geração de documentação interativa da API (Swagger UI) em `/docs`.

## 🛠️ Tecnologias Utilizadas
- **Python 3.12**
- **FastAPI**: Framework web para a construção da API.
- **Docker** & **Docker Compose**: Para containerização da aplicação e do banco de dados.
- **PostgreSQL**: Banco de dados relacional.
- **SQLAlchemy**: ORM para interação com o banco de dados.
- **Pydantic**: Para validação e serialização de dados.
- **Alembic**: Para gerenciamento de migrações do banco de dados.

---
## ⚙️ Configuração do Ambiente Local

Siga os passos abaixo para executar o projeto na sua máquina.

**Pré-requisitos:**
- Python 3.12 ou superior
- Docker e Docker Compose
- Git

**1. Clone o repositório:**
```bash
# Substitua pela URL do SEU repositório
git clone [https://github.com/LucasTagliaferro/api-academia-fastapi.git](https://github.com/LucasTagliaferro/api-academia-fastapi.git)
