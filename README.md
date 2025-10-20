<center>
  <h1 style="font-size:2.4em; margin-bottom:0.1em;">💰 N8N — Assistente Financeiro com Supabase</h1>
  <p style="margin-top:0.2em; font-size:1.05em; color:#555;">
    Automação financeira inteligente integrada ao <b>n8n</b>, com IA (Google Gemini), <b>Supabase</b> e <b>Telegram</b> para controle de despesas em tempo real.
  </p>
  <p>
    <a href="https://github.com/Rafael072187/N8N_Criando_um_assistente_financeiro_com_o_Supabase" style="background:#24292F;color:#fff;padding:8px 14px;border-radius:8px;text-decoration:none;font-weight:600;">
      🔗 Repositório no GitHub
    </a>
  </p>
</center>

<p align="center">
  <a href="https://github.com/Rafael072187/N8N_Criando_um_assistente_financeiro_com_o_Supabase">
    <img src="https://github.com/Rafael072187/N8N_Criando_um_assistente_financeiro_com_o_Supabase/blob/main/01.PNG" alt="Imagem ilustrativa do projeto" width="500"/>
  </a>
</p>

<hr>

## 🧭 **Tabela de Conteúdos**
- Descrição  
- Instalação  
- Uso  
- Tecnologias  
- Como contribuir  
- Autor  
- Observações  

---

## 📘 **Descrição**
<details>
  <summary><b>Resumo</b></summary>
  O **Assistente Financeiro com Supabase** é uma automação criada no **n8n** para gerenciamento de despesas empresariais.  
  Ele combina **IA (Google Gemini)**, **Supabase** e **Telegram** para permitir que empresas ou usuários controlem gastos diretamente pelo chat, sem planilhas manuais.
  
  Principais funcionalidades:
  - 💬 Interação via Telegram (consultas, registros e relatórios).
  - ➕ Registro automático de despesas no Supabase.
  - ✏️ Atualização e exclusão de transações via chat.
  - 📊 Relatórios automáticos e categorização inteligente por IA.
  - 🔁 Sincronização em tempo real com banco de dados.
</details>

---

## ⚙️ **Instalação**
<details>
  <summary><b>Passo a passo (Linux / macOS / Windows)</b></summary>

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/Rafael072187/N8N_Criando_um_assistente_financeiro_com_o_Supabase.git
   cd N8N_Criando_um_assistente_financeiro_com_o_Supabase
Configure o ambiente do n8n:

Instale o n8n globalmente:

bash
Copiar código
npm install n8n -g
Inicie o n8n:

bash
Copiar código
n8n start
Importe o fluxo Assistente_Financeiro.json.

Crie integrações e variáveis no n8n:

Telegram API Token

Supabase URL e API Key

Google Gemini API Key

Conecte as credenciais no painel do n8n.

</details>
🖥️ Uso
<details> <summary><b>Como usar o projeto</b></summary>
Inicie o fluxo dentro do painel do n8n.

Acesse o bot do Telegram configurado e envie comandos simples, como:

/adicionar 50 almoço equipe

/listar

/total mês

O sistema registra, atualiza ou exclui informações diretamente no Supabase.

O Google Gemini interpreta linguagem natural e classifica as categorias automaticamente.

</details> <p align="center" style="margin-top:14px;"> <img src="https://github.com/Rafael072187/N8N_Criando_um_assistente_financeiro_com_o_Supabase/blob/main/01.PNG" width="600" alt="Demonstração do projeto"> <br> <i>Exemplo da interface e fluxo do assistente no n8n.</i> </p>
🛠️ Tecnologias
<details> <summary><b>Stack principal</b></summary>
n8n — Orquestração de automações

Google Gemini — Inteligência Artificial para categorização

Supabase — Banco de dados e sincronização em tempo real

Telegram Bot API — Interface de comunicação com o usuário

CSV/Excel — Base auxiliar para despesas

</details>
🤝 Como contribuir
<details> <summary><b>Guia rápido</b></summary>
Faça um fork do repositório

Crie uma branch:

bash
Copiar código
git checkout -b feature/nova-funcionalidade
Commit e push:

bash
Copiar código
git commit -m "feat: adiciona nova automação financeira"
git push origin feature/nova-funcionalidade
Abra um Pull Request

💡 Sugestões de melhoria:

Integração com Google Sheets.

Criação de relatórios automáticos por e-mail.

Painel visual de dashboard financeiro no Supabase.

</details>
👤 Autor
<details> <summary><b>Contatos</b></summary> <p> <b>Rafael Bittencourt de Araújo</b> — desenvolvedor do projeto.<br> GitHub: <a href="https://github.com/Rafael072187" target="_blank">github.com/Rafael072187</a><br> </p> </details>
📝 Observações
✅ Projeto ideal para automatização de controle financeiro empresarial.
🔧 Extensível para integração com ERPs e APIs externas.
⚠️ Proteja suas chaves de API e tokens do Telegram antes de publicar.

<p align="center" style="margin-top:18px;"> <a href="https://github.com/Rafael072187/N8N_Criando_um_assistente_financeiro_com_o_Supabase" style="background:#0b5fff;color:#fff;padding:10px 18px;border-radius:8px;text-decoration:none;font-weight:600;"> Ver repositório </a> </p> <p align="center" style="margin-top:14px;color:#666;"> Estrutura gerada automaticamente com base no repositório analisado. </p> ```
