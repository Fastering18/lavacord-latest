[![npm](https://img.shields.io/npm/v/npm.svg)](https://www.npmjs.com/package/lavacord-latest)
[![npm downloads](https://img.shields.io/npm/dt/@lavacord/discord.js.svg?maxAge=3600)](https://www.npmjs.com/package/lavacord-latest)
[![NPM version](https://badge.fury.io/js/%40lavacord%2Fdiscord.js.png)](http://badge.fury.io/js/lavacord-latest)
[![Open Source Love](https://badges.frapsoft.com/os/mit/mit.svg?v=102)](https://github.com/ellerbrock/open-source-badge/)

> **Alternative to discord.js v13 lavalink**

# @Lavacord/Discord.js
A simple and easy to use lavalink wrapper for discord.js that uses lavacord underneath

## Documentation
[**lavacord.github.io/lavacord**](https://lavacord.github.io/Lavacord/)

## Installation

**For stable**
```bash
# Using yarn
yarn add @lavacord/discord.js

# Using npm
npm install @lavacord/discord.js
```

# How to use
`@lavacord/discord.js` acts as lavacord, it exports everything that lavacord has.
To use this you first start by initializing the `Manager` which you do like this

```javascript
const { Manager } = require("@lavacord/discord.js");

// Client is your Discord.js client instance.
// Nodes is ur array of node options.
// There is also an optional parameter, which is options so you can pass your user id, shard count manually if you want to
const manager = new Manager(client, nodes);

// Then you need to call Manager#connect, this connects to all of your Lavalink Nodes so the library can function. The function does return a Promise which you want to handle
await manager.connect();
```

That's all you have to do to get a basic start.
Look at the readme for Lavacord for more information, you also have the documentation. Join the discord for more!

## LavaLink configuration
Download from [the CI server](https://ci.fredboat.com/viewLog.html?buildId=lastSuccessful&buildTypeId=Lavalink_Build&tab=artifacts&guest=1)

Put an `application.yml` file in your working directory. [Example](https://github.com/Frederikam/Lavalink/blob/master/LavalinkServer/application.yml.example)

Run with `java -jar Lavalink.jar`

## The issue tracker is for issues only
If you're having a problem with the module contact us in the [**Discord Server**](https://discord.gg/wXrjZmV)
