# Como eu fiz o app de compras da minha empresa com o Claude Code

Não sou programador. Sou dono curioso. Meu CMV médio caiu de 34% pra 30% depois desse app. Esse é o caminho que eu usei.

## 1. Escolha a dor certa
Comece por uma coisa só, a que mais dói hoje. No meu caso foi compras: lista montada na mão, pedido no chute, preço que subia sem ninguém ver.

Antes de abrir o Claude Code, anote:
- Quais sistemas você já usa (vendas, compras, estoque, financeiro).
- De quais fornecedores você compra e como faz o pedido hoje.
- Quem da equipe vai usar o app e em que momento do dia.

## 2. Prompt pra começar
Cole no Claude Code e troque o que está entre colchetes.

```
Você é um desenvolvedor sênior e vai construir comigo um app de compras pra minha empresa. Eu não sei programar, então explique tudo em português simples.

Contexto do negócio:
- Tipo de negócio: [ex.: pizzaria com 2 unidades]
- Sistema de vendas: [nome], com API: [sim ou não sei]
- Sistema de compras: [nome], com API: [sim ou não sei]
- Fornecedores principais: [nomes e como faço o pedido hoje]
- Quem vai usar: [cargos] pelo celular

O app precisa:
1. Puxar as vendas por API e calcular quanto de cada insumo saiu na semana.
2. Receber a contagem de estoque pelo celular, rápida de fazer em pé na cozinha.
3. Sugerir o pedido de compra de cada fornecedor a partir de estoque e vendas.
4. Comparar o preço de cada item com o mês anterior e me avisar quando subir.
5. Deixar uma pessoa da equipe revisar e enviar o pedido.

Como quero trabalhar:
- Antes de escrever código, me faça as perguntas que faltarem e me proponha como montar (onde roda, onde guarda os dados, como cada um faz login).
- Depois construa uma parte de cada vez, na ordem que fizer mais sentido.
- No fim de cada parte, me diga exatamente como testar.
```

Responda as perguntas dele com calma. Quanto mais você explicar como funciona no dia a dia, melhor fica.

## 3. Uma parte de cada vez
A ordem que funcionou pra mim:
1. Cadastro dos itens (nome, unidade, estoque mínimo, fornecedor).
2. Tela de contagem no celular.
3. Conexão com o sistema de vendas.
4. Pedido sugerido por fornecedor.
5. Comparação de preço com o mês anterior.
6. Acesso da equipe, cada um com o seu login.

Depois de cada parte, teste você mesmo antes de seguir:

```
Me explica, passo a passo, como eu testo essa parte agora. Se der erro, eu te mando o print.
```

## 4. Regra que faz o app funcionar
O app só presta se a contagem for feita. Combine dias fixos com a equipe e defina quem é responsável. Sem contagem, não sai pedido.

## 5. Quando der erro
Não tente entender o código. Mande o que aconteceu:

```
Fiz [o que eu fiz] e aconteceu [o que apareceu na tela]. Esperava [o que deveria acontecer]. Corrige e me diz como testar de novo.
```

## 6. Depois de compras
Com uma parte funcionando, vá pra próxima: financeiro, vendas, clientes. Uma de cada vez.

Feito por @caio.panazio
