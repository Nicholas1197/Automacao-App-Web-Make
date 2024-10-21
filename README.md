# Integração Google Sheets e Google Docs

## Visão Geral

Este projeto visa facilitar a integração entre Google Sheets e Google Docs, permitindo a automação do processamento de dados coletados em planilhas e a criação de documentos personalizados a partir de modelos. A automação é ideal para situações em que há necessidade de gerar documentos repetidamente para registros, como contratos, com base em dados de formulários.

## Funcionalidades

- **Monitoramento de Linhas no Google Sheets**: O projeto observa novas entradas em uma planilha específica e coleta dados automaticamente.
- **Criação de Documentos Personalizados**: Utiliza um modelo de documento do Google Docs para gerar novos documentos com dados extraídos do Google Sheets.
- **Customização e Escalabilidade**: Permite personalizar a estrutura e os dados a serem inseridos nos documentos gerados.

## Fluxo do Projeto

1. **Monitoramento de Linhas**: O módulo `google-sheets:watchRows` é usado para monitorar uma planilha específica em busca de novas entradas.
2. **Feeding de Dados**: Os dados coletados são organizados para processamento.
3. **Geração de Documentos**: O módulo `google-docs:createADocumentFromTemplate` gera documentos a partir de um modelo, usando dados extraídos da planilha.

## Pré-requisitos

- Conta do Google (com acesso ao Google Sheets e Google Docs).
- Configuração de credenciais e permissões adequadas.
- Conhecimento básico sobre uso do Google Sheets e Google Docs.

## Instalação

1. Clone este repositório:
   ```bash
   git clone https://github.com/seuusuario/integracao-google-sheets-docs.git
   cd integracao-google-sheets-docs
