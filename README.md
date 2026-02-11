# Cloud-Native Weather Monitor

## Visão Geral
Este projeto é um **Monitor de Clima** desenvolvido em uma arquitetura **cloud-native**, utilizando:
- **Frontend** em HTML/JS
- **Backend** em Node.js/Python
- **Nginx** como proxy reverso
- **Containers (Docker)**
- **Kubernetes (AKS no Azure)**
- **Infraestrutura como Código (Bicep)**

O objetivo é aprender e demonstrar como construir e implantar uma aplicação moderna no **Azure**, aproveitando créditos do **Azure for Students**.

---

### 1. Preparação do ambiente local
- Instalação do **Git** no Windows.
- Configuração de nome e e-mail:
  ```bash
  git config --global user.name "Pedro Henrique"
  git config --global user.email "seuemail@exemplo.com"# Cloud-Native Weather Monitor
  ```bash
-  Instalação e teste do Azure CLI:
  ```powershell
  az login
  ```powershell
- Instalação do Bicep CLI:
  ```bash
  az bicep install
  az bicep version
  ```bash