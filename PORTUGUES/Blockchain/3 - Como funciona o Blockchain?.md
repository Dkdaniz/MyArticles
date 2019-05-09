# Como funciona o Blockchain?

Toda transação no Blockchain deve seguir alguns passos importantes como registro da transação, torna-la anônima, validar a transação e validar o bloco, vamos falar de cada uma delas para que você possa entender como toda transação no Blockchain funciona, para uma maior compreensão vamos usar o exemplo de uma planilha.

### Registrar Transação

Vamos imaginar que seis pessoas estão enviando moedas  uma para as outras (Imagem abaixo), mas essas transações estão com o seu verdadeiro nome de quem as enviou e o verdadeiro nome do destinatário, sabemos que isso não pode ocorrer, pois fere uma das características básicas do Blockchain, o Anonimato. (para saber mais sobre as características veja neste [link](http://descentralizado.com.br/index.php/2017/09/16/blockchain-definicao/))

![TRANSAÇÃO!](/src/transaction1.png)

### Tornar a transação anônima

Para tornar a transação anônima vamos submeter os nomes dos destinatários à função Hash (não sabe o que é Hash acesso a explicação do site no [link](http://descentralizado.com.br/index.php/2017/09/14/introducao-ao-blockchain/)) que por sua vez ira embaralhar (criptografar) essa informação para que seja impossível saber quem é o seu verdadeiro dono e destinatário.

![TRANSAÇÃO!](/src/transaction2.png)

### Tornar transação “OFICIAL” válida

Uma transação oficial ou válida, precisa passar por um processo de validação das transações, onde todas as transações que ocorreram naquele curto espaço de tempo ficaram em uma espécie de área de transferência para aguardar que validem essas transações e posteriormente validem o bloco.

![TRANSAÇÃO!](/src/transaction3.png)

Ao validar a transação ela recebera uma identificação que será única naquele bloco. Para localizar uma transação no Blockchain você precisa ter a id do bloco e da transação, assim será mais rápida a consulta posteriormente.

![TRANSAÇÃO!](/src/transaction4.png)

### Validação do bloco

Após todas as transações do bloco forem validadas será feito o “Fechamento do Bloco”, onde o bloco será finalizado e atribuído uma identificação ao mesmo.

![TRANSAÇÃO!](/src/transaction5.png)

### Assinar bloco

Ao ser realizado o processo de validação o sistema irá assinar este bloco, é aqui que está a mágica por trás do Blockchain, pois o bloco que está sendo criado recebe a identificação do bloco anterior que é baseado em hash, ou seja, qualquer informação que for alterada posteriormente a este bloco irá gerar um hash diferente do que foi assinado nele, portanto se a rede inteira estiver com uma informação diferente a essa e eles forem à maioria, os blocos posteriores a esse serão substituído pelos blocos corretos da rede, assim a rede garante que todos devem estar com os mesmo dados dos demais, sem haver qualquer diferença em nenhum ponto da rede.

![TRANSAÇÃO!](/src/transaction6.png)

Neste gif será mais fácil de compreender a herança dos blocos.

![BLOCKCHAIN!](/src/blockchain.gif)