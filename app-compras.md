# Como eu fiz o app de compras da minha empresa com o Claude Code

Não sou programador. Sou dono curioso. Esse é o caminho que eu usei, do zero até a equipe usar no celular.

## 1. Escolha a dor certa
Comece por uma coisa só, a que mais dói hoje. No meu caso foi compras: contagem de estoque em papel, lista montada na mão, preço que subia sem ninguém ver.

Responda pra você mesmo:
- O que eu faço hoje numa planilha ou no papel?
- Quem usa isso na equipe?
- O que dá errado quando ninguém faz?

## 2. Prompt pra começar
Cole no Claude Code e troque o que está entre colchetes.

```
Quero um app simples pra minha empresa, que a equipe abra no celular por um link.
Hoje eu faço isso numa planilha: [descreva o que a planilha faz, quem preenche e quando].
Me faça perguntas antes de começar.
Depois monte uma função de cada vez e me diga como testar.
```

Responda as perguntas que ele fizer com calma. Quanto mais você explicar como funciona no dia a dia, melhor fica.

## 3. Uma função de cada vez
Não peça tudo de uma vez. A ordem que funcionou pra mim:
1. Cadastro dos itens (nome, unidade, estoque mínimo, fornecedor).
2. Tela de contagem, simples de usar no celular.
3. Pedido de compra sugerido a partir da contagem e das vendas da semana (quem compra confere e fecha).
4. Comparação do preço de cada item com o que você pagava antes.
5. Acesso da equipe por link, cada um com o seu login.

Depois de cada função, teste você mesmo antes de seguir:

```
Me explica, passo a passo, como eu testo essa função agora. Se algo der erro, eu te mando o print.
```

## 4. Regra que faz o app funcionar
O app só presta se a contagem for feita. Combine dias fixos de contagem com a equipe e defina quem é responsável. Sem contagem, não sai sugestão de pedido.

## 5. Quando der erro
Não tente entender o código. Mande o que aconteceu:

```
Fiz [o que eu fiz] e aconteceu [o que apareceu na tela]. Esperava [o que deveria acontecer]. Corrige e me diz como testar de novo.
```

## 6. Depois de compras
Com uma parte funcionando, vá pra próxima: financeiro, vendas, clientes. Uma de cada vez.

Feito por @caio.panazio
