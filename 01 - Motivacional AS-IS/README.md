# Modelo Motivacional AS-IS da Biblioteca

Este diretório contém a modelagem **AS-IS** (estado atual) do cenário da biblioteca, conforme levantado nas entrevistas e documentos de requisitos. O modelo captura os stakeholders, drivers, processos e problemas atuais.

## 📌 Elementos Principais

### **Stakeholders e Diretivas (Drivers)**
- **Atendente**: Responsável pelo atendimento e controle dos empréstimos.
- **Usuários**: Utilizam os serviços de empréstimo e reserva.
- **Fornecedores**: Garantem a aquisição de novos livros.

**Diretivas Estratégicas (Drivers)**:
- Zelo pelo atendimento.
- Disponibilização das obras.
- Compartilhamento do conhecimento.

---

### **Processos Atuais (Business Process)**
1. **Aquisição de livros**: Compra de novas obras junto a fornecedores.
2. **Cadastro de usuários/livros**: Registro manual em planilhas.
3. **Atendimento ao público**:
   - Reserva de livros.
   - Empréstimo e devolução (controlados por planilhas).

---

### **Problemas Identificados (Assessment)**
- **Acervo limitado**: Restrição na disponibilidade de obras.
- **Demora no atendimento**: Processos manuais e burocráticos.
- **Controle por planilhas**: 
  - Risco de erros.
  - Dificuldade de auditoria.
  - Gestão trabalhosa.

---

### **Sistemas Atuais (Application Component)**
- **Planilhas eletrônicas**: Única ferramenta para gestão de empréstimos, cadastros e estoque.

---

## 🖼️ Diagrama AS-IS
![Modelo Motivacional AS-IS](assets/Motivacional AS-IS.JPG)  
*(Diagrama ilustrando os stakeholders, drivers, processos e problemas atuais.)*

---

## 📚 Contexto
A biblioteca busca modernizar sua operação, substituindo as planilhas por um **sistema em nuvem** (ex: AWS/Azure) para:
- Automatizar processos.
- Ampliar o acervo.
- Reduzir tempo de atendimento.
- Garantir controle eficiente (ex: limite de 5 obras por usuário).

---

## ➡️ Próximos Passos
- Modelagem **TO-BE** (estado futuro) com a proposta do novo sistema.
- Visão em camadas (AS-IS e TO-BE) para detalhamento técnico.
