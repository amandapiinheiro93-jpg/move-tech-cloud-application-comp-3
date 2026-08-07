# ADR 002 — Usar DBaaS PostgreSQL da Magalu Cloud

**Status:** Aceito

**Data:** 2026-08-07

## Contexto

A aplicação precisa armazenar pedidos e itens de forma persistente e acessível para múltiplas réplicas da API.

## Alternativas consideradas

### DBaaS PostgreSQL

- Backup gerenciado
- Alta disponibilidade
- Menor esforço operacional

### PostgreSQL em Container

- Menor custo inicial
- Maior responsabilidade operacional
- Backup manual

## Decisão

Utilizar o DBaaS PostgreSQL da Magalu Cloud.

### Critério da decisão

Garantir persistência dos dados com menor custo operacional e maior confiabilidade.

## Consequências

### Positivas

- Backup automático
- Menor manutenção
- Alta disponibilidade

### Negativas

- Custo recorrente
- Dependência do provedor
- Menor controle de configuração
