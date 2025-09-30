# 💰 Assistente Financeiro

Este projeto implementa um **assistente financeiro automatizado**, desenvolvido no **n8n**, que integra **IA (Google Gemini)** e **Supabase** para facilitar o controle de despesas corporativas. Ele permite interação via **Telegram**, oferecendo um gerenciamento prático e inteligente das finanças em tempo real.

---

## 🚀 Funcionalidades

* 💬 **Interação via Telegram** → consultas e comandos simples.
* ➕ **Adicionar despesas** com registro automático no banco.
* ✏️ **Atualizar valores e categorias** de forma dinâmica.
* ❌ **Remover despesas** diretamente pelo chat.
* 📊 **Somar despesas por período ou categoria**.
* 🧠 **Classificação inteligente de categorias** usando IA.
* 🔄 **Sincronização em tempo real** com Supabase.

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia           | Finalidade                                        |
| -------------------- | ------------------------------------------------- |
| **n8n**              | Orquestração do fluxo                             |
| **Google Gemini**    | IA para interpretação de comandos e categorização |
| **Supabase**         | Banco de dados para registros financeiros         |
| **Telegram Bot API** | Interface de interação com o usuário              |

---

## 📂 Estrutura do Fluxo

1. **Telegram Trigger** → Captura mensagens enviadas pelo usuário.
2. **Agente de IA (Gemini)** → Interpreta comandos e identifica intenções.
3. **Supabase (Insert/Update/Delete)** → Gerencia registros financeiros.
4. **Consultas no Supabase** → Retorna dados consolidados.
5. **Resposta no Telegram** → Fornece feedback ou relatórios ao usuário.

---

## 🎯 Casos de Uso

* Controle de despesas empresariais em tempo real.
* Automação de registro de gastos sem planilhas manuais.
* Gestão financeira colaborativa via chat.
* Classificação inteligente de custos para relatórios mais precisos.

