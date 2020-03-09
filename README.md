# Hands-on Express CSRF

This application is a demonstration prototype just to show how to perform CSRF attack.

## Setting-up

* Install nodejs

* Install dependencies

```console
$ npm install
```

* Start application

```console
$ node app.js
```

## CSRF attack

* Victim must be log in http://localhost:3000

* Create an evil web page that make a malicious fund transfer order (http://localhost:3000/order)

* Invit your victim to visit your evil page
