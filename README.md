# churchjs

Church web application serving web and mobile applications. 
restful web api to meet the church's diverse data needs.

Maintained by [New Life Church](http://newlife.global)

## Contents
  * [Planning](#user-content--thought)
  * [Client](#user-content--client)
  * [Server](#user-content--server)
  * [Database](#user-content--data)
  * [Install](#user-content--install)
  * [Style Guide](#user-content--styleguide)
  * [Testing](#user-content--testing)

### [](#thought) [thought](https://github.com/churchjs/thought)
  * planning repo 

### [](#server) Server
  * [hapijs](https://hapijs.com)
  * [jade template engine](http://jade-lang.com/)
    - to build server side templates.

### [](#client) Client
  * [react jsx](http://facebook.github.io/react/index.html)
    - react is used to build client side user interfaces.
  * [stylus css] (https://learnboost.github.io/stylus/)
    - expressive language to generator css.
  * [jQuery](http://jsquery.com) 

### [](#data) [data](https://github.com/churchjs/data)
  * [couchdb](http://couchdb.apache.org) 
  * couchdb interface: all logic used to interface with couchdb
    is built in the data repository. 
  * read install instructions on how to configure churchjs/data and churchjs/www 
    work together. 

### [](#install) Install
  * configure the church-www path in `lib/manifest.js` this will cause
    the church-www application to load the sofajs database interface.
  * The database interface will be accessible within the hapijs application at:
    `server.app.db`.

### [](#styleguide) Style Guide
  * [hapijs styles](https://github.com/hapijs/contrib/blob/master/Style.md)


### [](#testing) Testing
  hapijs testing suite. This testing suite applies linting to code 
  enforcing the style guide requirements.
  * [lab](https://github.com/hapijs/lab)
  * [code](https://github.com/hapijs/code)
  * 100% test coverage required.

#### Have question?
  * open up an [issue](https://github.com/churchjs/www/issues).
