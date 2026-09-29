# REST API — FastAPI + SQLite

> **Portfolio project · Backend · Python · FastAPI**

API de cadastro construída para demonstrar backend aplicado: **CRUD, validação, persistência, testes e documentação automática**.

## Funcionalidades

- Health check
- Criação de contatos
- Listagem de contatos
- Consulta por ID
- Atualização
- Exclusão
- Validação de dados
- Persistência em SQLite
- Documentação OpenAPI/Swagger

## Endpoints

- `GET /health`
- `POST /contacts`
- `GET /contacts`
- `GET /contacts/{id}`
- `PUT /contacts/{id}`
- `DELETE /contacts/{id}`

## Stack

**Python · FastAPI · SQLAlchemy · SQLite · Pydantic · Pytest**

## Como executar

```bash
pip install -r requirements.txt
uvicorn app.main:app --reload
```

A documentação interativa fica disponível em:

`http://127.0.0.1:8000/docs`

## Testes

```bash
pytest -q
```

A suíte validada cobre o health check, criação, listagem e tratamento de recurso inexistente.

## Evidências

- [Mapa dos endpoints e status de teste](output/openapi.json)
- [Evidência funcional](output/evidence.md)
- [Testes](tests/)

## Competências demonstradas

**Backend Development · APIs REST · FastAPI · Python · SQLAlchemy · SQLite · Pydantic · Testing · OpenAPI · Technical Documentation**
