# ADR 001 — Usar K3s para deploy da aplicação

**Status:** Aceito

**Data:** 2026-08-07

## Contexto

A aplicação precisa ser implantada na Magalu Cloud de forma acessível publicamente, resiliente a falhas e com capacidade de escalar.

## Alternativas consideradas

### K3s em VM

- Kubernetes leve
- Menor custo
- Provisionamento rápido
- Sem alta disponibilidade nativa

### MKS (Kubernetes Gerenciado)

- Alta disponibilidade nativa
- Gerenciamento simplificado
- Maior custo

### Docker Compose em VM

- Simples de configurar
- Sem orquestração
- Sem self-healing

## Decisão

Utilizar K3s em uma VM BV2-2-40 para executar a aplicação.

### Critério da decisão

Menor custo operacional, provisionamento rápido e compatibilidade com Kubernetes padrão.

## Consequências

### Positivas

- Baixo custo
- Provisionamento rápido
- Facilidade de escalabilidade horizontal
- Compatibilidade com Kubernetes

### Negativas

- Ponto único de falha
- Sem alta disponibilidade nativa
- Recursos limitados à VM
