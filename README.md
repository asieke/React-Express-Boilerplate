

## React Boilerplate

The following repo contains a very basic setup

```console
git clone https://github.com/asieke/React-Express-Boilerplate.git
cd React-Express-Boilerplate
npm install
```

### Running the server

Kick off webpack so that its running.  Its set to use the -w option so it'll continuously compile the `client/src` directory into `client/dist`

```console
npm run react-dev
```

### Start the  Server

Nodemon should be installed - so all changes to the server will be automatically reloaded.  You should be up and running at localhost:3000

```console
npm start
```

### The Express Server

It doesn't really do much other than serve the static files in client/dist

### Client

In the `client/dist` directory, you'll find the compiled `bundle.js` which is imported by `index.html`.

In the `src/ directory` we have the bare bones of a basic react app that has an `index.jsx` file and an App component that prints `Hello World`

### Webpack Config

Uses babel to precompile and currently is only set up for .jsx files
