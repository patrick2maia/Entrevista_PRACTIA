# Entrevista_PRACTIA
Entrevista do dia 23/02/2026
# Projeto de Automação e Versionamento - Patrick Analista

Este repositório contém o sistema de backup automático de workflows n8n, desenvolvido para atender aos requisitos de padronização e previsibilidade da PRACTIA.

## 🚀 Funcionalidades
* **Versionamento Automático (Item 6):** Sincronização a cada 30 minutos via Schedule Trigger.
* **CRUD via API (Item 7):** Extração de dados via n8n API e persistência via GitHub API.
* **Arquitetura:** Uso de Loops e Split Out para processamento em lote de múltiplos workflows.

## 📂 Estrutura de Pastas
* `/`: Contém o workflow principal (Main).
* `/library`: Contém os componentes globais reutilizáveis (Standard_Logger e Error_Handler).

## 🔒 Segurança
* Credenciais gerenciadas via ambiente seguro (Secrets/API Keys), garantindo que dados sensíveis não fiquem expostos no código.
