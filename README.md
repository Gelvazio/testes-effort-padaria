# 🥖 Padaria Pão Nosso — projeto de teste de esforço (`effort`)

Projeto **simples e fictício** usado só para medir se o esforço de raciocínio (`effort`: `low`,
`medium`, `high`) muda o resultado dos modelos de IA. Não é um sistema: não tem código, banco nem
tela. Tem só os dados da padaria e um desafio de planejamento.

Tarefa no quadro deste projeto: `EFFORT-PADARIA` em `tasks/STATUS.md` (etapa 001). Gabarito fora
do projeto: `C:/fontes/rules-ai/gabaritos/EFFORT-PADARIA.md`.

## Estrutura

| Arquivo | Conteúdo |
|---|---|
| `dados/cardapio.md` | Produtos, receitas por unidade, tamanho da fornada, tempo de forno e preço |
| `dados/estoque.md` | Estoque atual, estoque mínimo e pacotes de compra com preço |
| `dados/pedidos.md` | Pedidos de sábado (clientes e balcão) |
| `dados/regras.md` | Regras de produção, compras, descontos e forno |
| `DESAFIO.md` | As perguntas e o formato obrigatório da resposta |

## Como usar no teste

1. Abrir uma conversa nova com o modelo e o `effort` da rodada.
2. Mandar ler **só `dados/` e `DESAFIO.md`** (não `tasks/`) e responder o `DESAFIO.md` **sem executar código**.
3. Conferir a resposta contra o gabarito do `rules-ai` e anotar tokens, tempo e nota na etapa
   001 deste projeto (`tasks/etapas/`).
