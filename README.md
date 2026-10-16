# 🥖 Padaria Pão Nosso — projeto de teste de esforço (`effort`)

Projeto **simples e fictício** usado só para medir se o esforço de raciocínio (`effort`: `low`,
`medium`, `high`) muda o resultado dos modelos de IA. Não é um sistema: não tem código, banco nem
tela. Tem só os dados da padaria e um desafio de planejamento.

Tarefa no quadro global: `EFFORT-PADARIA` em `C:/fontes/rules-ai/tasks/STATUS.md` (etapa 003).

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
2. Mandar ler **só esta pasta** e responder o `DESAFIO.md` **sem executar código**.
3. Anotar tokens, tempo e a resposta na etapa 003 do `rules-ai`, que guarda o gabarito.
