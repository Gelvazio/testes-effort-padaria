# Regras da padaria

## Produção

1. **Reserva:** do pão francês produz-se o total pedido (clientes + balcão) **mais 10%**,
   arredondando a reserva para cima. Os outros produtos não têm reserva.
2. **Fornadas completas:** cada produto é feito em fornadas inteiras
   (fornadas = quantidade a produzir ÷ unidades por fornada, **arredondando para cima**). As
   unidades que sobram não são vendidas no sábado.
3. O consumo de ingredientes é calculado sobre **todas as unidades produzidas** (fornadas
   completas), não só sobre as pedidas.
4. **Ovos:** some o consumo de ovos de todos os produtos e arredonde o total para cima.

## Compras

5. Depois da produção, cada ingrediente precisa ficar com pelo menos o **estoque mínimo**.
6. Falta = consumo + estoque mínimo − estoque atual. Se a falta for positiva, compra-se o
   **menor número de pacotes inteiros** que a cubra; se for zero ou negativa, não se compra.

## Faturamento

7. Cada cliente paga as unidades **pedidas** pelo preço do cardápio (valor bruto).
8. **Descontos** (só para clientes; o balcão não tem desconto):
   - valor bruto a partir de R$ 500,00 → 8%;
   - valor bruto a partir de R$ 200,00 e abaixo de R$ 500,00 → 5%;
   - Escola Aurora tem convênio de **10%**; vale o **maior** desconto, sem somar.
9. O balcão fatura o valor das unidades **previstas** no pedido "Balcão".
10. Faturamento líquido total = soma dos valores líquidos de todos os clientes + balcão.

## Forno

11. A padaria tem **2 fornos iguais**. Cada fornada ocupa **um** forno pelo seu tempo inteiro;
    fornadas não se dividem e um forno assa uma fornada por vez.
12. A jornada de cada forno no sábado é de **4 horas (240 min)**.
13. Pergunta-se o **menor tempo possível** para assar todas as fornadas distribuindo-as entre os
    dois fornos (o tempo do forno que terminar por último).
