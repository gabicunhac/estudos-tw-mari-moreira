# Technical Writer e Inteligência Artificial

Este repositório reúne os exercícios que fiz no curso Technical Writer e Inteligência Artificial, da Escola de Conteúdo, com a Mari Moreira.

Cada dia do curso tem uma pasta com a documentação produzida. As páginas estão em Markdown para ficarem legíveis direto no GitHub, e o `docs.json` organiza a navegação caso o conteúdo seja publicado na Mintlify.

## Conteúdo

| Dia | Exercício | Pasta |
|---|---|---|
| 1 | Documentação do zero com IA | [dia-1-documentacao-do-zero-com-ia](dia-1-documentacao-do-zero-com-ia) |
| 2 | Em breve | |

## Dia 1 · Documentação do zero com IA

**Cenário:** a feature Automations entra no ar em duas semanas e a pessoa de Tech Writing recebe só uma thread crua com as informações de engenharia e produto. O público da documentação são TWs e devs que administram a doc.

### Páginas

| Página | Tipo | Para que serve |
|---|---|---|
| [Visão geral das automações](dia-1-documentacao-do-zero-com-ia/visao-geral.md) | Conceito | Entender o que é uma automação e escolher gatilho e modo de atualização |
| [Como criar uma automação](dia-1-documentacao-do-zero-com-ia/criar-automacao.md) | Tarefa | Configurar uma automação passo a passo |
| [Referência das automações](dia-1-documentacao-do-zero-com-ia/referencia.md) | Referência | Consultar gatilhos, modos, créditos e limites |

### Revisão com o checklist de 8 princípios

A primeira versão juntava tudo numa página, dizia que toda execução custava 250 créditos (só cobra quando atualiza), não alertava sobre o risco do merge direto e não tinha dono nem momento de revisão definidos.

### Revisão com os erros comuns da IA

| Erro comum | O que aparecia no texto | O que mudou |
|---|---|---|
| Enche linguiça | Frase de abertura com cara de marketing e explicações que só repetiam o óbvio | Cortei o que não ajudava a pessoa a decidir ou agir |
| Usa jargão sem definir | Gatilho, execução e repositórios de contexto apareciam sem explicação | A visão geral abre com os conceitos principais definidos |
| Mistura os tipos | Conceito, tarefa e referência na mesma página | Três páginas, uma para cada tipo |
| Lista em vez de orientar | Os quatro gatilhos lado a lado numa tabela, sem dizer qual escolher | Perguntas em ordem que levam ao gatilho certo, com agendamento como última opção |

Também tirei duas afirmações que o insumo não sustentava: que os repositórios precisam estar conectados antes e que adicionar contexto demais causa mudanças fora do esperado.

### Pendências

Cada página termina com uma lista do que ainda precisa ser validado com engenharia e produto, como o caminho no dashboard, as integrações disponíveis e o que acontece quando os créditos acabam.

### Manutenção

| Página | Dono | Revisar quando |
|---|---|---|
| Visão geral | Tech Writing | A feature sair do beta ou um gatilho novo for lançado |
| Como criar uma automação | Tech Writing | O fluxo do dashboard mudar |
| Referência | Tech Writing | Preço, limites ou planos mudarem |
