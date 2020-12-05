# Docs

## Design by @perssBest

## 📥 Request and get API key

Simple request to kyaru-api:
```js
require("node-fetch")("https://kyaru-api.glitch.me/v1/hug", {
    headers: {
        "Authorization": `YOUR TOKEN`
    },
}).then(x => x.json().then(console.log));
```
You can also use our official wrappers to send requests. [Kyaru-api.js (JavaScript)](https://github.com/Kyaru-Development/Kyaru-api.js) / [miss-api.py (Python)](https://github.com/Kyaru-Development/Kyaru-api.py)<br>
 


 
