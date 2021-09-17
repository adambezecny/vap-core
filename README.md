# vap-core

> Core VAP services

## About

This project uses [Feathers](http://feathersjs.com). An open source web framework for building modern real-time applications.

## Getting Started

Getting up and running is as easy as 1, 2, 3.

1. Make sure you have [NodeJS](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed.
2. Install your dependencies

    ```
    cd path/to/vap-core
    npm install
    ```

3. Start your app

    ```
    npm start
    ```

## Testing

Simply run `npm test` and all your tests in the `test/` directory will be run.

## Scaffolding

Feathers has a powerful command line interface. Here are a few things it can do:

```
$ npm install -g @feathersjs/cli          # Install Feathers CLI

$ feathers generate service               # Generate a new Service
$ feathers generate hook                  # Generate a new Hook
$ feathers help                           # Show all commands
```

## Help

For more information on all the things you can do with Feathers visit [docs.feathersjs.com](http://docs.feathersjs.com).


## Customizations of default app built by app generator

WIP

```
VAP NG - Work In Progress...

---------------------
    "semi": [
      "error",
      "always"
    ],

    to

        "semi": [
      "error",
      "never"
    ],
---------------------
"@types/mongodb": "^4.0.7", -> "@types/mongodb": "^3.6.20",
---------------------
remove all semicolons
---------------------
app.ts remove channels config + respective file
also remove websockets: app.configure(socketio())
---------------------
add watch script "watch": "shx rm -rf lib/ && tsc --watch"
---------------------
---------------------
---------------------
---------------------
---------------------
---------------------
---------------------
---------------------
---------------------
---------------------
---------------------
---------------------
---------------------
---------------------
---------------------
---------------------
```