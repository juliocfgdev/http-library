# http-library
## Descrição 
Biblioteca para facilitar o consumo de API's 
### Tecnologias Usadas:
* HTML5
* Vannila JS + ES6:
  * Arrow Functions
  * OOP com Classes
  * Async / Await
  * Fetch API
#### Como utilizar
Importe a biblioteca
```javascript
import { http } from './http'
```
#### Métodos:
```javascript
// Get 
http.get('url')
    .then(data => console.log(data))
    .catch(err => console.log(err));
    
// Post
http.post('url', data)
    .then(data => console.log(data))
    .catch(err => console.log(err));

// Put
http.put('url', data)
    .then(data => console.log(data))
    .catch(err => console.log(err));

// Delete
http.delete('url')
    .then((data) => console.log(data))
    .catch(err => console.log(err));
```
#### Exemplo Prático:
Para ver um exemplo prático, cheque o código do app.js, nele os métodos são utilizados com a Fake REST API JSONPlaceholder
