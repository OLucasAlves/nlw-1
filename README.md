# nlw-1

## 💻 Projeto
Projeto criado durante a NLW promovido pela Rocketseat

<h1 align="center">
    <img style="width:70%" alt="ecoleta" src="https://i.ibb.co/pj5Sb3B/2020-06-07-04-08-33-Configura-es.png" />
    <br>
</h1>

<p align="center">
    <img alt="npm" src="https://img.shields.io/npm/v/npm?color=%23FF0000">
    <img alt="node" src="https://img.shields.io/badge/node-v12.14.1-brightgreen" />
    <img alt="node" src="https://img.shields.io/badge/expo-v3.16.1-lightgrey" />
     <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/OLucasAlves/nlw-1" />
    <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/OLucasAlves/nlw-1" />
    
    
</p>

<p align="center">
  <a href="#rocket-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#bookmark_tabs-dependencies">Dependencies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#information_source-how-to-use">How To Use</a>
</p>


## :rocket: Technologies

This project was developed at the **Next Level Week #1** by [Rockseat](https://rocketseat.com.br/) using the following technologies:

-  [ReactJS](https://reactjs.org/)
-  [Node.js](nodejs)
-  [React Native](https://reactnative.dev/)
-  [TypeScript](https://www.typescriptlang.org/)
-  [Leaflet](https://leafletjs.com/examples/quick-start/)

## :bookmark_tabs: Dependencies

**Server (Node.js):**

<img alt="express" src="https://img.shields.io/badge/express-^4.17.1-brightgreen" /> <img alt="celebrate" src="https://img.shields.io/badge/celebrate-^12.1.1-brightgreen" /> <img alt="cors" src="https://img.shields.io/badge/cors-^2.8.5-brightgreen" /> <img alt="knex" src="https://img.shields.io/badge/knex-^0.21.1-brightgreen" /> <img alt="multer" src="https://img.shields.io/badge/multer-^1.4.2-brightgreen" /> <img alt="sqlite3" src="https://img.shields.io/badge/sqlite3-^4.2.0-brightgreen" />

<br/>
<br/>

**Web (ReactJS):**
  
<img alt="axios" src="https://img.shields.io/badge/axios-^0.19.2-blue" /> <img alt="axios" src="https://img.shields.io/badge/leaflet-^1.6.0-blue" /> <img alt="axios" src="https://img.shields.io/badge/react-^16.13.1-blue" /> <img alt="axios" src="https://img.shields.io/badge/react--dom-^16.13.1-blue" /> <img alt="axios" src="https://img.shields.io/badge/react--dropzone-^11.0.1-blue" /> <img alt="axios" src="https://img.shields.io/badge/react--icons-^3.10.0-blue" /> <img alt="axios" src="https://img.shields.io/badge/react--leaflet-^2.7.0-blue" /> <img alt="axios" src="https://img.shields.io/badge/react--router--dom-^5.2.0-blue" /> <img alt="axios" src="https://img.shields.io/badge/react--scripts-3.4.1-blue" /> <img alt="axios" src="https://img.shields.io/badge/typescript-^3.7.5-blue" />

<br/>
<br/>

**Mobile (React Native):**
    
<img alt="axios" src="https://img.shields.io/badge/@expo--google--fonts/roboto-^0.1.0-cyan" /> <img alt="axios" src="https://img.shields.io/badge/@expo--google--fonts/ubuntu-^0.1.0-cyan" /> <img alt="axios" src="https://img.shields.io/badge/@react--native--community/masked--view-0.1.6-cyan" /> <img alt="axios" src="https://img.shields.io/badge/@react--navigation/native-^5.5.0-cyan" /> <img alt="axios" src="https://img.shields.io/badge/@react--navigation/stack-^5.4.1-cyan" /> <img alt="axios" src="https://img.shields.io/badge/axios-^0.19.2-cyan" /> <img alt="axios" src="https://img.shields.io/badge/expo-~37.0.3-cyan" /> <img alt="axios" src="https://img.shields.io/badge/expo--constants-~9.0.0-cyan" /> <img alt="axios" src="https://img.shields.io/badge/expo--font-~8.1.0-cyan" /> <img alt="axios" src="https://img.shields.io/badge/expo--location-~8.1.0-cyan" /> <img alt="axios" src="https://img.shields.io/badge/expo--mail--composer-~8.1.0-cyan" /> <img alt="axios" src="https://img.shields.io/badge/react-~16.9.0-cyan" /> <img alt="axios" src="https://img.shields.io/badge/react--dom-~16.9.0-cyan" /> <img alt="axios" src="https://img.shields.io/badge/react--native--gesture--handler-~1.6.0-cyan" /> <img alt="axios" src="https://img.shields.io/badge/react--native--maps-0.26.1-cyan" /> <img alt="axios" src="https://img.shields.io/badge/react--native--picker--select-^7.0.0-cyan" /> <img alt="axios" src="https://img.shields.io/badge/react--native--reanimated-~1.7.0-cyan" /> <img alt="axios" src="https://img.shields.io/badge/react--native--safe--area--context-0.7.3-cyan" /> <img alt="axios" src="https://img.shields.io/badge/react--native--screens-~2.2.0-cyan" /> <img alt="axios" src="https://img.shields.io/badge/react--native--svg-11.0.1-cyan" /> <img alt="axios" src="https://img.shields.io/badge/react--native--web-~0.11.-cyan" />

## :information_source: How To Use

To clone and run this application, you'll need [Git](https://git-scm.com), [Node.js v12.14.1][nodejs] or higher and [npm v6.13.4] or higher installed on your computer. From your command line:

```bash
# Clone this repository
$ git clone https://github.com/OLucasAlves/nlw-1.git

# For each folder (server, web and mobile) go into folder and install dependecies

# For server project (Node.js)
$ cd server
$ npm install
$ npx knex migrate:latest
$ npx knex seed:run
$ npm run dev

# For web project (ReactJS)
$ cd web
$ npm install
$ npm start

# For mobile project (React Native)
$ cd mobile
$ npm install
$ npm start

