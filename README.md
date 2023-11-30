# Api REST e RESTFul

A Api REST (Representational State Transfer) é um conjunto de regras que orientam como os serviços da web se comunicam usando o HTTP. Ela permite que diferentes sistemas troquem informações de forma eficaz, seguindo o conceito de recursos identificados por URIs. Para operar nessa arquitetura, são usados métodos como GET, POST, PUT e DELETE para manipular esses recursos. Uma API REST é flexível, escalável e segue o princípio de statelessness, ou seja, não armazena informações sobre o cliente entre as interações.

* **Comunicação via HTTP:** Utiliza o protocolo HTTP para permitir a interação entre serviços web de diferentes sistemas.
  
* **Recursos e URIs:** Baseia-se no conceito de recursos, cada um identificado por uma URI única, facilitando o acesso e manipulação dos dados.

- **Métodos HTTP:** Utiliza métodos como GET (obter), POST (criar), PUT (atualizar), DELETE (excluir), entre outros, para realizar operações nos recursos.

- **Escalabilidade e Flexibilidade:** Projetada para ser flexível e adaptável, permitindo um desenvolvimento ágil e escalável de serviços.

- **Statelessness:** Segue o princípio de statelessness, não mantendo informações sobre o estado do cliente entre as solicitações, o que ajuda na simplificação e eficiência das interações.

- **Padrão de Design:** Adere a um conjunto de regras e diretrizes para o desenvolvimento de serviços web, mantendo a uniformidade e consistência na comunicação entre sistemas.

RESTful refere-se à capacidade de uma API (Interface de Programação de Aplicações) ou serviço web seguir os princípios e práticas do REST (Representational State Transfer). Uma API ou serviço RESTful adere estritamente aos conceitos e diretrizes definidos pelo estilo arquitetural REST.

Alguns dos princípios fundamentais de uma abordagem RESTful incluem:

- **Recursos Identificáveis:** Os recursos (dados, objetos, serviços) são identificados por URIs (Uniform Resource Identifiers) únicas.

- **Operações baseadas em Métodos HTTP:** Utiliza os métodos HTTP (GET, POST, PUT, DELETE, etc.) para realizar operações nos recursos.

- **Statelessness (Estado):** Cada requisição feita ao servidor contém todas as informações necessárias para processar a solicitação, sem depender de um estado mantido pelo servidor. Isso torna as interações independentes e simplifica a comunicação.

- **Representação dos Recursos:** Os recursos são representados por meio de formatos como JSON (JavaScript Object Notation) ou XML (eXtensible Markup Language) para facilitar a transferência de dados entre cliente e servidor.

- **HATEOAS (Hypermedia As The Engine Of Application State):** Idealmente, uma abordagem RESTful inclui links navegáveis para permitir que o cliente descubra dinamicamente e acesse outros recursos relacionados.

## Diferenças entre REST e RESTFul

REST (Representational State Transfer):

- É um estilo arquitetural que descreve um conjunto de restrições, princípios e boas práticas para criar serviços web.
- Estabelece diretrizes para a criação de APIs que são escaláveis, flexíveis e interoperáveis entre diferentes sistemas.
- Define um conjunto de regras para a comunicação entre cliente e servidor, baseando-se na manipulação de recursos identificados por URIs e usando métodos HTTP (GET, POST, PUT, DELETE, etc.).
- Foi introduzido por Roy Fielding em sua tese de doutorado em 2000.
  
RESTful:

- Refere-se a uma API ou serviço web que adere aos princípios do REST.
- Uma API RESTful segue as diretrizes e as restrições estabelecidas pelo REST, implementando os métodos HTTP e outras práticas para criar uma arquitetura de serviço web conforme descrita pelo estilo REST.
- É uma aplicação prática dos princípios do REST, ou seja, é a implementação concreta de uma API ou serviço web de acordo com essas diretrizes.

REST é o conjunto de princípios arquiteturais, enquanto RESTful é a aplicação desses princípios na implementação de uma API ou serviço web específico. Portanto, uma API RESTful segue as diretrizes e restrições do REST para oferecer uma interface de programação que se encaixe nesse modelo arquitetural.

## HTTP verbs

HTTP verbs (métodos HTTP) são ações que descrevem a operação que está sendo solicitada em uma determinada URL. Eles são usados na comunicação entre um cliente (como um navegador da web ou um aplicativo) e um servidor web para indicar a ação a ser realizada sobre um recurso específico. Cada verbo HTTP tem uma função específica:

- GET: Recupera dados de um recurso.
- POST: Envia dados para criar ou atualizar um recurso.
- PUT: Substitui completamente um recurso existente.
- DELETE: Remove um recurso.
- PATCH: Aplica modificações parciais em um recurso.
- HEAD: Obtém apenas os cabeçalhos da resposta, sem o corpo da mensagem.
- OPTIONS: Descobre quais métodos são permitidos em um recurso.

## HTTP Status Code

Os códigos de status HTTP são códigos numéricos retornados pelo servidor web em resposta a uma requisição feita pelo cliente, indicando o resultado da solicitação. Esses códigos são divididos em cinco classes e cada classe possui uma série de códigos específicos:

1. **1xx - Informational (Informativo):** Indica que a requisição foi recebida e o processo continua em andamento.

2. **2xx - Success (Sucesso):** Indica que a requisição foi recebida, entendida e aceita com sucesso.

3. **3xx - Redirection (Redirecionamento):** Indica que mais ações precisam ser tomadas para completar a requisição.

4. **4xx - Client Error (Erro do Cliente):** Indica que houve um erro por parte do cliente ao realizar a requisição.

5. **5xx - Server Error (Erro do Servidor):** Indica que houve um erro por parte do servidor ao processar a requisição do cliente.

Esses códigos são fundamentais para a comunicação entre cliente e servidor na web, pois fornecem informações sobre o status da requisição, permitindo que os clientes (navegadores, aplicativos, etc.) entendam se a solicitação foi bem-sucedida, se houve um erro do cliente, do servidor ou se é necessário tomar alguma ação adicional.

---

Autor do resumo: Gabriella Lacerda Chaves Korinfsky - 01511663
