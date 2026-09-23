# Como criar uma automação

Siga este passo a passo para configurar sua primeira automação. No final, ela vai rodar sozinha sempre que o gatilho escolhido acontecer.

Se ainda não sabe qual gatilho ou modo de atualização usar, comece pela [visão geral](visao-geral.md).

## Antes de começar

Tenha em mãos:

- **Acesso ao dashboard** com permissão para criar automações.
- **Créditos na conta.** Cada execução que atualiza a documentação usa 250 créditos.
- **O gatilho definido.** Veja [Qual gatilho escolher](visao-geral.md#qual-gatilho-escolher).
- **Os repositórios que o agente vai consultar.** Você pode escolher até 10.

## Passo a passo

### 1. Abra a área de automações

No dashboard, entre na área de automações e comece uma nova.

### 2. Escolha o gatilho

Selecione o evento que vai fazer a automação rodar.

### 3. Adicione os repositórios de contexto

Selecione os repositórios que o agente pode consultar para decidir o que atualizar. O limite é de 10 por automação.

### 4. Escolha o modo de atualização

- **Pull request:** para revisar cada mudança antes de publicar.
- **Merge direto:** para publicar sem revisão.

Se for sua primeira automação, escolha pull request.

### 5. Salve e acompanhe a primeira execução

Salve a automação. Quando o gatilho acontecer, confira se o resultado ficou como esperado.

## Depois de criar

- **No modo pull request**, revise e aprove os PRs abertos pelo agente no repositório da documentação.
- **No modo merge direto**, acompanhe as primeiras execuções de perto, já que as mudanças vão para o ar sem revisão.

---

> [!NOTE]
> **Pendente de validação com engenharia e produto**
> - Caminho exato no dashboard e nome dos botões
> - Permissão necessária para criar automações
> - Se os repositórios de contexto precisam estar conectados antes
> - Onde ver o histórico de execuções
> - Como editar, pausar ou excluir uma automação
