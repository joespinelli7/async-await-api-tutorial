# async-await-api-tutorial: https://joespinelli7.github.io/async-await-api-tutorial/
**https://www.youtube.com/watch?v=6WclW4ThDUU**

async/await example:
```javascript
async function name() {
  const res = await fetch('url.com') // fetching API url
}
```
What we're saying here is we're making an async function then awaiting a response that we're fetching
from our API url.

Should I use ‘Async/Await’ instead of just Fetch in JavaScript? <br />
https://medium.com/@dannysoto/should-i-use-async-await-instead-of-just-fetch-in-javascript-710a72731e29
- In ES8, JavaScript introduced the async and await keywords. It makes the function you've attached the async keyword to return a promise (a promise object represents the eventual completion (or failure) of an asynchronous operation and its resulting value).
- Functions preceded by async run asynchronously via JavaScript’s event loop. The await keyword tells JavaScript to wait until a promise is resolved and then return its result. However, await can only be used inside an async function, or else you will get a syntax error.
- In the end, they are both able to return the same data. However, async and await are cleaner newer code that should be used instead.
