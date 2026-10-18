# AGENTS.md — testes-effort-padaria

<!-- rules-ai:global -->
> 🌐 **Regras globais:** além das regras deste arquivo, valem as regras globais de
> `C:/fontes/rules-ai` (`regras/*.md`, entregues a cada IA pelo arquivo global dela). Em divergência,
> a regra deste projeto prevalece, e o usuário decide o que fazer com cada divergência
> (`rules-ai/CONFLITOS.md`). Ao finalizar uma tarefa: commit + push.

## Regras deste projeto

- Projeto de **teste de esforço** (`effort`): só dados (`dados/`) e enunciado (`DESAFIO.md`).
- ⛔ Quem responde o desafio **não executa código** (Python, Node, planilha, calculadora de shell):
  resolve raciocinando e mostra as contas.
- ⛔ Não mudar os números de `dados/` nem o `DESAFIO.md` depois que as rodadas começarem: o
  gabarito (`C:/fontes/rules-ai/gabaritos/EFFORT-PADARIA.md`) depende deles.
- O gabarito **não** fica nesta pasta. Ele fica em `C:/fontes/rules-ai/gabaritos/EFFORT-PADARIA.md`.
- Quadro de tarefas: `tasks/STATUS.md` (+ `task_complete.md` e `etapas/`). Quem responde o
  desafio **não lê** `tasks/`: só `dados/` e `DESAFIO.md`.

<!-- rules-local:inicio -->
## Regras globais (rules-local)

No início da sessão, antes do primeiro pedido, rode na raiz do projeto:

```
node rules-local/sessao.mjs
```

Leia as linhas que começam com `rules-local:`:

- `versão igual`, `sem acesso`, `nuvem inconsistente` ou `outra sessão`: siga o pedido.
- `DISPARAR A SINCRONIZAÇÃO DE TASKS`: faça a sincronização de tasks antes do pedido, como manda
  `rules-local/regras/rules-local.md`.

Não edite a pasta `rules-local/` à mão. Ela é gerada pelo script.
<!-- rules-local:fim -->
