# STATUS — testes-effort-padaria

**Objetivo:** medir se o `effort` (`low`/`medium`/`high`) muda tokens, tempo e acerto dos modelos de IA num desafio de raciocínio sem código.
**Partes interessadas:** Gelvazio (decide e aceita) · IAs executam as rodadas.
**Links:** [Regras](../AGENTS.md) · [Etapas](etapas/) · [Concluídas](task_complete.md)

Legenda: ⬜ Pendente · 🔄 Em progresso · ✅ Concluído · ⛔ Bloqueado · 👀 Aguardando o usuário

## 📌 Tarefas

| Tarefa | Título | Prioridade | Modelo | Depende de | Status | Em uso por | Etapa |
|---|---|---|---|---|---|---|---|
| **EFFORT-PADARIA** | **Testar `low`/`medium`/`high` em todos os modelos com o projeto da padaria** | 🟠 Alta | — | Nenhuma | 🔄 Em execução | — (não reservável) | [ETAPA-001](etapas/ETAPA-001-79b1fa8f-EFFORT-PADARIA.md) |
| EFFORT-PADARIA.6 | Gemini Pro: 3 níveis de raciocínio | 🟠 Alta | MEDIO · só Gemini CLI · effort medium | EFFORT-PADARIA.2 | ⬜ Pendente | — | [ETAPA-001](etapas/ETAPA-001-79b1fa8f-EFFORT-PADARIA.md) |
| EFFORT-PADARIA.7 | DeepSeek (raciocínio): 3 níveis | 🟠 Alta | MEDIO · só DeepSeek · effort medium | EFFORT-PADARIA.2 | ⬜ Pendente | — | [ETAPA-001](etapas/ETAPA-001-79b1fa8f-EFFORT-PADARIA.md) |

## 🧭 Frentes de trabalho

| Frente | Tarefa (etapa) | Situação | Atualizado em |
|---|---|---|---|

## Escopo do projeto

Só dados (`dados/`) e enunciado (`DESAFIO.md`). O gabarito fica fora deste projeto, em `C:/fontes/rules-ai/gabaritos/EFFORT-PADARIA.md`.

## 🗂️ Etapas

| Etapa | Tarefa | Situação |
|---|---|---|
| [ETAPA-001](etapas/ETAPA-001-79b1fa8f-EFFORT-PADARIA.md) | EFFORT-PADARIA | 🔄 faltam .6 (Gemini) e .7 (DeepSeek) |

## Riscos

| Risco | Plano B |
|---|---|
| Modelo testado ler o quadro `tasks/` e não só o desafio | a rodada manda ler só `dados/` e `DESAFIO.md`; o gabarito nunca fica aqui |

## Bloqueios gerais

| Bloqueio | O que destrava |
|---|---|

## Registro de decisões

| Data | Decisão | Quem | Por quê |
|---|---|---|---|
| 2026-10-18 | Tarefa EFFORT-PADARIA movida do quadro do `rules-ai` (etapa 003) para este projeto, **sem o gabarito**, que fica em `rules-ai/gabaritos/EFFORT-PADARIA.md` | Usuário (registrado por Claude Code (Opus 5.5)) | "ESTA TAREFA EFFORT-PADARIA, MOVA PARA O PROJETO C:ontes	estes-effort-padaria"; opção "Mover sem o gabarito" |

## Pendências (ficou para depois)

| Data | Pendência | Motivo | Origem |
|---|---|---|---|

## Lições aprendidas

| Data | Lição |
|---|---|
