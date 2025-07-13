# 🚀 Visão em Camadas TO-BE da Biblioteca

Este diretório contém a modelagem arquitetural **em camadas** do cenário futuro (TO-BE) da biblioteca, com a proposta de migração para um sistema em nuvem. O modelo detalha as transformações nas camadas de **Aplicação** e **Infraestrutura de TI**, mantendo a camada de Negócios com adaptações.

---

## 🌟 **Principais Melhorias Propostas**
- **Substituição das planilhas** por um **Sistema Integrado de Gerenciamento (SGB)**  
- **Migração para nuvem** (AWS/Azure) com infraestrutura escalável  
- **Automatização completa** dos processos manuais  

---

## 📊 **Camadas e Elementos Principais**

### **1. Camada de Negócios** *(mantida com ajustes)*
- **Atores/Papéis**:
  - `Funcionário` (Atendente, Compras)
- **Processos**:
  - `Adquirir livros` → `Cadastrar usuários` → `Cadastrar livros` → `Reservar` → `Emprestar` → `Devolver`
- **Serviços**:
  - `Cadastramento` (agora integrado ao SGB)

### **2. Camada de Aplicação** *(totalmente modernizada)*
- **Novos Componentes**:
  - `Sistema de Gerenciamento da Biblioteca (SGB)`
  - `Banco de Dados` (SGBD)
- **Serviços**:
  - `Gerenciamento automatizado` (empréstimos, devoluções, reservas)

### **3. Camada de Infraestrutura de TI** *(nova arquitetura em nuvem)*
- **Componentes em Nuvem**:
  - `Servidor de Aplicação` (Cloud)
  - `Storage` (Armazenamento em nuvem)
  - `Firewall` e `VPN` (segurança)
- **On-Premise**:
  - `Micro-computadores` (para acesso ao sistema)
  - `Windows` + `Office` (clientes leves)

---

## 🖼️ **Diagrama da Visão em Camadas TO-BE**
![Visão em Camadas TO-BE](assets/Vis%C3%A3o%20em%20Camadas%20TO-BE.jpg)  
*(Diagrama ArchiMate mostrando a nova arquitetura com destaque para a nuvem e integração entre camadas.)*

---

## 💡 **Benefícios Esperados**
| **AS-IS** (Problema) | **TO-BE** (Solução) |
|-----------------------|---------------------|
| Planilhas manuais | Sistema integrado com banco de dados |
| Infraestrutura física limitada | Escalabilidade em nuvem |
| Processos lentos e suscetíveis a erros | Automação e SLA de 48h |

---

## 🔗 **Relacionamentos com Outros Modelos**
- **Baseado no**: [Motivacional TO-BE](../02-motivacional-to-be/) (objetivos, requisitos)  
- **Comparação com**: [Visão AS-IS](../03-visao-camadas-as-is/) para análise de gap  

---

## 📂 **Estrutura do Diretório**