# 🤖 WhatsApp AI Agent — Atendente Virtual com Inteligência Artificial

Automação completa de atendimento ao cliente via WhatsApp usando IA. 
O agente responde mensagens 24/7, entende o contexto do negócio e 
escalona para um atendente humano quando necessário.

---

## 🎯 Problema que resolve

Pequenas e médias empresas perdem tempo respondendo manualmente 
as mesmas perguntas repetidas todos os dias. Este agente automatiza 
esse processo, liberando a equipe para focar no que realmente importa.

**Resultado:** até 80% de redução no volume de mensagens manuais.

---

## ⚙️ Como funciona

1. Cliente envia mensagem no WhatsApp
2. n8n recebe via webhook e processa
3. OpenAI gera resposta com contexto do negócio
4. Resposta é enviada automaticamente ao cliente
5. Se necessário, escalona para atendente humano

---

## 🛠️ Stack

| Ferramenta | Função |
|---|---|
| n8n | Orquestrador do fluxo de automação |
| OpenAI API (GPT-4o mini) | Geração de respostas inteligentes |
| WhatsApp Business API | Envio e recebimento de mensagens |
| Python | Scripts auxiliares e processamento |
| Webhook | Integração em tempo real |

---

## 💼 Casos de uso

- Clínicas e consultórios (agendamentos, dúvidas)
- Lojas e e-commerces (status de pedido, produtos)
- Restaurantes (cardápio, reservas, delivery)
- Imobiliárias (informações sobre imóveis)
- Qualquer negócio com alto volume de mensagens repetitivas

---

## 📁 Estrutura do projeto
```
whatsapp-ai-agent/
├── README.md
├── n8n-workflow.json       # Fluxo exportado — importe direto no n8n
├── prompts/
│   └── system-prompt.txt  # Prompt base customizável por negócio
└── docs/
    └── demo.gif            # Demonstração do agente em ação
```

---

## 🚀 Como usar

1. Clone o repositório
2. Importe `n8n-workflow.json` no seu n8n
3. Configure suas credenciais (OpenAI API Key + WhatsApp API)
4. Edite `prompts/system-prompt.txt` com informações do seu negócio
5. Ative o fluxo — pronto!

---

## 📬 Contato

Precisa desse agente configurado para o seu negócio?

**[Entre em contato via Workana](https://www.workana.com/freelancer/31269f99b35f5687270b4fce3048c7a6)**
