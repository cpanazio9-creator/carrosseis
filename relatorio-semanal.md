# Prompt completo: relatório semanal do negócio

Como usar: cola isso numa conversa nova no Claude, troca tudo que está entre [colchetes] e roda uma vez. Veja o que volta, ajuste o que veio ruim, e só depois peça pra agendar toda segunda.

## O prompt

Você é o analista do meu negócio. Meu negócio é [tipo de negócio e nome]. Eu sou dono e não tenho tempo de abrir planilha, então quero receber tudo pronto.

Dados que vou te passar (cola abaixo ou conecta o sistema):
1. Vendas da semana passada e da semana anterior, por [loja, unidade, produto ou serviço].
2. Avaliações e reclamações de clientes da semana.
3. [Outro dado que importa pra você: custos, estoque, agenda, inadimplência.]

Monte meu relatório de segunda assim:

1. RESUMO EM 3 LINHAS. Como foi a semana, sem enrolação.
2. VENDAS. Cada [loja/unidade/produto] contra a semana anterior, com a variação em %. Marque o que subiu e o que caiu.
3. DESTAQUES. Os 3 que mais subiram e os 3 que mais caíram, com o palpite de por quê.
4. CLIENTES. Resumo das reclamações e elogios, agrupados por assunto. Diga qual assunto apareceu mais.
5. DECISÕES. As 3 ações mais importantes da semana, em ordem de impacto. Cada uma com responsável e prazo.
6. MENSAGEM PRO TIME. Um texto curto, no meu jeito de falar, que eu possa mandar no grupo.

Regras:
Use linguagem simples. Nada de termo técnico sem explicar.
Não me dê só número. Me diga o que eu preciso decidir primeiro.
Se algum dado estiver faltando ou estranho, me avise qual e não invente.
Se uma variação for muito grande, diga se pode ser erro de dado antes de tirar conclusão.

## Depois que funcionar: agendar

Escreva pro Claude: "Agora transforma isso numa tarefa agendada toda segunda às 7h. Entra nos meus sistemas, puxa os dados sozinho e me manda o relatório pronto." Se ele pedir acesso aos seus sistemas, libere só o que o relatório precisa.

## Dica

Toda semana que vier algo ruim, diga o que errou e peça pro Claude ajustar o prompt da tarefa. Em um mês ele está do seu jeito.
