# ChatBot.js

A sample npm.js for your chatBots for discord!

**Install**
```js
$ npm i chatBot.js
```

**Request**
```js
//ES6 module
import chatBot from 'chatBot.js'
//CommonJs 
const chatBot = require('chatBot.js')
```

**Usage**

```js
client.chat = new chatBot({ 
   debug: <Boolean>,
   learn: <Boolean>,
   channel: <String>,
   client: <String>,
   custom: <Array>,
})
```

***Learn option***

`Danger`
> This function will make the bot talk like the people on your server over time

```js

client.chat = new chatBot({ 
   debug: true,
   learn: true,
})
```

***Custom function***
> This function will make the bot speak customizable things

```js
const array = [
  { in:'you are', reply:'Beautiful!' }
]
client.chat = new chatBot({ 
   debug: true,
   learn: true,
   client: '
   custom: array
})
```

***Channel (optional)***
> This function will make the bot speak only in a specific channel

```js
client.chat = new chatBot({ 
   debug: true,
   learn: true,
   channel: '879328834464407563',
   client: '879328942664855572',
})
```
