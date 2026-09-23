# Estudos de Tech Writing

Exercícios que fiz durante o curso de Tech Writing e IA da Mari Moreira.

Cada oficina tem uma pasta própria com a documentação produzida, no formato usado pela Mintlify (arquivos `.mdx` e navegação no `docs.json`).

## Oficinas

| Oficina | O que foi feito |
|---|---|
| [01 · Documentação do zero com IA](oficina-01-automacoes/visao-geral.mdx) | Seção de documentação da feature Automations, criada a partir de uma thread interna simulada e revisada com o checklist de 8 princípios |

## Oficina 01 · Documentação do zero com IA

**Cenário:** a feature Automations entra no ar em duas semanas e a pessoa de Tech Writing recebe só os insumos crus de engenharia e produto.

**Como a seção foi organizada:** conceito, tarefa e referência ficam em páginas separadas.

- `visao-geral.mdx` explica o que é uma automação, qual gatilho usar e quando escolher merge direto ou pull request
- `criar-automacao.mdx` traz o passo a passo de configuração
- `referencia.mdx` reúne gatilhos, modos, créditos e limites em tabelas

**Revisão com o checklist:** a primeira versão juntava tudo numa página, dizia que toda execução custava 250 créditos (só cobra quando atualiza) e não alertava sobre o risco do merge direto. A versão final corrige esses pontos, separa os tipos de conteúdo e registra dono e momento de revisão em cada página.

**Pendências:** os trechos marcados com `[CONFIRMAR]` são informações que o insumo não trazia e que precisariam ser validadas com engenharia e produto, como o caminho no dashboard, as integrações disponíveis e o que acontece quando os créditos acabam.
