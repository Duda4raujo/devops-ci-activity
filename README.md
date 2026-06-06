# Relatório de Atividade DevOps - Pipeline CI

## Objetivo

Esta atividade teve como objetivo implementar um pipeline de Integração Contínua (CI) utilizando GitHub Actions, com execução automática a cada alteração enviada ao repositório. O pipeline foi configurado para executar testes automatizados em um projeto Python simples e, posteriormente, foi adaptado para rodar em um runner auto-hospedado utilizando uma máquina virtual Ubuntu Server.

## Ambiente utilizado

- Sistema operacional do servidor: Ubuntu Server 24.04.4 LTS
- Virtualizador: Oracle VM VirtualBox
- Linguagem: Python 3.12.3
- Controle de versão: Git 2.43.0
- Plataforma: GitHub
- CI/CD: GitHub Actions
- Runner utilizado: Self-hosted runner

## Estrutura do projeto

O repositório foi organizado com os seguintes arquivos:

```text
devops-ci-activity/
├── .github/workflows/ci.yml
├── calculadora.py
├── test_calculadora.py
└── requirements.txt
