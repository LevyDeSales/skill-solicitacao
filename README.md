# Solicitação

Uma skill para quando você pensa “vou ter que pedir ajuda a alguém”. O agente procura a resposta nas fontes disponíveis. Se encontrar, responde com o que você precisa para seguir. Se depender de outra pessoa, prepara uma solicitação clara, pronta para enviar.

## Como usar

Instale em um agente compatível usando a CLI `skills`.

```sh
npx skills add LevyDeSales/skill-solicitacao --skill solicitacao
```

Depois, conte o que você quer conseguir, do seu jeito.

> Use a skill solicitação. Preciso ver as despesas do mês e não sei onde fica o painel. Acho que vou ter que falar com o financeiro.

Se o agente encontrar o painel no guia da equipe, você recebe o link. Se você já tem o link e aparece “acesso negado”, ele procura o procedimento de liberação e pode preparar um pedido como este.

> **Liberar acesso de leitura ao painel de despesas**  
> Preciso consultar as despesas do mês. Ao abrir o painel pelo link do guia da equipe, recebo “acesso negado”. Vocês conseguem liberar a consulta para a minha conta?

## Quando usar

- **Para resolver uma dúvida.** Encontrar um recurso, entender uma função do software ou consultar um erro de build.
- **Para esclarecer um pedido.** Peça um *grilling* e o agente faz perguntas curtas sobre as escolhas que mudam o encaminhamento.
- **Para redigir uma issue.** Envie um relato, ata ou log. O agente organiza o pedido com os detalhes relevantes para quem vai recebê-lo. Você pode copiar o texto ou pedir que ele registre a issue no destino indicado.

A entrevista se inspira no [Grilling de Matt Pocock](https://github.com/mattpocock/skills/blob/main/skills/productivity/grilling/SKILL.md), e o formato da issue segue o [GitHub Issue Creator da Microsoft](https://github.com/microsoft/skills/blob/main/.github/skills/github-issue-creator/SKILL.md). As instruções completas e as demais referências estão no [SKILL.md](skills/solicitacao/SKILL.md).
