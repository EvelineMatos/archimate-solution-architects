# 🏛️ Visão em Camadas AS-IS da Biblioteca

Este diretório contém a modelagem arquitetural **em camadas** do cenário atual (AS-IS) da biblioteca, seguindo o framework ArchiMate. O modelo detalha as camadas de **Negócios**, **Aplicação** e **Infraestrutura de TI**, com foco nos elementos e relações existentes.

---

## 📊 **Camadas e Elementos Principais**

### **1. Camada de Negócios**
- **Atores/Papéis**:
  - `Funcionário` (Atendente, Compras)
- **Processos** (reaproveitados do Motivacional AS-IS):
  - `Adquirir livros` → `Cadastrar usuários` → `Cadastrar livros` → `Reservar` → `Emprestar` → `Devolver`
- **Serviços**:
  - `Cadastramento` (usuários/livros)

### **2. Camada de Aplicação**
- **Componentes**:
  - `Planilhas Excel` (único sistema atual)
- **Serviços**:
  - `Gerenciamento da biblioteca` (controle manual de empréstimos/devoluções)

### **3. Camada de Infraestrutura de TI**
- **Dispositivos**:
  - `Micro-computador`
- **Software**:
  - `Windows` (SO)
  - `Office` (Planilhas Excel)
- **Hardware**:
  - `SSD` (armazenamento)

---

## 🖼️ **Diagrama da Visão em Camadas AS-IS**
![Visão em Camadas AS-IS](assets/Vis%C3%A3o%20em%20Camadas%20AS-IS.jpg)  
*(Diagrama ArchiMate das três camadas interligadas, mostrando processos, sistemas e infraestrutura atuais.)*

---

## ⚠️ **Problemas Identificados**
- **Dependência crítica** de planilhas manuais (risco de erros, baixa auditoria).
- **Infraestrutura limitada**: Micro-computadores com Windows/Office sem integração.
- **Processos manuais**: Lentidão no atendimento e cadastros.

---

## 🔗 **Relacionamentos com Outros Modelos**
- **Baseado no**: [Motivacional AS-IS](../01-motivacional-as-is/) (stakeholders, drivers, processos).
- **Suporta a análise de gap** para o [TO-BE](../04-visao-camadas-to-be/).

---

## 📂 **Estrutura do Diretório**