# DevConnector 1.0

Social Network application for developers, being built on the MERN stack (Work In Progress). [Demo Currently Unavailable](https://bankole2000.github.io/devconnector)

[![Practice](https://img.shields.io/badge/Practice-JavaScript-yellow.svg)](https://bankole2000.github.io/devconnector)

_<p align="center">"Thanos Snapped..."</p>_

<div align="center" style="text-align:center; margin:auto;">
<img align="center" src="https://i.imgur.com/WGO3ULK.png" width="150"/>
</div>

## What it is (or will be)

A learning oriented, MERN stack demo Project to practice Full Stack Web app development. A basic social Network for develpers, to be built with:

- MongoDB
- Mongoose
- Express
- React
- Redux
- Bootstrap 4
- PostMan
- JSON Web Tokens
- Passport
- Bcrypt js
- HTML
- Vanilla JS - ES6
- [Awesomeness](https://www.wikihow.com/Love-Programming) - Strictly for the love of coding _Mehn!_

## What it will do

- User Registration and Authentication
- Extensive User Profiles
- Users can CRUD Posts
- Users can CRUD comments
- Users can Like/Unlike Posts

## Learning Points

- Like... A whoooole lot, lol. I'll write em out soon enough

## Issues

Encoutered errors logging into MongoDB Atlas.

1. First error

```javascript
name: 'MongoNetworkError',
  errorLabels: [ 'TransientTransactionError' ],
  [Symbol(mongoErrorContextSymbol)]: {}
```

**how to fix**: Check that IP address is White listed On Cloud mongoDB hosting (or just use `allow all IP addresses` and be done with that)

2. Second Error

```javascript
ok: 0,
  errmsg: 'bad auth Authentication failed.',
  code: 8000,
  codeName: 'AtlasError',
  name: 'MongoError',
  [Symbol(mongoErrorContextSymbol)]: {}
```

**how to fix**: Check collection database login details in mongoDB connection string. (Make sure your details - database username and password) - in the connection string are correct.

## Some cool stuff

Work In progress... Cool stuff will go here don't worry, lol

```javascript
// There will be some cool code here too
```

```javascript
// And also here
```

## Features in Development

Work in Progress.

## Acknowledgments

- Many thanks to [@bradtraversy](https://github.com/bradtraversy) for his awesome courses - _i will not fail you sensei_
- Thanks to [@torvalds](https://github.com/torvalds) For Making the world a better place
- And To anyone reading this... _You're awesome!_

That being said
_<p align="center">Adieu, Till I push again... I must return to my meditations on the Ways of JS Ninjustu</p>_
