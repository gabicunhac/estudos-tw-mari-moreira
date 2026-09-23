# Referência das automações

Consulte aqui as opções, os custos e os limites das automações. Para entender quando usar cada opção, veja a [visão geral](visao-geral.md).

## Gatilhos

| Gatilho | Roda quando |
|---|---|
| **Alteração de código** | O código de um repositório muda |
| **Atualização de conteúdo** | Uma página da documentação muda |
| **Integração** | Um evento acontece numa ferramenta integrada. Só no plano Custom |
| **Agendamento personalizado** | Chega o horário que você definiu |

## Modos de atualização

| Modo | O que acontece | Revisão humana |
|---|---|---|
| **Pull request** | O agente abre um PR com as mudanças | Sim |
| **Merge direto** | As mudanças são publicadas na hora | Não |

## Créditos

| Resultado da execução | Custo |
|---|---|
| Atualizou a documentação | 250 créditos |
| Não encontrou nada para atualizar | Sem custo |

## Limites

| Item | Limite |
|---|---|
| Repositórios de contexto por automação | 10 |

---

> [!NOTE]
> **Pendente de validação com engenharia e produto**
> - Se alteração de código roda a cada commit ou só em uma branch específica
> - O que conta como atualização de conteúdo
> - Frequência mínima do agendamento
> - Em quais planos cada gatilho está disponível
> - O que acontece quando os créditos acabam
