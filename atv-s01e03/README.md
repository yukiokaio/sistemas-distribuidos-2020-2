# Sistemas Distribuídos

Um sistema distribuído nada mais é que um software que garantirá que os usuários enxerguem um conjunto de computadores um sistema único e consistente. Tendo como características a comunicação através de mensagens, partilha de recursos, sistema assíncrono, falhas independentes, concorrência e heterogeneidade. Possuindo ainda 3 tipos: Sistemas de Computação Distribuídos, Sistemas de Informação Distribuídos e Sistemas Distribuídos Pervasivos.

## Tipos de Sistemas Distribuídos 

### Sistemas de Computação Distribuídos 

É utilizado para tarefas de alto desempenho, sendo subdividido em: Computação em Cluster e Computação em grade.
Na computação em Cluster os sistemas computacionais são consistidos de uma coleção de estações de trabalho similares, fortemente conectadas por uma rede de alta velocidade com um nó funcionando como gerenciador. Já a computação em grade é construída como uma federação de sistemas computacionais, onde cada sistema está sob um domínio administrativo e, portanto, pode contemplar heterogeneidade de “hardware”, “software” e tecnologia de rede. 

### Sistemas de Informação Distribuídos

Uma grande quantidade de sistemas distribuídos em uso hoje em dia são formas de sistemas tradicionais, integrando legados. Tendo como exemplo os sistemas de processamento de transações, que é uma classe importante e satisfazem as propriedades a seguir: 

* Isolamento - as transações concorrentes não interferem entre si. 
* Atomicidade - ou todas as operações são bem sucedidas, ou todas falham. Quando uma falha, o estado do objeto permanecerá inalterado.
* Durabilidade - Após o término de uma transação, seus efeitos são permantentes.
* Consitência - uma transação estabelece um estado de transição válido.

### Sistemas Distribuídos Pervasivos

São Sistemas Distribuídos em que os nós são pequenos, mantidos por bateria, móveis, passíveis de conexão através de rede sem fio e geralmente embutidos em um sistema maior. Possuindo os seguintes requisitos:

* Composição ad hoc - cada nó pode ser usado em diferentes maneiras, por diferentes usuários.
* Mudança contextual - o sistema é parte de um ambiente onde mudanças devem ser rapidamente levadas em consideração.
* Compartilhar é o padrão - nós vão e veem, fornecendo serviços e informação compartilháveis.

## Middlewares

### Java RMI

É um mecanismo de comunicação entre o servidor e o cliente para se comunicarem e transmitirem informações entre si, tendo as seguintes propriedades: 

* Localização de objetos remotos.
* Comunicação com objetos remotos.
* Carregar os bytecodes de classe dos objetos que são transferidos como argumentos ou valores.

*Tendo seu desenvolvimento em JAVA com base no RPC.*

### Havok

É um pacote de software de middleware desenvolvido pela impresa irlandesa Havok. Ele é usado principalmente em jogos devido ao seu uso para criar as físicas deles, permitindo colisão e dinâmica entre corpos rígidos. Possuindo ainda outros diveros módulos como: 

* Havok Animation Studio (descontinuado).
* Pano Havok.
* Havok Physics.
* Havok Destruction (descontinuado). 
* Havok Vision Engine (descontinuado).
* Havok AI.
* Havok Script (descontinuado).

*Tendo C/C++ como sua principal linguagem de desenvolvimento.*

### CORBA

É a especificação de um OMA (object management architecture) que tem por objetivo a interoperabilidade entre diferentes sistemas computacionais e linguagens de programação através de ORB’s, que são estruturas que permitem que os programadores façam chamadas de um computador a outro através de uma rede. O CORBA é definido e padronizado pela OMG (Object Management Group).

*Utiliza IDL(Interface Definition Language), uma linguagem baseada em C++*
