# Visão geral das automações

As automações mantêm a documentação atualizada sem que alguém precise revisar página por página. Um agente acompanha o evento que você escolheu e, quando ele acontece, verifica se alguma página precisa mudar.

Esta página é para quem administra a documentação e precisa decidir **quando** e **como** usar automações.

## Conceitos principais

- **Automação:** a regra que você configura. Ela define o que observar, o que o agente pode ler e como as mudanças são publicadas.
- **Gatilho:** o evento que faz a automação rodar, como uma mudança no código.
- **Execução:** cada vez que a automação roda.
- **Repositórios de contexto:** os repositórios que o agente consulta para decidir o que atualizar. Cada automação aceita até 10.
- **Modo de atualização:** o jeito como a mudança chega na documentação, por pull request ou por merge direto.
- **Créditos:** a forma de cobrança. Só consome créditos a execução que atualiza alguma página.

## Como uma automação funciona

1. O gatilho acontece.
2. O agente lê os repositórios de contexto.
3. O agente decide se alguma página precisa mudar.
4. Se precisar, aplica a mudança pelo modo de atualização escolhido. Se não precisar, a execução termina sem custo.

## Qual gatilho escolher

Escolha pelo evento que deixa a documentação desatualizada. Responda às perguntas na ordem e pare na primeira resposta "sim".

1. **A mudança nasce no código do produto?**
   Use **alteração de código**. Exemplo: um endpoint novo ou um parâmetro que mudou.
2. **A mudança nasce em outra página da documentação?**
   Use **atualização de conteúdo**. Exemplo: manter uma tradução alinhada com a página original.
3. **A mudança nasce numa ferramenta fora do repositório?**
   Use **integração**. Esse gatilho só está disponível no plano Custom.
4. **Nenhuma das opções acima?**
   Use **agendamento personalizado**, que roda em intervalos fixos definidos por você.

> [!TIP]
> Deixe o agendamento como última opção. Com ele, qualquer mudança só chega na documentação na próxima execução marcada.

## Qual modo de atualização escolher

| | Pull request | Merge direto |
|---|---|---|
| **O que acontece** | O agente abre um PR para revisão | A mudança é publicada na hora |
| **Revisão humana** | Sim | Não |
| **Quando usar** | Na maioria dos casos | Só em conteúdo em que um erro publicado não cause problema |

> [!WARNING]
> Com merge direto, ninguém revisa a mudança antes de ela ir para o ar. Em traduções, referência de API e conteúdo para clientes, use sempre pull request.

## Próximos passos

- [Como criar uma automação](criar-automacao.md)
- [Referência das automações](referencia.md)

---

> [!NOTE]
> **Pendente de validação com engenharia e produto**
> - Se o gatilho de atualização de conteúdo cobre o caso das traduções
> - Quais ferramentas estão disponíveis no gatilho de integração
