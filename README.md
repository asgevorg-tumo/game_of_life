# Programming 3 (by asgevorg)

This is code example of Tumos project GameOfLife with server side programming.

## Installation

Use the node package manager [npm](https://www.npmjs.com/) to install project modules.

```bash
npm install
```

It will installs [express.js](https://expressjs.com/) and [socket.io](https://socket.io/)

After that you can run server by typing.

```bash
npm start
```
# About the programm

There is a big matrix, which is generated randomly. There are grass, everything eater and grass eater.
Everything eater eats everything ;), grass eater eats only grass.

### Bomb
The Bomb, it appears in a random place, after it fires up every 8 cell near him fullfills with grassEaters. The grassEaters are real so after that they start moving and eating grasses.
By clicking on the matrix it will automaticly add a Bomb !

Server will start on Port 3000 by default. If you would want to change it, just go [server.js:64].
