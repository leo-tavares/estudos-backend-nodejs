## NODE ([doc](https://nodejs.org/en/))

Plataforma de desenvolvimento que utiliza javascript no backend da aplicação. O node foi criado com a engine V8

### caracteristicas

- Arquitetura Event-loop
- Single-Thread, a [libuv](https://github.com/libuv/libuv) permite rodar codigo c++ para dar suporte ao multi-thread.
- Non-blocking I/O

### gerenciadires de pacotes

Permite a instalação de lib de terceiros. O [yarn](https://yarnpkg.com/pt-BR/) e [npm](https://www.npmjs.com/) são exemplos de gerenciadores

### Frameworks

 - [ExpressJs](https://expressjs.com/)
 	- non opinionated
	- micro serviços
 - [AdonisJs](https://adonisjs.com/)
 	- opinionated
	- monolito
	
## API REST

- input => requisisão feita pelo cliente
- output => resposta através de uma estrutura de dados
- [doc-method](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods)
- [doc-status](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Status)

</br>
informações sensíveis devem ser enviados no "Body" da requisição pois esta não será visivel na URL. </br>
informações complementares podem ser enviadas no "head" da requisição.
