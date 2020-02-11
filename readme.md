## Estudos sobre Node.js

Para primeira configuração: `node.init`
Preenche as informações

Instala-se o express via `npm install express --save` 

Para facilitar o desenvolvimento instala-se o Nodemon via `npm install nodemon --save-dev` e coloca-se com global usando `npm install -g nodemon`

Para facilitar o inicio altera-se o script start em package.json para `"nodemon server.js"`

Marko: Usado para criar templates. Instalação: `npm install marko --save`. Os arquivos tem extensão .marko e dever ser solicitados usando require e o método `resp.marko();`

No segundo parâmetro de resp.marko é possível adicionar data e renderizar de modo dinâmico usando um laço for no arquivo .marko

Com o sqlite é possível adicionar o banco de dados para persistir dados e lançar no template

Com padrão DAO a responsabilidade do acesso aos dados fica encapsulado