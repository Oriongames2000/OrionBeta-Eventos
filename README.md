# OrionBeta — Calendário de Eventos (público)

Esse repositório existe só pra hospedar `calendario.json` — os dados de
eventos ativos/próximos que a aba **Eventos → Calendário** do OrionBeta
lê, sem precisar de bot ou token do Discord.

O arquivo é gerado e publicado automaticamente pela instância que tem o
bot do Discord configurado (lê o canal-espelho, extrai as mensagens
marcadas com `[EVENTO] ...` e sobe o resultado aqui).

## Como usar (quem não tem bot do Discord)

Na aba **Eventos → Configuração** do OrionBeta, cole no campo
**"URL pública do calendário (JSON)"**:

```
https://raw.githubusercontent.com/Oriongames2000/OrionBeta-Eventos/main/calendario.json
```

Clique em "Atualizar agora" — o Calendário passa a mostrar o mesmo evento
ativo/próximos que a instância principal publicou aqui.
