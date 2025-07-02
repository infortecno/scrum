# 🧩 Épico: Pagamentos via Pix

> Grande iniciativa que envolve melhorias e novos recursos no sistema de Pix.

---

## 🎯 Features do Épico "Pagamentos via Pix"

1. **Atalho para Solicitar Aumento de Limite**
2. **Agendamento de Transferência Pix**
3. **Recibo Compartilhável no WhatsApp**

---

## 🔹 Feature: Atalho para Solicitar Aumento de Limite

### 👤 User Stories

#### 1. Como usuário, quero ver um botão para solicitar aumento de limite quando meu Pix falhar por limite excedido.
##### ✅ Tasks:
- [ ] Adicionar verificação de erro "limite excedido" na resposta da API  
- [ ] Criar botão de atalho no bottomsheet de erro  
- [ ] Exibir botão apenas se a feature flag estiver ativada  

#### 2. Como usuário, quero ser redirecionado automaticamente para a tela de solicitação ao clicar no botão.
##### ✅ Tasks:
- [ ] Navegar para a rota `PixModulePaths.requestMoreLimit`  
- [ ] Garantir passagem dos parâmetros necessários  
- [ ] Criar testes de navegação

---

```text
Épico
├── Feature 1: Atalho para Solicitar Aumento de Limite
│   ├── User Story 1
│   │   ├── Task A
│   │   ├── Task B
│   │   └── Task C
│   └── User Story 2
│       ├── Task A
│       └── Task B
├── Feature 2: Agendamento de Transferência Pix
└── Feature 3: Recibo Compartilhável no WhatsApp
