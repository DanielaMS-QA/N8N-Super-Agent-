# N8N Super Agent - Chat Inteligente com IA

## 🤖 Descrição do Projeto

Este projeto implementa um **super agente de suporte** usando N8N que combina chat inteligente, processamento de dados e integração com Google Sheets. O agente é educado, engraçado e utiliza emojis para humanizar a conversa.

**Link do Agente**: (https://silvadannie.app.n8n.cloud/workflow/A8m3EdjbIkP9d5Zd)

## 🚀 Funcionalidades

- ✅ **Chat Inteligente** - Responde perguntas com IA (Groq llama-3.1-8b-instant)
- ✅ **Integração Google Sheets** - Salva conversas automaticamente
- ✅ **Ferramentas Avançadas** - Calculadora, Wikipedia, Memória
- ✅ **Interface Amigável** - Mensagem inicial personalizada
- ✅ **Processamento de Dados** - Organiza Id_Conversa e Mensagem
- ✅ **Memória de Conversa** - Lembra do contexto anterior

## 🛠️ Tecnologias Utilizadas

- **N8N** - Plataforma de automação de workflow
- **Groq AI** - Modelo llama-3.1-8b-instant para respostas inteligentes
- **Google Sheets API** - Integração com planilhas
- **LangChain** - Framework para aplicações de IA
- **JavaScript/JSON** - Lógica de processamento

## 🔗 Links do Projeto

- **Agente Virtual**: (https://silvadannie.app.n8n.cloud/workflow/A8m3EdjbIkP9d5Zd)
- **N8N Cloud**: (https://silvadannie.app.n8n.cloud)
- **Google Sheets**: (https://docs.google.com/spreadsheets/d/1uv2kYRPd3wfONMb3_UbTsrGIZRevsIrw95PaeYKJvrA/edit#gid=0)

## 📁 Estrutura do Projeto

N8N-Super-Agent/
├── workflows/
│   └── n8n-super-agent-workflow.json
├── docs/
│   ├── setup-guide.md
│   └── features-guide.md
├── screenshots/
│   ├── workflow-overview.png
│   └── chat-interface.png
├── README.md
└── .gitignore

## 🔄 Fluxo de Trabalho

Chat Message → Process Data → Google Sheets → AI Agent → Response

### Detalhes do Fluxo:
1. **Trigger**: "When chat message received" (mensagem inicial personalizada)
2. **Processamento**: "Edit Fields" (organiza Id_Conversa e Mensagem)
3. **Armazenamento**: "Append row in sheet" (salva no Google Sheets)
4. **IA**: "AI Agent" com Groq llama-3.1-8b-instant
5. **Ferramentas**: Calculadora, Wikipedia, Memória
6. **Resposta**: Resposta inteligente e humanizada

## 🎯 Como Usar

### Acessar o agente:
1. **Via link direto**: (https://silvadannie.app.n8n.cloud/workflow/A8m3EdjbIkP9d5Zd)
2. **Mensagem inicial**: "Olá. Tudo bem?👋 Como posso te ajudar hoje?"

### Exemplos de uso:
- **Pergunta**: "Como posso calcular 2+2?"
- **Resposta**: O agente usa a calculadora e responde com emojis
- **Pergunta**: "O que é Python?"
- **Resposta**: O agente consulta a Wikipedia e explica de forma educada

## 📊 Dados Processados

O agente processa e armazena:
- **Id_Conversa**: ID único da sessão (`{{ $json.sessionId }}`)
- **Mensagem**: Conteúdo da mensagem (`{{ $json.chatInput }}`)
- **Timestamp**: Data e hora da conversa
- **Resposta**: Resposta gerada pela IA

## 🔧 Configuração Avançada

### Personalizar o agente:
- **Mensagem inicial**: Edite o campo `initialMessages`
- **Sistema de IA**: Modifique o `systemMessage`
- **Ferramentas**: Adicione/remova ferramentas (Calculator, Wikipedia, etc.)

### Integrar com outros sistemas:
- **APIs externas**: Adicione novos nós de API
- **Bancos de dados**: Conecte com PostgreSQL, MongoDB, etc.
- **Notificações**: Integre com Slack, Email, WhatsApp

## 🧠 Funcionalidades da IA

### Modelo Groq:
- **llama-3.1-8b-instant** - Respostas rápidas e inteligentes
- **Memória de conversa** - Lembra do contexto anterior
- **Ferramentas integradas** - Calculadora e Wikipedia

### Personalidade do agente:
- **Educado** - Sempre respeitoso
- **Engraçado** - Usa humor apropriado
- **Humanizado** - Utiliza emojis e linguagem natural

## 🛠️ Instalação e Configuração

### Pré-requisitos
- Conta N8N (cloud ou self-hosted)
- Conta Groq (para IA)
- Conta Google com acesso ao Google Sheets
- Navegador web

### Passos de configuração

1. **Importe o workflow:**
   - Acesse seu N8N
   - Clique em "Import from file"
   - Selecione o arquivo `n8n-super-agent-workflow.json`

2. **Configure as credenciais:**
   - **Groq API** - Para o modelo de IA
   - **Google Sheets API** - Para integração com planilhas

3. **Ative o workflow:**
   - Clique no toggle "Inactive" para "Active"



## 🤝 Contribuição

1. Faça um Fork do projeto
2. Crie uma branch para sua feature
3. Commit suas mudanças
4. Push para a branch
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT.

## 👨‍💻 Autor

**Seu Nome**
- GitHub: DanielaMS-QA (https://github.com/DanielaMS-QA/N8N-Super-Agent-/edit/main/README.md)
- N8N: silvadannie (https://silvadannie.app.n8n.cloud)

## 📞 Contato 55 (11) 99336 5375

- Email: danielasilva3251@gmail.com

## 🙏 Agradecimentos

- **N8N** pela plataforma de automação
- **Groq** pelo modelo de IA
- **Google Sheets** pela integração
- **LangChain** pelo framework de IA
- **Nocode StartUP** pela instrução

---

⭐ **Se este projeto foi útil para você, considere dar uma estrela!**
