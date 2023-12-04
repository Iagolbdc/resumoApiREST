# Api REST e RESTFul

Uma API REST é uma interface de programação de aplicativos (API) que usa o protocolo HTTP para comunicar com um servidor. Ela é baseada nos princípios da arquitetura REST (Representational State Transfer), que define uma série de restrições e recomendações para o desenvolvimento de APIs.
Quando uma implementação segue os princípios do REST, ela é considerada "RESTful". É mais uma abordagem prática que aplica os princípios do REST para criar serviços web.
## Implementação RESTful

Uma API é considerada RESTful quando adere aos princípios da arquitetura REST. Isso inclui:

- **Identificação de Recursos:** Cada recurso é identificado por uma URI (Uniform Resource Identifier).
  
- **Manipulação de Recursos:** Recursos são manipulados usando os verbos HTTP padrão, como GET, POST, PUT e DELETE.

- **Representação:** Os recursos podem ter diferentes representações, como JSON ou XML. O cliente pode negociar a representação desejada.

- **Estado Stateless:** A comunicação entre cliente e servidor é stateless, ou seja, cada solicitação do cliente contém toda a informação necessária para entender e processar a requisição.

## Verbos HTTP

- **GET:** Obtém um recurso ou uma lista de recursos.
  
- **POST:** Cria um novo recurso com os dados fornecidos.
  
- **PUT:** Atualiza um recurso existente ou cria um novo se não existir.

- **PATCH:** Atualiza um recurso parcialmente economizando largura de banda e reduzindo o risco de conflitos.
  
- **DELETE:** Remove um recurso.

- **HEAD:** Semelhante ao GET, mas é usado para obter informações sobre um recurso sem receber o corpo da resposta..

- **OPTIONS:** Utilizado para obter informações sobre os métodos HTTP permitidos em um determinado recurso, ou seja, as capacidades do servidor.

## HTTP Status Code

O HTTP Status Code (Código de Status HTTP) é uma parte essencial do protocolo HTTP usado para indicar o resultado de uma solicitação feita a um servidor web. Esses códigos são incluídos nas respostas do servidor para informar ao cliente sobre o sucesso, falha ou outro estado da solicitação.

