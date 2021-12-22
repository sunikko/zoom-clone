#Noom

Zoom clone using NodeJS, WebRTC and Websockets.

mkdir zoom
cd zoom
sudo npm init -y
code .

touch README.md
npm i nodemon -D
-create file: babel.config.json, nodemon.json, src/server.js

git init .
npm i @babel/core @babel/cli @babel/node -D
npm i @babel/preset-env -D

npm i express
npm i pug

create server.js
package.json
add
```
"scripts": {
    "dev": "nodemon"
  },
```
npm run dev
