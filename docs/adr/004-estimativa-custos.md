# ADR 004 — Estimativa de Custos da Solução

**Status:** Aceito

**Data:** 2026-08-07

## Contexto

A solução deve operar com baixo custo, mantendo disponibilidade adequada para um ambiente de aprendizado e desenvolvimento.

## Componentes de custo

| Recurso | Finalidade |
|----------|-----------|
| VM BV2-2-40 | Execução do cluster K3s |
| DBaaS PostgreSQL | Persistência dos dados |
| Container Registry | Armazenamento das imagens Docker |

## Decisão

Utilizar recursos de menor porte disponíveis para atender aos requisitos da aplicação.

### Critério da decisão

Equilibrar custo, simplicidade operacional e disponibilidade.

## Consequências

### Positivas

- Baixo custo operacional
- Ambiente simples de administrar

### Negativas

- Limitação de capacidade
- Necessidade de upgrade caso o tráfego aumente

## Observação

Os valores podem variar conforme a tabela de preços vigente da Magalu Cloud.
