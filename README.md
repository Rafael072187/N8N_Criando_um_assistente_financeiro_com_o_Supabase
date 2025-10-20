<center> <h1 style="font-size:2.4em; margin-bottom:0.1em;">💰 N8N — Assistente Financeiro com Supabase</h1> <p style="margin-top:0.2em; font-size:1.05em; color:#555;"> Automação financeira inteligente com <b>n8n</b>, <b>Supabase</b>, <b>IA Google Gemini</b> e <b>Telegram</b> — controle de despesas corporativas em tempo real. </p> <p> <a href="{REPO_URL}" style="background:#24292F;color:#fff;padding:8px 14px; border-radius:8px;text-decoration:none;font-weight:600;"> 🔗 Repositório no GitHub </a> </p> </center> <p align="center" style="margin-top:8px;"> <a href="{REPO_URL}/blob/main/01.PNG" target="_blank" style="background:#0b5fff;color:#fff;padding:8px 14px;border-radius:8px; text-decoration:none;font-weight:600;"> 📷 Ver imagem 01 </a> </p> <hr>
🧭 Tabela de Conteúdos

Descrição

Instalação

Uso

Tecnologias

Como contribuir

Autor

Observações

📘 Descrição
<details> <summary><b>Resumo</b></summary> O **Assistente Financeiro com Supabase** é um projeto desenvolvido em **n8n** que integra **IA Google Gemini**, **Supabase** e **Telegram** para automatizar o controle financeiro empresarial. Ele elimina o uso de planilhas manuais e oferece interação via chat, permitindo: - Adicionar, editar e remover despesas pelo Telegram; - Classificação automática de categorias via IA; - Relatórios de gastos em tempo real; - Integração direta com banco de dados Supabase. </details>
⚙️ Instalação
<details> <summary><b>Passo a passo (Linux / macOS / Windows)</b></summary>

Clone o repositório:

git clone {REPO_URL}.git
cd N8N_Criando_um_assistente_financeiro_com_o_Supabase


Instale o n8n globalmente:

npm install n8n -g


Inicie o n8n:

n8n start


Importe o fluxo:

Arquivo: Assistente_Financeiro.json

Local: Interface do n8n (via Import Workflow)

Configure as credenciais:

Telegram Bot Token

Supabase URL e API Key

Google Gemini API Key

</details>
🖥️ Uso
<details> <summary><b>Como usar o projeto</b></summary>

Execute o n8n e ative o fluxo do Assistente Financeiro.

Interaja com o bot no Telegram:

/adicionar 100 almoço equipe

/listar

/total mês

As mensagens são processadas pela IA (Gemini), classificadas e gravadas no Supabase.

O sistema responde em tempo real com feedback e relatórios automáticos.

</details> <div align="center" style="overflow-x:auto; white-space:nowrap; padding:10px;"> <a href="{REPO_URL}/blob/main/imagem/02.png" target="_blank" style="background:#0b5fff;color:#fff;padding:8px 14px;border-radius:8px; text-decoration:none;font-weight:600;display:inline-block;margin:4px;">📷 02</a> <a href="{REPO_URL}/blob/main/imagem/03.png" target="_blank" style="background:#0b5fff;color:#fff;padding:8px 14px;border-radius:8px; text-decoration:none;font-weight:600;display:inline-block;margin:4px;">📷 03</a> </div>
🛠️ Tecnologias
<details> <summary><b>Stack principal</b></summary>

n8n — Plataforma de automação

Google Gemini — IA de interpretação e categorização

Supabase — Banco de dados e autenticação

Telegram Bot API — Comunicação com o usuário

CSV / Excel — Base auxiliar de despesas

</details>
🤝 Como contribuir
<details> <summary><b>Guia rápido</b></summary>

Faça um fork do repositório e crie uma nova branch:

git checkout -b feature/nova-feature


Realize suas alterações:

git commit -m "feat: adiciona nova automação financeira"
git push origin feature/nova-feature


Abra um Pull Request explicando sua contribuição.

</details>
👤 Autor
<details> <summary><b>Contatos</b></summary> <p> <b>Rafael Bittencourt de Araújo</b> — desenvolvedor do projeto.<br> GitHub: <a href="https://github.com/Rafael072187" target="_blank">github.com/Rafael072187</a> </p> </details>
📝 Observações

✅ Ideal para empresas que buscam automatizar o controle financeiro.
🔧 Pode ser expandido para dashboards e integração com ERPs.
⚠️ Proteja suas credenciais antes de implantar publicamente.

<p align="center" style="margin-top:18px;"> <a href="{REPO_URL}" style="background:#0b5fff;color:#fff;padding:10px 18px; border-radius:8px;text-decoration:none;font-weight:600;"> Ver repositório </a> </p> <p align="center" style="margin-top:14px;color:#666;"> Estrutura gerada automaticamente com base no repositório analisado. </p> ```
