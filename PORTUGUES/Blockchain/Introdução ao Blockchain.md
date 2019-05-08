## Introdução ao Blockchain

Para entendermos o que é Blockchain antes vamos viajar para os primórdios da criação desta rede mundial de computadores, a nossa Internet. Você já se perguntou como funciona a internet? Não?

### Como funciona a internet?

A rede mundial de computadores foi pensada para compartilhar informações com os demais membros desta mesma rede, seja uma rede local ou uma rede externa, por sua vez essa rede tem um servidor (denomina-se esse nome por ser o centralizador dos dados/informações).

Nossa internet funciona da seguinte forma, Vários Clientes (Maquinas dos usuários) conectadas a uma rede, solicitam ao servidor os dados que desejam e por sua vez o servidor retorna os dados requisitados, para melhor ilustrar esses procedimentos vamos usar como exemplo o Facebook:

Ao acessar o perfil de algum usuário você irá visualizar todos os dados e post do mesmo, mas por baixo dos panos o que realmente ocorre é o cliente (máquina do usuário, celular do usuário, dispositivos eletrônicos) solicitando ao servidor do Facebook todos os dados de um determinado perfil, o servidor irá processar a solicitação, pesquisar, em seguida vai verificar se realmente os dados desse perfil estão disponíveis, caso estejam, o servidor ira retornar os dados para a máquina do cliente e ela irá mostrar para o usuário.

### Rede Centralizada

Uma rede centralizada se característica por haver vários clientes (computadores solicitantes dos dados) e um único servidor (fornecedor dos dados), essa rede se nomeia rede centralizada por centralizar em um único local todas as informações requeridas dos seus clientes. Exemplo: (Facebook, Google+, Hotmail, Uol).

![REDE CENTRALIZADA!](/src/source.gif "REDE CENTRALIZADA")

### Rede Descentralizada

Consiste em decentralizar a informações, não unificar em um único local os dados e sim distribuir a todos os clientes essa informação, onde todos possuem parte ou todo os dados que a rede precisa.

### Peer to Peer (P2P)

É uma arquitetura de rede de computadores, em que cada ponto ou node(nós) da rede funciona tanto como cliente, como servidor (Cliente/Servidor), permitindo assim o compartilhamento de serviços os dados digitais. um exemplo de redes P2P (peer to peer) são os torrent que realizam o compartilhamento desses dados.


### HASH

Uma função Hash é um algoritmo que mapeia dados de comprimento variável para dados de comprimento fixo, o conceito teórico diz que “Hash é a transformação de uma grande quantidade de dados em uma pequena quantidade de informações”, ou seja, ele ira pegar o dado e submete-lo a função, que fara a conversão retornando outro valor completamente diferente.

##### Exemplo:

Eu vou submeter meu nome á função hash, como mostra no gif ele ira pegar a informação e transforma-la em uma pequena informação criptografada.


DANIEL 

Hash code:  3cd576727e759d144ec497e19ece0089cd0db11578ae10a94560920abafc1d7d

Agora vamos adicionar apenas uma letra,

DANIELL

Hash code: d92066d3037efbb8a34be858c4d79abe11b5177f94a1c7c7fdc4bce594562b62

Podemos perceber que o código mudou completamente, ou seja, é impossível dizer o que esse código representa, códigos hash só podem ser comparados, depois que eles forem criptografados não conseguimos a partir do código gerado realizar o processo inverso.

### Criptografia

É o estudo dos princípios e técnicas pelas quais a informação pode ser transformada da sua forma original para outra ilegível, de forma que possa ser conhecida apenas por seu destinatário (detentor da “chave secreta”), o que a torna difícil de ser lida por alguém não autorizado.

O Blockchain deve ser criptografado e inviolável, a criptografia usada é a Assimétrica, mas vamos falar de duas principais são:

##### Chave Simétrica

Chave Simétrica tem como objetivo utilizar uma única chave para criptografar e descriptografar os dados.


Na chave Simétrica a mesma chave criptografa e descriptografa a mensagem, o problema disso e que se essa chave for possuída por um invasor, ele pode descriptografar todas as mensagem do usuário.  
**Desvantagens: **Vulnerabilidade dos dados.  
**Vantagens: **Processo de envio é muito mais rápido comparado com a chave Assimétrica.

 

##### Chave Assimétrica

São criadas duas chaves: uma para Criptografia da informação e outra para descriptografar, a chave publica pode ser obtida por todos.


A chave Assimétrica tem como objetivo deixar mais seguro a informação, ou seja, o usuário possui uma chave publica e uma privada, a Publica irá ser responsável por criptografar e todos podem solicitar ao destinatário a mensagem de modo que se ela for interceptada por um hacker mal intencionado, a mensagem só poderá ser descriptografada pelo seu real destinatário, pois para descriptografar será necessário uma chave privada.  
**Desvantagens: **Lento

**Vantagens: **Muito mais seguro