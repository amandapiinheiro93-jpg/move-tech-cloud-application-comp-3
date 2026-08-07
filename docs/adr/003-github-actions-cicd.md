# ADR 003 — Utilizar GitHub Actions para CI/CD

**Status:** Aceito

**Data:** 2026-08-07

## Contexto

A aplicação necessita de um processo automatizado para build, testes e deploy, reduzindo erros manuais e aumentando a rastreabilidade das entregas.

## Alternativas consideradas

### GitHub Actions

- Integração nativa com GitHub
- Fácil configuração
- Sem necessidade de servidor dedicado

### Jenkins

- Altamente customizável
- Requer administração própria

### Deploy Manual

- Simples inicialmente
- Propenso a erros humanos

## Decisão

Utilizar GitHub Actions como ferramenta de CI/CD.

### Critério da decisão

Integração nativa com o repositório, facilidade de manutenção e automação do processo de entrega.

## Consequências

### Positivas

- Deploy automatizado
- Rastreabilidade das versões
- Menor risco de erro manual

### Negativas

- Dependência do GitHub
- Curva inicial de aprendizado para workflows
