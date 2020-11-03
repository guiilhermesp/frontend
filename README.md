## Inicar o projeto

Para rodar este projeto localmente, deve-se seguir os seguintes passos

1. Instalar Nodejs em seu ambiente de desenvolvimento. [Linux](https://tecadmin.net/install-nodejs-with-nvm/) [Win/MacOs](https://medium.com/node-brasil/instalando-node-js-via-nvm-node-version-manager-219cef173952)
2. `git clone https://github.com/PRJEXT/frontend.git`
3. `cd frontend`
4. npm install
5. npm start

## Live-server

O comando `npm start` utiliza o [live-server](https://www.npmjs.com/package/live-server), que é responsável por escutar mudanças nos seus arquivos locais e reproduzi-las no servido estático local. Portando basta roda o comando `npm start` e ver suas alterações refletidas no browser.


## Estrutura do projeto


Cada widget será desenvolvido dentro de uma pasta destinada à ele, ou seja, todos os recursos usados para a construção do componente devem estar dentro de uma pasta sob seu nome. 
A estrutura da pasta deve ser a seguinte:

- nome-do-componente.html
- nome-do-componente.css
- nome-do-componente.js
- assets/ (opcional: pasta que deverá conter todos os recursos de mídia [imagens, icones, videos, etc])
