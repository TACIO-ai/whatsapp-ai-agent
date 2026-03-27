# Como funciona o WhatsApp AI Agent

## Fluxo completo de uma conversa
```
Cliente envia mensagem
        ↓
Webhook recebe no n8n
        ↓
Histórico da conversa é montado
        ↓
OpenAI processa com o system prompt
        ↓
Resposta enviada ao cliente
        ↓
É complexo? → Escalona para humano
É simples?  → Continua automático
```

## Personalização por negócio

Edite apenas o arquivo `prompts/system-prompt.txt` com:
- Nome e segmento da empresa
- Horário de atendimento
- Perguntas frequentes do seu negócio

Pronto — o agente já está treinado para o novo contexto.

## Demo

> 📹 GIF de demonstração em breve.

## Tempo médio de implantação

| Etapa | Tempo estimado |
|---|---|
| Configurar n8n + credenciais | ~30 min |
| Editar system prompt | ~20 min |
| Testes e ajustes | ~30 min |
| **Total** | **~1h30** |
```
