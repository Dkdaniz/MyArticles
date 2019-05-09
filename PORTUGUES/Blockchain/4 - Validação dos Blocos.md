# Validação dos Blocos

Hoje existem dois tipos principais de validação dos blocos, Poof of Work – PoW (Prova de Trabalho) e Proof of Stake – PoS (Prova de Participação) que iremos abordar nesse artigo.

obs: quando usar o termo Minerador, não é de fato uma pessoa que esta mineirando e sim uma maquina (hardware) com poder computacional.

![POS - POW!](/src/pow-pos.png)

### PoW – Proof Of Work

Prova de trabalho é um protocolo usado para evitar ataques a rede, ou seja, se um invasor tentar alterar um bloco ele primeiro terá que realizar a prova de trabalho a todos os blocos anteriores a fim de reorganizar a cadeia de blocos.

A prova de trabalho funciona da seguinte forma, os mineradores tentam resolver um problema matemático muito complexo, mas que por sua vez é muito fácil para verificar se a resposta esta correta ou não, esse problema matemático nunca é o mesmo, obrigando os mineradores a usarem poder computacional para tentarem resolver o mais rápido possível. 
![POW!](/src/1-pow.png)

Após esse processo teremos o minerador vencedor,ou seja, o que conseguiu resolver o problema matemático primeiro que os demais, esse minerador terá o direito de validar o bloco atual e processa-lo para a rede, depois de validar ele receberá uma recompensa por esse trabalho, que é na própria moeda da rede, ela geralmente é composta por  (Taxas pagas para processamento + recompensa da rede pelo trabalho).

![POW!](/src/2-pow.png)

Realizado o processo de validação, a corrida para resolver o próximo problema é reiniciado, aumentando assim a dificuldade.

![POW!](/src/3-pow.png)

### PoS – Proof Of Stake

A definição de Prova de Participação (prova de estaca na tradução livre) afirma que uma pessoa pode mina ou validar operações de bloqueio de acordo com a quantidade de moedas que detém. Isto significa que quanto mais tokens(moedas) pertencer a um mineiro, mais poder de mineração ele ou ela tem.

Ao contrário da prova de trabalho onde minerador deve ceder poder computacional em pró a rede para validação do bloco, na prova de participação o usuário só pode minerar a quantidade proporcional ao valor de tokens da rede, esse processo foi criado pois a prova de trabalho a longo prazo gera uma demanda cada vez maior de poder computacional e energia para resolver o enigma matemático, e definir de quem é o direto de validar o bloco.

![POS!](/src/1-pos.png)
 
Ao contrario da Prova de trabalho, no PoS não há recompensa do sistema por minerar o bloco, a única recompensa pela validação são os acúmulos das taxas de todas as transações feitas naquele bloco.

![POS!](/src/2-pos.png)

As moedas podem ser mais rentáveis e mais segura, pois  se o usuário detêm 51% dos tokens o que é muito difícil mas não impossível, ele poderia em tese falsificar blocos, mas como ele detêm 51% desses tokens, com a falsificação a moeda iria cair de valor e portanto ele iria perder seus investimentos junto com a rede.

![POS!](/src/3-pos.png)