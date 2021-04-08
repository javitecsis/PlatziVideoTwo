<div align = "center">
  <br>
  <img alt = "Salsa abierta" src = "https://i.ibb.co/7jPXt0Z/logo1-92f1a87f.png" width = "300px">
  <h1> 🍕 Salsa abierta 🍕 </h1>
  <strong> El camino hacia su próxima contribución de código abierto </strong>
</div>
<br>
<p align = "centro">
  <a href="https://github.com/open-sauced/open-sauced/actions?query=workflow%3A%22Node+CI%22">
    <img src = "https://github.com/open-sauced/open-sauced/workflows/Node%20CI/badge.svg" alt = "Nodo CI">
  </a>
  <a href="https://app.netlify.com/sites/open-sauced/deploys">
    <img src = "https://api.netlify.com/api/v1/badges/76a3de8e-270c-4adf-89d5-3a3863da74e6/deploy-status" alt = "Estado de Netlify">
  </a>
  <img src = "https://badgen.net/dependabot/open-sauced/open-sauced?icon=dependabot" alt = "Insignia de Dependabot">
  <img src = "https://img.shields.io/github/languages/code-size/open-sauced/open-sauced" alt = "Tamaño del código de GitHub en bytes">
  <img src = "https://img.shields.io/github/commit-activity/w/open-sauced/open-sauced" alt = "Actividad de confirmación de GitHub">
  <a href="https://github.com/open-sauced/open-sauced/issues">
    <img src = "https://img.shields.io/github/issues/open-sauced/open-sauced" alt = "Problemas de GitHub">
  </a>
  <a href="https://github.com/open-sauced/open-sauced/releases">
    <img src = "https://img.shields.io/github/v/release/open-sauced/open-sauced.svg?style=flat" alt = "Versión de GitHub">
  </a>
  <a href="https://discord.gg/gZMKK5q">
    <img src = "https://img.shields.io/discord/714698561081704529.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2" alt = "Discord">
  </a>
  <a href="https://twitter.com/saucedopen">
    <img src = "https://img.shields.io/twitter/follow/saucedopen?label=Follow&style=social" alt = "Twitter">
  </a>
</p>

Open Sauced proporciona una incorporación estructurada para nuevos contribuyentes al código abierto. Esta estructura proporciona una forma de realizar un seguimiento de sus próximas contribuciones aprovechando un panel de control exclusivo creado sobre la [API GraphQL de GitHub] (https://docs.github.com/en/free-pro-team@latest/graphql).

[! [open-sauced-screencap] (/ src / images / homepage.png)
] (https://opensauced.pizza)

## 🤝 Contribuyendo

¡Te animamos a contribuir a Open Sauced! Consulte la [Guía de contribución] (CONTRIBUTING.md) para obtener instrucciones sobre cómo proceder.

<img align = "right" src = "https://i.ibb.co/CJfW18H/ship.gif" width = "200" />

### 📖 Requisitos previos

- [Node.js] (https://nodejs.org/en/): recomendamos usar [nvm] (https://github.com/nvm-sh/nvm#installing-and-updating) para instalar el nodo versión.
- [NPM] (https://npmjs.com/): consulte su [guía de instalación] (https://docs.npmjs.com/downloading-and-installing-node-js-and-npm).
+ La versión mínima admitida de Node.js de `terser-webpack-plugin` es 10.13

### 🖥️ Desarrollo local

''
npm install
inicio npm
''

### 🧪 Prueba

''
prueba npm

// para limpiar instantáneas
npm ejecutar limpio
''

### 📙 Libro de cuentos

Storybook se está aprovechando para simular componentes visuales de React. La última versión del sistema de diseño se puede encontrar en esta [url] (https://sauced-components.netlify.app/).

''
npm ejecutar libro de cuentos
''

! [captura de pantalla de ejemplo de libro de cuentos] (https://user-images.githubusercontent.com/5713670/68147486-0cd14600-ff32-11e9-8cc0-fd91f4171b87.png)

### 🔑 Autenticación

La autenticación se maneja a través del servicio [AuthGuardian de OneGraph] (https://www.onegraph.com/docs/auth_guardian.html).

### 💾 Base de datos

Este proyecto usa GitHub como base de datos. Cuando inicie sesión, se le presentará un botón para crear un repositorio de objetivos. Esa plantilla de repositorio se encuentra en [open-sauced / Goals-template] (https://github.com/open-sauced/goals-template).

### 💨 Trabajador de servicio

Este proyecto utiliza sw-precache para iniciar un caché fuera de línea. La caché fuera de línea solo se registra en producción. Si el servicio debe eliminarse manualmente, realice una llamada de ** anulación del registro ** desde la importación de registerServiceWorker.js.

## 🍕 Comunidad

Tienes preguntas? Únase a la conversación en nuestro [Discord] (https://discord.gg/gZMKK5q).
Encuentre videos de Open Sauced y resúmenes de lanzamientos en nuestro [Canal de YouTube] (https://www.youtube.com/channel/UCklWxKrTti61ZCROE1e5-MQ).

## ⚖️ LICENCIA

MIT © [Open Sauced] (LICENCIA)
