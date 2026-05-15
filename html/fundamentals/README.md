## 1. Fundamentos

Uma rede de computadores consiste num sistema que conecta dois ou mais dispositivos eletrônicos — como computadores, smartphones e impressoras — para que eles possam trocar dados e compartilhar recursos entre si.

*"Cada dispositivo conectado a uma rede recebe o nome de host, e todos os dispositivos conectados a rede se comunicam entre si por meio de um conjunto padronizado de protocolos"*

### 1.1 Cliente-Servidor

A arquitetura cliente-servidor consiste num modelo onde um ou mais sistemas centralizados — servidores — fornecem recursos, e um ou mais dispositivos — clientes — solicitam e consomem esses recursos.

*"Dentro de uma rede, este modelo distribui as tarefas e cargas de trabalho entre os fornecedores de um recurso e os solicitantes destes recursos"*

Desse modo, o modelo define a forma como clientes interagem com servidores para acessar e consumir recursos e executar tarefas:

- Cliente: refere-se a qualquer dispositivo que inicia a troca de dados, solicitando um determinado recurso

- Servidor: refere-se ao sistema centralizado que recebe os pedidos dos clientes, processa-os e envia as respostas adequadas

O modelo cliente-servidor se baseia em requests — requerimentos — e responses — respostas. O ciclo fundamental deste modelo se resume em:

- Um cliente solicita um recurso e envia o pedido a um servidor por meio de uma rede de computadores;

- O servidor recebe o pedido, processa-o e envia uma resposta apropriada de volta ao cliente;

- O cliente exibe o resultado do pedido realizado para o utilizador final

### 1.2 Protocolos

Um protocolo, no contexto dos computadores, corresponde a um conjunto de regras e esquemas que define como dois agentes — dispositivos — se comunicam e trocam dados entre si em uma rede.

### 1.3 Internet

A internet consiste em uma gigante rede de computadores que conecta todos que a utilizam com todo o mundo — um dos maiores exemplos de rede de computadores existente — podendo ser interpretada como uma teia gigante que interliga dispositivos de diferentes tipos.

*"Assim sendo, enquanto uma rede doméstica conecta os dispositivos da casa, a internet conecta centenas de milhares de redes menores ao redor do mundo — incluindo a doméstica"*

Tudo funciona por meio de uma rede global de roteadores interconectados, os quais direcionam o fluxo de dados entre diferentes dispositivos e sistemas:

- Os computadores dividem os dados enviados pela internet em pequenas partes — chamadas de pacotes — e os envia para um outro roteador;

- O roteador examina o pacote e encaminha-o para o roteador seguinte;

- O processo continua até que o pacote chegue ao seu destino final.

Para garantir que os pacotes sejam enviados e recebidos corretamente, a internet utiliza protocolos diversos, incluindo o IP — Internet Protocol — e o TCP — Transmission Control Protocol:

- IP: protocolo da camada de internet que encaminha os pacotes para seus destinos corretos — atuando como um sistema de endereçamento e roteamento

- TCP: protocolo da camada de transporte que garante que os pacotes sejam transmitidos de forma confiável e na ordem correta

Uma ampla gama de outros protocolos ajudam a viabilizar a troca de dados pela internet e facilitam o acesso aos recursos da web, como o DNS — Domain Name System:

- DNS: protocolo da camada de aplicativo que traduz nomes de domínio em endereços do protocolo de internet — IP —, facilitando o acesso a websites sem a necessidade de decorar números complexos

*"A internet fornece toda a infraestrutura técnica que torna a web possível, ou seja, a web corresponde a um serviço construído sobre a internet — sem a internet, a web nunca existiria"*

Agora, para que a web seja acessada e seus recursos possam ser utilizados utiliza-se o HTTP — Hypertext Transfer Protocol —, um protocolo utilizado especificamente para troca de dados na web.

- HTTP: protocolo da camada de aplicativo utilizado para transferir dados entre um cliente — como um navegador — e um servidor, definindo o formato das requests e responses

- HTTPS: semelhante ao protocolo anterior, no entanto, mais seguro — ele adiciona uma camada de criptografia por meio do protocolo TLS

*"O protocolo TLS — Transport Layer Security — oferece privacidade e integridade dos dados por meio de criptografia, operando principalmente na troca de dados entre cliente e servidor"*

Ao acessar um site, o cliente — navegador — solicita um recurso do documento — página — acessado e aguarda uma resposta. O servidor — site — analisa o pedido e envia uma resposta de volta ao cliente, contendo os dados solicitados.

#### 1.3.1 Navegadores

Os navegadores consistem em softwares que permitem aos utilizadores acessar e interagir com a web, servindo para visualizar o conteúdo de páginas web: eles interpretam — transformam — códigos complexos na interface visual que aparece na tela

Existem diversos navegadores no mercado — cada um com suas peculiaridades: a forma como cada um processa um documento web pode resultar em conteúdos e estruturas diferentes para cada navegador

*"Os desenvolvedores devem realizar testes em mais de um navegador, procurando adequar a estrutura do código-fonte para funcionamento na maioria destes softwares"*

Cada navegador possui um conjunto de ferramentas integradas que ajudam desenvolvedores a inspecionar, depurar e testar sites de aplicativos web. Esse conjunto de ferramentas é chamado de DevTools — Ferramentas de Desenvolvimento — e, geralmente, pode ser acessado no navegador por meio da tecla de atalho F12

### 1.4 Servidores

Um servidor de rede corresponde a um sistema computacional centralizado de alto desempenho que armazena, gerencia e fornece recursos para outros dispositivos conectados a uma rede.

*"Existem diferentes tipos de servidores fundamentais para a infraestrutura da internet, como os servidores web, os servidores de arquivos e os servidores de bancos de dados: cada tipo centraliza recursos exclusivos"*

Um servidor web consiste numa subcategoria de servidor de rede — hardware ou software — que gerencia os recursos armazenados em um site, desenhados exclusivamente para processar requests HTTP:

- Servidores web fornecem suporte para HTTP: protocolo utilizado para transferir arquivos entre clientes e servidores;

- As requests sempre partem do cliente em rumo ao servidor — nunca o contrário;

- Servidores respondem a todas as requests recebidas — seja com os dados solicitados ou com uma mensagem de erro.
