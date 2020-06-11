<h1 align="center">
<img src="https://i.imgur.com/pnhSod4.png" alt="Ecoleta" width="700">
</h1>

<h3 align="center"> 🚀 Ecoleta: Sistema de pontos de coleta de resíduos...</h3>

<blockquote align="center">Aplicação base desenvolvida durante a Next Level Week da Rocketseat</blockquote>

<p align="center">	
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/Davispc10/ecoleta">
	
  <a href="https://www.linkedin.com/in/david-azeredo/">
    <img alt="Made by David Azeredo" src="https://img.shields.io/badge/made%20by-DavidAzeredo-%2304D361">
  </a>
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License MIT">
  </a>
</p>

## Ferramentas
Foram utilizadas a stack Javascript para o desenvolvimento do projeto:

- ⚛️ **React Js** — Biblioteca JavaScript para construção do frontend da aplicação web:
  - Uso do react hooks;
  - Requisições com o axios;
  - Typescript;
  - Mapa leaflet.
- ⚛️ **React Native** — Biblioteca que provê uma maneira eficiente de criar aplicações nativas para Android e iOS:
  - Uso do expo;
  - Typescript;
  - Requisições com o axios.
- 💹 **Node Js** — Plataforma que permite utilizar javascript para criar aplicações do lado do servidor(backend):
  - Axios;
  - Framework express;
  - Banco de dados Sqlite;
  - Query builder Knex;
  - Typescript.

## Sobre:
<p>Ecoleta é um projeto baseado na semana internacional do meio ambiente, que conectam pessoas a companhias de coleta de resíduos como pilhas, óleos, lâmpadas, material eletrônico, etc.</p>

<p>Na aplicação web é possível cadastrar o ponto de coleta e inserir informações para as pessoas encontrarem o local. No app mobile é possível filtrar a região e ver no mapa quais pontos de coleta próximos para fazer o descarte.</p>

<p>⚙ FrontEnd: <a href="https://github.com/Davispc10/ecoleta/tree/master/web">Ecoleta - FrontEnd</a></p>
<p>📱 Mobile: <a href="https://github.com/Davispc10/ecoleta/tree/master/mobile">Ecoleta - Mobile</a></p>
<p>💻 Backend: <a href="https://github.com/Davispc10/ecoleta/tree/master/server">Ecoleta - API</a></p>

### Configuração - Backend
Para rodar o projeto, voce precisa do yarn, node e git instalados.
```bash
# Vá a pasta server
$ cd ecoleta/server

# Instale as dependências
$ yarn install

# Execute as migrações do banco
$ yarn knex:migrate

# Execute as seeds
$ yarn knex:seed

# Inicie o servidor
$ yarn dev
```

Você terá acesso a api pelo url: `http://localhost:3334`.
### Configuração - Frontend
Para iniciar o **Frontend** do React utilize os comandos:
```bash
# Vá a pasta web
cd ecoleta/web

yarn install

yarn start
```
Assim que o processo terminar, automaticamente será aberta no seu navegador a página `localhost:3000` com a aplicação funcionando.

### Configuração - Mobile

Para ver a aplicação mobile com o React Native primeiro é necessário colocar o IP do seu servidor (ou computador) no arquivo `src/services/api.js`, e depois executar os comandos:

```bash
# Vá a pasta
cd ecoleta/mobile

# NÃO é preciso executar a linha de baixo caso ja tenha o Expo (CLI) instalado
yarn global add install expo-cli

yarn install

expo start
```
Assim que o processo terminar, automaticamente será aberta no seu navegador a página `localhost:19002`. Conecte seu emulador, ou teste o aplicativo por `LAN`: baixe o aplicativo **Expo** da Play Store ou App Store e em seguida escaneie o código QR.

## Imagens - Web
![](https://i.imgur.com/MurNYJs.png)

![](https://i.imgur.com/raXOFTV.png)

![](https://i.imgur.com/0oSFl2y.png)

## Imagens - Mobile

![](https://i.imgur.com/sYTlxA8.png)

![](https://i.imgur.com/hLlyin3.png)

![](https://i.imgur.com/4b5C8M8.png)

## Licença

Esse projeto é licensiado pela MIT License - Veja a página da [licença](https://opensource.org/licenses/MIT) para detalhes
