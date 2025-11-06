# S.A.O.R.I. — Sistema Avançado de Organização de Recursos e Insumos

## Descrição
S.A.O.R.I. é uma solução composta por:
- Aplicação Desktop (Python + CustomTkinter) para geração de listas de materiais.
- API (FastAPI) para comunicação entre desktop e web.
- Frontend Web (React) para gestão, aprovações e logs.

## Objetivo
Reduzir erros em pedidos de materiais e agilizar o fluxo entre operador, gerência e compras.

## Como rodar (resumo)
1. Backend (FastAPI) — `docker-compose up backend`
2. Banco de dados — MySQL e PostgreSQL (docker-compose ou RDS)
3. Frontend (React) — `npm install && npm start`
4. Desktop — executar exe/py com endpoint configurado para a API

## Membros do grupo
- Augusto de Barros Almeida  
- Bruno Henrique Gusmão Gonçalves  
- Renato Fernandes da Silva  
- Rodrigo Bastos Amaral

## Licença
MIT
