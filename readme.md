# Oracle EPM Data Generator

![Oracle EPM Data Generator Logo](static_site/images/logo.png) 

## Visão Geral

O Oracle EPM Data Generator é uma ferramenta abrangente para gerar dados de teste realistas para aplicativos Oracle Enterprise Performance Management (EPM) Cloud, incluindo:

- Financial Consolidation and Close Cloud (FCCS)
- Enterprise Planning and Budgeting Cloud Service (EPBCS)
- Profitability and Cost Management (PCM)
- Account Reconciliation Cloud Service (ARCS)

Esta ferramenta permite que desenvolvedores, consultores e administradores gerem rapidamente conjuntos de dados de teste que seguem as melhores práticas da Oracle, facilitando o desenvolvimento, teste e demonstração de aplicativos EPM Cloud.

## Recursos Principais

- **Geração de Dados Realistas**: Crie dados financeiros realistas com base em padrões do setor
- **Suporte a Múltiplos Módulos EPM**: Compatível com FCCS, EPBCS, PCM e ARCS
- **Validação de Melhores Práticas**: Garante que os dados gerados sigam as melhores práticas da Oracle
- **Validação de Entity Currency**: Implementa a regra crítica de que 99% dos membros da dimensão Entity devem ter uma moeda especificada
- **Sistema de Regras Personalizadas**: Interface para criar e gerenciar regras de validação personalizadas
- **Suporte Multilíngue**: Interface disponível em inglês, português e grego
- **Exportação Flexível**: Exporte dados em formatos compatíveis com Data Management e Data Integration
- **Integração com EPM Cloud**: Carregue dados diretamente para instâncias do EPM Cloud

## Instalação

### Pré-requisitos

- Node.js 14+ e npm
- Python 3.8+ e pip
- Docker e Docker Compose (opcional, para implantação em contêiner)

### Instalação Local

1. Clone o repositório:
