# Technical Writer e Inteligência Artificial

Exercícios que fiz no curso Technical Writer e Inteligência Artificial, da Escola de Conteúdo, com a Mari Moreira.

Cada dia do curso tem uma pasta com a documentação produzida no formato da Mintlify: páginas em `.mdx` e a navegação no `docs.json`.

## Conteúdo

| Dia | Exercício | Pasta |
|---|---|---|
| 1 | Documentação do zero com IA | [dia-1-documentacao-do-zero-com-ia](dia-1-documentacao-do-zero-com-ia) |
| 2 | Em breve | |

## Dia 1 · Documentação do zero com IA

**Cenário:** a feature Automations entra no ar em duas semanas e a pessoa de Tech Writing recebe só uma thread crua com as informações de engenharia e produto. O público da documentação são TWs e devs que administram a doc.

**Como a seção foi organizada:** conceito, tarefa e referência ficam em páginas separadas, porque cada uma é lida num momento diferente.

- `visao-geral.mdx` explica o que é uma automação e ajuda a escolher o gatilho e o modo de atualização
- `criar-automacao.mdx` traz o passo a passo de configuração
- `referencia.mdx` reúne gatilhos, modos, créditos e limites em tabelas

### Revisão com o checklist de 8 princípios

A primeira versão juntava tudo numa página, dizia que toda execução custava 250 créditos (só cobra quando atualiza), não alertava sobre o risco do merge direto e não tinha dono nem momento de revisão definidos.

### Revisão com os erros comuns da IA

| Erro comum | O que aparecia no texto | O que mudou |
|---|---|---|
| Enche linguiça | Frase de abertura com cara de marketing e explicações que só repetiam o óbvio | Cortei o que não ajudava a pessoa a decidir ou agir |
| Usa jargão sem definir | Gatilho, execução e repositórios de contexto apareciam sem explicação | Cada termo é definido na primeira vez em que aparece |
| Mistura os tipos | Conceito, tarefa e referência na mesma página | Três páginas, uma para cada tipo |
| Lista em vez de orientar | Os quatro gatilhos lado a lado numa tabela, sem dizer qual escolher | Perguntas que levam ao gatilho certo, com agendamento como última opção |

Nessa rodada também tirei duas afirmações que o insumo não sustentava: que os repositórios precisam estar conectados antes e que adicionar contexto demais causa mudanças fora do esperado. As duas viraram pendência ou saíram do texto.

### Pendências

Os trechos marcados com `[CONFIRMAR]` são informações que o insumo não trazia e que precisariam ser validadas com engenharia e produto, como o caminho no dashboard, as integrações disponíveis e o que acontece quando os créditos acabam.
