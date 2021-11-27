# the-coffee-dealer
Proyecto Coder House
Para poder utilizar este repositorio tiene que instalar:
- nodejs
- npm
Clone este repositorio, abra git bash here e inserte estos comandos:
1. npm init
2. npm install -D node-sass nodemon

Edita el package.json e inserta los lineas.
    "build-css": "node-sass --include-path scss scss/styles.scss css/stylescss.css",
    "watch-css": "nodemon -e scss -x \"npm run build-css\""

Ejecuta en git bash run watch-css
