# text-editor
This web application allows users to create and access notes and code snippets from any device, whether online or offline.

Using service workers and the Cache API enables a fully functional offline experience. Users can access previously visited pages even when the app loses internet connectivity.

## Key Technologies:

    JavaScript
    Webpack Workbox (for service workers)
    Concurrently (for running dev scripts)
    IndexedDB (for offline data storage)
    Express (backend framework)
    Node.js
    Babel (for transpilation)
    Nodemon (autoreload server)

## Usage

To run it locally:

Clone the repo:

```git clone [repo link]```

Install dependencies:

```npm install```

Start the development server:

```npm run start```

View in browser at:

http://localhost:3000 ↗

This provides a fully functioning offline-first text editor that can be used from any device when internet is available or not.

[`scrot1`](https://github.com/JessePomeroy/text-editor/blob/main/assets/scrot1.png)

[`scrot2`](https://github.com/JessePomeroy/text-editor/blob/main/assets/scrot2.png)


The deployed application is hosted on Heroku at:
https://salty-escarpment-43923-9943375d24f7.herokuapp.com/

https://github.com/JessePomeroy/text-editor