Sistema para Controle de Transporte Particular

O sistema utiliza API’s para a exibição de dados e informações na tela, tal qual usaremos para exibir o MAPA (API: Google Maps | OpenLayers). A partir da ideia de ser um sistema de transporte particular, vimos em sua documentação que os atores são Cliente, Motorista e Gerente e que o Cliente e o Motorista terão uma interação através do APP, por isso, decidimos desenvolver um aplicativo Mobile. 

Requisito Não Funcional encontrado na documentação:
Desempenho: “ O tempo de resposta do aplicativo é essencial. A demora em transmitir solicitações de corrida e suas aceitações podem causar o cancelamento das solicitações e atraso dos clientes.” 

Bons softwares são projetados segundo estruturas bem definidas e organizadas. Uma definição de arquitetura de software:
“Conjunto de estruturas necessárias para compreender o sistema, que inclui os elementos do software, as relações entre eles e as propriedades de ambos” (BASS et alii, 2013).

A escolha da arquitetura afeta:
* Desempenho;
* Robustez;
* Capacidade de distribuição;
* Manutenibilidade;
* Entre diversos outros atributos de qualidade do sistema.

Pensando em um dos Requisitos Não Funcionais, que é Desempenho, a arquitetura escolhida foi Cliente-servidor, que é organizada em:
* Um conjunto de serviços e servidores;
* Clientes que solicitam os serviços. 

Resumindo, esse modelo é composto principalmente de um conjunto de servidores que oferecem serviços a outros componentes e um conjunto de clientes que solicitam esses serviços oferecidos pelos servidores através de uma rede.

O que estamos utilizando nesse trabalho?
React Native - é um Framework para desenvolvimento de aplicativos móveis multiplataforma. 
Yarn e o NPM - ambos são gerenciadores de pacotes e dependências em projetos JavaScript.
Expo - é uma ferramenta utilizada no desenvolvimento mobile com React Native que permite o fácil acesso às API's nativas do dispositivo sem precisar instalar qualquer dependência ou alterar código naTtivo.

To be continued
...
