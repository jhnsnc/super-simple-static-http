Super Simple Static HTTP Server
-------------------------------
Setup
=====
If you don't already have Node.js installed, get it from https://nodejs.org/

Open terminal and navigate to the project directory.

Install the only required node package:
```sh
npm install node-static
```

Run the project:
```sh
node app.js
```

You can now open your browser to http://localhost:3000

Making changes
==============
All files in the `public/` directory are made available on http://localhost:3000 as long as `node app.js` is running.

Edit `public/index.html`, `public/css/main.css`, and `public/js/main.js` and add new files/folders as needed.
