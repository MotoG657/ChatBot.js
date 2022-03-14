# blacklist the words

> This function will make the bot not learn forbidden words

***Usage***

```js
const array = [
  'fuck',
  'pussy',
]

client.chat.blacklistWords({
  words: array
})

